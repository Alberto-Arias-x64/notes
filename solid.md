# Principios S.O.L.I.D.
## S. Single Responsibility (Unica Responsabilidad)
Una clase solo debe tener una responsabilidad, es decir, debe ser capaz de realizar una sola tarea.

## O. Open Closed (Abierto Cerrado)
Las clases deben ser cerrada para su modificacion pero abierta para su extensión.

## L. Liskov Substitution (Liskov Sustitucion)
Si una clase hereda de otra, entonces la clase derivada debe ser capaz de sustituir la clase base sin modificar el código de la clase derivada. (evitar agregar métodos en la clase base)

## I. Interface Segregation (Segregacion de Interfaces)
Deben existir interfaces mínimas, es decir, una interfaz por cada clase.

## D. Dependency Inversion (Inversion de Dependencias)
Dependiendo de una clase, no debe depender de otra. (inyectar dependencias)