# Variables

## ¿Qué es una variable?

Son contenedores, como cajas, que pueden almacenar cierta cantidad de cosas como dulces, frutas o verduras, el tamaño o el tipo de caja, va a ser determinado según qué hemos guardado en ellas. Siguiendo ese ejemplo, si nuestra caja está llena de manzanas, podríamos decir que nuestra caja es del tipo "frutas".
<br/>
A las variables les podemos identificar con un nombre, que podemos asignar a gusto propio, sin embargo, es una buena práctica ponerle un nombre, corto, que defina su uso, como: "container", que nos indica que es un contenedor.

## Tipos de variables.

El tipo de datos que puedes guardar en una variable son:

* ### Cadena
Almacena una secuencia de caracteres ordenados que siempre van entre comillas, pueden ser dobles o sencillas. Se compone de letras del alfabeto, números o símbolos (@, !, /). Es decir, cuando deseas asignar frases, nombres u oraciones a una variable debes hacerlo con un tipo cadena.

```
// Como puedes ver la variable esta identificada como palabra.
// Y se le asigna la frase "Esto es una cadena" como el valor a almacenar.

let palabra = "¡Esto es una cadena!";

let otraPalabra = "tucorreo@correo.com";
```

* ### Números Enteros.

Los números enteros, en matemáticas, son el conjunto que contienen los números naturales de menos infinito a infinito positivo. Así pues, las variables de enteros contienen números de ese conjunto, exceptuando los irracionales o decimales, que se redondean, si es que son el resultado de una operación.
<br/>
En resumen, esta variable almacena un número que no tienen decimales, ejemplo: 10, 20, 100, etc.

![Recta Numérica](https://upload.wikimedia.org/wikipedia/commons/thumb/8/83/Integers-line.svg/706px-Integers-line.svg.png)

```
//Las variables NO pueden ser identificadas por un número, 
//deben de tener, al menos, una letra al inicio.

let diez = 10;

let iso1020 = 1000;
```

* ### Números Reales.
Conocido como "coma flotane" (*float point* en inglés) almacenan datos decimales muy pequeños o números muy grandes (gracias a una forma de notación científica usada en las computadoras)
```
//Números como 0.324984
//O resultados de operaciones aritméticas que tienen como resultado números irracionales.

let pi = 3.14159265359;

let decimal = 0.00000534;
```
![Imagen de Pi](https://as01.epimg.net/tikitakas/imagenes/2017/03/14/portada/1489510011_902538_1489510263_sumario_normal.jpg)

* ### Valores lógicos(booleanos).
Contienen solo dos tipos de valores, verdadero o falso (true // false) y están destinados a operaciónes lógicas o decisiones que dependan de un simple si o un no.

```
// Nos sirve para tomar decisiones del tipo si/sino

let verdadero = true;
let falso = false;
```

## Fuentes
* [Fing - Variables y tipos](https://www.fing.edu.uy/inco/cursos/fpr/wiki/index.php/Variables_y_Tipos)
* [Wikipedia - variables](https://es.wikipedia.org/wiki/Variable_(programaci%C3%B3n))