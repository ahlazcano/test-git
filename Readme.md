# Comandos útiles de Git

#### 1.  Para gestionar la carpeta con git

    git init

Para ver archivos ocultos en Mac OS utiliza la combinacion de teclas "command + shift + ." y se verá en el finder la carpeta .git que estaba oculta en el diretorio gestionado con git.

#### 2. Para poner en escena los archivos que se incluirarn en el commit 

    git add .

#### 3. Para bajar en escena los archivos que se incluiran en el commit

    git reset .

#### 4. Para realizar un commit  

    git commit -m "Primer Commit"

#### 5. Para restaurar el estado de los archivos al ultimo commit 

    git checkout -- .

#### 6. Para ver registro de commits 

    git log

#### 7. Para modificar el nombre del commit

para insertar presionar i

    git commit --amend

Para cerrar Esc  :wq! 

#### 8. Para crear una rama
 
````bash
    git checkout -b rama-heroes
````
#### 9. Para ver las ramas existentes

    git branch

#### 10. Para cambiarse de rama 

    git checkout master

#### 11. Fusionar Ramas

    git merge rama-heroes

#### 12. Para borrar una rama

    git branch -d rama-heroes

#### 13. Para actualizar cambios en un repositorio git 

    git add .
    git commit -m "Readme Actualizado"
    git push

#### 14. Si quieres hacer un commit a un archivo al que ya se le esta dando seguimiento, simplemente escribe:

    git commit -am "git commit -am agregado"