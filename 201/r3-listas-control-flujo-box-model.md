# Conceptos básicos de HTML, CSS y JS
## Listas Ordenada y No ordenada
1 **¿Cuándo se puede utilizar una lista no ordenada en tu documento HTML?**  
Cuando se necesita listar por lo menos dos cosas y el orden no es importante.
2 **¿Cómo cambias el estilo bullet de la lista de elementos no ordenados?**  
Mediante el atributo *type*. Entre las opciones disponibles se encuentran *circle*, *square* y *bullet*.
3 **¿Cuándo debes usar una lista ordenada o lista no ordenada en tu documento HTML?**  
Cuando es relevante ordenar el conjunto de cosas a listar, por lo menos dos.  
4 **Describe dos formas en las que puedes cambiar los números en los elementos de la lista proporcionados por una lista ordenada**  
A través del atributo *type* y *start*. Entre las opciones se encuentran disponibles la 'i' y '2', respectivamente. El primer valor permite especificar que habrá una lista mediante numeros romanos y el segundo valor que la numeración de la lista ininiará desde el valor 2.
## The Box Model
1 **Describe las propiedades de margin y padding en CSS como si fueran los personajes de una historia. ¿Cuál es su rol en la historia: “El Box Model”?**  
***Margen/margin***  \
+ *margin-top* . Determina la posición superior de la caja/box respecto a un contenedor y su referencia.  
+ *margin-rigth* . Determina la posición derecha de la caja/box respecto a un contenedor y su referencia.  
+ *margin-bottom* . Determina la posición inferior de la caja/box respecto a un contenedor y su referencia.  
+ *margin-left* . Determina la posición izquierda de la caja/box respecto a un contenedor y su referencia.  
***Relleno/padding***  \
+ *padding-top* . Determina la posición superior del contenido respecto a la caja.  
+ *padding-rigth* . Determina la posición derecha del contenido respecto a la caja.  
+ *padding-bottom* . Determina la posición inferior del contenido respecto a la caja.  
+ *padding-left* . Determina la posición izquierda del contenido respecto a la caja.  
2 **Enumera y describe las cuatro partes de un box del elementos HTML según el box model.**  
2 ".1" *margen* . Espacio invisible alrededor de la caja.  
2 ".2" *borde* . Linea que resalta dimensiones de la caja y que envuelve el contenido y el relleno.
3 ".3" *relleno* . El relleno se encuentra entre el borde y el área del contenido.  
4 ".4" *contenido*. El área donde se muestra el contenido de la caja.  
## Arrays. Operadores y Expresiones. Condicionales. Bucles.
1 **¿Qué tipos de datos puedes almacenar en un Array?**  
+ Undefined  
+ Boolean  
+ Number  
+ String  
+ BigInt  
+ Symbol  
+ Null  
+ Object  
2 **¿El array people es un array de JavaScript válido? De ser así, ¿cómo puedo acceder a los valores almacenados? Y si no, ¿por qué?**  
*const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];*  
Sí! sólo referenciando el item que interesre consultar. Considerando '0' como el primer valor.  
3 **Enumera cinco opreadores abreviados de asignación en javascript y describe lo que hacen.**
+ Aritméticos. Toma valores numericos y permiten hacer calculos como suma, resta, multiplicación y división.  
+ Lógicos. Toma valores booleanos y realiza operaciones de conjución (&&), disyunción (||) y negación (NOT).  
+ Cadena. Toma valores del tipo cadena para realizar operaciones de concatenación obteniendo como resultado una nueva cadena.  
+ Comparación. Toma valores de deistintios tipos sean numericos, cadena, lógicos y objetos y realiza operaciones de comparación obteniendo como resultado valores booleanos *true* o *false*, según corresponda.
+ bit a bit. Trata a sus operandos como un conjunto de 32 bits (ceros y unos) enlugar de décimales. Sin embargo retorna valores numericos décimales.  
4 **Enumera cinco operadores abreviados de asignación en javascript y describe lo que hacen.**  
+ '+' Suma  
+ === igualdad estricta  
+ && condicional que exige ser true sólo si ambos valores booleanos comparables son true.  
+ / división  
+ !== diferencia estricta  
5 **Lee el código a continuación, evalúa la última expresión y explica cuál sería el resultado y por qué.**
let a = 10;  
let b = 'dog';  
let c = false;  
(a + c) + b;
***output '10dog'***
6 *Describe un ejemplo cotidiano de por qué una declaración condicional se debería usar en un programa en JavaScript.*
Autenticar a un persona que pienbsa realizar la compra de un producto en una ecommerce.
7 *Da un ejempo de por qué un Bucle es últil en JavaScript.*
Print lista de productos seleccionados en uncarro de compras al momento de generar un comprobante electrónico.
## Cosas de las que quiero saber más
