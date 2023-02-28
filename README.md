# OOP-inheritance

## Diagrama de Clases

![diagrama de clases](https://github.com/MikelBarajas38/OOP-inheritance/blob/dfe2b7ce25db510d0af5267c6bdf094581985560/diagramaClasesPersonalUniversitario.png?raw=true)

## Herencia Múltiple

### ¿Por qué becario no hereda de alumno también?

En el diagrama se describe una clase becario (_ScolarshipHolder_), la cual contiene atributos iguales a los de alumno, pero solamente hereda de Empleado (_Employee_). Si la clase fuera a heredar de dos o más clases se le llamaría herencia múltiple, lo cual posible de modelar utilizando otros lenguajes de programación (como C++). Sin embargo, Java no permite el uso de herencia múltiple para prevenir problemas de ambigüedad (léase: problema del diamante). Si una clase fuera a heredar de dos clases que contienen métodos con el mismo nombre, ¿cuál debería utilizar al llamársele? Para no lidiar con este tipo de situaciones, Java simplemente no permite usar herencia múltiple.
