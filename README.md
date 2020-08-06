# Requerimientos generales banco de preguntas

Santiago Gómez Almeyda 20161020503

Jheisson Enrique Fortich Suarez 20172020049

Kevin Andres Malaver Cobos 20171020001

## Requerimiento 1.1:
* Nombre: Crear entidad.
* Roles: Docente, administrador.
* Condiciones de entrada: La entidad generada debe ser coherente con las condiciones asignadas a cada subtipo de entidad.
* condiciones de salida: La entidad quedara habilitada para ser asociada, eliminada o editada.
* ### Escenarios:
  1. Generar los campos de texto para ingresar los datos basicos de la entidad.
  2. Validar los datos leidos.
  3. Guardar los datos de la entidad en la base de datos.
  4. Se produce una excepcion lanzando el manejador de excepciones presentando el mensaje al usuario.

![Crear entidad](https://github.com/Forson666/Requerimientos-generales-banco-de-preguntas/blob/master/req%201.1.JPG)

## Requerimiento 1.2:
* Nombre: Eliminar entidad.
* Roles: Docente, administrador.
* Condiciones de entrada: La entidad que se desea eliminar debe haber sido creada con anterioridad.
* condiciones de salida: La entidad quedara eliminada.
* ### Escenarios:
  1. Generar los campos de texto para identificar la entidad a eliminar.
  2. Validar los datos leidos.
  3. Eliminar los datos de la entidad de la base de datos.
  4. Se produce una excepcion lanzando el manejador de excepciones presentando el mensaje al usuario.

![Eliminar entidad](https://github.com/Forson666/Requerimientos-generales-banco-de-preguntas/blob/master/req%201.2.JPG)

## Requerimiento 1.3:
* Nombre: Asociar entidad.
* Roles: Docente, administrador.
* Condiciones de entrada: Debe existir la entidad que se desea asociar y no debe estar asociada actualmente.
* condiciones de salida: Las entidades quedaran asociadas.
* ### Escenarios:
  1. Generar los campos de texto para identificar la entidad a asociar.
  2. Validar los datos leidos.
  3. Guardar los datos de la asociacion en la base de datos.
  4. Se produce una excepcion lanzando el manejador de excepciones presentando el mensaje al usuario.

![Asociar entidad](https://github.com/Forson666/Requerimientos-generales-banco-de-preguntas/blob/master/req%201.3.JPG)

## Requerimiento 1.4:
* Nombre: Visualizar entidad.
* Roles: Docente, administrador.
* Condiciones de entrada: Debe existir la entidad que se desea visualizar.
* condiciones de salida: Se mostraran los datos de la entidad.
* ### Escenarios:
  1. Generar los campos de texto para identificar la entidad a visualizar.
  2. Validar los datos leidos.
  3. Se produce una excepcion lanzando el manejador de excepciones presentando el mensaje al usuario.

![Visualizar entidad](https://github.com/Forson666/Requerimientos-generales-banco-de-preguntas/blob/master/req%201.4.JPG)

## Requerimiento 1.5:
* Nombre: Desasociar entidad.
* Roles: Docente, administrador.
* Condiciones de entrada: Debe existir la entidad que se desea Desasociar y debe estar asociada actualmente.
* condiciones de salida: Las entidades dejaran de estar asociadas.
* ### Escenarios:
  1. Generar los campos de texto para identificar la entidad a desasociar.
  2. Validar los datos leidos.
  3. Guardar los cambios en la base de datos.
  4. Se produce una excepcion lanzando el manejador de excepciones presentando el mensaje al usuario.

![Desasociar entidad](https://github.com/Forson666/Requerimientos-generales-banco-de-preguntas/blob/master/req%201.5.JPG)

## Requerimiento 1.6:
* Nombre: Editar entidad.
* Roles: Docente, administrador.
* Condiciones de entrada: Debe existir la entidad que se desea Editar.
* condiciones de salida: La entidad modificada quedará registrada con los nuevos valores.
* ### Escenarios:
  1. Generar los campos de texto para identificar la entidad a editar.
  2. Validar los datos leidos.
  3. Guardar los cambios en la base de datos.
  4. Se produce una excepcion lanzando el manejador de excepciones presentando el mensaje al usuario.

![Editar entidad](https://github.com/Forson666/Requerimientos-generales-banco-de-preguntas/blob/master/req%201.6.JPG)

## Diagrama de clases:
![Diagrama clases](https://github.com/Forson666/Requerimientos-generales-banco-de-preguntas/blob/master/Diagrama%20de%20clases.JPG)
