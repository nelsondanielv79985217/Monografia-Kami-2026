# Wiki LLM — Monografía Kami 2026

Este repo sigue el patrón "LLM Wiki": una wiki en Markdown que se acumula a partir
de las fuentes existentes, en vez de re-derivar todo desde cero en cada consulta.

## Arquitectura (tres capas — no mezclar)

1. **Fuentes crudas** (raíz del repo y `Bibliografia/`): los `.docx` y `.pdf` que
   ya existen. Son inmutables — se leen, nunca se editan ni se mueven sin pedido
   explícito del usuario.

   **Distinción importante dentro de esta capa:**
   - Los **17 PDFs de `Bibliografia/`** son las **fuentes académicas reales**:
     las novelas, ensayos y artículos que respaldan el análisis. Son la única
     base válida para el contenido factual de las páginas de `obras/`,
     `personas/` y `conceptos/` — citas, atribuciones, datos biográficos,
     marco teórico.
   - Los **3 `.docx`** (`Monografia Maria Kamila vega version 1.docx` y los
     dos `Revision_*.docx`) **no cuentan como fuente académica citable**. Son
     guías de estructura y proceso metodológico del anteproyecto: sirven para
     entender qué secciones tiene el trabajo, qué objetivos persigue, qué
     alertas quedaron abiertas. Su contenido alimenta exclusivamente
     `monografia/` (estado del proyecto) y los datos autorreferenciales de
     `personas/maria-kamila-vega-correa.md` y `personas/asesor.md` (el
     proyecto y su proceso son la fuente primaria de sí mismos). Cualquier
     afirmación sobre obras, autores o teoría que solo se haya visto citada
     dentro de un `.docx` —y no verificada contra el PDF original— debe
     marcarse **[incierto — pendiente de verificar contra fuente primaria]**.
2. **Wiki** (`wiki/`): páginas `.md` generadas y mantenidas por Claude — resúmenes,
   páginas de entidades/conceptos, índice, log. Esta capa se escribe y mantiene
   por completo desde acá.
3. **Schema** (este archivo): estructura, convenciones y flujo de trabajo. Se
   ajusta con el uso real; si algo no tiene sentido en la práctica, se discute
   con el usuario y se corrige acá.

## Estructura de `wiki/`

```
wiki/
  index.md       — catálogo de todas las páginas, por categoría
  log.md         — registro cronológico append-only de operaciones
  obras/         — páginas de obras literarias analizadas
  personas/      — autores, teóricas, personajes, la estudiante, el asesor
  conceptos/     — categorías de análisis y marco teórico (rol femenino,
                    autonomía, identidad, contexto histórico, realismo
                    mágico, etc.) — solo conceptos con respaldo
                    bibliográfico, no justificaciones propias del proyecto
  monografia/    — estado del anteproyecto en sí: estructura, objetivos,
                    ODS que lo respaldan, alertas metodológicas abiertas
  bibliografia/  — una página por fuente académica de `Bibliografia/`,
                    con resumen y datos de citación
```

## Convenciones de nombres

- Archivos de página: `kebab-case-sin-acentos.md` (ASCII), aunque el título y
  contenido dentro sí llevan tildes normales en español.
- Cada página empieza con un encabezado `# Título` y una línea de metadatos:
  `**Categoría:** obra | persona | concepto | monografía | bibliografía`
  (con tilde, coincide con el nombre de la carpeta pero en español correcto).
  Las páginas de `personas/` y `monografia/` agregan una aclaración entre
  paréntesis, ej. `persona (personaje)`, `persona (autor)`,
  `persona (referente teórica)`, `monografía (estado del proyecto)` — esto
  es la convención real en las 48 páginas existentes, no una excepción.
- Los links entre páginas usan rutas relativas dentro de `wiki/`, ej.
  `[Como agua para chocolate](../obras/como-agua-para-chocolate.md)`.
- Lo que una fuente no aclara se marca explícitamente como **[incierto]** en la
  página — nunca se completa el hueco por inferencia.

## Archivos especiales

- **`index.md`**: catálogo de todas las páginas, organizado por categoría, con
  link y resumen de una línea por página. Se actualiza en cada ingest.
- **`log.md`**: registro cronológico, append-only. Cada entrada con el prefijo
  `## [YYYY-MM-DD] <tipo> | <descripción corta>` para poder grepearlo
  después. `<tipo>` es una de las operaciones de la sección siguiente
  (`ingest`, `profundización`, `LINT`) u otro tipo de evento de
  mantenimiento del propio schema/wiki cuando aplique (`corrección de
  schema`, `reorganización`) — no solo `ingest`.

## Operaciones

- **INGEST**: al procesar una fuente (nueva o ya existente en el repo), se lee,
  se discuten los puntos clave con el usuario, se escriben/actualizan las
  páginas relevantes (una fuente puede tocar varias páginas), se actualiza
  `index.md` y se agrega entrada a `log.md`.
- **QUERY**: ante una pregunta, se busca primero en `index.md`, luego se entra a
  las páginas relevantes y se sintetiza con referencias. Si la respuesta vale
  la pena conservarla, se propone guardarla como página nueva en vez de que se
  pierda en el chat.
- **LINT**: revisión de la wiki en busca de contradicciones entre páginas,
  afirmaciones desactualizadas, páginas huérfanas sin links entrantes,
  conceptos mencionados sin página propia, y cross-references faltantes.
  Puede pedirse sobre el contenido de la wiki o sobre este mismo archivo de
  schema (verificar que las convenciones declaradas coincidan con la
  práctica real).
- **PROFUNDIZACIÓN**: releer una fuente ya ingerida con más detalle o
  alcance del que tuvo su INGEST original (por ejemplo, un primer INGEST
  que solo cubrió el capítulo 1 de una novela, seguido de una
  PROFUNDIZACIÓN que lee la obra completa). A diferencia de INGEST, no
  introduce una fuente nueva — corrige y expande páginas existentes.
  **Riesgo particular a vigilar**: una PROFUNDIZACIÓN casi siempre deja
  atrás páginas relacionadas que no se tocaron en la pasada (personajes o
  conceptos secundarios ya creados antes, con contenido desactualizado) —
  conviene cerrar cada PROFUNDIZACIÓN con un LINT.

## Estilo de trabajo

- Fuentes de a una: no se procesa todo el repo de una sola pasada. Cada
  actualización se revisa con el usuario antes de seguir con la próxima fuente.
- Los dos documentos `Revision_*.docx` (casi idénticos entre sí, versiones
  parciales superpuestas del mismo anteproyecto) se tratan como **una sola
  fuente lógica**: el estado más reciente del anteproyecto + sus alertas
  metodológicas, no como dos ingests separados.
- No se inventa contenido: si una fuente no aclara algo, se marca como
  **[incierto]** en la página en lugar de completar el hueco.
