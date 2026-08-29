# Log — Wiki Monografía Kami 2026

Registro cronológico, append-only. No editar entradas pasadas.

## [2026-08-28] ingest | Monografia Maria Kamila vega version 1.docx

Primera fuente ingerida. Páginas creadas:

- `obras/como-agua-para-chocolate.md`
- `obras/las-travesias.md`
- `personas/maria-kamila-vega-correa.md`
- `personas/laura-esquivel.md`
- `personas/gilmer-mesa.md`
- `personas/simone-de-beauvoir.md`
- `personas/mama-elena.md`
- `conceptos/rol-femenino.md`
- `conceptos/contexto-historico-de-las-obras.md`
- `conceptos/ods-4-y-5.md`
- `monografia/anteproyecto.md`

Hallazgos notables: dos formulaciones distintas del título investigativo
coexisten en el documento; la sección "MARCO TEÓRICO" contiene contenido de
plantilla sobre maltrato animal, sin relación con el tema real; la
bibliografía de esta fuente no incluye entradas para Beauvoir ni Pareja Díaz
pese a citarlos en el texto.

## [2026-08-28] ingest | Revision_Anteproyecto_Kamila.docx + Revision_Introduccion_Justificacion_Objetivos.docx

Tratadas como una sola fuente lógica (ver CLAUDE.md), por ser versiones casi
idénticas y parcialmente superpuestas del mismo anteproyecto revisado.

Páginas creadas:

- `personas/asesor.md`
- `monografia/alertas-metodologicas.md`
- `personas/mercedes-las-travesias.md`
- `personas/carmela-las-travesias.md`

Páginas actualizadas:

- `obras/las-travesias.md` — referencias completas de Mesa (2021) y Pareja
  Díaz (2024); hallazgo crítico del vacío de fuentes sobre el rol femenino.
- `obras/como-agua-para-chocolate.md` — cross-references a las alertas
  metodológicas 1 y 2.
- `monografia/anteproyecto.md` — resuelto parcialmente el título investigativo
  (tres versiones, ninguna confirmada como definitiva); cross-reference a
  alertas metodológicas.
- `personas/simone-de-beauvoir.md` — entrada bibliográfica sugerida por la
  revisión (editorial y traductor siguen sin identificar).

Hallazgo más importante de este ingest: el proyecto no tiene el texto completo
de "Las travesías", solo una reseña que menciona a sus personajes femeninos de
paso — esto compromete la simetría del análisis comparativo (alerta
metodológica 4). También queda abierta la tensión entre dos instrucciones
contradictorias del asesor sobre el título investigativo (alerta 7).

## [2026-08-28] corrección de schema | los .docx no son fuente académica

El usuario aclaró: los 3 `.docx` no cuentan como fuente citable para
`obras/`, `personas/` ni `conceptos/` — solo como guía de estructura y
proceso metodológico, y por eso siguen siendo válidos para `monografia/` y
para las páginas autorreferenciales de la autora y el asesor. Se actualizó
`CLAUDE.md` con esta distinción y se marcaron como
**[incierto — pendiente de verificar contra fuente primaria]** las páginas
cuyo contenido solo se había visto a través de los `.docx`:
`personas/laura-esquivel.md`, `personas/gilmer-mesa.md`,
`personas/mama-elena.md`, `personas/mercedes-las-travesias.md`,
`personas/carmela-las-travesias.md`, `conceptos/rol-femenino.md`,
`conceptos/contexto-historico-de-las-obras.md`, `conceptos/ods-4-y-5.md`.
Pendiente: aplicar el mismo ajuste a `obras/como-agua-para-chocolate.md`,
`obras/las-travesias.md` y `personas/simone-de-beauvoir.md` al ingerir sus
PDFs primarios correspondientes.

## [2026-08-28] ingest | Bibliografia/Como agua para chocolate.pdf

Primer PDF de `Bibliografia/` ingerido — fuente primaria real de la novela
(no solo lo citado indirectamente vía el `.docx`). Extraído con `pdftotext`.

Páginas creadas: `personas/tita.md`, `personas/pedro-muzquiz.md`,
`personas/rosaura.md`.

Páginas reescritas con fuente primaria: `obras/como-agua-para-chocolate.md`
(estructura de 12 capítulos mensuales, narradora, premisa de la tradición
familiar, personajes principales), `personas/mama-elena.md` (episodio
verificado del capítulo "V. Mayo", carácter confirmado).

**[incierto]**: solo se leyó el inicio de la novela (capítulos "I. Enero" y
"V. Mayo") y el final; el desarrollo completo de la trama en los demás
capítulos queda pendiente de lectura.

## [2026-08-28] ingest | Bibliografia/Las travesías Gilmer M.pdf

Segundo PDF de `Bibliografia/` ingerido. Extraído con `pdftotext` (13,910
líneas). **Hallazgo mayor: contradice directamente el punto 4 de las alertas
metodológicas.** El PDF contiene el texto completo de la novela (Penguin
Random House, 2021, ISBN 978-958-5581-71-5), no solo la reseña de Pareja
Díaz como afirmaban las revisiones. Mercedes y Carmela aparecen 160 veces en
el archivo y están ampliamente desarrolladas desde el capítulo 1.

Páginas reescritas con fuente primaria: `obras/las-travesias.md` (edición
confirmada, estructura narrativa, contexto de fundación en el norte de
Antioquia, personajes del capítulo 1), `personas/mercedes-las-travesias.md`,
`personas/carmela-las-travesias.md` (historia completa del capítulo 1: su
orfandad de guerra, la fundación de la finca, la relación secreta entre
Carmela y Cruz María).

Página actualizada: `monografia/alertas-metodologicas.md` — punto 4 marcado
como **refutado**, con el texto original de la observación preservado para
que quede registro de la discrepancia.

**[incierto]**: solo se leyó el inicio del capítulo 1; el resto de la novela
(estructura completa de capítulos, desenlace, desarrollo posterior de
Mercedes y Carmela) queda pendiente de lectura.

## [2026-08-28] profundización | Como agua para chocolate.pdf + Las travesías Gilmer M.pdf

A pedido del usuario, se profundizó la lectura de ambas novelas antes de
seguir con el resto de la bibliografía.

**Como agua para chocolate**: se leyeron los capítulos "I. Enero" (nacimiento
de Tita, tradición familiar), "II. Febrero" (boda de Pedro y Rosaura, el
pastel con lágrimas, muerte de Nacha), pasajes del capítulo "III. Marzo"
(huida de Gertrudis), pasajes intermedios (Rosaura enferma, tensión por
Esperanza) y el desenlace completo (muerte de Rosaura, boda de Esperanza y
Alex, muerte de Tita y Pedro en el incendio). Páginas nuevas:
`personas/gertrudis.md`, `personas/nacha.md`, `personas/chencha.md`,
`personas/john-brown.md`, `personas/alex-brown.md`, `personas/esperanza.md`.
Reescritas con el arco completo: `obras/como-agua-para-chocolate.md`,
`personas/tita.md`, `personas/rosaura.md`, `personas/pedro-muzquiz.md`.
Actualizada `conceptos/rol-femenino.md` con el contraste entre las cuatro
respuestas femeninas a la tradición familiar (Tita, Rosaura, Gertrudis,
Esperanza).

**Las travesías**: se identificó la estructura completa de 7 capítulos y se
leyó el inicio del capítulo 2, "Las hermanas" — salto temporal en el que Cruz
María es asesinado, sus hijos varones son detenidos, y Mercedes queda viuda
y expuesta al despojo de tierras y al acoso de un terrateniente oportunista
(Evelio Jaramillo). Página nueva: `personas/carolina-las-travesias.md`
(hija de Mercedes, cae en demencia). Actualizadas:
`obras/las-travesias.md`, `personas/mercedes-las-travesias.md`.

**[incierto]**: ambas novelas siguen leídas solo parcialmente (capítulos
III–XII de *Como agua para chocolate* más allá de lo indicado arriba, y
capítulos 3–7 completos de *Las travesías*) — quedan como lectura pendiente
para una profundización futura si se requiere.

A partir de aquí se continúa con los 15 PDFs restantes de `Bibliografia/`,
sin pausar para confirmación entre cada uno (instrucción explícita del
usuario).

## [2026-08-28] ingest | 9 PDFs académicos de Bibliografia/ (tanda 1 de 2)

Extraídos con `pdftotext` y creadas sus páginas en `wiki/bibliografia/`:

- `El segundo sexo.pdf` → verificadas palabra por palabra las dos citas de
  Beauvoir ya usadas en la monografía (p. 7 y p. 109) — ambas exactas.
  Actualizadas `personas/simone-de-beauvoir.md` y
  `monografia/alertas-metodologicas.md` (punto 3: confirmado, con precisión
  añadida — las páginas citadas sí son correctas, solo falta editorial).
- `Escritura de mujeres escritura de las diferencias.pdf` — autora no
  identificada en el archivo.
- `Literatura De Crimenes Femenina Y Feminista En Colombia.pdf` — Delgado
  Ricci (2021), analiza *Los Divinos* de Laura Restrepo.
- `Cicatrices sociales en la novela Los Divinos de Laura Restrepo.pdf` —
  Cardona González y Londoño Garzón (2026), misma novela que la fuente
  anterior.
- `El cuento de la criada los simbolos y las mujeres en la narrativa
  distopica.pdf` — Moreno Trujillo (2016).
- `El espejo de las generaciones en la narrativa contemporanea.pdf` —
  Ciplijauskaité (1986). **Hallazgo relevante**: su marco del "espejo de las
  generaciones" madre-hija-abuela encaja directamente con el patrón de
  cuatro generaciones ya identificado en *Como agua para chocolate*.
- `Interpretacion del rol femenino en la historiografia.pdf` — en realidad
  contiene el libro completo *De-liberadas Vol. 2* (Universidad del
  Tolima, 2026); el capítulo relevante es de Rondón González, p. 153+.
- `La identidad femenina en los cuentos de Eva Luna.pdf` — Mousa Abd El
  Azeem (2017), sobre Isabel Allende.
- `La validacion literaria a través de una identidad colectiva- Jarintzi
  Quintana.pdf` — tesis de licenciatura (UAEM, 2026) sobre la antología
  *Tsunami*.

Quedan 6 PDFs: *Las orquídeas rojas de Shanghai*, *Narrativas y experiencias
frente al conflicto armado de las mujeres campesinas*, *Transcripción
episodio 136 (entrevista a Gilmer Mesa)*, *Violencia de género en
instituciones de educación superior* (Rodríguez), *Violencias basadas en
género en la educación superior* (Penilla), *las topografías de la casa*.

## [2026-08-28] ingest | 6 PDFs restantes de Bibliografia/ (tanda 2 de 2) — bibliografía completa

Extraídos con `pdftotext` y creadas sus páginas en `wiki/bibliografia/`:

- `Narrativas y experiencias frente al conflicto armado de las mujeres
  campesinas.pdf` — Gallego López (2026), trabajo de grado UTP, Santuario
  (Risaralda).
- `Violencia de genero en instituciones de educacion superior Rodriguez
  Karla J.pdf` — Rodríguez Hernández y Rodríguez Barraza (2021), México.
- `Violencias basadas en genero en la educacion superior una revision del
  estado delarte Penilla M F.pdf` — Penilla Quintero (2026), Colombia.
- `las topografias de la casa.pdf` — Lucía Guerra. **Hallazgo relevante**:
  la casa como espacio de reclusión femenina; aplica directo al rancho De la
  Garza y al confinamiento de Tita en la cocina en *Como agua para
  chocolate*. Archivo con calidad de OCR pobre (caracteres corruptos).
- `Transcripcion episodio 136 entrevista a Gilmer Mesa por Alejandro
  Salgado .pdf` — podcast "No hay banderas en Marte". Aporta biografía del
  autor (infancia en pobreza, asesinato de su hermano, primera novela *La
  cuadra*) pero **no menciona *Las travesías*** en ningún momento.
  Actualizada `personas/gilmer-mesa.md` con estos datos.
- `Las orquideas rojas de Shanghai - Juliette Morillot.pdf` — novela
  histórica completa (no artículo académico) sobre esclavitud sexual de
  mujeres coreanas por el ejército japonés, 1937 en adelante.

Actualizada `conceptos/rol-femenino.md` con cross-references a las dos
fuentes teóricas más aplicables encontradas en toda la bibliografía: el
"espejo de las generaciones" (Ciplijauskaité) y "las topografías de la casa"
(Guerra), ninguna de las dos citada todavía en los `.docx` de la monografía.

**Los 17 PDFs de `Bibliografia/` están ahora completamente ingeridos**: 2
como obras centrales en `obras/` (con lectura profundizada más allá del
capítulo inicial) y 15 como fuentes académicas/literarias en
`bibliografia/`. Quedan como trabajo futuro, si se requiere: lectura
completa de los capítulos restantes de ambas novelas centrales, y una pasada
de LINT para revisar contradicciones, páginas huérfanas y cross-references
faltantes en el conjunto ya construido.

## [2026-08-28] LINT | primera pasada completa sobre las 39 páginas de contenido

**Contradicción corregida (error propio, no de una fuente)**: en
`obras/como-agua-para-chocolate.md` se había escrito que la paternidad
biológica de Esperanza era ambigua/incierta. Se releyó el pasaje original
del PDF (nacimiento prematuro de Esperanza, histerectomía de urgencia de
Rosaura) y se confirmó, sin ambigüedad, que Esperanza es hija biológica de
Rosaura y Pedro — como ya decían correctamente `personas/esperanza.md`,
`personas/rosaura.md` y `personas/pedro-muzquiz.md`. Corregido el párrafo.

**Afirmaciones desactualizadas corregidas**:
- `conceptos/rol-femenino.md` tenía en su pie de página un `[incierto]`
  diciendo que el marco teórico de Beauvoir "no fue verificado aún", pese a
  que esa verificación ya se había hecho y documentado más arriba en la
  misma página. Corregido.
- `monografia/alertas-metodologicas.md`: el título de la página decía
  "(estado: abiertas)" pese a que el punto 4 está refutado. Cambiado a
  "(6 abiertas, 1 refutada)".
- `personas/simone-de-beauvoir.md` citaba "21.422 líneas extraídas" para
  `El segundo sexo.pdf`; el conteo real (verificado con `wc -l`) es ~24.000
  — la cifra original venía de un conteo de PowerShell impreciso. Corregido
  a una cifra aproximada.
- `personas/maria-kamila-vega-correa.md` presentaba un título de la
  monografía como si fuera definitivo y su nota `[incierto]` solo mencionaba
  "dos formulaciones", desactualizada frente a las tres ya documentadas en
  `monografia/anteproyecto.md`. Corregida para apuntar a la resolución
  completa.

**9 páginas huérfanas encontradas** (sin ningún link entrante desde otra
página de contenido, solo listadas en `index.md`) — todas reparadas con
cross-references reales:
`bibliografia/el-segundo-sexo.md`,
`bibliografia/cicatrices-sociales-en-la-novela-los-divinos.md`,
`bibliografia/literatura-de-crimenes-femenina-y-feminista-en-colombia.md`
(estas dos últimas se mencionaban mutuamente solo como ruta de archivo cruda
en backticks, no como link de wiki — corregido a link real),
`bibliografia/el-cuento-de-la-criada-simbolos-y-mujeres.md`,
`bibliografia/escritura-de-mujeres-escritura-de-las-diferencias.md`,
`bibliografia/la-identidad-femenina-en-cuentos-de-eva-luna.md`,
`bibliografia/la-validacion-literaria-identidad-colectiva.md`,
`bibliografia/las-orquideas-rojas-de-shanghai.md`,
`bibliografia/narrativas-y-experiencias-conflicto-armado-mujeres-campesinas.md`.
Se agregó una sección "Otras fuentes de la bibliografía relacionadas con
este eje" en `conceptos/rol-femenino.md` para enlazarlas desde un lugar con
sentido temático real, y se enlazó `El segundo sexo` desde
`personas/simone-de-beauvoir.md`.

**Verificaciones sin hallazgos**: no se encontraron links rotos (rutas
relativas a archivos inexistentes) en ninguna de las 39 páginas. `index.md`
lista correctamente las 39 páginas de contenido.

**Pendiente de decisión del usuario (no corregido de oficio)**: "realismo
mágico" aparece como concepto significativo en 3 páginas
(`obras/como-agua-para-chocolate.md`, `personas/tita.md`,
`bibliografia/la-identidad-femenina-en-cuentos-de-eva-luna.md`) sin tener
página propia en `conceptos/` — candidato a nueva página si se considera
relevante. `conceptos/ods-4-y-5.md` sigue con la nota abierta de si debería
vivir en `monografia/` en vez de `conceptos/` (ver esa página).

## [2026-08-28] ingest | conceptos/realismo-magico.md (a pedido del usuario)

Creada la página pendiente del LINT anterior. Sintetiza lo ya verificado en
`obras/como-agua-para-chocolate.md` y `personas/tita.md` (las emociones de
Tita transmitidas a través de la comida: el pastel de la boda, las
codornices en pétalos de rosas) y lo aportado por
`bibliografia/la-identidad-femenina-en-cuentos-de-eva-luna.md` (Post-Boom,
Isabel Allende). Se agrega una lectura propia — marcada explícitamente como
`[incierto]` por no venir de ninguna fuente — que conecta el dispositivo
mágico con el encierro de Tita en la cocina, cruzando con
`bibliografia/las-topografias-de-la-casa.md`. Se deja registrado que no se
ha encontrado realismo mágico en la lectura hecha hasta ahora de
*Las travesías*. Enlazada desde las tres páginas que ya mencionaban el
concepto y desde `index.md`.

## [2026-08-28] reorganización | ods-4-y-5.md movida de conceptos/ a monografia/

A pedido del usuario, resuelta la nota pendiente del LINT: `ods-4-y-5.md` se
movió de `conceptos/` a `monografia/` con `git mv` (conserva historial).
Razón: es contenido metodológico/de justificación del propio proyecto (por
qué la autora eligió estos ODS), no un concepto teórico con respaldo
bibliográfico como el resto de `conceptos/`. Actualizado su link interno a
`rol-femenino.md` (ahora `../conceptos/rol-femenino.md`), su categoría, y
las referencias en `index.md`, `monografia/anteproyecto.md` y `CLAUDE.md`
(que ya no cita ODS como ejemplo de `conceptos/`). Las menciones de la ruta
vieja en entradas anteriores de este log no se editan, por ser registro
histórico de dónde estaba el archivo en ese momento.
