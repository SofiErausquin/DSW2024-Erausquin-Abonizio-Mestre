# Propuesta TP DSW

## Grupo
### Integrantes
* legajo - Apellido(s), Nombre(s)
* 51490  - Erausquin, Sofia
* 51153  - Abonizio, Abril
* 51494  - Mestre, Marcos

### Repositorios
* [frontend app](http://hyperlinkToGihubOrGitlab)
* [backend app](http://hyperlinkToGihubOrGitlab)
*Nota*: si utiliza un monorepo indicar un solo link con fullstack app.

## Tema
### Descripción
Somos un centro de ski y ofrecemos el servicio de compra de diferentes tipos de pases para acceder al centro en el cual podrán realizar ski o snow. Además se ofrecen tipos de clases con instructores para que principiantes en estos deportes puedan disfrutar de la experiencia.  


### Modelo
link:
https://drive.google.com/file/d/1svq_grbS4N1rKJ-4NkbK0uvPjkfvipR4/view?usp=sharing


*Nota*: incluir un link con la imagen de un modelo, puede ser modelo de dominio, diagrama de clases, DER. Si lo prefieren pueden utilizar diagramas con [Mermaid](https://mermaid.js.org) en lugar de imágenes.

## Alcance Funcional 

### Alcance Mínimo

*Nota*: el siguiente es un ejemplo para un grupo de 3 integrantes para un sistema de hotel. El 

Regularidad:
|Req|Detalle|
|:-|:-|
|CRUD simple|1. CRUD Tipo Pase<br>2. CRUD Tipo de Clase<br>3. CRUD Turno <br>4. CRUD Persona|
|CRUD dependiente|1. CRUD Pase {depende de} CRUD Tipo pase<br>2. CRUD Clase {depende de} CRUD Tipo de clase y CRUD Turno<br>3. CRUD Uso {depende de} CRUD Pase|
|Listado<br>+<br>detalle| 1. Listado de pases comprados filtrados por rango de fechas, muestra dni, nombre y apellido de la persona, id, descripcion, fechaOtorgado del pase y nombre de Tipo de Pase, => detalle CRUD Pase => detalle CRUD Tipo de Pase => detalle CRUD Persona<br> 2. Listado de Clases disponibles de determinada actividad en una fecha determinada, muestra fecha, tipo actividad, turno, cupos disponibles.|
|CUU/Epic|1. Realizar compra de un pase<br>2. Reservar una clase de ski o snow.|


Adicionales para Aprobación
|Req|Detalle|
|:-|:-|
|CRUD |1. CRUD Tipo Pase<br>2. CRUD Pase<br>3. CRUD Uso<br>4. CRUD Persona<br>5. CRUD Clase<br>6. CRUD Tipo de Clase<br>7. CRUD Turno<br>8. CRUD Precio|
|CUU/Epic|1.Realizar compra de un pase<br>2.  Reservar una clase de ski o snow.<br>3. Registrar uso de pase.|


### Alcance Adicional Voluntario

*Nota*: El Alcance Adicional Voluntario es opcional, pero ayuda a que la funcionalidad del sistema esté completa y será considerado en la nota en función de su complejidad y esfuerzo.

|Req|Detalle|
|:-|:-|
|Listados ||
|CUU/Epic||
|Otros||

