# GUIA BASICA PARA GITHUB	
Para poder crear repositorios, subir y comentar tus proyectos
con github necesitas aprender una serie de pasos. Los pasos 
son sencillos para ejecutar tus proyectos desde tu maquina. 
Asumimos que ya tienes instalado Github en tu maquina.	

# Crear un nuevo repositorio
Instrucciones: Crearemos el repositorio desde la pagina web 
de Github con el usuario que utilizas:

1- Damos clic en la parte superior, en el boton que tiene
   la forma del simbolo de la suma.	

2- Damos clic en New Repository	

3- Se nos abre una serie de casillas para rellenar el nombre	
   de repositorio que tendra el proyecto, una descripcion que	 
   que tendra, si es publico el proyecto y lo demas lo dejamos	
   asi como esta.	

4- Damos clic en Create Repository	

5- Ahora ya tenemos un repositorio nuevo para el proyecto.	

# Subir el proyecto alojado en la maquina	
Instrucciones: Siga los pasos que se le solicitan para poder
subir los archivos de los proyectos.	

1- Se supone que ya tienes acceso desde la terminal.	
2- Ahora creas una carpeta con el nombre del proyecto.	
3- Dentro de la carpeta creas el archivo README.md con el comando touch		
4- Ahora teclea el comando git init	
5- ahora que ya tenemos creado el archivo lo subimos con el comando git add README.md	
6- Agregamos un comentario al archivo, con el comando	
   $ git commit -m "Comentario breve sobre el archivo"	
7- Ahora colocamos la ruta donde esta ubicado nuestro proyecto con el comando:		
   $ git remote add origin git@github.com:smartdesignsv/guideGithub.git			
8- Ahora ponemos los archivos en la carpeta del proyeto	para subirlos al alojamiento de Github con el comando:	    
   $ git push -u origin master	
9- Luego de hacer esto, ya tendremos subido el archivo y si deseas subir mas archivos solo hace los pasos anterior de esta guia sobre como subir al alojamiento.	
10- Ahora si haces una modificacion a cualquier archivo que tiene el proyecto, solo debes repetir los pasos anteriores.		

