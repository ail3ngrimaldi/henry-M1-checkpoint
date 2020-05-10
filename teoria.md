## Explica los siguentes conceptos con tus propias palabras. (no más de tres líneas por respuesta).

* Estructura de Datos: Es lo que almacena cualquier tipo de dato en javascript. Su almacenamiento tambien implica una organizacion determinada y en base a como sea el almacenamiento y organizacion de cada estructura de datos elegiremos uno u otro segun lo que querramos hacer.

* Lista Enlazada: Son un tipo de estructura de datos donde lo importante es que los datos esten enlazados. Estan compuestas por nodos los cuales tienen una referencia al nodo siguiente (si es simple)
 o al siguiente y al anterior (si son doblemente enlazadas). Se utilizan para datos que SIEMPRE van a estar uno detras/adelante de otro.

* Árbol: Es un tipo de estructura de datos que tiene sus nodos conectados entre si por un unico camino, con una referencia a otro nodo (estos seran conocidos como los nodos hijos), pero ninguna referencia apunta al nodo raiz (que es el superior). Tiene niveles segun la cantidad de conexiones entre node y root node.

* Closures: Se utiliza para asignarle diferentes valores a las variables y que estas tengan ese valor dentro del contexto de cada funcion, fuera de este no se podran usar con ese valor ni modificar. Tambien se puede declarar el valor de una variable en el contexto global, para poder acceder a este o modificarlo en este.

* Contexto de Ejecución: Es el contexto que creamos, del cual javascript tomará los datos que declaremos y lo que queremos que se ejecute. Contiene la información que se ejecuta a medida que lee las lineas de codigo, y la que tiene. Sirve para diferenciar valores de variables segun el contexto en que se lo asignemos, por ejemplo.

* Variable THIS: Se refiere siempre al "madre/padre". Si lo llamamos dentro de un objeto, por ejemplo, hara referencia a este. Varia según el contexto en que se lo ejecute. Si lo ejecutamos en el contexto global, this hace referencia al objeto global.

* Hoisting: Es un proceso que lleva a cabo Javascript para las funciones y variables que declaramos. Lo que hace es guardar en su memoria un espacio para determinados datos, que pueden ser dotados de valor luego, es decir que, por ejemplo, podemos invocar una función y luego declararla, sin problemas en su ejecución.

* Pasar por valor y por referencia: Cuando se pasa el valor de una variable "por valor", este queda guardado en memoria, y cuando se modifica posteriormente, el valor original se mantiene intacto. Mientras que cuando se pasa el valor por referencia, primero se guarda el valor incial en memoria, pero al ser modificado posteriormente, el valor inicial tambien cambia.

* Algoritmo: Son instrucciones que estan bien definidas y se utilizan como solucion a distintos problemas, para resolverlos. Deben ser comprensibles y eficientes, es decir que utilicen la menor cantidad de recursos que se pueda, segun el problema particular (por ejemplo, que utilice poco tiempo, poco espacio en memoria, etc.)

* Big O notation: Se trata de estimar la complejidad que va a tener una funcion, y esto se hace acercando esa funcion a una funcion conocida, que sea parecida en cuanto a complejidad. Implica la descripción del peor de los casos, que debe ser tenido como referencia para crear nuestra función y que sea mejor que la que tomamos de ejemplo.

* Inmediatly Invoked Function Expression (IIFF): Se le llama asi a la funcion que invocamos justo luego de declararla. La forma de hacerlo es poner "()" justo al cerrar la llave de la funcion que declare.
