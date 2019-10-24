# Funciones
## ¿Qué es una función?
Podemos ver las funciónes como pequeños robots los cuales van a repetir la misma serie de pasos una y otra vez. Cuando reciben datos o una instrucción de ejecución, realizan un proceso, que puede repetirse las veces que sea necesario, ahorrandonos líneas de código (y tiempo).

Las funciónes tienen una estructura y están conformadas por:

* El nombre de la función (si no tiene uno, se define como función anónima).
* El proceso de la función.
* Los datos de entrada (parámetros).
* Valores de retorno.

Ejemplo:

```javascript
/* Le decimos al programa que vamos a usar una función escribiendo la palabra reservada 
 * (en inglés) "function".
 * function...
 */

/* Separados con un espacio, asignamos el identificador o nombre de la función.
 * function miPrimeraFuncion...
 */

/* Se escribe un par de paréntesis al final, en ellos se introducen los datos de entrada (parámetros) que vamos
 * a recibir cuando se mande llamar a la función, después se escriben las llaves "{}" para que dentro de ellas
 * escribamos los pasos que va a seguir esa función, ejemplo:
 */

function miPrimeraFuncion(msg){
    let sentence = "Hello World!!!";

    console.log(sentence);
}
```

Para hacer uso de las funciónes que tenemos declaradas como en el ejemplo de arriba, debemos invocarlas -o llamarlas- por su identificador o nombre, el programa interpretará esto como: "Ok, quieres hacer uso de esta función".
```javascript
//Invocamos la función anterior por su nombre y sin argumentos(un paréntesis vacío).

miPrimeraFuncion();
```

Si queremos pasar ciertos datos a la función, debemos hacerlo a través de argumentos, estos nos permiten tomar resultados de otros procesos, usarlos para calcular otro resultado, tomar una decisión o invocar otras funciones.
```javascript
//Nuestras variables:
function suma(a, b){
    // asignamos el resultado de nuestra operación a 
    // la variable de nombre res
    let res = a + b
    
    // regresamos el valor de res para que este pueda
    // ser utilizado por código externo a esta función
    return res;
}

//Pasamos los argumentos: 5 corresponde al parámetro "a", 10 corresponde al parámetro "b".
suma(5,10);
```