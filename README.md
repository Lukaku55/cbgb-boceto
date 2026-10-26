# CBGB Distribución — propuesta de rediseño

Propuesta de rediseño para [CBGB Distribución](https://www.cbgbdistribucion.com.ar/), hecha por Canelo. **No es el sitio oficial de CBGB.**

Es un único archivo estático (`index.html`), sin dependencias ni paso de compilación. Se publica en Vercel desde la rama `main`.

## Contenido

- Verificación de edad, hero con shader WebGL, recorrido narrativo, catálogo con búsqueda y filtros, ficha de producto, carrito y página 404.
- Datos: snapshot real del catálogo de CBGB (`/api/products/list`) del **2026-10-21**. Los precios y el stock no se actualizan solos.
- Las fotos de producto se cargan desde el servidor de CBGB.

## Pendiente de integración

- Checkout con cuenta (login, envío/retiro, descuentos, MercadoPago) y carrito sincronizado con el sistema actual.
- Formulario de contacto y newsletter.
- Fotos de producto en alta resolución.

## Indexación

El sitio no se indexa: `noindex` en el HTML y en la cabecera `X-Robots-Tag` (`vercel.json`).

## Ver localmente

Abrí `index.html` en el navegador, o serví la carpeta con cualquier servidor estático.
