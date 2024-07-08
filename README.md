# Foro Hub - REST API
Foro Hub es una REST API que simula diversos endpoints de un foro, incluyendo el inicio de sesión de usuarios, la creación de tópicos, su actualización y su eliminación lógica en una base de datos. Este proyecto forma parte de la formación de Alura Latam ONE (Oracle Next Education).

## ¿Cómo funciona?
Esta aplicación utiliza Spring Framework para la creación y seguridad de endpoints, y JWT para la autenticación de los usuarios. Una vez que el usuario envía la petición de inicio de sesión a la ruta correspondiente, puede acceder a los métodos relacionados con los tópicos, como consultar, crear, actualizar y borrar.

Cada tópico creado por los usuarios se guarda en una base de datos MySQL. Cuando un usuario consulta o actualiza un tópico, se muestra el nombre del autor de la creación o actualización. Por último, un usuario puede borrar un tópico, pero para mantener la integridad de la base de datos y la persistencia de los datos, este borrado es solo de forma lógica.
