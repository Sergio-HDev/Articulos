# Qué es un algoritmo
En matemáticas, lógica, ciencias de la computación y disciplinas relacionadas, un algoritmo es un conjunto de instrucciones o reglas definidas y no-ambiguas, ordenadas y finitas que permite, típicamente, solucionar un problema, realizar un cómputo, procesar datos y llevar a cabo otras tareas o actividades. Esta es la definición de algoritmo directamente sacada de la Wikipedia, pero, ¿qué significa todo esto?

En este artículo se procurará hacer entender a cualquier persona qué es un algoritmo informático, tanto si es un graduado en Ingeniería Informática, un estudiante o alguien que no sabe absolutamente nada de algoritmia. La información que se encuentra por internet o libros es confusa y muchas veces demasiado especializada para entender. Para esta explicación me serviré de un símil que todos pueden entender: una receta de cocina.

Primero hay que explicar qué es una receta. Es una descripción ordenada de un procedimiento culinario, que suele consistir en una lista de ingredientes necesarios, seguido de una serie de instrucciones con la cual se elabora un plato o una bebida específica. Se suelen incluir anotaciones para aclarar pasos, utensilios a usar,...

Cuando un cocinero usa una receta para cocinar, se vale de todos sus elementos para guisar, aderezar, adobar, aliñar, condimentar, batir o freír unos alimentos. Podemos ver todos estos procesos como minirecetas para realizar pequeñas tareas de un conjunto.

Entonces, ¿qué tiene que ver esto con un algoritmo informático? Pues, se sustituye receta por algoritmo, cocinero por ordenador y plato de cocina por solución. Haciendo este intercambio ya se puede empezar a entender un algoritmo, que no es más que una serie de instrucciones y pasos a seguir con unos ingredientes (variables, constantes,...) para solucionar un problema, procesar unos datos o llevar a cabo una tarea.

Las recetas se valen del lenguaje común, sea en español, inglés o cualquier idioma. Los algoritmos informáticos usan lenguajes de programación. Ejemplos de ellos son Python, C/C++, Java, Kotlin, Rust, y muchos más. En la mayoría de estos lenguajes, las instrucciones se van ejecutando una a una de principio a fin, como en una receta. Este escrito no pretende enseñar a programar, sino sentar las bases de la algoritmia.

La operación más básica es la suma. En ella se toma un mínimo de dos números y se combinan sus valores. Sea la suma de 1 + 2, los ingredientes son un 1 y un 2, y el proceso o tarea que se va a realizar es la suma, que a su vez es la solución que se busca. Esta operación se podría ver así:

```
solución = 1 + 2
```

Viendo este pequeño código asalta una duda. ¿Por qué asignamos la suma a “solución”? En el desarrollo de software, la mayoría de las veces vamos a querer guardar un valor para poder usarlo más adelante. Para eso definimos la variable “solución”, asignándole el resultado de 1 + 2. Al final de esa ejecución, en “solución” hay guardado un 3.

Si por ejemplo se quieren hacer varias sumas y restas, solo hay que escribir varias sumas una después de otra. Al fin y al cabo se le están dando unos pasos a seguir a la máquina.

```
solución1 = 4 + 9
solución2 = 7 - 2
solución3 = solución1 - solución2
```

En este caso, el ordenador ha guardado un 13 en “solucion1”, un 5 en “solución2” y, por último, se restan los valores guardados en “solución1” y “solución2”, dando lugar a la resta de 13 - 5, que guarda un 8 en “solución3”.
En cocina se puede ver como una ensalada, comenzando con el lavado de las verduras, para luego trocearlas, mezclarlas en un bol (suma de todo) y por último, aliñar la preparación. 

Para ir finalizando, falta uno de los conceptos más importantes en programación, los bucles. En cocina, un bucle no es más que una acción como batir realizada muchas veces. Al hacer una tortilla, se baten los huevos hasta que se vean bien batidos. En un algoritmo se puede ver como, por ejemplo, sumar 1 a una variable hasta que llegue a 100.

```
mientras número < 100 haz:       (símbolo para menor que <)
    número = número + 1
```

Para finalizar, anteriormente, en la descripción de la receta, se comentó que a veces se incluyen anotaciones varias. Esto en programación se puede ver como los comentarios o la documentación, una práctica recomendada si no necesaria en trabajos conjuntos. Cuando hay muchos programadores en un mismo proyecto, hace falta entender el código de los demás. Para eso sirve la documentación. Son aclaraciones de cómo funciona un programa, qué hace, cómo usarlo y demás. Estas anotaciones tienen una manera de indicarse en cada lenguaje para que el computador no las ejecute. Los comentarios y documentación se colocan para que las personas interpreten el código, no la máquina.

El mundo de la informática es tan amplio y apasionante como intrincado y confuso. Empezar en una nueva rama supone un desbordamiento de información de las muchas tecnologías que se usaron en su momento o se usan ahora. Una buena práctica es seleccionar una en concreto y empezar a aprender, poco a poco. Para aprender a programar se recomienda empezar con Python, ya que su curva de aprendizaje es muy amigable y cada vez es más popular, aunque siempre puedes elegir tu propio camino.
