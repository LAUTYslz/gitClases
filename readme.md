# GIT Desarrollo Colaboorativo

Esto es una guia creada para facilitar el entendimiento e implementación de la herramienta conocida como GIT, desarrollada por Linus Torvalds, y cuya finalidad es el control de versiones de los diferentes proyectos que realicemos.

## Configuración inicial

Comandos que debemos utilizar tanto para crear un proyecto con git, como para establecer la configuracion de nuestro nombre y correo a utilizar en cada una delas confirmaciones de cambios. El parametro *--global* indica que dicha configuracion aplica para todos los proyectos del mismo usuario.

* **git init**: inicializa un repositorio en el directorio actual.
* **git config --global user.name** `username`: define de manera global el nombre con el que nos identificamos.
* **git config --global user.email** `email`: define el correo de contacto para las confirmaciones de cambios.