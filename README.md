# Práctica de Git y GitHub

# Nombre

### Farid Antonio Zavala Barron

# Matrícula

### 2630039

# Práctica

Creación y sincronización de un repositorio local con GitHub

# Objetivo

El objetivo de esta práctica fue aprender a crear un repositorio local usando Git, conectarlo con GitHub y aprender a pasar cambios de la computadora a GitHub y también de GitHub a la computadora

## Procedimiento realizado

Primero fue hacer la carpeta en el escritorio para en esa misma inicializar git y crear 2 archivos datos. txt y README.md luego se sincronizo el repositorio local con Github para subirlos de la DB a github con git push -u origin main
en github se edito por primera vez el texto de datos.txt y se subio lo guardado luego se sincronizaron los cambios en el dispositivo local y se volvio a editar para subir un atercera vez a github y listo ahi termina la practica Xd

## Comandos de Git utilizados

git init sirve para iniciar un repositorio de Git en una carpeta.

git branch -M main sirve para poner main como la rama principal.

git status sirve para ver si hay archivos nuevos o cambios en el repositorio.

git add . sirve para agregar los archivos y cambios al Staging Area.

git commit -m "mensaje" sirve para guardar los cambios realizados.

git remote add origin URL sirve para conectar el repositorio local con el repositorio de GitHub.

git remote -v sirve para comprobar que el repositorio de GitHub esté conectado.

git push sirve para mandar los cambios de la computadora a GitHub.

git pull origin main sirve para traer los cambios de GitHub a la computadora.

## Creación del repositorio local

Primero creé la carpeta llamada practica-git-Farid-zavala en PowerShell y en ella escribí git init para crear el repositorio local y utilicé git branch -M main para poner main como la rama principal 

## Vinculación con GitHub

se crea en GitHub un repositorio y se copia el URL en la PowerShell con el comando git remote add origin URL y para verificar se usa el git remote -v

## Sincronización Local -> GitHub

Para hacer la sincronización del dispositivo local a GitHub primero se hacen los cambios en el archivo y se sube a staging con git add -A y luego se hace el commit para finalmente usar git push para subir los cambios a GitHub.

## Sincronización GitHub -> Local

para l asincronizacion desde GitHub primero se edito el archivo y luego se hizo un commit pero ahora en GitHub y despues de guardar los cambios se sincroniza con el comando git pull origin main

## Archivos del repositorio

El repositorio tiene dos archivos principales.

README.md que es este mismo arcgivo donde se describen los pasos

datos.txt que sirve para verificar que se hicieron las ediciones solicitadas

## Conclusión

esta practica me ayudo a reforzar lo aprendido en clase sobre git y GitHub y tambien a saber como sincronizar los cambios desde local a GitHub y viscebersa para cuando sea necesario como subir trabajos o guardar los cambios que se lleguen a realizar en algun proyecto futuro