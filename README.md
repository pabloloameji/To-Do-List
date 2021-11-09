# ToDo List

## ¿Que es?

ToDo List es una página que permite hacer una lista de objetivos o tareas a realizar, permitiendo al usuario marcar las tareas ya realizadas, eliminarlas de la lista y agregarla cuantas desee.

## Implementación

** omitir las comillas en los comandos **
1.	Se debe de clonar el repositorio:
    *	Para esto utilizamos el comando *“ git clone https://github.com/pabloloameji/To-Do-List.git ”* 
2.	Se abre la carpeta del repositorio.
3.	Abrimos la terminal como administrador y nos ubicamos dentro de la carpeta.
4.	Una vez ubicados dentro de la carpeta creamos la imagen utilizando el comando *“ docker build . ”* 
5.	Una vez terminado el proceso utilizamos el comando *“ Docker images ”* para ver el IMAGE ID de la imagen que se creó.
6.	Utilizamos el comando *“ docker run -d -P 80:80 [IMAGE ID] apachectl -D FOREGROUND ”*.
7.	Ahora solo queda poner la ip de nuestra maquina en un navegador.
