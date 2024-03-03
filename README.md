# DOCKER

En este repositorio se han añadido los archivos Dockerfile y docker-compose como parte del codelab de DOCKER del curso de SOLID & Design Patterns.

Se ha incluido un archivo Dockerfile que contiene:

-   La creación de la imagen a partir de node:18-alpine.
-   Establecimiento del directorio de trabajo en /app.
-   Copia de las dependencias del proyecto (archivos package.json y yarn.lock).
-   Instalación de las dependencias
-   Copia del código fuente del proyecto al directorio de trabajo.
-   Ejecución de la aplicación.
-

Se ha incluido un archivo docker-compose.yml que contiene la definición de los servicios y volúmenes de la aplicación, que son:

-   El servicio principal "api" basado en la imagen anteriormente creada.
-   Un servicio auxiliar "mysql" para el acceso a una base de datos mysql.
-   Definición de un volumen para la persistencia de los datos de la BD.
