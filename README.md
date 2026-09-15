# Gestor de Compromisos Ambientales — Prototipo MVP

Prototipo navegable (HTML estático autocontenido) del Gestor de Compromisos
Ambientales de Valor Ambiental.

## Sitio publicado

https://jistarki.github.io/Valor_Ambiental_POC/

## Estructura

- `index.html` — prototipo completo. No requiere build ni servidor: se puede
  abrir directamente en el navegador.
- `.nojekyll` — evita el procesamiento Jekyll al servir el sitio.

El sitio se publica con GitHub Pages en modo *Deploy from a branch*
(`main`, carpeta `/ (root)`): cada push a `main` republica el sitio.

## Dependencias externas

El prototipo es autocontenido salvo por dos recursos cargados desde CDN,
necesarios para que se vea y funcione correctamente online:

- Google Fonts (Barlow, Barlow Condensed)
- SheetJS `xlsx` 0.18.5 (cdnjs) — exportación a Excel
