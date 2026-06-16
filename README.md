# DataCleaner Pro

Aplicación web para limpieza y filtrado de datos tabulares (Excel / CSV), desarrollada por [DEN](https://github.com/denplus007). Todo el procesamiento ocurre en el navegador — ningún dato sale del equipo.

## Funcionalidades

- **Carga** de archivos `.xlsx`, `.xls` y `.csv` por clic o drag & drop
- **Filtros avanzados** con 10 condiciones (contiene, igual, vacío, mayor que, etc.) y lógica AND / OR
- **Limpieza rápida**: trim, mayúsculas/minúsculas, capitalizar, eliminar duplicados, borrar filas vacías
- **Detección de caracteres especiales** por categoría: control/invisibles, ancho-cero/BOM, Latin extendido, puntuación tipográfica, emojis, otros no-ASCII
- Modal de detalle por columna con codepoint Unicode, ocurrencias y ejemplos de celdas afectadas
- Resaltado visual en tabla de celdas con caracteres problemáticos
- Limpieza selectiva por categoría o columna individual
- **Columnas visibles** configurables (pills on/off)
- **Paginación** real de 50 filas con navegación
- **Exportación** a `.csv` (separador `;`) y `.xlsx` con nombre dinámico
- Dark mode automático

## Uso

Abrí directamente desde [GitHub Pages](https://denplus007.github.io/datacleaner-pro/) o cloná y abrí `index.html` en el navegador — no requiere instalación ni servidor.

## Stack

HTML · CSS · Vanilla JS · [SheetJS](https://sheetjs.com/) · [Tabler Icons](https://tabler-icons.io/)
