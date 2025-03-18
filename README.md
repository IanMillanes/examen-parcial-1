Bitácora del Examen Parcial 1

1) Crear un proyecto local y darle seguimiento
Crear una carpeta nueva
Se utiliza “cd C:\Users\al375973\Documents”  para navegar al lugar donde deseamos crear la carpeta, al encontrarnos en la ubicación utilizamos “mkdir proyectoLocal”
Agregue 4 archivos en ella
nos movemos a la nueva carpeta con “cd C:\Users\al375973\Documents\proyectoLocal”, ya ahí utilizamos git init para crear un repositorio vacío, creamos los 4 archivos con “echo ‘Texto’ > archivo” 
Darle seguimiento con git
utilizamos “git add .” para añadir los nuevos archivos al area de preparación, por consiguiente hacemos git commit para confirmar los cambios

2) Creación del Repositorio en GitHub
Inicio de sesión en GitHub y creación de un nuevo repositorio llamado examen-parcial-1 (público)
No se selecciona la opción de inicializar con README
Se copia la URL del repositorio

3) Subir el Repositorio a GitHub
En nuestra terminal o cmd, subimos el repositorio local de nuestra computadora al repositorio de GitHub creado
utilizamos el comando “git remote add origin https://github.com/IanMillanes/examen-parcial-1.git” y git push -u origin master para subir el repositorio local a nuestro repositorio en GitHub. Ya en GItHub nos queda hacer un pull para ver nuestros archivos creados en nuestro repositorio local en GitHub, que es igual a recargar la pagina.
Vamos a GitHub y creamos el archivo README de forma manual, agregando como primera línea “Bitácora del Examen Parcial 1”, lo guardamos.
Al realizar este paso, simplemente presionamos el botón verde para confirmar los cambios en el README

4) Recuperar cambios remotos
Ahora recupere los cambios realizados en Github a su carpeta local (archivo README)
Para esto, nos ubicamos en nuestro cmd y ejecutamos el comando “git pull” para traer la creación del README a nuestra carpeta.

5) Control y seguimiento local
Edite dos de los cuatro archivos de su carpeta
Abra su archivo README para que agregue las instrucciones ejecutadas hasta el momento
Guarde, haga un commit y suba los cambios a GitHub

6) Control y seguimiento remoto
Edite dos de los cuatros archivos de su carpeta
Presionamos el archivo a editar en GitHub, ubicamos un icono de un lápiz con el que vamos a editar el archivo, al agregar los cambios presionamos el botón verde para hacer commit.
Abra su archivo README para que agregue las instrucciones ejecutadas hasta el momento, incluida las instrucciones para la línea siguiente.
Mismo procedimiento que el anterior.
Guarde los archivos y recupere los cambios a su carpeta local
Nos vamos al cmd y realizamos un “git pull” para jalar los cambios a la carpeta local

7) Creación y uso de ramas
Creen una nueva rama para agregar otra funcionalidad, la cual debe llamarse rama-1
“git branch rama-1” para crear la nueva rama y “git checkout rama-1 para moverse a ella”
Cree dos archivos nuevos
nuevamente utilizamos el echo “texto” > archivo
En la rama-1, agregue los dos archivos recién creados
“git add .” para agregar todos los archivos pendientes por agregar
Confirmen los cambios y subanlos a GitHub.
“git commit” y “git push origin rama-1” para subirlo pero mantener la rama
Regrese a la rama main y fusione la rama-1 con ella.
“git checkout master” y “git merge rama-1”
Confirme que la fusión fue realizada exitosamente
“git log”
Asegúrese que README tenga todas las instrucciones realizadas, guardelo y suba todos los cambios al repositorio de GitHub.
