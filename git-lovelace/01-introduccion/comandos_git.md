# comandos de git 
## comando para ver la version de git

- git -v
- git --version

## comando para configuracion inicial de git

- git config --global user.name "your name"
- git config --global user.email "your emai"

## comando para ver o editar la cofiguracion git(tecla i para empezar a escribir cuando se muestra el listado) 
 para salir del edit ctrl + o y ctrl +x y si es VIM esc + :wq

-git config --global --list
-git config --global --edit

## como inicializar git en un directorio

- git init

## comando para saber el estado de nuestros arcrivos

- git status

## comando para listar las versiones de mi proyecto

-git log
-git log --oneline

## comando para cambiar la version 

- git checkout <id del commit o nombre de la rama>

## pasos para crear una version en nuestro codigo
1. agregar todos los archivos al commit 

- git add .
- git add *.js
- git add index.js
- git add styles.js

2. tomar la foto del codigo (crear una nueva version (fotografia))

- git commit -m "nombre del commit"