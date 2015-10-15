# Introducción a Javascript para navegadores web

Esta introducción a Javascript no pretende ser material detallado del lenguaje sino un resumen de modo introductorio a sus principales características y su aplicación en páginas web.
Vamos a mezclar conceptos del lenguaje con elementos propios de su funcionamiento dentro de un navegador.

##Qué es Javascript
Javascript es un lenguaje de programación que puede ser interpretado por los navegadores web de la actualidad, permite manipular todo el contenido de una página web a partir de su interacción con el DOM y las capacidades que le da AJAX.
Existen varias versiones del lenguaje vamos a concentrarnos en las características más comunes al día de la fecha.

Características más sobresalientes:

- Tipado Dinámico: una variable puede tomar diferentes valores y tipos
- Interpretado: no se compila, se interpreta mientas se ejecuta
- Basado en objetos.
- Se utiliza principalmente en navegadores web si bien es posible hacerlo en otras plataformas.
- Tiene un pequeño número de objetos predefinidos.
- Se accede a las propiedades de los objetos como un array asociativo o con .
- Las funciones son objetos en sí mismo.
- Utiliza prototipos en lugar de clases para la herencia.
- Las funciones se pueden comportar como constructores de objetos.


Javascript posee las estructuras más clásicas dentro de su sintáxis:

- for
- do
- while
- if
- else
- switch

##Cómo declarar una variable en Javascript?
````javascript
var nombre = "Leonardo";
````
La palabra var nos permite declarar una variable, nunca espeficamos el tipo sino que el mismo es inferido por el contenido, en este caso una cadena de texto.

###Una vez declarada la variable se comporta según su tipo, es decir, podemos utilizar algunas de las funciones propias del tipo, por ejemplo:
````javascript
var nombre = "Leonardo";
nombre.indexOf("e");
````
En este ejemplo la función indexOf nos devuelve la posición de la letra "e" dentro de la variable.

