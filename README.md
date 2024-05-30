# Desafío opcional - Creando y modificando objetos

Aplicando los conceptos y herramientas aprendidas hasta ahora, nos pondremos en el caso
de que un consultorio médico requiere un programa realizado en JavaScript, que permita
almacenar y/o modificar los datos de sus pacientes. Así como filtrar y mostrar los pacientes
por nombre para poder hacer una búsqueda más rápida y ubicar la historia médica de cada
persona. En el siguiente diagrama UML se puede observar cual es la cardinalidad de los
objetos y las propiedades que tiene cada uno.

![uml](screenshot/uml.png)

Primeramente se deben mostrar todos los pacientes con sus datos personales, luego
mediante un método de búsqueda, mostrar los datos del paciente que concuerden con el
nombre que se envíe al método como argumento. Igualmente se deben proteger los datos y
evitar modificaciones directas, por lo que se debe implementar getters y setters. Todo esto
se puede mostrar en la consola del navegador web de tu preferencia.