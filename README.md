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
-**|| Sandra Carolina Perales Rodriguez ||**
-**|| Desarrollo de Aplicaciones Móviles ||**
- **|| ITIID-4 ||**
<h2>
	<img src="https://i.pinimg.com/originals/e4/96/0c/e4960c1d084132279f17ca869846c00c.gif" width="4%">
	Códigos de la unidad

</h2>
<details>
<summary>01_holamundo</summary>

Es un código simple que imprimi el texto hola mundo
El programa presentado está escrito en Dart y constituye el ejemplo clásico de iniciación en cualquier lenguaje de programación. La función main() es el punto de entrada del programa, es decir, el lugar donde comienza la ejecución. Dentro de ella se encuentra la instrucción print('Hello, World!');, que envía a la consola el texto “Hello, World!”. Este ejercicio tiene como propósito mostrar la estructura mínima de un programa en Dart y comprobar que el entorno de desarrollo funciona correctamente.

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/01_holamundo.dart)
</details>

<details>
<summary>02_dataTypes</summary>

Este programa en Dart muestra distintos tipos de datos y estructuras del lenguaje. Comienza con la función main(), que es el punto de entrada del programa. En la primera sección se declaran variables numéricas: int a = 10;, double b = 3.14;, una variable entera opcional int? c; que puede ser nula, y una variable late int d; que se inicializa después con el valor 20. Se imprimen estas variables y se realiza una operación aritmética con a + b. Luego se trabajan las cadenas de texto: se definen variables como String nombre = 'caro';, String apellido = "Piz";, y se muestra cómo concatenar cadenas ('$nombre $apellido').

En la sección de booleanos se declara bool isActive = true; y se utiliza la negación lógica para obtener isNotActive. Después se presentan las listas: una lista heterogénea var general = [...] y una lista tipada List<String> villanos = [...]. Se modifica un elemento, se agregan valores repetidos y se observa cómo se comporta la lista. Tambien se introducen los conjuntos (Set), que eliminan duplicados automáticamente, mostrando cómo se agregan elementos repetidos y cómo se convierten listas en conjuntos con toSet().

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/02_dataTypes.dart)

</details>

<details>
<summary>03_finalConst</summary>

Este programa en Dart tiene como objetivo mostrar la diferencia entre variables declaradas con var, final y const, además de cómo se comportan las listas cuando se definen con estas palabras clave. La variable var a = 10; es mutable, lo que significa que puede cambiar su valor más adelante. La variable final double b = 10; se asigna una sola vez y no puede ser modificada después de su inicialización, aunque si es un objeto, sus elementos internos sí pueden cambiar. La variable const double c = 10; es una constante en tiempo de compilación, lo que implica que su valor es inmutable y fijo desde el inicio.

En cuanto a las listas, final List<String> personasFinal = ['Caro', 'Piz']; define una lista cuyo contenido puede modificarse (por ejemplo, se le puede agregar un nuevo elemento con .add()), pero la referencia a la lista no puede ser reasignada a otra lista distinta. Por otro lado, List<String> personasConst = const ['Caro2', 'Piz2']; crea una lista constante, lo que significa que no se pueden modificar sus elementos ni agregar nuevos valores, ya que está protegida contra cambios. En el código, cuando se intenta hacer personasConst.add('piz2');, se producirá un error porque las listas constantes son inmutables.

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/03_finalConst.dart)

</details>

<details>
<summary>04_comments</summary>

Este archivo en Dart tiene como propósito mostrar los distintos tipos de comentarios que se pueden utilizar en el lenguaje y cómo se integran dentro del código. Al inicio se incluye un bloque de comentario con /** ... */, que suele emplearse para documentación general del archivo, indicando datos como la fecha de creación y el autor. Luego, dentro de la función main(), se utilizan comentarios de una sola línea con //, útiles para explicar instrucciones puntuales, y comentarios multilínea con /* ... */, que permiten abarcar varias líneas de explicación. También se muestran los comentarios de documentación con ///, que son especiales porque se usan para describir clases, funciones o elementos del código y pueden ser procesados por herramientas de documentación automática.

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/04_comments.dart)

</details>

<details>
<summary>05_mathOperators</summary>

El objetivo de este ejercicio fue entender cómo funcionan los operadores en Dart. Vimos las operaciones básicas (suma, resta, multiplicación, división) y operaciones más específicas como el módulo, la división entera, la negación y los operadores de incremento/decremento. Además, del cómo los operadores de asignación compuesta simplifican la escritura del código, haciendo más clara y eficiente la manipulación de valores.

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/05_mathOperators.dart)


</details>

<details>
<summary>06_operators</summary>

Este ejercicio muestra cómo los operadores de asignación condicional (??=) permiten inicializar variables nulas de forma segura, y cómo los operadores condicionales (?:) permiten tomar decisiones rápidas dentro de una sola línea de código.

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/06_operators.dart)

</details>

<details>
<summary>07_read</summary>

Este ejercicio muestra cómo realizar entrada y salida estándar en Dart, cómo manejar variables opcionales (String?), y cómo convertir cadenas a números con int.parse(). Lo cual es muy útil para comprender la interacción entre el programa y el usuario.

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/07_read.dart)

</details>

<details>
<summary>08_helloName</summary>

Este programa en Dart muestra cómo realizar una interacción sencilla con el usuario a través de la consola. Se importa la librería dart:io, que permite usar funciones de entrada y salida estándar. Dentro de la función main(), se solicita al usuario que escriba su nombre con stdout.write('Cual es tu nombre? ');. La entrada se captura mediante stdin.readLineSync(), que devuelve una cadena opcional (String?) porque el usuario podría no ingresar nada.

Luego, el programa imprime un mensaje con print('tu name es: $nombre!');, mostrando el valor ingresado. En este caso, si el usuario escribe un nombre, se verá reflejado en la salida; si no escribe nada, el valor será null.

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/08_helloName.dart)

</details>

<details>
<summary>09_sum</summary>

Este programa en Dart muestra cómo realizar operaciones básicas de entrada y salida con números ingresados por el usuario. Se importa la librería dart:io para poder usar stdout y stdin. En la función main(), primero se solicita al usuario que ingrese el primer número con stdout.write('Ingresa el primer numero: ');. El valor se captura con stdin.readLineSync()! y se convierte a entero mediante int.parse(). Lo mismo ocurre con el segundo número.

Luego, ambos valores (a y b) se suman y se almacenan en la variable n. Finalmente, se imprime el resultado con print('resultado es: $n!');.

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/09_sum.dart)

</details>

<details>
<summary>10_concat</summary>


Este programa en Dart solicita al usuario que ingrese su nombre, apellido y segundo nombre, y luego imprime el nombre completo en la consola. Se importa la librería dart:io para poder usar stdout.write() y stdin.readLineSync(), que permiten mostrar mensajes y leer entradas desde la consola.
[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/10_concat.dart)

</details>

<details>
<summary>11_ifBasic</summary>

Este programa en Dart ejemplifica cómo comparar dos números ingresados por el usuario y determinar cuál es mayor. Se importa la librería dart:io para poder usar stdout.write() y stdin.readLineSync(), que permiten mostrar mensajes en consola y leer entradas. En la función main(), primero se solicita el primer número y se convierte a entero con int.parse(). Lo mismo ocurre con el segundo número. Luego, se utiliza una estructura condicional if-else para comparar los valores e imprime cual es el mayor o si son iguales.

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/11_ifBasic.dart)
</details>

<details>
<summary>12_Nested</summary>

Este programa en Dart tiene como propósito ordenar cuatro números ingresados por el usuario de mayor a menor. Para ello, se importa la librería dart:io, que permite leer datos desde la consola. En la función main(), se solicita al usuario que ingrese cuatro números (a, b, c, d), cada uno convertido a entero con int.parse().

El algoritmo utiliza una variable auxiliar (aux o temp) para intercambiar valores entre las variables. Primero compara a contra b, c y d, asegurando que a quede con el mayor valor posible. Luego compara b contra c y d, y finalmente c contra d. Después se repite un bloque adicional de comparaciones para garantizar que todos los valores estén correctamente ordenados.

Al final, el programa imprime los números de mayor a menor.

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/12_Nested.dart)

</details>

<details>
<summary>13_menus</summary>

Este programa en Dart implementa un menú interactivo que permite al usuario calcular áreas y volúmenes de distintas figuras geométricas, o salir del programa. Se utilizan las librerías dart:io para la entrada/salida en consola y dart:math para funciones matemáticas como pi y pow.

En la función principal main(), se ejecuta un bucle infinito while (true) que muestra el menú principal con tres opciones: calcular área, calcular volumen o salir. Según la opción ingresada, se llama a la función correspondiente (calcularArea() o calcularVolumen()), o se rompe el bucle si se elige salir.

La función calcularArea() presenta un submenú con tres figuras: círculo, triángulo y rectángulo. Dependiendo de la elección, se solicitan los valores necesarios (radio, base, altura) y se aplica la fórmula correspondiente, y lo mismo aplica para calcularVolumen() pero para las figuras 3D.

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/13_menus.dart)

</details>

<details>
<summary>14_tablamult</summary>

Este programa es una tabla de multiplicar interactiva que se repite hasta que el usuario decida salir. Se importa la librería dart:io para manejar la entrada y salida en consola.

En la función main(), se declara la variable test inicializada en 1. Luego se utiliza un bucle while (test != 0) que se ejecuta mientras el valor ingresado no sea cero. Dentro del bucle, el programa solicita al usuario un número con stdin.readLineSync()!, lo convierte a double y lo guarda en test. Si el usuario ingresa 0, el bucle se rompe y el programa termina.

Si el número es distinto de 0, se ejecuta un ciclo for que va desde 1 hasta 50. En cada iteración se calcula el producto de test por el valor de i y se imprime en formato de tabla, mostrando todas las multiplicaciones hasta el 50.

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/14_tablamult.dart)
</details>

<details>
<summary>15_calif</summary>

Este programa en Dart convierte calificaciones del sistema estadounidense (A+, A, B, C, D, F) a sus equivalentes en el sistema mexicano (10, 9, 8, 7, 6, 5).
El programa solicita al usuario que ingrese una calificación en el sistema americano. Para validar la entrada, se usa un bucle while (!valido) que se repite hasta que el usuario escriba una calificación correcta. La entrada se procesa con trim() para eliminar espacios y toUpperCase() para convertirla a mayúsculas, asegurando que coincida con los valores de la lista usa.

Si la calificación ingresada existe en la lista, se obtiene su índice con usa.indexOf(entrada) y se usa ese índice para acceder a la lista mex, mostrando la equivalencia. Si la calificación no es válida, se imprime un mensaje de error y se vuelve a pedir la entrada.

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/15_calif.dart)
</details>

<details>
<summary>16_sumas</summary>

El programa muestra un mensaje inicial indicando que se deben introducir números y que el valor 0 detendrá la ejecución. Luego, se utiliza un ciclo while (x != 0) que se repite mientras el usuario no ingrese cero. Dentro del bucle, cada número introducido se convierte a tipo double y se suma a la variable acumuladora y. Cuando el usuario introduce 0, el bucle se rompe y el programa imprime el resultado final mostrando la suma total. 

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/16_sumas.dart)
</details>

<details>
<summary>17_labels</summary>

Este programa en Dart ejemplifica el uso de bucles anidados y las sentencias de control break y continue (aunque en este caso están comentadas). En la función main(), se declara una variable entera r inicializada en 0. Luego se ejecuta un ciclo for externo donde la variable j recorre los valores de 0 a 9. Dentro de este ciclo, se imprime el valor de j y se ejecuta un segundo ciclo for interno con la variable i, que también recorre los valores de 0 a 9.

En cada iteración del ciclo interno, se calcula el residuo de dividir i entre 2 (r = i % 2). Si el resultado es 1, significa que el número es impar. En ese punto, el código muestra ejemplos comentados de cómo se podría usar continue para saltar la impresión de los números impares, o break para salir del ciclo. Si el número es par, se imprime su valor con stdout.writeln('El valor de I es: $i');.

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/17_labels.dart)
</details>

<details>
<summary>18a_functions</summary>

Este programa en Dart genera la tabla de multiplicar de un número ingresado por el usuario. Primero se importa la librería dart:io para manejar la entrada y salida en consola. En la función main(), se declara una variable entera n y se solicita al usuario que ingrese un número con stdout.write(). La entrada se lee con stdin.readLineSync()! y se convierte a entero mediante int.parse().

Luego, se utiliza un ciclo for que recorre los valores de c desde 0 hasta 9. En cada iteración, se calcula el producto de n por c y se guarda en la variable r. Finalmente, se imprime el resultado.

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/18a_funtions.dart)


</details>

<details>
<summary>18b_functions</summary>

Este programa en Dart genera la tabla de multiplicar de un número ingresado por el usuario, pero lo hace de manera más organizada al separar la lógica en una función. Primero se importa la librería dart:io para manejar la entrada y salida en consola. En la función main(), se declara una variable n y se solicita al usuario que ingrese un número. La entrada se lee con stdin.readLineSync()! y se convierte a entero mediante int.parse().

Después, se llama a la función multiply(n), que recibe el número como parámetro y se encarga de generar la tabla de multiplicar. Dentro de esta función, se utiliza un ciclo for que recorre los valores de c desde 0 hasta 9. En cada iteración, se calcula el producto de numero * c y se imprime.

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/18b_funtions.dart)


</details>

<details>
<summary>19_primos</summary>

En este programa tienes que ingresar un número y este debe de determinar si es primo o no. Se importa la librería dart:io para manejar la entrada y salida en consola. En la función main(), se solicita al usuario que ingrese un número, el cual se convierte a entero mediante int.parse(). Luego, se llama a la función primo(), que se encarga de realizar la comprobación.

Dentro de la función primo(int numero, bool esPrimo), se inicializa una variable booleana esPrimo en true. Si el número es menor o igual a 1, automáticamente se considera no primo. En caso contrario, se ejecuta un bucle for que recorre desde 2 hasta la mitad del número (numero ~/ 2). Si en algún momento el número es divisible por otro distinto de 1 y de sí mismo, se marca como no primo y se rompe el bucle. Finalmente, se imprime un mensaje indicando si el número es primo o no.

[Archivo](https://github.com/UngivenStar/portafolioMovil/blob/main/19_primos.dart)


</details>


<h2>
	<img src="https://i.pinimg.com/originals/3d/f0/1c/3df01c6b1798d403648a281195d87a41.gif"  width="5%">
	Conclusión 
</h2>
Este repositorio reúne ejercicios básicos de programación en Dart, aunque también busca ser una guía accesible y clara para quienes están dando sus primeros pasos en el lenguaje (como yo). Cada programa refleja cómo combinar entrada y salida de datos, estructuras de control, y operaciones matemáticas para resolver problemas de manera práctica.

 <div align="center">
  <img src="https://media.tenor.com/hGQZUS8D3fQAAAAM/flug-little-aliens-forever.gif" width="40%"/>
</div>
  








