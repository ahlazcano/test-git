# comandos útiles de Git

#### 1.-  para gestionar carpeta con git

    git init

Para ver archivos ocultos en Mac OS utiliza: command+shift+.

#### 2.- para poner en escena los archivos que se incluirarn en el commit 

    git add .

#### 3.- Para bajar en escena los archivos que se incluiran en el commit

    git reset .

#### 4.- Para realizar un commit  

    git commit -m "Primer Commit"

#### 5.- Para resturar el estado de los archivo al ultimo commit 

    git checkout -- .

### 6.- para ver registro de commits 

    git log

#### 7.- Para modificar el nombre del commit

para insertar presionar i

    git commit --amend

Para cerrar Esc  :wq! 

#### 8.- Para crear una rama
 
````bash
    git checkout -b rama-heroes
````
#### 9.- Para ver las ramas existentes

    git branch

#### 10.- Para cambiarse de rama 

    git checkout master

### 11.- Fusionar Ramas

    git merge rama-heroes
