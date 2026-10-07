# Evidencia trazable con un asistente de investigación

Curso breve, en cinco etapas, para construir en parejas una **síntesis de evidencia trazable**: cada afirmación se puede rastrear hasta una fuente, una página y un pasaje literal. Un asistente de IA **propone** y las personas **deciden**; ninguna etapa avanza sin la aprobación registrada de los dos revisores.

Adaptación de la guía 08, «Asistente de investigación con aprobación humana», del curso **Vibe Coding CEDIA 2026**, aplicada en la Universidad Técnica Particular de Loja (UTPL).

**Ver el curso:** https://&lt;usuario&gt;.github.io/&lt;repositorio&gt;/ *(actualizar tras activar GitHub Pages)*

---

## Las cinco etapas

| Etapa | El asistente propone | Las personas deciden |
|---|---|---|
| 1. Incorporar | Registra cada fuente con un identificador fijo (F01, F02…) | Eligen las fuentes |
| 2. Verificar | Revisa DOI, ISBN o enlace y marca las citas incompletas | Corrigen o descartan; nada se completa de memoria |
| 3. Pertinencia | Puntúa con la rúbrica C1–C4 (se publica después) | Cada revisor puntúa por separado; luego acuerdan y se calcula el kappa de Cohen |
| 4. Extraer | Para cada campo, valor, pasaje literal y página, o «ausente» | Aprueban, corrigen o rechazan cada fila |
| 5. Sintetizar | Redacta solo con filas aprobadas; cada afirmación con `[Fxx, p.]` | Rastrean afirmaciones al azar y aprueban |

## Contenido del repositorio

| Archivo | Qué es |
|---|---|
| `index.html` | El curso completo e interactivo en un solo archivo: ruta de cinco etapas con una práctica en cada una (identificadores estables, citas completas, rúbrica C1–C4 y calculadora de kappa, resaltado del pasaje literal, rastreo de afirmaciones), tarjetas de contradicciones, autoevaluación con la rúbrica, política de IA, ejemplo resuelto y guía para docentes. Incluye para descargar las 7 plantillas y la síntesis del piloto. El avance se guarda solo en el navegador de cada persona. |
| `README.md` | Este archivo. |

`index.html` no depende de otros archivos. Solo usa Google Fonts para la tipografía y, sin conexión, muestra las fuentes del sistema. Las ilustraciones son originales, dibujadas en SVG dentro del propio archivo. Los textos de práctica F98 y F99 son ficticios; las citas del piloto son fragmentos breves con su referencia.

## Uso

**Estudiantes:** abran el curso, lean las reglas y descarguen las plantillas desde la sección «Plantillas». Cada hoja de cálculo trae una pestaña de instrucciones. Las celdas amarillas las completan ustedes; las grises se calculan solas.

**Docentes:** la sección «Para docentes» resume el armado en Canvas: archivos, páginas, grupos de revisión, rúbrica, actividades, módulo con progreso secuencial y prueba con el Estudiante de prueba. La plantilla `etapa3_propuesta_asistente_plantilla.xlsx` se entrega a los estudiantes **después** de la puntuación individual, para que el kappa refleje un acuerdo independiente.

## Piloto

El ejemplo resuelto proviene de un piloto realizado en octubre de 2026 con la pregunta *¿Cómo ha sido abordada la competencia «Desarrollo personal integral» o sus constructos afines en la literatura científica sobre educación superior?*

| Dato | Valor |
|---|---|
| Fuentes registradas | 10 (4 duplicados descartados) |
| Kappa de Cohen antes del consenso | 0,70 (sustancial) |
| Filas de extracción con pasaje literal | 63 |
| Citas en la síntesis, todas rastreables | 77 |

El repositorio **no incluye los PDF de las fuentes** analizadas, que tienen sus propias licencias. La síntesis las cita con su DOI, ISBN o enlace.

## Publicar con GitHub Pages

1. Suba `index.html` y `README.md` a la raíz del repositorio.
2. En **Settings → Pages**, elija la rama `main` y la carpeta `/ (root)`, y guarde.
3. Tras unos minutos, actualice el enlace «Ver el curso» al inicio de este archivo.

## Pendientes antes de usarlo con estudiantes

- [ ] Completar en `index.html`, sección «Uso de IA», los tres campos marcados `[COMPLETAR]`: normativa de la UTPL sobre IA, herramienta autorizada, y si se permite subir PDF completos o solo resúmenes.
- [ ] Definir la licencia del material. [COMPLETAR: por ejemplo, CC BY-NC-SA 4.0]

## Autoría y créditos

Autoría: Martha Vanessa Agila Palacios · UTPL · 2026.
Basado en la guía 08 del curso Vibe Coding CEDIA 2026 (UTE y UTPL).
