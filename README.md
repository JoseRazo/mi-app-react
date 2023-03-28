# mi-app-react
Mi primera aplicación REACT

## Pre-requisitos

- Instalar [Docker.](https://www.docker.com/get-started)
- Instalar [Docker Compose.](https://docs.docker.com/compose/install/)

## Instalación

- Clonar repositorio `https://github.com/JoseRazo/mi-app-react.git`
- Crear APP en caso de que no la tengas creada `docker compose run --rm react-app sh -c 'npx create-react-app mi-app-react --template typescript'`
- Mover el código creado a la raíz del proyecto.
- Crear imagen docker **`docker compose build`**
- Crear contenedor **`docker compose up -d`**
- Abrir navegador y entrar a URL [127.0.0.1:4200](http://127.0.0.1:4200)

## Subir cambios del proyecto a servidor de producción

- Entrar al contenedor `docker exec -i -t react_app /bin/sh`
- Compilar el codigo **``**

##
<p style="color:yellow">Si te gusta nuestro proyecto por favor deja una estrella ☆<p>
