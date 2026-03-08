<div align="right">
	<img src="https://pixelsafari.neocities.org/dividers/bluestarribbon2.gif" width="50%">
			<img src="https://pixelsafari.neocities.org/dividers/bluestarribbon2.gif" width="49%">
		</div>
</div>


<h1 align="center">
·.★·.·´¯`·.·★ Portafolio Móviles ★·.·´¯`·.·★.· 
</h1>

## --------------------------------------------------------------------------------------
<div align="center">
	Este repositorio contiene los ejercicios trabajados en la unidad. 
</div>

<div align="center">
  El objetivo principal es servir como material de aprendizaje para comprender cómo aplicar Dart.
</div>

## --------------------------------------------------------------------------------------

<h2>
	<img src="https://i.pinimg.com/originals/99/f0/e0/99f0e02f90185be9fbfb46e62ddfa9f3.gif" width="5%">
	Estudiante
</h2>
- || Sandra Carolina Perales Rodriguez ||
 - || Desarrollo de Aplicaciones Móviles ||
 -  || ITIID-4 || -
<h2>
	<img src="https://i.pinimg.com/originals/e4/96/0c/e4960c1d084132279f17ca869846c00c.gif" width="4%">
	Códigos

</h2>
<details>
<summary>Unidad 1</summary>

<details>
<summary>01_holamundo</summary>

Es un código simple que imprimi el texto hola mundo
El programa presentado está escrito en Dart y constituye el ejemplo clásico de iniciación en cualquier lenguaje de programación. La función main() es el punto de entrada del programa, es decir, el lugar donde comienza la ejecución. Dentro de ella se encuentra la instrucción print('Hello, World!');, que envía a la consola el texto “Hello, World!”. Este ejercicio tiene como propósito mostrar la estructura mínima de un programa en Dart y comprobar que el entorno de desarrollo funciona correctamente.

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/U1/01_holamundo.dart)
</details>

<details>
<summary>02_dataTypes</summary>

Este programa en Dart muestra distintos tipos de datos y estructuras del lenguaje. Comienza con la función main(), que es el punto de entrada del programa. En la primera sección se declaran variables numéricas: int a = 10;, double b = 3.14;, una variable entera opcional int? c; que puede ser nula, y una variable late int d; que se inicializa después con el valor 20. Se imprimen estas variables y se realiza una operación aritmética con a + b. Luego se trabajan las cadenas de texto: se definen variables como String nombre = 'caro';, String apellido = "Piz";, y se muestra cómo concatenar cadenas ('$nombre $apellido').

En la sección de booleanos se declara bool isActive = true; y se utiliza la negación lógica para obtener isNotActive. Después se presentan las listas: una lista heterogénea var general = [...] y una lista tipada List<String> villanos = [...]. Se modifica un elemento, se agregan valores repetidos y se observa cómo se comporta la lista. Tambien se introducen los conjuntos (Set), que eliminan duplicados automáticamente, mostrando cómo se agregan elementos repetidos y cómo se convierten listas en conjuntos con toSet().

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/U1/02_dataTypes.dart)

</details>

<details>
<summary>03_finalConst</summary>

Este programa en Dart tiene como objetivo mostrar la diferencia entre variables declaradas con var, final y const, además de cómo se comportan las listas cuando se definen con estas palabras clave. La variable var a = 10; es mutable, lo que significa que puede cambiar su valor más adelante. La variable final double b = 10; se asigna una sola vez y no puede ser modificada después de su inicialización, aunque si es un objeto, sus elementos internos sí pueden cambiar. La variable const double c = 10; es una constante en tiempo de compilación, lo que implica que su valor es inmutable y fijo desde el inicio.

En cuanto a las listas, final List<String> personasFinal = ['Caro', 'Piz']; define una lista cuyo contenido puede modificarse (por ejemplo, se le puede agregar un nuevo elemento con .add()), pero la referencia a la lista no puede ser reasignada a otra lista distinta. Por otro lado, List<String> personasConst = const ['Caro2', 'Piz2']; crea una lista constante, lo que significa que no se pueden modificar sus elementos ni agregar nuevos valores, ya que está protegida contra cambios. En el código, cuando se intenta hacer personasConst.add('piz2');, se producirá un error porque las listas constantes son inmutables.

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/U1/03_finalConst.dart)

</details>

<details>
<summary>04_comments</summary>

Este archivo en Dart tiene como propósito mostrar los distintos tipos de comentarios que se pueden utilizar en el lenguaje y cómo se integran dentro del código. Al inicio se incluye un bloque de comentario con /** ... */, que suele emplearse para documentación general del archivo, indicando datos como la fecha de creación y el autor. Luego, dentro de la función main(), se utilizan comentarios de una sola línea con //, útiles para explicar instrucciones puntuales, y comentarios multilínea con /* ... */, que permiten abarcar varias líneas de explicación. También se muestran los comentarios de documentación con ///, que son especiales porque se usan para describir clases, funciones o elementos del código y pueden ser procesados por herramientas de documentación automática.

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/U1/04_comments.dart)

</details>

<details>
<summary>05_mathOperators</summary>

El objetivo de este ejercicio fue entender cómo funcionan los operadores en Dart. Vimos las operaciones básicas (suma, resta, multiplicación, división) y operaciones más específicas como el módulo, la división entera, la negación y los operadores de incremento/decremento. Además, del cómo los operadores de asignación compuesta simplifican la escritura del código, haciendo más clara y eficiente la manipulación de valores.

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/U1/05_mathOperators.dart)


</details>

<details>
<summary>06_operators</summary>

Este ejercicio muestra cómo los operadores de asignación condicional (??=) permiten inicializar variables nulas de forma segura, y cómo los operadores condicionales (?:) permiten tomar decisiones rápidas dentro de una sola línea de código.

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/U1/06_operators.dart)

</details>

<details>
<summary>07_read</summary>

Este ejercicio muestra cómo realizar entrada y salida estándar en Dart, cómo manejar variables opcionales (String?), y cómo convertir cadenas a números con int.parse(). Lo cual es muy útil para comprender la interacción entre el programa y el usuario.

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/U1/07_read.dart)

</details>

<details>
<summary>08_helloName</summary>

Este programa en Dart muestra cómo realizar una interacción sencilla con el usuario a través de la consola. Se importa la librería dart:io, que permite usar funciones de entrada y salida estándar. Dentro de la función main(), se solicita al usuario que escriba su nombre con stdout.write('Cual es tu nombre? ');. La entrada se captura mediante stdin.readLineSync(), que devuelve una cadena opcional (String?) porque el usuario podría no ingresar nada.

Luego, el programa imprime un mensaje con print('tu name es: $nombre!');, mostrando el valor ingresado. En este caso, si el usuario escribe un nombre, se verá reflejado en la salida; si no escribe nada, el valor será null.

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/U1/08_helloName.dart)

</details>

<details>
<summary>09_sum</summary>

Este programa en Dart muestra cómo realizar operaciones básicas de entrada y salida con números ingresados por el usuario. Se importa la librería dart:io para poder usar stdout y stdin. En la función main(), primero se solicita al usuario que ingrese el primer número con stdout.write('Ingresa el primer numero: ');. El valor se captura con stdin.readLineSync()! y se convierte a entero mediante int.parse(). Lo mismo ocurre con el segundo número.

Luego, ambos valores (a y b) se suman y se almacenan en la variable n. Finalmente, se imprime el resultado con print('resultado es: $n!');.

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/U1/09_sum.dart)

</details>

<details>
<summary>10_concat</summary>


Este programa en Dart solicita al usuario que ingrese su nombre, apellido y segundo nombre, y luego imprime el nombre completo en la consola. Se importa la librería dart:io para poder usar stdout.write() y stdin.readLineSync(), que permiten mostrar mensajes y leer entradas desde la consola.


[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/U1/10_concat.dart)

</details>

<details>
<summary>11_ifBasic</summary>

Este programa en Dart ejemplifica cómo comparar dos números ingresados por el usuario y determinar cuál es mayor. Se importa la librería dart:io para poder usar stdout.write() y stdin.readLineSync(), que permiten mostrar mensajes en consola y leer entradas. En la función main(), primero se solicita el primer número y se convierte a entero con int.parse(). Lo mismo ocurre con el segundo número. Luego, se utiliza una estructura condicional if-else para comparar los valores e imprime cual es el mayor o si son iguales.

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/U1/11_ifBasic.dart)
</details>

<details>
<summary>12_Nested</summary>

Este programa en Dart tiene como propósito ordenar cuatro números ingresados por el usuario de mayor a menor. Para ello, se importa la librería dart:io, que permite leer datos desde la consola. En la función main(), se solicita al usuario que ingrese cuatro números (a, b, c, d), cada uno convertido a entero con int.parse().

El algoritmo utiliza una variable auxiliar (aux o temp) para intercambiar valores entre las variables. Primero compara a contra b, c y d, asegurando que a quede con el mayor valor posible. Luego compara b contra c y d, y finalmente c contra d. Después se repite un bloque adicional de comparaciones para garantizar que todos los valores estén correctamente ordenados.

Al final, el programa imprime los números de mayor a menor.

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/U1/12_Nested.dart)

</details>

<details>
<summary>13_menus</summary>

Este programa en Dart implementa un menú interactivo que permite al usuario calcular áreas y volúmenes de distintas figuras geométricas, o salir del programa. Se utilizan las librerías dart:io para la entrada/salida en consola y dart:math para funciones matemáticas como pi y pow.

En la función principal main(), se ejecuta un bucle infinito while (true) que muestra el menú principal con tres opciones: calcular área, calcular volumen o salir. Según la opción ingresada, se llama a la función correspondiente (calcularArea() o calcularVolumen()), o se rompe el bucle si se elige salir.

La función calcularArea() presenta un submenú con tres figuras: círculo, triángulo y rectángulo. Dependiendo de la elección, se solicitan los valores necesarios (radio, base, altura) y se aplica la fórmula correspondiente, y lo mismo aplica para calcularVolumen() pero para las figuras 3D.

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/U1/13_menus.dart)

</details>

<details>
<summary>14_tablamult</summary>

Este programa es una tabla de multiplicar interactiva que se repite hasta que el usuario decida salir. Se importa la librería dart:io para manejar la entrada y salida en consola.

En la función main(), se declara la variable test inicializada en 1. Luego se utiliza un bucle while (test != 0) que se ejecuta mientras el valor ingresado no sea cero. Dentro del bucle, el programa solicita al usuario un número con stdin.readLineSync()!, lo convierte a double y lo guarda en test. Si el usuario ingresa 0, el bucle se rompe y el programa termina.

Si el número es distinto de 0, se ejecuta un ciclo for que va desde 1 hasta 50. En cada iteración se calcula el producto de test por el valor de i y se imprime en formato de tabla, mostrando todas las multiplicaciones hasta el 50.

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/U1/14_tablamult.dart)
</details>

<details>
<summary>15_calif</summary>

Este programa en Dart convierte calificaciones del sistema estadounidense (A+, A, B, C, D, F) a sus equivalentes en el sistema mexicano (10, 9, 8, 7, 6, 5).
El programa solicita al usuario que ingrese una calificación en el sistema americano. Para validar la entrada, se usa un bucle while (!valido) que se repite hasta que el usuario escriba una calificación correcta. La entrada se procesa con trim() para eliminar espacios y toUpperCase() para convertirla a mayúsculas, asegurando que coincida con los valores de la lista usa.

Si la calificación ingresada existe en la lista, se obtiene su índice con usa.indexOf(entrada) y se usa ese índice para acceder a la lista mex, mostrando la equivalencia. Si la calificación no es válida, se imprime un mensaje de error y se vuelve a pedir la entrada.

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/U1/15_calif.dart)
</details>

<details>
<summary>16_sumas</summary>

El programa muestra un mensaje inicial indicando que se deben introducir números y que el valor 0 detendrá la ejecución. Luego, se utiliza un ciclo while (x != 0) que se repite mientras el usuario no ingrese cero. Dentro del bucle, cada número introducido se convierte a tipo double y se suma a la variable acumuladora y. Cuando el usuario introduce 0, el bucle se rompe y el programa imprime el resultado final mostrando la suma total. 

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/U1/16_sumas.dart)
</details>

<details>
<summary>17_labels</summary>

Este programa en Dart ejemplifica el uso de bucles anidados y las sentencias de control break y continue (aunque en este caso están comentadas). En la función main(), se declara una variable entera r inicializada en 0. Luego se ejecuta un ciclo for externo donde la variable j recorre los valores de 0 a 9. Dentro de este ciclo, se imprime el valor de j y se ejecuta un segundo ciclo for interno con la variable i, que también recorre los valores de 0 a 9.

En cada iteración del ciclo interno, se calcula el residuo de dividir i entre 2 (r = i % 2). Si el resultado es 1, significa que el número es impar. En ese punto, el código muestra ejemplos comentados de cómo se podría usar continue para saltar la impresión de los números impares, o break para salir del ciclo. Si el número es par, se imprime su valor con stdout.writeln('El valor de I es: $i');.

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/U1/17_labels.dart)
</details>

<details>
<summary>18a_functions</summary>

Este programa en Dart genera la tabla de multiplicar de un número ingresado por el usuario. Primero se importa la librería dart:io para manejar la entrada y salida en consola. En la función main(), se declara una variable entera n y se solicita al usuario que ingrese un número con stdout.write(). La entrada se lee con stdin.readLineSync()! y se convierte a entero mediante int.parse().

Luego, se utiliza un ciclo for que recorre los valores de c desde 0 hasta 9. En cada iteración, se calcula el producto de n por c y se guarda en la variable r. Finalmente, se imprime el resultado.

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/U1/18a_funtions.dart)


</details>

<details>
<summary>18b_functions</summary>

Este programa en Dart genera la tabla de multiplicar de un número ingresado por el usuario, pero lo hace de manera más organizada al separar la lógica en una función. Primero se importa la librería dart:io para manejar la entrada y salida en consola. En la función main(), se declara una variable n y se solicita al usuario que ingrese un número. La entrada se lee con stdin.readLineSync()! y se convierte a entero mediante int.parse().

Después, se llama a la función multiply(n), que recibe el número como parámetro y se encarga de generar la tabla de multiplicar. Dentro de esta función, se utiliza un ciclo for que recorre los valores de c desde 0 hasta 9. En cada iteración, se calcula el producto de numero * c y se imprime.

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/U1/18b_funtions.dart)


</details>

<details>
<summary>19_primos</summary>

En este programa tienes que ingresar un número y este debe de determinar si es primo o no. Se importa la librería dart:io para manejar la entrada y salida en consola. En la función main(), se solicita al usuario que ingrese un número, el cual se convierte a entero mediante int.parse(). Luego, se llama a la función primo(), que se encarga de realizar la comprobación.

Dentro de la función primo(int numero, bool esPrimo), se inicializa una variable booleana esPrimo en true. Si el número es menor o igual a 1, automáticamente se considera no primo. En caso contrario, se ejecuta un bucle for que recorre desde 2 hasta la mitad del número (numero ~/ 2). Si en algún momento el número es divisible por otro distinto de 1 y de sí mismo, se marca como no primo y se rompe el bucle. Finalmente, se imprime un mensaje indicando si el número es primo o no.

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/U1/19_primos.dart)


</details>
</details>

<details>
<summary>Unidad 2</summary>

<details>
<summary>20a_factorial</summary>

El programa muestra un mensaje inicial solicitando al usuario que ingrese un número para calcular su factorial. Después, el valor introducido se lee y se convierte a tipo int, almacenándose en la variable n. Además, se inicializa la variable f con el valor 1, la cual funcionará como acumulador para calcular el factorial.

Posteriormente, el programa utiliza un ciclo for que comienza en n y disminuye hasta llegar a 2 (for (int c = n; c > 1; c--)). Dentro de este ciclo, en cada iteración la variable f se multiplica por el valor actual de c, lo que permite ir acumulando el resultado del factorial paso a paso.

Cuando el ciclo termina, es decir, cuando c deja de ser mayor que 1, el programa sale del bucle y finalmente muestra en pantalla el resultado, indicando el número ingresado y su factorial correspondiente mediante un mensaje.

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/U2/20a_factorial.dart)
</details>

<details>
<summary>20b_factorial</summary>

El programa muestra un mensaje inicial solicitando al usuario que ingrese un número para calcular su factorial. Después, el número introducido se lee desde el teclado y se convierte a tipo int, almacenándose en la variable n. Además, se inicializa la variable f con el valor 1, que se utilizará como acumulador para el cálculo.

Posteriormente, el programa llama a la función factorial(f, n), enviando como argumentos el valor inicial del acumulador (f) y el número ingresado (n). Dentro de esta función se utiliza un ciclo for que inicia en n y se decrementa hasta que el contador sea mayor que 1 (for (int c = n; c > 1; c--)). En cada iteración, el valor de f se multiplica por c, permitiendo calcular progresivamente el factorial del número.

Cuando el ciclo termina, la función regresa el valor final de f mediante la instrucción return. Este resultado se guarda nuevamente en la variable f dentro del main. Finalmente, el programa muestra en pantalla el resultado, indicando el número ingresado y su factorial correspondiente.

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/U2/20b_factorial.dart)

</details>

<details>
<summary>20c_factorialt</summary>

El programa muestra un mensaje inicial solicitando al usuario que ingrese un número para calcular su factorial. El valor introducido se lee desde el teclado y se convierte al tipo de dato int, almacenándose en la variable num.

Posteriormente, el programa llama a la función factorial(num), la cual está definida de forma recursiva. Dentro de esta función se establece primero un caso base: si el número es menor o igual a 1, la función devuelve 1, ya que el factorial de 0 y de 1 es 1.

Si el número es mayor que 1, se ejecuta el caso recursivo, donde la función multiplica el número actual por el resultado de llamar nuevamente a la misma función con num - 1 (num * factorial(num - 1)). Este proceso se repite sucesivamente hasta llegar al caso base, momento en el que comienzan a devolverse los resultados de cada llamada.

Finalmente, el resultado del factorial se guarda en la variable resultado y el programa imprime en pantalla el número ingresado junto con su factorial, mostrando el resultado entre líneas decorativas para una mejor presentación.

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/U2/20c_factorial.dart)

</details>

<details>
<summary>21_sumass</summary>

El programa muestra un mensaje inicial solicitando al usuario que ingrese un número. Posteriormente, el valor introducido se lee desde el teclado mediante stdin.readLineSync() y se convierte al tipo de dato int usando int.parse, guardándose en la variable num.

Después, el programa llama a la función factorial(num), que está definida de manera recursiva. Dentro de esta función primero se establece un caso base: si el número es menor o igual a 1, la función regresa el valor 1, lo que permite detener las llamadas recursivas.

Si el número es mayor que 1, se ejecuta el caso recursivo, donde la función suma el valor actual de num con el resultado de llamar nuevamente a la función con num - 1 (num + factorial(num - 1)). Este proceso continúa reduciendo el valor del número en cada llamada hasta alcanzar el caso base.

Finalmente, el resultado obtenido se almacena en la variable resultado y el programa muestra en pantalla el número ingresado junto con el resultado calculado.

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/U2/21_sumass.dart)

</details>

<details>
<summary>22_rear</summary>

El programa muestra un mensaje inicial indicando que se pueden ingresar números para agregarlos a una cola, así como algunos comandos especiales: dequeue para eliminar el primer elemento, mostrar para ver el estado de la cola y salir para terminar la ejecución del programa.

Primero se define una clase genérica Queue<T>, la cual utiliza una lista (List<T>) llamada _items para almacenar los elementos de la cola. Dentro de esta clase se implementan varios métodos: enqueue() para agregar un elemento al final de la cola, dequeue() para eliminar el primer elemento, showQueue() para mostrar el estado actual de la cola, e isEmpty() para verificar si la cola está vacía.

En la función main, se crea un objeto cola de tipo Queue<int>, que almacenará números enteros. Después, el programa entra en un ciclo while (true), el cual permite que el usuario interactúe continuamente con la cola hasta que decida salir.

Dentro del ciclo, el programa lee la entrada del usuario. Si el usuario escribe salir, el programa muestra un mensaje de despedida y termina la ejecución. Si escribe dequeue, se elimina el primer elemento de la cola. Si escribe mostrar, se imprime el contenido actual de la cola. En cualquier otro caso, el programa intenta convertir la entrada a un número entero; si la conversión es exitosa, el número se agrega a la cola usando el método enqueue(). Si la entrada no es válida, se muestra un mensaje de error indicando que se deben usar números o los comandos disponibles.

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/U2/22_rear.dart)


</details>

<details>
<summary>23_stacks</summary>

El programa implementa una estructura de pila (stack) usando una lista de enteros. Para controlar su funcionamiento, se utilizan funciones que permiten verificar si la pila está vacía (emptyStack) o llena (fullStack), así como agregar (push) y eliminar (pop) elementos.

La función push agrega un nuevo valor a la pila si aún hay espacio disponible, mientras que la función pop elimina el elemento que se encuentra en la parte superior de la pila, siempre y cuando no esté vacía.

En la función main, se crea una pila con capacidad máxima de 5 elementos y se agregan varios valores. Después se elimina el último elemento, se inserta uno nuevo y finalmente se utiliza un ciclo for para mostrar en pantalla los elementos que quedaron almacenados en la pila.

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/U2/23_stacks.dart)

</details>

<details>
<summary>24_tryCatch</summary>

El programa solicita al usuario ingresar un número para calcular su factorial. El valor introducido se lee desde el teclado y se intenta convertir a un número entero usando int.parse.

El cálculo se realiza mediante una función recursiva llamada factorial. Esta función tiene un caso base: si el número es menor o igual a 1, devuelve 1. Si el número es mayor, multiplica el número actual por el resultado de llamar nuevamente a la misma función con num - 1, repitiendo el proceso hasta llegar al caso base.

Además, el programa utiliza un bloque try-catch para manejar posibles errores. Si el usuario introduce un dato que no es un número o un número negativo, se genera una excepción y se muestra un mensaje de error indicando que la entrada es inválida.

Finalmente, si el número es válido, el programa muestra en pantalla el factorial del número ingresado.

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/U2/24_tryCatch.dart)

</details>

<details>
<summary>25_test</summary>

El programa implementa un sistema de gestión de tickets utilizando dos estructuras de datos: una cola (Queue) para administrar los tickets pendientes y una pila (Stack) para registrar las acciones realizadas por los técnicos.

Primero se definen las funciones de la pila, que permiten verificar si está vacía (emptyStack) o llena (fullStack), además de las operaciones push, que registra una nueva acción del técnico, y pop, que permite deshacer la última acción registrada.

Después se define una clase Queue, que maneja la cola de tickets siguiendo el principio FIFO (First In, First Out). Esta clase incluye métodos como enqueue para agregar tickets, dequeue para atender el primero de la cola y showQueue para mostrar los tickets pendientes.

El programa también declara variables globales, incluyendo la cola de tickets y la pila de acciones del técnico, donde se almacenan las actividades realizadas durante la atención de los tickets.

Posteriormente se implementan varias funciones del sistema que permiten agregar tickets, atenderlos, registrar acciones del técnico, deshacer la última acción y mostrar el estado actual del sistema.

Finalmente, el programa utiliza un menú interactivo dentro de un ciclo que permite al usuario seleccionar distintas opciones para gestionar los tickets y las acciones. El sistema continúa funcionando hasta que el usuario selecciona la opción de salir, momento en el cual el programa termina su ejecución.

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/U2/25_test.dart)

</details>
</details>


<h2>
	<img src="https://i.pinimg.com/originals/3d/f0/1c/3df01c6b1798d403648a281195d87a41.gif"  width="5%">
	Conclusión 
</h2>
Este repositorio reúne ejercicios básicos de programación en Dart, aunque también busca ser una guía accesible y clara para quienes están dando sus primeros pasos en el lenguaje (como yo). Cada programa refleja cómo combinar entrada y salida de datos, estructuras de control, y operaciones matemáticas para resolver problemas de manera práctica.

 <div align="center">
  <img src="https://media.tenor.com/hGQZUS8D3fQAAAAM/flug-little-aliens-forever.gif" width="40%"/>
</div>
  








