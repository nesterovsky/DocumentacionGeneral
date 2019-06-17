## NETLIFY

Para desplegar un proyecto virgen de angular en netlify, teniendo previamente creada nuestra cuenta en netlify con acceso de escritura y lectura sobre todos los repositorios o el repositorio a desplegar, hacemos lo siguiente:

- En el proyecto local ejecutamos: 

![1560223858516](C:\Users\Gabi\AppData\Roaming\Typora\typora-user-images\1560223858516.png)

con este comando veremos la carpeta dist en nuestro local. Procederemos a subirla manualmente al repo en github a traves del upload file:

![1560224086444](C:\Users\Gabi\AppData\Roaming\Typora\typora-user-images\1560224086444.png)

![1560224123235](C:\Users\Gabi\AppData\Roaming\Typora\typora-user-images\1560224123235.png)

aqui arrastramos la carpeta dist y cargara los archivos, colocamos el comentario para el commit y presionamos "COMMIT CHANGES"

Adicionalmente, debemos cambiar el parametro "production" ubicado en el archivo environments.ts del proyecto de "false" a "true" :

![1560224424433](C:\Users\Gabi\AppData\Roaming\Typora\typora-user-images\1560224424433.png)

subimos los cambios al repo central en github y procedemos a enlazar nuestro proyecto de github con netlify:

Ubicados con nuestro usuario en netlify, presionamos "New site from Git":

![1560224569353](C:\Users\Gabi\AppData\Roaming\Typora\typora-user-images\1560224569353.png)

![1560224600649](C:\Users\Gabi\AppData\Roaming\Typora\typora-user-images\1560224600649.png)

luego de ser autorizado, carga los repositorios a los que le diste permisos a netlify:

![1560224701483](C:\Users\Gabi\AppData\Roaming\Typora\typora-user-images\1560224701483.png)

presionamos el proyecto que queremos desplegar y completamos con la siguiente informacion:

![1560224785129](C:\Users\Gabi\AppData\Roaming\Typora\typora-user-images\1560224785129.png)

Presionamos Deploy site y se encargara de procesar la informacion. Luego de ello te permitira cambiar el nombre del dominio, para que puedas colocar uno mas personalizado:

![1560225013094](C:\Users\Gabi\AppData\Roaming\Typora\typora-user-images\1560225013094.png)

![1560225064039](C:\Users\Gabi\AppData\Roaming\Typora\typora-user-images\1560225064039.png)