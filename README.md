Realización de ejercicio Repositorio - README - Commit inicial - Push inicial
1. Cree un repositorio en github
2. Clone dicho repositorio en local utilizando git clone "link"
Una vez clonado correctamente, utilicé el comando cd para moverme hacia el repositorio creado
3. Cree un archivo local README.md utilizando el comando touch 
4. Edité el archivo con vs studio code antes de enviarlo al repositorio remoto
Guardo el archivo editado
5. Con git status corroboro que aún tengo el archivo sin preparar
6. Con el comando git add preparo el archivo 
7. Realicé un commit inicial utlizando git commit -m ""
8. Utilizo git status para corrobar el estado
9. Por ultimo para esta tarea, utilizo el comando git push para enviar al repositorio remoto los cambios realizados.

Realización de ejercicio Ignorar archivos
1. Investigación: es un archivo que Git usa para determinar qué archivos y carpetas debe ignorar al realizar operaciones de seguimiento de cambios
2. Cree un fichero privado.txt utilizando el comando touch, luego una carpeta con el nombre privada utilizando el comando mkdir
3. Edité el archivo .gitignore con las lineas 
             privado.txt
             privada
4. Agregué un fichero1.txt al repositorio local utilizando touch, git add, git commit -m

Realización de ejercicio Crear una rama V0.2
1. Con el comando git branch cree dicha rama
2. Posicione mi carpeta de trabajo en esta rama utilizando el comando git checkout v0.2
3. Agregué un fichero 2.txt utilizando touch, git add, git commit -m

Realización de ejercicio Crear rama remota v0.2
1. Subí los cambios al repositorio remoto utilizando git push origin v0.2

Realización de ejercicio Merge directo
1. Me posiciono en la rama master utilizando git checkout main 
2. Realizo un merge de la rama v0.2 en la master utilizando el comando git merge v0.2

Realización de ejercicio Merge con conflicto
1. En la rama main escribo el mensaje "Hola" en el fichero1.txt, comandos: git add, git commit -m 
2. Me posiciono en la rama v0.2 
3. Escribo el mensaje "Adios" en el fichero1.txt, comandos: git add, git commit -m
4. Me posiciono nuevamente en la rama main
5. Realizo un merge con git merge v0.2

Realización de ejercicio Listado de ramas
1. Investigación:
--merged : Muestra las ramas que están fusionadas en la rama actual
--no merged : Muestra las ramas que no están fusionadas en la rama actual

Realización de ejercicio Arreglar conflicto
1. Abro el archivo fichero1.txt, arreglo el conflicto dejando lo que quiero en el archivo
2. Realizo un git commit -m "Arreglar conflicto"

Realización de ejercicio Borrar rama
1. Elimino la rama v0.2 utilizando el comando git branch -d 

Realización de ejercicio Listado de cambios
1. Utilizo el comando git config --global alias.list 'log --oneline --decorate --graph --all'
2. Utilizo git list para ver el listado de cambios











