# Meyparking — copia para GitHub Pages (`meyparjeffrey/meyparking-legal`)

Carpeta **espejo** del sitio estático publicado en GitHub Pages (URL pública mínima para Play Console).

## Contenido

- `_config.yml` — configuración Jekyll (sin tema remoto; diseño propio).
- `_layouts/default.html` — cabecera y pie con marca MEYPAR.
- `assets/css/meypar-legal.css` — colores alineados a la app (`Color.kt`) y a **meypar.com** (rojo `#e62144`, fondos `#121212` / `#f0f0f0`).
- `index.md`, `privacy-policy-es.md`, `terms-of-service-es.md` — fuente de verdad sincronizada con `../privacy-policy-es.md` y `../terms-of-service-es.md`.

## Sincronizar con GitHub

Desde la raíz del repo Android, con permisos sobre `meyparjeffrey/meyparking-legal`:

1. Copiar estos archivos al clon del repo legal **o**
2. Subir vía API REST / editor web de GitHub.

Tras cada cambio, GitHub Pages tarda 1–3 minutos en regenerar el sitio.
