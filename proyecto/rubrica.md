# Rúbrica de evaluación del proyecto

> **Borrador provisional.** Pendiente de revisión.

<br>

## Resultado de aprendizaje evaluado

Módulo profesional 0488 *Desarrollo de interfaces*, según el Real Decreto 405/2023, de 29 de mayo, por el que se actualiza el título de Técnico Superior en Desarrollo de Aplicaciones Multiplataforma.

**RA4. Diseña interfaces gráficas identificando y aplicando criterios de usabilidad y accesibilidad.**

| CE | Criterio de evaluación |
| --- | --- |
| a | Se han identificado los principales estándares de usabilidad y accesibilidad. |
| b | Se ha valorado la importancia del uso de estándares para la creación de interfaces. |
| c | Se han creado diferentes tipos de menús cuya estructura y contenido siguen los estándares establecidos. |
| d | Se han distribuido las acciones en menús, barras de herramientas, botones de comando, entre otros, siguiendo un criterio coherente. |
| e | Se han distribuido adecuadamente los controles en la interfaz de usuario. |
| f | Se ha utilizado el tipo de control más apropiado en cada caso. |
| g | Se ha diseñado el aspecto de la interfaz de usuario (colores y fuentes entre otros) atendiendo a su legibilidad. |
| h | Se ha verificado que los mensajes generados por la aplicación son adecuados en extensión y claridad. |
| i | Se han realizado pruebas para evaluar la usabilidad y accesibilidad de la aplicación. |


## Puntuación

**Cada CE evaluado tiene el mismo peso**: hay una fila por CE (criterios 1 a 9, uno por cada CE de la *a* a la *i*). Los aspectos que no corresponden a ningún CE (el proceso de diseño y la presentación, criterios 10 y 11) se evalúan en filas propias con el mismo peso que cada CE. En total, 11 criterios que valen lo mismo. Cada uno se puntúa con uno de estos niveles, y la puntuación aparece en cada celda de la rúbrica, tal y como la configura Moodle:

| Nivel | Puntos |
| --- | --- |
| Sobresaliente | 10 |
| Notable | 8 |
| Suficiente | 6 |
| Insuficiente | 0 |

Moodle suma los puntos de todos los criterios y los convierte en la calificación final de forma proporcional: `calificación = (puntos obtenidos − puntos mínimos) / (puntos máximos − puntos mínimos) × calificación máxima`. Como el nivel más bajo vale 0, un proyecto con todos los criterios en Suficiente obtiene un 6 y uno con todos en Sobresaliente, un 10.


## Rúbrica

| # | Criterio | CE | Sobresaliente | Notable | Suficiente | Insuficiente |
| --- | --- | --- | --- | --- | --- | --- |
| 1 | **Identificación de estándares de usabilidad y accesibilidad** | a | **10 puntos.** Identifica los principales estándares aplicables (heurísticas de Nielsen, WCAG, estándares de facto) y señala con ejemplos dónde los aplica en su prototipo. | **8 puntos.** Identifica los principales estándares, pero los ejemplos de aplicación en el prototipo son escasos o poco claros. | **6 puntos.** Cita algún estándar de forma genérica, sin relacionarlo con su diseño. | **0 puntos.** No incluye el estudio de estándares, o no identifica ninguno. |
| 2 | **Valoración del uso de estándares** | b | **10 puntos.** Explica con claridad por qué es importante seguir los estándares y cómo mejoran la usabilidad y la accesibilidad de su interfaz. | **8 puntos.** Explica la importancia de los estándares, aunque de forma algo superficial o sin relacionarla con su interfaz. | **6 puntos.** Menciona que los estándares son importantes, sin argumentarlo. | **0 puntos.** No valora la importancia del uso de estándares. |
| 3 | **Tipos de menú y su estructura** | c | **10 puntos.** Incluye la barra de menús y al menos otros dos tipos de menú bien elegidos para su función (menú contextual, menú de un botón, pestañas, panel de navegación…); todos siguen los estándares de escritorio (posición esperada, opciones agrupadas con separadores y ordenadas con lógica, puntos suspensivos en las que abren un diálogo, atajos de teclado y teclas de acceso visibles, etiquetas breves y claras) y la documentación justifica cada tipo con capturas. | **8 puntos.** Incluye los tres tipos de menú y siguen los estándares, con algún fallo puntual (una opción mal agrupada, sin atajos ni teclas de acceso) o una justificación superficial. | **6 puntos.** Solo incluye la barra de menús y otro tipo, o los menús no siguen las convenciones en varios aspectos, o no se justifican. | **0 puntos.** Solo hay un menú, o los menús no siguen ningún estándar reconocible. |
| 4 | **Distribución de las acciones y navegación** | d | **10 puntos.** Cada acción está donde el usuario la espera: todas en la barra de menús, las más frecuentes también en la barra de herramientas y en el menú contextual, y las de cada formulario o diálogo en sus botones de comando (abajo a la derecha, Aceptar o Guardar antes que Cancelar, botón predeterminado destacado). Las acciones ocupan la misma posición y tienen el mismo aspecto en todas las pantallas, se distingue la acción principal de las secundarias y las acciones destructivas están separadas. Prototipo totalmente navegable en Figma. | **8 puntos.** Distribución coherente con alguna inconsistencia puntual (una acción solo accesible desde un sitio, un botón en otra posición o con otro estilo). El prototipo es navegable, pero algún enlace falla. | **6 puntos.** Las acciones cambian de posición o de aspecto entre pantallas, o están duplicadas sin criterio; no hay jerarquía clara entre acciones principales y secundarias. Varios enlaces no funcionan. | **0 puntos.** Acciones repartidas sin criterio, sin menú ni barra de herramientas reconocibles, o el prototipo no es navegable en Figma. |
| 5 | **Distribución de los controles y composición** | e | **10 puntos.** Ventana principal a 1280 × 720 y versión maximizada a 1920 × 1080 que muestra con lógica qué crece y qué se mantiene; cuadros de diálogo con su propio tamaño. Espaciado en múltiplos de 8 y cada pantalla organizada en filas y columnas, con todas las zonas bien definidas (barras de menús, herramientas y estado, panel lateral, área de contenido) y una jerarquía visual clara. Etiquetas alineadas con sus controles y controles relacionados agrupados. Aplica y justifica varios ejemplos de equilibrio y tensión compositiva. | **8 puntos.** Cumple los tamaños y el espaciado con algún desajuste puntual. Zonas presentes y jerarquía correcta. La versión maximizada existe, pero la adaptación es poco razonada. Los ejemplos de equilibrio y tensión están aplicados, pero su justificación es poco precisa. | **6 puntos.** El espaciado o la organización en filas y columnas se siguen solo en parte, falta alguna zona o no hay versión maximizada. Jerarquía mejorable (elementos compitiendo por la atención, poco espacio en blanco, controles sin agrupar). Los ejemplos de equilibrio y tensión son escasos o no se justifican. | **0 puntos.** Sin estructura de filas y columnas ni espaciado coherente, o tamaño de ventana no indicado. Composición desordenada o sobrecargada, sin jerarquía. No hay ejemplos de equilibrio ni de tensión. |
| 6 | **Tipo de control adecuado** | f | **10 puntos.** Cada dato se recoge con el control más apropiado (opciones, casillas, desplegables, selectores de fecha…) y todos los campos tienen etiqueta visible. | **8 puntos.** Controles apropiados en casi todos los casos, con alguna elección mejorable. | **6 puntos.** Varias elecciones inadecuadas (por ejemplo, texto libre donde bastaría una lista) o campos sin etiqueta. | **0 puntos.** Controles mal elegidos de forma generalizada, o el prototipo no incluye ningún control interactivo más allá de los enlaces. |
| 7 | **Aspecto visual: color, tipografía y legibilidad** | g | **10 puntos.** UI Kit completo (colores, tipografías, iconos, espaciado y estilos de los controles) del que salen todos los componentes del prototipo. Color dominante y paleta coherentes y justificados, con uso y proporción explicados. Combinación tipográfica armónica con jerarquía de pesos. Contraste entre texto y fondo calculado según WCAG. Imágenes acordes a la temática. | **8 puntos.** Todos los apartados están presentes y bien resueltos, con justificaciones algo superficiales o algún componente del prototipo que no sale del UI Kit. | **6 puntos.** UI Kit incompleto o usado solo en parte. Paleta y tipografía correctas, pero poco justificadas. El contraste está calculado de forma incompleta o con errores. Imágenes poco coherentes con la paleta. | **0 puntos.** No hay UI Kit, colores o fuentes elegidos sin criterio, más de tres familias tipográficas, contraste no calculado, o faltan apartados de la documentación. |
| 8 | **Mensajes de la aplicación** | h | **10 puntos.** El prototipo incluye mensajes de error, confirmación, éxito y estado vacío; todos son breves, dicen qué ha pasado y qué puede hacer el usuario, y usan su lenguaje. La documentación recoge el inventario de mensajes y cómo se ha verificado su claridad (heurísticas o usuarios del test). | **8 puntos.** Están los cuatro tipos de mensaje y son claros, pero alguno es demasiado largo o vago, o la verificación de su claridad es superficial. | **6 puntos.** Falta algún tipo de mensaje, o varios son confusos, técnicos o no indican qué hacer; no se explica cómo se han verificado. | **0 puntos.** El prototipo no incluye mensajes de la aplicación, o no se ha verificado su adecuación. |
| 9 | **Pruebas de usabilidad y accesibilidad** | i | **10 puntos.** Test de usabilidad (SUS) con al menos dos usuarios y revisión de accesibilidad (simulación de daltonismo, tamaño de los elementos pulsables, uso con teclado), con resultados analizados y mejoras aplicadas. | **8 puntos.** Realiza el test de usabilidad y alguna comprobación de accesibilidad, pero el análisis es superficial o no se traduce en mejoras. | **6 puntos.** Realiza solo una de las dos pruebas (usabilidad o accesibilidad), o con errores en el cálculo y sin conclusiones. | **0 puntos.** No realiza ninguna prueba de usabilidad ni de accesibilidad. |
| 10 | **Proceso de diseño: investigación y *user flow*** | — (no asociado a CE) | **10 puntos.** Hipótesis, idea, público objetivo (con personas tipo) y competencia bien argumentados, con conclusiones aplicadas al diseño. *User flow* en Mermaid completo, con la notación correcta y coherente con el prototipo. | **8 puntos.** Todos los apartados están presentes y son correctos, pero alguno es superficial (competencia sin conclusiones, personas poco desarrolladas). *User flow* correcto con algún error menor de notación. | **6 puntos.** Los apartados están presentes pero son escuetos o genéricos. El *user flow* recoge el flujo principal, pero omite caminos alternativos o no coincide del todo con el prototipo. | **0 puntos.** Faltan apartados, o el *user flow* no existe, no usa la notación indicada o no guarda relación con el prototipo. |
| 11 | **Presentación y edición del trabajo** | — (no asociado a CE) | **10 puntos.** Documentación en Markdown bien estructurada (índice enlazado, encabezados, tablas y listas bien usadas, capturas legibles con texto alternativo, sin faltas), repositorio con la estructura pedida y fichero de Figma ordenado y con nombres descriptivos. | **8 puntos.** Trabajo bien presentado, con algún descuido menor: alguna errata, capturas de distinto tamaño, alguna imagen sin texto alternativo o alguna capa sin nombrar. | **6 puntos.** Presentación correcta pero poco cuidada: Markdown irregular (encabezados sin jerarquía, tablas o listas mal formadas), varias faltas de ortografía, capturas poco legibles, imágenes o enlaces que no se ven, o ficheros de Figma desordenados (*Frame 1*, *Frame 2*...). | **0 puntos.** Presentación descuidada: sin estructura ni índice, numerosas faltas, capturas ilegibles, documentación entregada solo en PDF o ficheros de Figma muy desordenados que dificultan la revisión. |


## Requisitos mínimos

Para que el proyecto pueda considerarse superado, debe incluir como mínimo:

- Una temática aprobada por el profesor antes de empezar.
- El prototipo en alta fidelidad, navegable en Figma, con una ventana principal y al menos 4 pantallas más enlazadas, sobre una temática de gestión de datos que se pueda programar en el curso.
- La copia local del fichero de Figma (`.fig`) en el repositorio y el enlace al prototipo, accesible para cualquiera con el enlace.
- La documentación en Markdown con la justificación del color y la tipografía y el cálculo del contraste.

Sin estos elementos, el proyecto se califica como insuficiente, independientemente de la puntuación del resto de criterios.


## Relación entre los apartados del proyecto y los criterios

| Apartado del proyecto | Criterios de la rúbrica |
| --- | --- |
| Documentación: temática, objetivos, público objetivo y competencia (`01` a `03`) | 10 |
| Documentación: navegación y *user flow* en Mermaid (`04`) | 10 |
| Documentación: tabla de pantallas (`04`) | 4, 5 |
| Documentación: estándares de usabilidad y accesibilidad (`05`) | 1, 2 |
| UI Kit (diseño atómico) y su documentación (`06`) | 6, 7 |
| Documentación: imágenes, color dominante, paleta, tipografía y contraste (`07`) | 7 |
| Wireframe de baja fidelidad (*frames* de 1280 × 720 en filas y columnas) | 5 |
| Documentación: tamaño de la ventana, rejilla, equilibrio visual y tensión compositiva (`08`) | 5 |
| Prototipo y documentación: menús (`09`) | 3 |
| Documentación: distribución de las acciones (`09`) | 4 |
| Documentación: controles (`09`) | 6 |
| Prototipo y documentación: mensajes de la aplicación (`10`) | 8 |
| Documentación: test SUS, revisión de accesibilidad y mejoras aplicadas (`11`) | 9 |
| Prototipo en alta fidelidad (ventana de 1280 × 720 y maximizada a 1920 × 1080, espaciado de 8, 1 + 4 pantallas enlazadas) | 4, 5, 6, 11 |
| Plantilla de la documentación completa, capturas exportadas, repositorio y fichero de Figma en conjunto | 11 |


