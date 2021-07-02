# Tutorial CSS

## CSS Sintaxis

![alt text](https://www.w3schools.com/css/img_selector.gif)

El selector apunta al elemento HTML al que desea aplicar estilo.

El bloque de declaración contiene una o más declaraciones separadas por punto y coma.

Cada declaración incluye un nombre de propiedad CSS y un valor, separados por dos puntos.

Varias declaraciones CSS se separan con punto y coma y los bloques de declaración están rodeados por llaves.

#### Ejemplo explicado 

* p:  es un selector en CSS (apunta al elemento HTML que desea aplicar estilo: p).
* color: es una propiedad y redes el valor de la propiedad
* text-align: es una propiedad y centeres el valor de la propiedad

## Selectores CSS

Un selector de CSS selecciona los elementos HTML a los que desea aplicar estilo.

#### Selectores CSS

Los selectores CSS se utilizan para "buscar" (o seleccionar) los elementos HTML que desea aplicar estilo.

Podemos dividir los selectores de CSS en cinco categorías:

* Selectores simples (seleccione elementos según el nombre, la identificación, la clase)
* Selectores de combinador (seleccione elementos en función de una relación específica entre ellos)
* Selectores de pseudo-clase (seleccione elementos basados ​​en un cierto estado)
*Selectores de pseudo-elementos (seleccionar y aplicar estilo a una parte de un elemento)
* Selectores de atributos (seleccione elementos basados ​​en un atributo o valor de atributo)

#### El selector de id de CSS

El selector de id utiliza el atributo id de un elemento HTML para seleccionar un elemento específico.

La identificación de un elemento es única dentro de una página, por lo que el selector de identificación se utiliza para seleccionar un elemento único.

Para seleccionar un elemento con una identificación específica, escriba un carácter de almohadilla (#), seguido de la identificación del elemento.

``` CSS

#para1 {
  text-align: center;
  color: red;
}

```