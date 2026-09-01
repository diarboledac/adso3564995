# Progreso - adso3564995

## Estado actual
- Proyecto estatico revisado.
- Pagina `01-emmet/index.html` corregida para visualizacion estable.

## Tareas completadas
- Reemplace el uso de `<xmp>` por bloques `<pre><code>` con HTML escapado.
- Corregi textos visibles que podian aparecer con codificacion danada.
- Actualice rutas de imagen de Emmet a `../src/images/logo-emmet.svg`.
- Converti `src/css/master.css` de CSS anidado a selectores CSS planos.
- Agregue estilos responsivos para evitar desbordes en pantallas pequenas.

## Tarea actual
- Sin tarea pendiente en curso.

## Proximas tareas
- Revisar las carpetas `02-html`, `03-css` y `04-javascript` cuando existan o se completen.
- Corregir codificacion visible en `README.md` si se desea dejar todo el repositorio consistente.

## Problemas conocidos
- `README.md` todavia tiene texto con codificacion danada y referencia `src/images/profile.webp`, archivo que no existe actualmente.

## Ultima verificacion
- 2026-08-26: servidor local con `python -m http.server 8765 --bind 127.0.0.1`.
- `http://127.0.0.1:8765/01-emmet/index.html` respondio `200`.
- `http://127.0.0.1:8765/src/css/master.css` respondio `200`.
- `http://127.0.0.1:8765/src/images/logo-emmet.svg` respondio `200`.
- Busqueda de `<xmp>`, rutas `src/imagenes` y texto corrupto en archivos modificados: sin coincidencias.
