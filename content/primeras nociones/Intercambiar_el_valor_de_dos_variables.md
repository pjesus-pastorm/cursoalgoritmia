---
title: Intercambiar_el_valor_de_dos_variables
date: 2022-04-13T11:07:54+02:00
---

# título
Intercambiar el valor de dos variables

## descripción
Inicialmente comenzar con dos variables y dos valores diferentes y mostrar que finalmente el valor de una es el de la otra y viceversa

## conceptos
Asignación

## solución
Hay que tener cuidado con el enunicado, ya uqe partiendo de dos valores:
var a1= "uno";
var a2="dos";
Se podría pensar que es tan simple como indicar:
a1=a2;
a2=a1;
Pero si ejecutamos secuencialmente almas instrucciones, la primer almacena en a1 el valor "dos" y la segunda de nuevo almacena el valor "dos " en a2 (ya que el valor "uno" se ha perdido.
Por ello en este caso resulta imprescindible usar una variable auxiliar para almacenar el valor de la priemra variable y usarla finalmente para cargarlo en la segunda.

## código
```javascript
//damos cualquier valor a una variable
var a1= "uno"; 
//y otro diferente a otra segunda variable
var a2="dos"; 
//definimos una variable auxiliar para 
// guardar uno de los valores
var aux=a1; 
// cambiamos el valor de la segunda a la primera
a1=a2; 
//guardamos en la segunda el valor de la variable aux, de la primera
a2=aux; 
//ya podemos mostrar que se han intercambiado los valores
alert ("Al final a1 vale "+a1+" y a2 vale "+a2);`
```

## ejercicios
Mover el valor de una variable a1 a a2, el de a2 a a3 y el de a3 a a1

## referencias
http://www.w3schools.com/js/js_assignment.asp
