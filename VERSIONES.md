# Historial de versiones — Contador Agrícola

Esta rama reconstruye cómo evolucionó el programa a partir de las copias que quedaron guardadas en el computador del autor (Descargas, Escritorio y Documentos). Cada commit es una versión; la fecha es la de la copia guardada, que suele ser el momento en que esa versión se generó o descargó. La columna "Cambios detectados" se calculó automáticamente comparando las funciones de una versión con la anterior.

La versión vigente está en la rama `main`.

| Versión | Fecha | Archivo | Tamaño | Título | Copia original | Cambios detectados |
|---|---|---|---|---|---|---|
| v01 | 2026-08-22 14:45 | `index.html` | 20 KB | ContaFrutos | `contador-frutos-offline.html` | primera versión de este archivo |
| v02 | 2026-08-22 14:50 | `index.html` | 11 KB | ContaFrutos En Vivo | `gemini-code-1787421043634.html` | agrega cargarModelo, procesarVideo; quita applySlidersFromSettings, dilate3x3, erode3x3, escapeHtml, hueInRange, loadSettings, refreshSliderLabels, rgbToHsv … |
| v03 | 2026-08-22 14:55 | `index.html` | 8 KB | ContaFrutos HSV En Vivo | `gemini-code-1787421336952.html` | agrega getSettings, hueInRange, procesarFrame, rgbToHsv; quita cargarModelo, getSpecies, goHome, goSpecies, loadData, procesarVideo, renderHome, renderSpecies … |
| v04 | 2026-08-25 20:59 | `index.html` | 15 KB | Contador Agrícola | `index.html` | agrega actualizarConteoEnVivo, cargarMemoria, dibujarBoundingBoxes, entrarACamara, escapeHtml, guardarMemoria, iniciarCamara, iniciarModelo …; quita getSettings, hueInRange, procesarFrame, rgbToHsv |
| v05 | 2026-08-25 21:04 | `index.html` | 13 KB | Contador Agrícola (MediaPipe) | `gemini-code-1787702648160.html` | ajustes internos (mismas funciones) |
| v06 | 2026-08-25 21:08 | `index.html` | 18 KB | Contador Agrícola | `index (1).html` | agrega cajaPareceFruto, rgbToHsv |
| v07 | 2026-08-25 21:08 | `index.html` | 19 KB | Contador Agrícola | `gemini-code-1787702932987.html` | agrega procesarTracks, resetearTracker; quita actualizarConteoEnVivo |
| v08 | 2026-08-25 21:41 | `index.html` | 18 KB | Contador Agrícola ONNX | `gemini-code-1787704913333.html` | agrega calcularIoU; quita cajaPareceFruto, rgbToHsv |

| final | — | — | — | versión publicada en `main` | — | — |

© 2026 Vicente Bohle Alveal. Todos los derechos reservados; ver la licencia de la rama `main`.
