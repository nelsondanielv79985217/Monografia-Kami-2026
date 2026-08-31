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

## [2026-08-28] profundización | Como agua para chocolate.pdf — lectura de los 12 capítulos completos

A pedido del usuario, se leyó la novela completa (antes solo se habían leído
fragmentos de los capítulos I, II, III, V y el final). Se encontraron varias
correcciones importantes sobre lo que ya estaba escrito en la wiki:

- **Corrección mayor**: el desenlace no es que Tita y Pedro "finalmente
  puedan estar juntos" recién tras la muerte de Rosaura — llevaban veinte
  años en una relación secreta con un pacto tácito de discreción con
  Rosaura, desde la misma noche en que murió Mamá Elena.
- **Corrección mayor**: Pedro no muere quemado en el incendio final — muere
  de la intensidad de su última unión con Tita (el corazón se le detiene);
  el incendio lo causan los cuerpos de ambos ya después de que Tita, para
  reencontrarse con él, come una caja de cerillos siguiendo la teoría del
  alma que John Brown le explicó años antes.
- **Hallazgo mayor no documentado antes**: tras la muerte de Mamá Elena,
  Tita descubre que esta tuvo un amor prohibido (José Treviño, asesinado
  antes de poder fugarse con ella) y fue obligada a casarse con Juan De la
  Garza — y que Gertrudis es hija biológica de José Treviño, no de Juan De
  la Garza. Esto reencuadra a Mamá Elena como víctima, una generación
  antes, del mismo tipo de control familiar sobre el matrimonio que ella
  impone a sus hijas.
- **Hallazgo mayor**: Tita se compromete con John Brown y usa su anillo,
  pero rompe el compromiso a favor de Pedro; John nunca se casó con nadie
  más. Corregido en `personas/tita.md` y `personas/john-brown.md`.

Páginas reescritas con el arco completo: `obras/como-agua-para-chocolate.md`,
`personas/tita.md`, `personas/pedro-muzquiz.md`, `personas/mama-elena.md`,
`personas/rosaura.md`, `personas/john-brown.md`, `personas/esperanza.md`,
`personas/gertrudis.md`, `conceptos/realismo-magico.md` (catálogo ampliado a
8 episodios: pastel de bodas, codornices, lactancia sobrenatural de Tita,
fantasma de "Luz del amanecer", fantasma de Mamá Elena y embarazo
psicosomático, tornado de gallinas, chiles en nogada finales, muerte de
Tita y Pedro).

Páginas nuevas: `personas/roberto.md` (primer hijo de Pedro y Rosaura,
amamantado por Tita, muere niño), `personas/luz-del-amanecer.md` (abuela
kikapú de John Brown).

**[incierto]**: algunos pasajes de transición menores (el detalle exacto de
cuándo Tita rompe su compromiso con John) no se verificaron palabra por
palabra — la reconstrucción es fiel a los 12 capítulos leídos, pero no es
una relectura exhaustiva de cada línea.

## [2026-08-28] profundización | Las travesías Gilmer M.pdf — lectura de los 7 capítulos completos

A pedido del usuario, se leyó la novela completa (antes solo se había leído
el inicio de los capítulos 1 y 2). Hallazgo estructural mayor: la novela
cubre casi un siglo de conflicto en el norte de Antioquia — de las guerras
liberal-conservadoras de inicios del siglo XX, pasando por La Violencia
bipartidista de mediados de siglo (con atrocidades históricas reales
documentadas explícitamente, como el "corte de florero"), hasta la
guerrilla y el paramilitarismo de fin de siglo, cerrando con una
recreación explícita de la masacre real de El Aro (Antioquia, 1997).

Correcciones importantes sobre lo que ya estaba escrito:

- Carolina es hija de **Mercedes**, no de Carmela (la wiki no lo tenía mal
  explícitamente, pero quedó ambiguo — ahora aclarado).
- **Carmela no ama a Cruz María**: lo seduce deliberadamente por un rencor
  de infancia hacia Mercedes (favoritismo de la abuela que las crió), no
  por atracción romántica genuina — corregido en su página.
- Hallazgo mayor no documentado antes: **Mercedes funda una escuela
  exclusivamente para niñas**, un gesto de agencia feminista explícito
  ("este era un mundo de hombres... las mujeres necesitaban más la
  instrucción para equilibrar la carga").

Páginas reescritas con el arco completo: `obras/las-travesias.md`,
`personas/mercedes-las-travesias.md`, `personas/carmela-las-travesias.md`,
`personas/carolina-las-travesias.md`, `conceptos/contexto-historico-de-las-obras.md`
(arco histórico completo de tres eras), `conceptos/rol-femenino.md`
(comparación ampliada entre las dos obras).

Páginas nuevas: `personas/raquel-las-travesias.md` (violada y asesinada por
"pájaros"), `personas/cruz-maria-garcia.md`, `personas/ismael-las-travesias.md`
("Revancha"), `personas/gavino.md` (esposo violento de Carolina),
`personas/evelio-jaramillo.md` (seduce y abandona a Raquel).

**[incierto]**: por volumen (13.910 líneas), los capítulos 3, 5, 6 y 7 se
leyeron con muestreo amplio (varios pasajes largos por capítulo) en vez de
línea por línea completa, a diferencia de los capítulos 1 y 2 que sí se
leyeron íntegros. Personajes secundarios de esos capítulos (Abraham, Fidel,
Esther, Fidelito, Martín, Manuel, Jorge, Jairo, Crucito) se mencionan en
`obras/las-travesias.md` y `personas/mercedes-las-travesias.md` pero no
tienen página propia — se priorizaron los personajes femeninos y los
directamente relevantes para el eje de la monografía, dado el volumen total
de personajes de la novela.

## [2026-08-28] LINT | segunda pasada, tras la profundización de ambas novelas

**Página huérfana encontrada y reparada**: `personas/luz-del-amanecer.md`
se mencionaba por nombre en cuatro páginas
(`personas/john-brown.md`, `personas/tita.md`,
`obras/como-agua-para-chocolate.md` ×2, `conceptos/realismo-magico.md`) pero
ninguna la enlazaba como página de wiki — quedaba solo listada en
`index.md`. Corregidos los cinco enlaces.

**Afirmación desactualizada corregida**: `conceptos/realismo-magico.md`
seguía diciendo, en su sección sobre *Las travesías*, que solo se habían
leído los capítulos 1 y 2 — desactualizado tras la lectura completa de la
novela. Se confirmó y documentó la conclusión (no hay realismo mágico en
ningún capítulo de *Las travesías*, a diferencia de *Como agua para
chocolate*), añadiendo el contraste con el caso límite de Carolina (su
"comunicación" con su padre muerto se enmarca como síntoma de demencia, no
como hecho sobrenatural objetivo). También se agregó un noveno episodio de
realismo mágico que faltaba en el catálogo: el fantasma de Nacha encendiendo
el último cirio en el desenlace.

**Dos páginas de personajes de Como agua para chocolate quedaron
desactualizadas** tras la lectura completa de la novela (creadas/editadas
antes de la profundización, nunca revisadas después):
- `personas/chencha.md`: le faltaba la violación que sufre en el ataque de
  bandoleros (capítulo VII) y su matrimonio posterior con Jesús Martínez.
- `personas/nacha.md`: le faltaba su aparición como fantasma en el
  desenlace de la novela.

Ambas corregidas. `monografia/alertas-metodologicas.md` (punto 4) también
tenía una frase residual ("queda pendiente una lectura más completa... más
allá del capítulo 1") que ya no aplicaba — actualizada.

**Verificaciones sin hallazgos**: no se encontraron links rotos ni páginas
huérfanas en las 48 páginas de contenido actuales. Se verificó consistencia
de la revelación sobre José Treviño/Gertrudis entre `personas/mama-elena.md`,
`personas/gertrudis.md`, `personas/tita.md` y `obras/como-agua-para-chocolate.md`
— sin contradicciones. Se verificó que Carolina se identifica consistentemente
como hija de Mercedes (no de Carmela) en todas las páginas que la mencionan.

## [2026-08-28] LINT del schema | CLAUDE.md contra la práctica real

A pedido del usuario, se auditó `CLAUDE.md` (no el contenido de `wiki/`)
contra el estado real del repo. Verificado sin hallazgos: estructura de
carpetas (`obras/`, `personas/`, `conceptos/`, `monografia/`,
`bibliografia/`), convención de nombres de archivo (`kebab-case-sin-acentos`,
verificado en las 48 páginas), conteo de fuentes (17 PDFs, 3 `.docx`), y
orden de categorías en `index.md`.

**Dos desalineaciones reales encontradas y corregidas** (la práctica había
evolucionado y el texto del schema se quedó atrás):

1. La línea `**Categoría:**` del schema definía un enum plano de 5 palabras
   sin tilde (`obra | persona | concepto | monografia | bibliografia`), pero
   las 48 páginas usan consistentemente la palabra con tilde más una
   aclaración entre paréntesis (`persona (personaje)`,
   `monografía (estado del proyecto)`, etc.). Se actualizó el schema para
   documentar la convención real en vez de forzar 48 páginas a la más pobre.
2. El formato de entrada de `log.md` solo documentaba el prefijo `ingest`,
   pero ya se usaban cinco tipos distintos y consistentes (`ingest`,
   `profundización`, `LINT`, `corrección de schema`, `reorganización`). Se
   generalizó el formato documentado y se agregó **PROFUNDIZACIÓN** como
   cuarta operación formal en la sección "Operaciones" (antes solo INGEST,
   QUERY, LINT) — releer una fuente ya ingerida con más alcance del que
   tuvo su INGEST original, distinto de ingerir una fuente nueva.

También se prolijó el diagrama ASCII de `wiki/` en "Estructura de `wiki/`",
que tenía espaciado inconsistente entre entradas.

## [2026-08-30] entrega | Monografia Maria Kamila Vega version 2.docx

A pedido del usuario: se produjo una nueva versión completa del anteproyecto
(`Monografia Maria Kamila Vega version 2.docx`, en la raíz del repo, fuera
de `wiki/`), partiendo del contenido ya mejorado de las dos revisiones
(Introducción, Justificación, Planteamiento, Objetivos) e incorporando las
15 fuentes académicas de `Bibliografia/`. Decisiones tomadas, confirmadas
por el usuario de antemano:

- Se escribió un **Marco Teórico** nuevo desde cero (cinco subsecciones),
  reemplazando el contenido de relleno sobre maltrato animal.
- Se redactó una sección de **Hipótesis** y una de **Alcances y límites**,
  que antes solo existían como encabezados vacíos.
- Se resolvieron con criterio propio, documentando la decisión dentro del
  mismo documento: el título investigativo (se adoptó la reformulación del
  asesor sin población, dejando constancia de que la población ya aparece
  en intro/objetivos/pregunta), la cita no verificable de "Fernanda (2021)"
  (retirada), y la aplicación de comillas en títulos de obras (extendida a
  todo el documento). Ninguna de estas decisiones reemplaza la confirmación
  del asesor real — quedan documentadas como propuesta razonada.
- Dos alertas quedan explícitamente abiertas en el documento (sección
  "Alcances y límites"): faltan los datos editoriales de "El segundo sexo"
  y de "Como agua para chocolate".

Actualizada `monografia/alertas-metodologicas.md` con el estado de cada
punto tras esta entrega (1 refutada, 4 resueltas en v2, 2 abiertas).

**[incierto]**: el documento no se generó a partir de un template de Word
existente (no había ninguno disponible), sino con la librería `docx` de
Node.js siguiendo una estructura académica estándar — el formato visual
(fuente, tamaños, portada) es una propuesta razonable, no una plantilla
oficial del colegio.

## [2026-08-30] entrega | prompt-encuesta-forms.md

A pedido del usuario: se redactó un prompt listo para pegar en un generador
de Google Forms, con la encuesta completa (20 preguntas en 4 secciones)
para el componente cuantitativo de la monografía. Las preguntas se
diseñaron ancladas directamente en las seis dimensiones de análisis de
[Rol femenino](conceptos/rol-femenino.md) y en dos situaciones concretas
verificadas en la lectura directa de las novelas (la tradición que prohíbe
casarse a la hija menor en *Como agua para chocolate*; la escuela solo para
niñas que funda Mercedes en *Las travesías*). Se evitó deliberadamente
referenciar los episodios de violencia sexual de *Las travesías* por
tratarse de una encuesta a menores de edad.

Entregable: `prompt-encuesta-forms.md` (raíz del repo). Página nueva:
`monografia/encuesta.md`, documentando el instrumento y su estado (redactado,
no aplicado todavía). Actualizada `monografia/anteproyecto.md` con nota
apuntando a la versión 2 del documento y a esta encuesta.

**[incierto]**: el formulario de Google Forms en sí no fue creado por este
asistente — el usuario debe pegar el prompt en la herramienta de generación
de formularios de su preferencia y aplicarlo. El análisis de resultados
(porcentajes, tablas, gráficos) queda pendiente hasta que se aplique.

## [2026-08-30] entrega | Formulario de Google Forms creado directamente

A pedido del usuario ("créala vos directo en Google Forms con el connector"),
se construyó el formulario real en Google Forms (cuenta
nelsondanielv123@gmail.com), en vez de solo entregar el prompt. Se crearon
las 4 secciones y las 20 preguntas exactas de `prompt-encuesta-forms.md`,
verificando uno a uno tipo de pregunta (varias opciones / escala lineal 1-5
/ párrafo), texto y obligatoriedad contra el diseño original. Se desactivó
la recolección automática de correo electrónico ("No recoger" en
Configuración → Respuestas), preservando el anonimato exigido por el
diseño del instrumento.

Antes de publicarlo (acción que hace el formulario accesible a cualquier
persona con el enlace) se confirmó explícitamente con la autora; con su
autorización, se publicó. Enlace para compartir con los estudiantes:
<https://docs.google.com/forms/d/e/1FAIpQLSeD_zHf1HbbvtJ8uF8T7mID80SLJRPHAua7t9-M9v4ZF2xBVg/viewform>

Actualizada `monografia/encuesta.md` con el estado nuevo (formulario
construido y publicado) y el enlace.

## [2026-08-30] entrega | Monografia Maria Kamila Vega version 3.docx

A pedido del usuario ("vamos a crear la versión tres escondiendo las notas
editoriales y retirando la referencia de pareja de la reseña que no está en
la bibliografía"): se produjo `Monografia Maria Kamila Vega version 3.docx`,
partiendo del contenido de la v2 con dos cambios puntuales:

- Se retiraron del cuerpo del documento las 6 notas editoriales en cursiva
  (`noteBox`) que la v2 usaba para explicar decisiones tomadas durante su
  redacción (Resumen, Título investigativo, Hipótesis, Marco teórico,
  Alcances y límites, Bibliografía). Su contenido no se perdió: quedó
  documentado en `monografia/alertas-metodologicas.md`, su lugar natural en
  la wiki.
- Se retiró por completo la cita y la entrada bibliográfica de Pareja Díaz
  (2024) — reseña que nunca estuvo entre los PDF de `Bibliografia/` y no fue
  posible verificar contra la fuente original. Las tres oraciones que la
  citaban para ubicar temporalmente *Las travesías* (Introducción, Situación
  problema, Objetivo general) se reescribieron apoyándose en cambio en la
  lectura directa y ya verificada de la novela completa (Mesa, 2021), que
  confirma de forma independiente el mismo marco histórico —de las guerras
  liberal-conservadoras de inicios del siglo XX a la masacre de El Aro,
  Antioquia, 1997.

La bibliografía de la v3 queda en 15 entradas (antes 16). Verificado por
round-trip con `pandoc -t markdown`: sin rastros de "Pareja" ni de las
frases de las notas editoriales en el texto resultante; estructura completa
intacta (Portada, Resumen, Introducción, Justificación, Planteamiento del
problema, Hipótesis, Objetivos, ODS, Enfoque, Marco teórico con sus 5
subsecciones, Alcances y límites, Bibliografía).

Actualizada `monografia/alertas-metodologicas.md` (puntos 4 y 7, y nota de
cabecera) y `monografia/anteproyecto.md` con el estado de la v3.

**[incierto]**: igual que con la v2, la generación es programática (librería
`docx` de Node.js), no a partir de una plantilla oficial del colegio.

## [2026-08-30] corrección | lenguaje de version 3 más natural, tras ajustes de formato de la autora

La autora hizo ajustes de forma en `Monografia Maria Kamila Vega version
3.docx` directamente en Word (tipos de fuente y tamaños, además de un logo
y una tabla de contenido nuevos). A pedido suyo, se releyó el documento
completo y se aplicó una pasada de "humanizer" sobre el texto para que
sonara más natural y menos "de IA", sin tocar citas, referencias
bibliográficas, ni la estructura de encabezados (para no desincronizar la
tabla de contenido que ella agregó). Se editó directamente el XML interno
del `.docx` ya modificado por la autora —no se regeneró desde los scripts
de Node.js— para conservar íntegros sus cambios de formato.

16 ajustes puntuales: se quitaron transiciones repetidas ("en este
sentido" ×2, "por esta razón" ×2, "resulta pertinente"/"resulta
especialmente relevante" ×3, "se retoma también" ×3, "en la misma línea"
×2) variando la redacción entre apariciones, se simplificó una oración
particularmente rígida ("con particular claridad..."), se completó el
sujeto implícito de la frase de ODS 5, se cambiaron dos gerundios finales
por verbos coordinados en los objetivos, y se corrigió una comilla curva
suelta que había quedado de la edición manual, para que combinara con las
comillas rectas usadas en el resto del documento.

**Hallazgo durante la relectura, no corregido de oficio**: la última
oración de "Límites" —la que documentaba que faltan los datos editoriales
de "El segundo sexo" y de "Como agua para chocolate"— ya no está en el
documento. No está claro si la autora la quitó a propósito al editar el
formato o si se perdió por accidente; no se restituyó sin confirmar con
ella. La alerta sigue documentada y abierta en
[Alertas metodológicas](monografia/alertas-metodologicas.md), esté o no en
el cuerpo del documento entregable.
