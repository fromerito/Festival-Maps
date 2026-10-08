# Radio Monumental Caracas

Mapa interactivo de Caracas centrado en el Estadio Monumental Simón Bolívar (La Rinconada).
Permite elegir un radio en kilómetros, muestra qué municipios y localidades abarca (con el porcentaje de cada municipio que queda dentro) y exporta la imagen en PNG.

## Archivos

- `index.html`: la página completa (incluye los límites municipales y las localidades).
- `vendor/leaflet.js` y `vendor/leaflet.css`: librería del mapa (Leaflet 1.9.4).

El mapa de fondo se carga en vivo desde CARTO, así que la página necesita internet.

## Publicar con GitHub Pages

1. Sube el contenido de esta carpeta a la raíz del repositorio, conservando la carpeta `vendor`.
2. En el repositorio: Settings → Pages → Source: "Deploy from a branch", rama `main`, carpeta `/ (root)`.
3. La página queda en `https://<usuario>.github.io/<repositorio>/` en uno o dos minutos.

## Créditos y licencias

- Mapa base: © colaboradores de OpenStreetMap, © CARTO (estilo Voyager). Uso gratuito no comercial con atribución.
- Límites municipales y ubicación de localidades: © colaboradores de OpenStreetMap, licencia ODbL.
- Leaflet: licencia BSD-2 (ver `vendor/LEAFLET-LICENSE.txt`).
