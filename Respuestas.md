# **Actividad de Programación II**.
## *Felipe Banco.*
## *Desarrollo de Software IES 9023.*
- - -
## **Introducción a Git y Github**

***1) ¿Qué es Git?***

Git es una herramienta definida como un sistema de control de versiones, es open source y fue desarrollada por Linus Torvalds

***2) ¿Por qué queremos utilizar Git?***

Utilizamos Git para administrar toda la complejidad de un programa y todos sus cambios, brinda comunicación con otros programadores que trabajan en un mismo proyecto desde cualquier parte del mundo. El sistema Git cuenta con un registro de cada línea de código, de cada versión del programa, junto con la fecha en que se hcieron dichos cambios en el código guardandólos a todos. 

***3) ¿Qué es el Bash que instala Git?***

El Git Bash es un herramienta característica de Git de tipo consola para administrar y gestionar todo el desarrollo del proyecto. Funciona por medio de comandos. 

***4) Describa los estados (working directory, staging area, repository).***

* Working directory: Sitio donde el programador se encuentra trabajando en los archivos del proyecto. Se ejecuta por medio del comando "git init".
* Staging Area: Segundo estado de git donde se cargan los archivos para su correspondiente guardado y visualizar la losta de cambios de todas las versiones del programa. Se agregan los archivos con git add.
* Repository: Una vez que se guardaron todos cambios en los archivos se los sube al repositorio con el comando git commit. 

***5) Describa el flujo para crear un nuevo repositorio Git.***

Para inicializar un repositorio de código:

Paso 1) Abrir una carpeta o terminal con click derecho y seleccionar
* “Git Bash Here”.

Paso 2) Abrir la consola de Windows= Tecla Windows+R:
* Escribir:
* cmd + Enter.
* cd Desktop. 
* cd + “Nombre de Proyecto”.

Paso 3) Abrir la consola Git Bash:
* Escribir:
* pwd (ruta de nuestro proyecto, es decir el directorio actual).
* cd Desktop.
* cd + “Nombre de Proyecto”.
* ingresamos "ls".
* git init (inicializar un nuevo proyecto).
* Ahora nos encontramos en el Working Directory.

***6) Describa el flujo para agregar un archivo simple al repositorio.***

Para agregar un archivo simple a nuestro repositorio escribimos:

* Ejecutar:
* git init
* git status (visualizar el estado actual de nuestros archivos).
* git add + “name file” (agregar nuestro archivo al staging area).
* git commit (agregar un punto de partida para controlar el código), luego se nos muestras dos opciones dentro de este comando:
* * git config --global user.email "nombre@example.com". Este comando sirve para asociar una dirección al usuario que ha  hecho los cambios.
* * git config --global user.name "Nombre". Asociar el proyecto al nombre de usuario.

* Tomamos un snapshot: git commit para dar un punto de partida.
* Se abre un editor de código llamado bin.

***7) Describa el flujo para cambiar el archivo agregado y guardar los cambios en el repositorio.***

Abrimos nuestro archivo y realizamos los cambios que deseamos, luego escribimo git status y sisualizamos todas las modificaciones en dicho elememento. Para agregar un archivo escribimos git diff para visualizar los cambios, luego git add "name file" y ya agregamos el archivo y para verificar su estado git status, después git commit para guardar dichos cambios(texto+:qw) luego se muestran todas las modificaciones realizadas.

***8) ¿Cómo hago para ignorar un archivo o carpeta?***

Creando un nuevo archivo con un nombre ".gitignore" + "name file". 

***9) Explique qué es un branch. Dé un pequeño ejemplo de cómo haría uno.***

Un branch es un comando o atajo para crear versiones alternativas a los proyectos. Para crear uno primero tenemos que tomar un snapshot, luego git branch + “name folder”, y para verificar escribimos git branch y visualizamos los nombres de las versiones alternativas.

***10) ¿Qué hago con 'git add'?***

Transferir archivos de working directory a staging area.

***11) ¿Cómo cambiamos de un branch a otro?***

Escribimos git checkout + “name branch” y ya estariamos dentro de la version solicitada.

***12) Investigue qué es Markdown y responda todas las preguntas anteriores en este lenguaje (con el nombre del archvio RESPUESTAS.md). Súbalo al repositorio.***

