# sexotiendas.com

Sitio estático de [sexotiendas.com](https://sexotiendas.com), desplegado en Cloudflare.

## Estructura

- `index.html`: portada pública y estilos del sitio.
- `content/blog/`: artículo editorial firmado por Sofía.
- `assets/`: fotografía oficial autorizada y estilos editoriales.
- `site/`: salida estática generada para el Worker.
- `robots.txt`: reglas de rastreo.
- `sitemap.xml`: sitemap principal.
- `_redirects`: normalización del dominio `www`.

## Publicación

El repositorio contiene fuentes estáticas; el generador canónico de PBNS crea `site/` con portada, índice de blog y artículo. El Worker existente `sexotiendas` publica esa carpeta. No se crea otro Worker ni se cambian sus dominios.

- Rama de producción: `main`
- Directorio de salida: `site/`
- Dominio principal: `https://sexotiendas.com`

## Gestión

El repositorio está preparado para incorporarse al inventario y al flujo editorial de PBNS.
