# Tamalada Comunitaria — Iztapalapa

Sitio web estático para GitHub Pages con mapa de sedes y registro de participantes.

## Publicar en GitHub Pages
1. En GitHub, crea un repositorio nuevo (por ejemplo `tamalada-comunitaria-iztapalapa`).
2. Sube **todos los archivos de este paquete a la raíz** del repositorio, incluido `index.html`, `participantes.json`, `sedes.json` y `poster-tamalada.png`.
3. Abre **Settings → Pages**.
4. En **Build and deployment**, elige **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/(root)`, y pulsa **Save**.
6. Espera a que GitHub Pages publique el sitio. La URL aparecerá en esa misma sección.

## Importante
- Mantén juntos los archivos JSON, el póster y `index.html`.
- La carga de JSON requiere publicar el sitio mediante un servidor web; no abras `index.html` como archivo local.
- El mapa utiliza Leaflet/OpenStreetMap y la geocodificación consulta Nominatim. Las ubicaciones aproximadas deben verificarse antes de desplazarse.
- GitHub Pages publica contenido estático. Si el sitio necesita guardar registros nuevos de forma compartida, se requiere una API o base de datos externa; editar la vista del navegador no actualiza por sí solo los archivos del repositorio.
