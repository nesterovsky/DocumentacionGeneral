# Operaciones basicas con git en local

#### Para bajarnos el repo suponiendo que hayamos hecho alguna actualizacion en la nube o simplemente queramos descargar a nuestro local un proyecto:

1- Nos ubicamos en el repo que deseamos descargar, damos click al boton "Clone or download" y luego copiamos la direccion que nos aparece:

![1556511393659](C:\Users\Gabi\AppData\Roaming\Typora\typora-user-images\1556511393659.png)

2- En nuestro local, abrimos una terminal, nos dirigimos al directorio del proyecto y colocamos 

git pull origin master

con este comando, procederemos a descargar todo el repo:

![1556511614123](C:\Users\Gabi\AppData\Roaming\Typora\typora-user-images\1556511614123.png)

listo.

---------------------------------

Tomando en cuenta que queramos descargar un repo de alguien mas en local ejecutamos

git clone y el URL copiado de la pag de github

![1557105396569](C:\Users\Gabi\AppData\Roaming\Typora\typora-user-images\1557105396569.png)

esto crea un directorio llamado "git", inicializa un directorio `.git` en su interior, descarga toda la información de ese repositorio, y saca una copia de trabajo de la última versión. 

------------------------------

Si queremos actualizar nuestro repositorio local luego de haber bajado el repo de alguien mas usando el git clone o el .zip, solo ejecutamos estando en el directorio del repo local los siguiente:

git pull origin master

![1560226454886](C:\Users\Gabi\AppData\Roaming\Typora\typora-user-images\1560226454886.png)

----------------------

PARA EL PRIMER COMMIT

ng new <miproyecto>
cd /miproyecto
git init
git add .
git commit -m "mi comentario"
git remote add origin url-del-proyect-en-github
git push -u -f origin master 



PARA LOS COMMITS SIGUIENTES

git add .
git commit -m "mi comentario"
git push origin master 