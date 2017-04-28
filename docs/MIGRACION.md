# Proceso de migración

Estoy en proceso de desarrollar un [script de importación en masa de XenForo](https://github.com/discourse/discourse/tree/master/script/bulk_import) el cual es necesario debido a la cantidad de tiempo que con el [método tradicional](https://github.com/discourse/discourse/blob/master/script/import_scripts/xenforo.rb) tomaría. Los items a importar son:

- Grupos
- Usuarios
- Usuarios baneados
- Nodos
- Temas
- Estado de los temas (sticky, cerrado, borrado, moderado)
- Avatares
- Likes
- Attachments
- Passwords
- Encuestas
- Mensajes privados
- Calificaciones de usuario (cuando tenga el plugin listo)
