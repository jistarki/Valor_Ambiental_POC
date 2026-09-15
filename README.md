# Gestor de Compromisos Ambientales — Prototipo MVP

Prototipo navegable (HTML estático autocontenido) del Gestor de Compromisos
Ambientales de Valor Ambiental.

## Sitio publicado

https://jistarki.github.io/Valor_Ambiental_POC/

## Estructura

- `index.html` — prototipo completo. No requiere build ni servidor: se puede
  abrir directamente en el navegador.
- `.github/workflows/pages.yml` — publica el contenido de la raíz en GitHub
  Pages en cada push a `main`.

## Dependencias externas

El prototipo es autocontenido salvo por dos recursos cargados desde CDN,
necesarios para que se vea y funcione correctamente online:

- Google Fonts (Barlow, Barlow Condensed)
- SheetJS `xlsx` 0.18.5 (cdnjs) — exportación a Excel
