## Redirección de URLs y SEO

Discourse maneja un tipo de direcciones completamente diferente a XenForo por lo que hay que tener una estrategia clara en este sentido y evitar pérdida de elementos indexados en Google. Inicialmente indicaremos aquí algunos recursos que hemos encontrado sobre el tema para luego de estudiados tomar la mejor decisión.

- [El sitemap en Discourse no es necesario](https://meta.discourse.org/t/1-million-topics-takes-millions-of-days-to-get-indexed-without-sitemap-in-robots/57234)
- [Plugin de Sitemap](https://meta.discourse.org/t/discourse-sitemap-plugin/40348?source_topic_id=57234)
- [Redireccionar con Permalinks](https://meta.discourse.org/t/redirecting-old-forum-urls-to-new-discourse-urls/20930) - esto no es recomendable puesto que habria que agregar 600.000+ urls a la base de datos.

# Posibles soluciones
- Redireccionar con NGINX (esto es posible siempre y cuando se mantengan los Ids)
- Modificar las rutas en Ember y Rails
