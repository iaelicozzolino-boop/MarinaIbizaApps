# Marina Ibiza Apps (panel)

Panel PWA en un solo `index.html`, sin build. Se publica con GitHub Pages desde `main`: https://iaelicozzolino-boop.github.io/MarinaIbizaApps/

- La lista de apps está en el bloque `APPS` de `index.html` y abre cada app en un iframe.
- Apps enlazadas: `revision-de-contadores/#recepcion`, `listado-contadores/`, `alarma-guias/` (repos hermanos con el mismo usuario de GitHub).
- `v2/index.html` solo redirige a la raíz, porque hay iPhones con la app instalada desde `/v2/`. No borrar.
- Al cambiar archivos cacheados, subir el número de `mi-apps-vN` en `sw.js`.
- Sin modo administrador ni PIN. Las apps se editan en el código.
