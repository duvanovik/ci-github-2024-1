# Documentación del Proyecto | Duvan García



## Introducción

Este proyecto consiste en una GitHub Action que automatiza la construcción y el empuje de una imagen Docker a Docker Hub. La acción se activa cuando se realiza un push en la rama main del repositorio.

### Instalación

No se requiere instalación específica para utilizar esta acción. Sin embargo, asegúrate de tener una cuenta en Docker Hub y de haber configurado los secretos necesarios en tu repositorio de GitHub para autenticarte en Docker Hub durante la ejecución de la acción.

### Configuración

1. Asegúrate de tener un archivo Dockerfile en la raíz de tu repositorio que defina cómo construir la imagen Docker.
2. Configura los secretos DOCKERHUB_USERNAME y DOCKERHUB_TOKEN en la configuración de tu repositorio de GitHub con tus credenciales de Docker Hub.

### Uso

Para utilizar esta GitHub Action, simplemente realiza un push en la rama main de tu repositorio en GitHub. La acción se ejecutará automáticamente y construirá la imagen Docker según lo definido en el Dockerfile, y luego la empujará a Docker Hub.


### Evidencias

**Evidencia dockerhub**
![docker](https://github.com/duvanovik/ci-github-2024-1/assets/42594511/adb5396b-8dc7-4495-b97d-690229f231b0)

**Evidencia pipeline**
![docker2](https://github.com/duvanovik/ci-github-2024-1/assets/42594511/45b812f4-38e6-4b04-81af-b84ca958e1f0)




