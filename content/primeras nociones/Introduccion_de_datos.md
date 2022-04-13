---
title: Introduccion_de_datos
date: 2022-04-13T11:07:54+02:00
---

# título
Introducción de datos

## descripción
Entrada de información para la ejecución con valores diferentes: saludar con el nombre introducido

## conceptos
Instrucción: prompt

## solución
Primero preguntamos al uusario con la sentencia "prompt". 
Cuando se ejecute el ordenador para la ejecución de instrucciones hasta que el usuario introduce una cadena por el teclado y pulsa "INTRO".
En ese momento, el valor introducido se almacena en la variable nombre.
En la segunda instrucción se muestra un mensaje que resulta de la concatenación de dos valores uno constante y el nombre introducido.

NOTA: "Prompt" por defecto nos devuelve una cadena. Cuando queremos introducir un número es necesario convertirlo con parseInt(cadena).
Así:
var num=parseInt("5.324"); // carga 5.324 en num.

## código
```javascript
//este es un ejemplo de saludo variable
//el nombre nos lo introducirán por el teclado
var nombre=prompt ("Introduzca su nombre");
//y mostraremos la concatenacion de la constante
//y el valor de la variable introducida
alert ("Hola "+ nombre);`
```

## ejercicios
La misma ejecución con nombre de variable diferentes.
Ejecución con números.

## referencias
http://www.w3schools.com/jsref/met_win_prompt.asp
