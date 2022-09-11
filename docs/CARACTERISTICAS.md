## Comparativo de características entre Laneros (XenForo) y Discourse

A continuación proponemos una tabla que lista las características que actualmente necesitamos, su contra parte en Discourse y los comentarios al respecto de frente a la migración.

### Tabla de características

Laneros | Discourse | Comentarios
--- | --- | ---
Foros | Foros | El funcionamiento básico de un foro está incluído en Discourse
ElasticSearch | Básico | Discourse solo tiene una búsqueda basada en Postgree, por ahora no hay búsqueda con ES pero es algo que estoy dispuesto a renunciar pues aún se tendría una búsqueda básica
User Upgrades | N/A | Ya existe un [plugin de tercero](PLUGINS.md) que pueden servir
Spoiler Tag | Plugin Oficial |
Compra / Venta | N/A | En Laneros.com utilizamos un plugin de terceros que aunque era pago, dejó de mantenerse hace meses. Fue un error depender de este plugin pues es parte escencial de la sección Compra / Venta. Esta sección necesita como mínimo la característica para calificar a otros usuarios que actualmente no existe en Discourse. Mirar la posibilidad de [desarrollarla](DESARROLLO.md).
Tapatalk / App Oficial | N/A | Tapatalk es una aplicación utilizada por muchos de nuestros usuarios pero que es una pesadilla mantener, además de que no controlamos el tráfico que por allí viaja. La idea es desechar Tapatalk y la aplicación oficial por una especie de Progressive Web App. Básicamente la idea es fomentar el uso del sitio móvil de Discourse junto con notificaciones push que funcionen muy bien para que los usuarios en dispositivos móviles no extrañen a Tapatalk.
Moderación | Trust system y Community moderation | Discourse enfoca la moderación en la comunidad, algo similar a lo que hace reddit.
Adjuntos en S3 | Object Storage | Ambos lo soportan
