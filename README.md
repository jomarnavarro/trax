# Aplicacion TRACKS

## Introduccion

Tracks es una aplicacion Web cuyo objetivo es llevar registro de las tareas pendientes de un usuario para ayudarlo a ser mas productivo.  Como tal tiene una GUI Web y una REST API que usa XML como formato de Payload.

## Comandos Docker

La aplicacion es muy sencilla de arrancar, debido al esfuerzo de [staannoe](https://hub.docker.com/u/staannoe), quien creo esta imagen.  Simplemente hay que bajar la imagen para arrancar la aplicacion:

```docker pull staannoe/tracks```

Tal como se indica en la pagina de [dockerhub de tracks](https://hub.docker.com/r/staannoe/tracks/), se utiliza este comando para arrancar el contenedor, utilizando  un puerto diferente al 80 en caso de ya tenerlo ocupado.

```docker run -d --name=tracks -p 80:80 staannoe/tracks```
