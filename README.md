Proyecto: exam_docker_git

Este proyecto contiene una aplicación sencilla en Python que muestra un mensaje con tu nombre y la fecha actual.
El objetivo es ejecutar la aplicación dentro de un contenedor Docker utilizando Dockerfile y Docker Compose.

Estructura del proyecto
exam_docker_git/
│── app.py
│── Dockerfile
│── docker-compose.yml
│── README.md

Cómo ejecutar el proyecto
Construir y ejecutar el contenedor con Docker Compose

En la carpeta del proyecto, ejecuta:
------------------------------------
docker compose up --build
------------------------------------

Esto hará lo siguiente:
------------------------------------
Construirá la imagen Docker usando el Dockerfile.

Creará y ejecutará un contenedor con la aplicación.

Mostrará en pantalla el mensaje generado por app.py.
------------------------------------

Comandos útiles
Ver logs del contenedor
------------------------------------
docker compose logs -f
------------------------------------

Detener y eliminar los contenedores
------------------------------------
docker compose down
------------------------------------

Descripción de archivos
====================================
app.py

Archivo principal de Python que imprime tu nombre y la fecha actual.
====================================

====================================
Dockerfile

Define la imagen Docker que ejecuta la aplicación Python.
====================================

====================================
docker-compose.yml

Gestiona la construcción y ejecución del contenedor mediante Docker Compose.
====================================