**Comando para iniciar un repositorio en git**

git init    

**Revisar el estado del git** 

git status 

**Para subir un archivo que se encuentra dentro de tu repositorio
local, con su respectiva extesión, se utiliza el siguiente comando**

git add Nombre-de-archivo.txt

**Para hacer  un commit,se realiza a continuación lo siguiente**

git commit -m "Descripcion de los cambios realizados"

**Uso de Comodines** 

git add '*.txt' agrega todos los archivos con ese termino de extensión

**Agregar varios commits**

git commit  -m "Descripción de los cambios"

**Revisión del Log**

git log

**Repositorio Remoto**

Para agregar un repositorio local a la nube, se realiza lo siguiente

git remote add origin url del repositorio

**Push Remoto**
Se utiliza para subir cambios a nuestro repositorio en la nube

git push -u repositorio(github) repositorio local

**Pull Remoto**
 
 Se utiliza para descargar los  cambios a nuestro repositorio  local
 
 git pull -u repositorio(github) repositorio local
 
 **Ver diferencias**
 Util para revisar  los ultimos commits que se han agregado
 
 git diff HEAD HEAD apunta al ultimo commit realizado
 
 **Diferencias del Stage**
  
  El comando siguiente, revisa los cambios que se han realizado en el stage
  
  git diff --staged
  
  **Resetear un Stage**
  
  Se utiliza para sacar un archivo del Stage
  
  git reset Directotio/archivo-ejemplo.txt
  
  **Creación de una nueva rama**
  
  git branch nombre-de-la-rama
  
  **Cambio entre ramas** 
 Se Utiliza para el cambio de ramas dentro del repositoio de Git
 
 git checkout  -- nombre-de-la-rama
 
 
 **Git status -s**
 Muestra que archivos han sido borrados, cambiados y modificados 
 
 git status -s
 
 (M) modified
 (A) añadidos 
 (AM) archivos no modificados desde la ultima vez
 
 **Elimina el archivo deseado del stage**
 
 git branch -r
 
 Muestra las listas  de las  ramas que se estan siguiendo actualmente
 
  
 **Agregar un repositorio Remoto**
 
 git remote add <name> <address>
 
 
 **Remover un repositorio**
 
 git remote rm <nombre>
 
 **Remover un repositorio**
 
 Desahace cualquier cambio pero no los une 
 git fetch
 
  **Lista todas las ramas remotas**
  
  git branch -r
  
  **Borra todas las ramas remotas**
  
 git push origin :<branch name>    