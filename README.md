# Integracion_Python_C
Repositorio dedicado a al proyecto de estancia de laboratorio de investigacion del estudiante Victor Guadalupe Rivera Juarez. En el presente repositorio se deposita un manual de integracion de herramientas computacionales escritas en los leguajes de progamacion Python y c.

Integra a detalle  herramientas numericas para administrar datos utilizados en la teoria NESCGLE, detallados principalmente de la siguiente manera:
Primero integramos nociones de la suma de  variables, esto por que muchas de las funciones que se utilizan en la teoria NESCGLE  , parten de una funcion con dos variables, por lo cual aplicamos el siguiente ejemplo:

```c 
#include <stdlib.h>// include library c.
#include <stdio.h> //include functions of the library  c.

 ``` 
Utiliza una funcion que suma dos numeros de la siguiente manera:
```c 
int suma(  int  a,  int b,  int sum){
sum = a + b;
//Posteriormente podemos agregar de manera compacta la suma con la variable sum , además de agregar el return para que regrese nuestra función de la 
 //siguiente manera.

return sum ;  
//return(sum);

}

