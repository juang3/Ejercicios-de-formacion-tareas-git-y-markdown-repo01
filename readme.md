 [//]: <> ()
 #   Ejercicio1
 ## Enunciado:
 1.1. Crear un directorio llamado repo01 (desde tu máquina) e inicia el repositorio en local.

 ~~~ html
 git init repo01
 ~~~

 1.2. Añade un documento llamado __readme.md__ (md de Mardown) y documenta en su interior todo los pasos que vas realizando para crear un repositorio.

 ~~~ html
 cd repo01
 touch readme.md
 nano readme.md <!-- Se escriben los pasos realizados. -->
 ~~~

 1.3. Añade el fichero al staging area y hay un snapshot hacía el repositorio en local.

 ~~~ html
 git add readme.md
 git commit
 <!-- Se abre el editor de textos y se escribe en él. -->
    Editado el fichero readme.md con:
        1. Los pasos a seguir para realizar un repositorio en local.
        2. Los pasos a seguir para añadir el archivo readme.md al staging area y realizar un snapshot hacia el repositorio local.
 ~~~

 1.4. Crear un repositorio remoto llamado repo01, asociado a tu repositorio loca y sube los camios al repositorio remoto.

 ~~~ html
 <!-- Creado repositorio en github 
    llamado "Ejercicios-de-formacion-tareas-git-y-markdond-repo01" -->
<!-- pasos recomendados por github para realizar un repositorio local -->

1. echo "# Ejercicios-de-formacion-tareas-git-y-markdown-repo01" >> README.md
2. git init
3. git add README.md
4. git commit -m "first commit"

5. git branch -M main
6. git remote add origin https://github.com/juang3/Ejercicios-de-formacion-tareas-git-y-markdown-repo01.git
7. git push -u origin main

<!-- Los pasos 1, 2, 3 y 4 ya se han realizado en los ejercicios anteriores 1.1, 1.2, y 1.3
 Ahora se realizan los pasos 5, 6 y 7 -->
 ~~~

