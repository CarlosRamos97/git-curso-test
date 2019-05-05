# git-curso-test
Este es un proyecto de prueba de GIT
// comandos del GIT
git init -> para inicializar un proyecto nuevo	
git status -> para ver el estado de nuestros archivos (wd,sa,r) estan los docs
git add <file> -> para agregar un archivo al staging area (sa)
git add . -> crea todos los archivos
git commit -> para crear un primer punto de control de nuestro código pero te mandará a VIN dónde escribiras un mensaje y para evitar escribe el de abajo.
git commit -m "comentario" -> Lo mismo que el commit sin "-m", pero no iras al VIN
git config --global user.email "car..."-> para configurar el email de este usuario
git config --global user "Carlos Ramos"-> para configurar el nombre de usuario
git checkout -- <file> -> para revertir los cambios de los archivos
git diff <file> --> para ver las diferencias hechas en los archivos
git branch -> Ver las ramas que hay ("master" es la rama default)
git branch "nombre" -> Crear una nueva rama
git log -> para ver los commit que haz hecho﻿
---
git branch login -> he creado una versiona llamada login
git checkout login -> cambiamos a la rama login
git branch -> estamos dentro de "login"
---
file -> archivo
--
Subir nuestro codigo al repositorio de github con los comandos

* git remote add origin https://github.com/CarlosRamos97/git-curso-test.git -> mandar a nuestro repositorio de git 

* git push -u origin master -> nos abre un login para que se suba al repositorio 

https://github.com/CarlosRamos97/git-curso-test.git -> link del repositorio

---

vin -> Es el editor de código de git desde la consola, ahí escribes un comentario para la nueva versión que estés versionando (si no te deja escribir presiona a letra i). Cuando termines presiona esc y luego :wq (write & quit)pasa salir.

.gitignore -> Es un archivo reservado de git que tenemos que crear si queremos decirle a git los archivos que no vamos a utilizar y así decida ignorarlos.
Escribe dentro de el archivo .gitignore los nombres de los archivos que desees ignorar.
Nota: Las carpetas se escriben solas y los archivos con su terminación.﻿

