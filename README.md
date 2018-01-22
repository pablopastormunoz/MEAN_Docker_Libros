# MEAN_Docker_Libros

Proyecto para IISS realizado por Santiago Godoy Poce, Jose María Correro Barquín, y Pablo Pastor Muñoz.

- Los contenedores se generan automáticamente con la herramienta Docker Compose, que habrá que instalar aparte ( ver el siguiente enlace para instalar la última versión: https://docs.docker.com/compose/install/ )

- Para construir y arrancar el proyecto en sus respectivos contenedores, hay que ejecutar en el directorio del mismo la siguiente orden en una terminal:

    docker-compose up --build
  
- Para acceder a la app usar en el navegador la siguiente URL: http://localhost:4200/

- El servidor Express se encuentra en http://localhost:3000/

- La base de datos de MongoDB se encuentra en el puerto 27017

- El repositorio incluye la carpeta node_modules por seguridad 

- El proyecto completo pesa 60 megas

- Sobre el proyecto: Consiste en una lista de lectura de libros. Se pueden añadir, eliminar, consultar y editar libros de la lista. Podemos poner un libro en estado "Completado" con el botón verde. Para editar un libro, primero habrá que pulsar el botón azul, modificar los campos (nombre, descripción, y estado en el que se encuentra) y de nuevo pinchar sobre el botón azul para guardar los cambios en la base de datos (de lo contrario, nada es modificado).



