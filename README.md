# Tercera pre-entrega de tu Proyecto final
Deberás entregar la tercera pre-entrega, correspondiente a tu proyecto final.
## Objetivos generales
Desarrollar una WEB Django con patrón MVT subida a Github.
## Se debe entregar
* Link de GitHub con el proyecto totalmente subido a la plataforma.
* Proyecto Web Django con patrón MVT que incluya:
	1) Herencia de HTML.
	2) Por lo menos 3 clases en models.
	3) Un formulario para insertar datos a todas las clases de tu models.
	4) Un formulario para buscar algo en la BD
	5) Readme que indique el orden en el que se prueban las cosas y/o donde están las funcionalidades.
### Ejecución del proyecto:
1) Ejecutar el comando python manage.py migrate para crear la base de datos
2) Ejecutar el proyecto en modo de desarrollo con python manage.py runserver
3) Acceder a http://localhost:8000
4) Todas las funcionalidades del proyecto se pueden probar desde su barra de navegación, excepto el formulario de búsqueda, disponible en todas las vistas en la barra lateral
5) El orden de creacion del proyecto es el siguiente

1. Crear autor, idioma y genero
2. ya se puede crear un libro y todos sus datos
una ves creado genero e idioma ya puden ser usados no hace falta crearlos para cada libro, solo seleccionarlos
3. si se desea se puede buscar por autor dejando limpio "buscar libro" y solo seleccionar "autor"