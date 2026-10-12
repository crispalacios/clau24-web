HOUSEWATCHERS.ES — ACTUALIZACIÓN OCTUBRE 2026

Cambios:
- _redirects: redirecciones 301 de clau24.com y www.clau24.com preservando la ruta (en Netlify).
- IMPORTANTE: el dominio clau24.com debe seguir conectado como alias y DNS válido; www.clau24.com también debe estar conectado si se quiere redirigir ese subdominio.
- Logo de navegación recortado para eliminar márgenes transparentes y mostrado más grande, también adaptado a móvil.
- Guía de octubre en español, catalán, inglés y francés, enlaces desde los 4 índices del blog y sitemap actualizado.
- llms.txt como referencia informativa opcional para asistentes; no garantiza menciones o indexación en buscadores de IA.
- Conservados los datos estructurados, canonicals, hreflang, robots.txt y contenidos existentes.

Publicación: sustituir los archivos del sitio por todos los contenidos de este ZIP, conservando la estructura plana y el archivo _redirects. Si el deploy se hace por GitHub, confirmar que se han subido los archivos nuevos.

PRUEBAS POST-DEPLOY:
1. https://housewatchers.es/ y las 4 versiones de idioma.
2. https://housewatchers.es/blog.html y el artículo de octubre.
3. https://housewatchers.es/sitemap.xml y /llms.txt.
4. curl -I https://clau24.com/servicios.html → HTTP 301 Location: https://housewatchers.es/servicios.html.
5. Validar formularios y WhatsApp, móvil y navegación.

NOTAS:
- El ZIP no modifica DNS ni publica automáticamente en Netlify.
- No se ha cambiado información legal o precios comerciales.
- Conviene revisar las reseñas y testimonios del sitio para asegurarse de que son reales y autorizados.
