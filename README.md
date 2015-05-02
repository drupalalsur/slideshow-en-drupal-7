#Crar una Slideshow en Drupal 7
>Actualizado al 02-05-2015

Para ver la página del vídeo haz clic [aquí](http://drupalalsur.org/videos/crear-un-slideshow-en-drupal-7)

##Instalación

1.Descarga este repositorio.
2.Crear una base de datos con el nombre que quieras.
3.Selecciona la nueva base de datos (por ej. desde phpMyAdmin)
4.Importa la base de datos, la encuentras en el directorio con el nombre de "slideshow.sql".
5.Una vez importada tienes que editar el archivo llamado *settings.php*.
El mismo se encuentra en tu sitio *sites/default/*.
6.Modifica las siguientes líneas

		$databases = array (
		  'default' => 
		  array (
	    'default' => 
	    array (
	      'database' => 'vid_node120',
	      'username' => 'root',
	      'password' => 'root',
	      'host' => 'localhost',
	      'port' => '',
	      'driver' => 'mysql',
	      'prefix' => '',
	   	 ),
		 ),
		);

Remplaza el valor de 'database' y  de 'username' por tus datos.

6.Guarda los cambios, ahora ya puedes llamar al sitio desde el navegador.
7.Los datos de acceso al sitio son: user=drupal y la contraseña=drupal