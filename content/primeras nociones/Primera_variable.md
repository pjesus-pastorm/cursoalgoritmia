---
title: Primera_variable
date: 2022-04-13T11:07:54+02:00
---

# título
Primera variable

## descripción
Variable como espacio para almacenar información

## conceptos
Variable y asignación de valor

## solución
Si solo se usaran constantes, las ejecuciones de los programas siempre darían los mismos resultados. Para ser útil, se deben poder especificar datos diferentes en cada ejecución y diferentes valores ser usados en los cálculos, comparaciones, etc.
Tanto los datos iniciales, como los cálculos intermedios o los resultados se deben almacenar en la memoria del ordenador, y deben ser accesibles a través de un nombre. Este conjunto de nombre y valor almacenado se denomina variable (puesto que el valor pude cambiar). 
Las variables pueden aparecer en expresiones para calculas nuevos valores, en comparaciones de condiciones, o en cualquier otro elemento del lenguaje. 
Hay variables de diferentes tipos, numéricas, cadenas de caracteres, fechas, horas, o incluso conjuntos de valores de otros tipos. 

Cuando se ejecutan los programas se pueden almacenar información, colocándolas a la izquierda de una igualdad, como en una asignación: var a= 3+5; //lo que hace almacenar un 8 en la variable de nombre "a". También se puede usar ese valor, colocando el nombre en cualquier operación. 
En algunos lenguajes además tienen un tipo, lo que limita los valores que pueden contener, pudiendo ser únicamente caracteres, valore numericos, enteros o decimales, de determinados rangos, cadenas de caracteres, etc. 
Dependiendo del tipo así pueden operarse con ellas. Por ejemplo la suma "+" de dos variables numéricas genra la suma de las cantidades; la suma "+" de dos cadenas de caracteres genera la concatenación de las cadenas.
En algunos lenguajes las variables se declaran para especificar el tipo de forma previa a su utilización.
En el lenguaje usado: javaScript, no es precisa la declaración, (aunque si es conveniente, por aclarar el código).
También hay variables de conjuntos de valores iguales y accesibles por un índice, como los vectores, pero se verán más adelante

Como en el caso de los comentarios, los nombres de laa variables no son significativos para el ordenador que los ejecuta, pero si para la comprensión de otros programadores, por ello deben ser significativos y suficientemente claros para el fin y el valor que almacenan.

## código
```javascript
// almacenamos el saludo en una variable:
var mensaje ="Hola mundo";
//y finalmente mostrar dicho mensaje
alert (mensaje);
//ello nos permitiría modificar el mensaje.`
```

## ejercicios
Definir variables para los ejemplos anteriores

## referencias
http://www.w3schools.com/js/js_variables.asp
