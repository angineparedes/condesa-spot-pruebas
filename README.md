# Condesa Spot — prototipo V6 de integración

Esta carpeta constituye **un único sitio estático** listo para probar en GitHub Pages. No se ha publicado.

- **Escritorio y tablet ancha (768 px o más):** portada y navegación originales de V3, presentados en el documento `escritorio-v3/index.html` dentro de la misma web.
- **Móvil (767 px o menos):** presentación V4.1, con búsqueda arriba y barra inferior de Inicio, Categorías, Novedades, Favoritos y Más.
- El cambio es **automático según el ancho de la ventana**, sin necesidad de elegir archivos distintos.
- Ambas vistas consumen `catalogo.json` y `config.js` de la raíz. Las vistas de producto incluyen tres acciones; cuando faltan URLs, los botones permanecen desactivados.

## Vista local

Desde esta carpeta, inicia un servidor HTTP estático: `python3 -m http.server 8000`. Abre `http://localhost:8000`. En Chrome puedes cambiar el ancho de la ventana o usar las herramientas de dispositivo y recargar.

## Archivos editables

- `catalogo.json`: productos, precios, categorías, estado de novedades/destacados, enlaces `landing` y `pago`, e imágenes.
- `config.js`: número global de WhatsApp, que debe permanecer vacío hasta que decidas configurarlo.
- `assets/`: imágenes provisionales del catálogo.

## Antes de publicar

Revisar la portada y navegación en Chrome escritorio (1440 px), móvil (390 px y 375 px), y dentro del navegador de Instagram. En esta primera versión todavía se mantiene el documento V3 separado internamente para conservar su apariencia exactamente. No contiene archivos digitales originales a la venta.

**Importante:** precios e imágenes de productos son provisionales; no hay pasarela ni teléfono activos. No reemplazar GitHub Pages hasta aprobar las pruebas.
