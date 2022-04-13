---
title: Sumar_dos_numeros
date: 2022-04-13T11:07:54+02:00
---

# título
Sumar dos números

## descripción
Concepto de operación

## conceptos
Operación con variables: suma (o concatenación)

## solución
Las variables intervienen en operaciones. Se pueden sumar (nombres de) variables y el resultado es la suma de los valores de las mismas. 
Además se puede asignar valores a las variables. Consiste en indicar el nombre de variable en el lado izquierdo de un signo igual ("=") y una expresión en el lado izquierdo. En cualquier manual de JavaScript podrás estudiar la forma de generar expresiones, pero a través de los ejemplos, igualmente podrás aprender los principales operadores que se usan para calcular con valores o con otras variables. El sentido de esta igualdad es el de ejecutar las operaciones del lado derecho y almacenar el resultado en la variable expresada en el lado izquierdo.
Como ejemplo se puede además ejecutar el programa introduciendo valores de lados que no sean numéricos para ver el efecto de la operación registrada. El signo de la operación demandada es "+", de suma. Calula la suma de los dos argumentos uméricos de cada lado. Si los argumentos son literales realiza la concatenación; lo que resulta en este caso.

## código
```javascript
//pedimos el primer número
var num1=parseInt(prompt ("Introduzca un numero")); 
//pedimos que introduzcan el segundo
var num2=parseInt(prompt ("Introduzca otro numero")); 
//calculamos la suma y la almacenamos en una variable
var suma= num1+num2; 
//mostramos por pantalla el resultado
alert ("La suma es "+suma);`
```

## ejercicios
Calcular el producto de dos números. El operador es "*" y no el operador usado en el cole "x".
El valor a mostrar en un alert puede ser una expresión. Modificar el programa anterior para que use esta posibilidad.

## referencias
http://www.w3schools.com/js/js_operators.asp
