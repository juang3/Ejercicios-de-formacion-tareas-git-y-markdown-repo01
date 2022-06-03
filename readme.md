 [//]: <> ()
 #   Ejercicio1
 ## Enunciado:
 1.1. Crear un directorio llamado repo01 (desde tu máquina) e inicia el repositorio en local.

 ~~~
 git init repo01
 ~~~

 1.2. Añade un documento llamado __readme.md__ (md de Mardown) y documenta en su interior todo los pasos que vas realizando para crear un repositorio.

 ~~~
 cd repo01
 touch readme.md
 nano readme.md <!-- Se escriben los pasos realizados.-->
 ~~~

 1.3. Añade el fichero al staging area y hay un snapshot hacía el repositorio en local.

 ~~~
 git add readme.md
 git commit
 <!-- Se abre el editor de textos y se escribe en él -->
    Editado el fichero readme.md con:
        1. Los pasos a seguir para realizar un repositorio en local.
        2. Los pasos a seguir para añadir el archivo readme.md al staging area y realizar un snapshot hacia el repositorio local.
 ~~~