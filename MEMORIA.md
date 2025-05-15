# Practica Docker - PHP

## Imagen 1: PHP puro
- Basado en php:8.2-cli
- Usa servidor embebido de PHP

## Imagen 2: Ubuntu + Apache + PHP
- Basado en Ubuntu 22.04
- Instala Apache2 y PHP
- Clona app sencilla desde GitHub

## Contenedores
- Imagen 1 probado en puerto 8080
- Imagen 2 probado en puerto 8081
- 20 contenedores de la imagen 2 mapeados de 8001 a 8020

## Scripts
- `lanzar.sh`: lanza 20 contenedores
- `borrar.sh`: los elimina

