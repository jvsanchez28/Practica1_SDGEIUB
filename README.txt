Practica1_SDGEIUB
=================

- Grupo 4 del Miercoles -

Este repositorio contiene los .jar de la practica 1 de Software Distribuït. 
Consiste en la implementación de un Domino Cliente Servidor (por terminal). El Cliente (usuario) juega contra el Servidor
una o mas partidas de dominó.

Ejecutar primero el servidor y luego los clientes que quieran jugar una partida.

Crear .jar en netbeans:
	1.- Botón secundario en el proyecto, ir a propiedades.
	2.- Seleccionar la pestaña de Packaging
	3.- Marcar la opción de Compress JAR File, aceptar.
	4.- Clean and Build el proyecto.
	5.- En el directorio donde esta el proyecto, mirar en la carpeta dist.


Ejecutar .jar por terminal:
	1.- java -jar practica.jar
	2.- Si se quiere pasar argumentos para la ejecución:
		2.1 Server:  java -jar practica.jar 1234
		2.2 Cliente java -jar practica.jar 127.0.0.1 1234

