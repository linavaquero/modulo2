# versionamiento de codigo con GIT
## inicializacion en un repositorio
1. crear la estructura de carpetas de nuestro proyecto:
- mkdir nombre_de_la_carpeta : creamos la carpeta principal del proyecto
- cd nombre_de_la_carpeta : nos movemos a la carpeta principal del proyecto
- code . : abrir en el VSC la carpeta del proyecto
- una vez abierto el VCS nos creamos la estructura  de carpeta y los archivos necesarios para empezar a trabajar.
- abrir una nueva terminal
- corremos el comando git init : para inicializar el repositorio 
-  corremos el comando git add . : para añadir todos los nuevos archivos y carpetas al espacio de prepáracion staging area 
-   corremos el comando git commit -m "mensaje del commit" 
2 crear el repositorio remoto en nuestra cuenta GitHub
- ingresar a nuestra cuenta GitHub 
- creamos un nuevo repositorio 
- nos regresamos a la terminal del proyecto en VSC para ejecutar las  tres ultimas lineas que nos proporcionan  GitHub : git remote add origin git@github.com:     : para apuntar al remoto
- git branch -M main : para  renombrar la rama principal de Master a main
- git push -u origin main : suben todos los archivos  al repositorio remoto

## subir cambios a un repositorio
1 tener disponible una terminal en VSC
2 si queremos comprobar el estatus de los archivos de nuestros proyectos: "git status"
- git add .
- git commit -m "mensaje del commit" 
- git push -u origin main


  
