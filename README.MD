# Instrucciones para ejecutar el proyecto

Este proyecto utiliza Docker Compose para la gestión de contenedores. A continuación, se detallan las instrucciones para ejecutar el proyecto desde cero, eliminando imágenes previamente creadas y borrando la caché de Docker.

## Paso 1: Eliminar imágenes y caché previas

docker-compose down --rmi all --volumes --remove-orphans

##Paso 2: Correr el composse
docker-compose up -d

#Estudiantes: 
#Angel Enrique Árevalo Cano 
#Josué Adan García Valiente 
#Hector Alexander Villalta Oviedo