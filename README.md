# Mis Taxis

Prototipo móvil para registrar taxis sin comprobante.

## Subir a GitHub

Sube el contenido de esta carpeta a la raíz de tu repositorio. `index.html` debe quedar en la raíz junto a `app.js`, `config.js`, `city-map.svg` y `aig-transparent.png`.

Para usar GitHub Pages: en Settings → Pages selecciona Deploy from a branch, la rama principal y la carpeta / (root). La app requiere HTTPS (GitHub Pages lo proporciona) o localhost para acceder a la ubicación.

## Probar localmente

Desde esta carpeta ejecuta:

```sh
python3 -m http.server 8765
```

Abre http://localhost:8765.

## Alcance del prototipo

Contraseña de demostración: **viáticos**, con acento. La lista y contraseña están en `config.js`, visibles para quien acceda al repositorio o al sitio. No es autenticación segura: no usar para gastos reales hasta implementar acceso seguro y revisar privacidad.

Los viajes se guardan únicamente en este navegador y dispositivo; el CSV permite exportarlos. GitHub Pages no agrega base de datos ni sincronización entre usuarios. El GPS exige permiso al inicio y final. Ciudad y estado se consultan en BigDataCloud solo con consentimiento. El indicador refleja disponibilidad de ubicación, no el interruptor físico del GPS. Los kilómetros no se calculan automáticamente.
