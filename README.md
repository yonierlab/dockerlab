
# Docker hola mundo

Docker es una herramienta de automatización de despliegue de aplicaciones dentro de contenedores.

![logo docker](https://www.docker.com/sites/default/files/social/docker_facebook_share.png)

## Construir la imagen de docker

Para construir la imagen ejecute el siguiente comando:
```shell
$ docker build -t #minombre .
```
## Crear container

Para crear el container se debe ejecutar la siguiente instrucción:

```shell
$ docker run --rm --name web -ti -p 80:80 apache
```

> Nota: Para salir pulse control + c


## Documentación de docker

Observe la documentación de Docker [aquí]([https://docs.docker.com/get-started/](https://docs.docker.com/get-started/))
