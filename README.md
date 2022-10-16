# Notas-Markdown

Como el título lo indica, el objetivo de este repositorio es dejar guardadas algunas notas sobre el lenguaje Markdown para poder consultarlas nuevamente.

## ¿Qué es Markdown?

Markdown es un lenguaje de marcado ligero utilizado para aagregar formato, vínculos e imágenes con facilidad a documentos de texto sin formato.

Esta herramienta fué creada en 2004 por John Gruber con el objetivo de ser una herramienta para convertir texto plano en HTML, permitiendo crear contenido de una manera sencilla de escribir, y que mantiene un diseño legible en todo momento.

### ¿Qué ofrece este lenguaje?

- Markdown se puede utilizar para muchas cosas. Entre ellas, se utiliza para crear sitios web, documentos, notas, libros, presentaciónes, correo electrónico y documentación técnica.

- Los archivos que tienen texto en formato Markdown se pueden abrir utilizando prácticamente cualquier aplicación.

- Es independiente d ela plataforma utilizada.

#### Ya sabemos qué es Markdown. Ahora veamos cómo es su sintaxis.

---

## Encabezados

Para agregar un encabezado debemos agregar uno o más simbolos numeral (#) y un espacio delante de una palabra o frase. La cantidad de numerales dependerá de el nivel del encabezado deseado:

Sintaxis Markdown:

```
# Encabezado nivel 1
```

Equivalente HTML:

```
<h1>Encabezado nivel 1<h1>
```

resultado:

# Encabezado nivel 1

Sintaxis Markdown:

```
# Encabezado nivel 2
```

Equivalente HTML:

```
<h2>Encabezado nivel 2<h2>
```

Resultará:

## Encabezado nivel 2

Sintaxis Markdown:

```
# Encabezado nivel 3
```

Equivalente HTML:

```
<h3>Encabezado nivel 3<h3>
```

Resultará:

## Encabezado nivel 3

Sintaxis Markdown:

```
# Encabezado nivel 4
```

Equivalente HTML:

```
<h4>Encabezado nivel 4<h4>
```

Resultará:

## Encabezado nivel 4

Sintaxis Markdown:

```
# Encabezado nivel 5
```

Equivalente HTML:

```
<h5>Encabezado nivel 5<h5>
```

Resultará:

## Encabezado nivel 5

Sintaxis Markdown:

```
# Encabezado nivel 6
```

Equivalente HTML:

```
<h6>Encabezado nivel 6<h6>
```

Resultará:

## Encabezado nivel 6

Alternativamente podemos expresar los encabezados de nivel 1 y 2 agregando debajo del texto cualquier cantidad de caracteres (=) y (-) respectivamente:

```
Encabezado de nivel 1
=====================
```

Resultará:

# Encabezado Nivel 1

```
Encabezado de nivel 2
---------------------
```

Resultará:

## Encabezado Nivel 2

---

## Párrafos

Para poder separar párrafos, debemos utilizar un renglón en blanco entre ellos:

Sintaxis Markdown:

```
Este es el primer párrafo

Este es el segundo párrafo
```

Equivalente HTML:

```
<p>Este es el primer párrafo<p>
<p>Este es el segundo párrafo<p>
```

Resultará:

Este es el primer párrafo

Este es el segundo párrafo

---

## Salto de línea

Para realizar un salto de línea, debemos terminar el renglón con dos o más espacios:

Sintaxis Markdown:

```
Este es el primer renglón
Este es el segundo renglón
```

Equivalente HTML:

```
<p>Este es el primer renglón<br>Este es el segundo renglón<p>
```

Resultará:

Este es el primer renglón  
Este es el segundo renglón

---

## Énfasis

El lenguaje Markdown permite utilizar los siguientes métodos para enfatizar secciónes del texto:

### Negrita

Para poder utilizar texto en negrita debemos agregar dos asteriscos o dos guiónes bajos delante y detrás del texto a rnfatizar:

Sintaxis Markdown:

```
Este texto **está en negrita**

Este texto __está en negrita__
```

Equivalente HTML:

```
Este texto <strong>está en negrita<strong>
```

Resultará:

Este texto **está en negrita**

Este texto __está en negrita__

Por otro lado, si queremos hacer negrita una porción de una palabra, sólo deberíamos usar el método de los asteriscos:

Sintaxis Markdown:

```
po**rció**n
```

Equivalente HTML:

```
po<strong>rció<strong>n
```

Resultará:

po**rció**n

### Cursiva

Para escribir texto en cursiva debemos colocar un solo asterisco o guión bajo antes y después de la palabra o frase a resaltar:

Sintaxis Markdown:

```
Este texto *está en cursiva*

Este texto _está en cursiva_
```

Equivalente HTML:

```
Este texto <em>está en negrita<em>
```

Resultará:

Este texto _está en cursiva_

Este texto _está en cursiva_

Por otro lado, si queremos escribir en cursiva una porción de una palabra, sólo deberíamos usar el método de los asteriscos:

Sintaxis Markdown:

```
po*rció*n
```

Equivalente HTML:

```
po<em>rció<em>n
```

Resultará:

po*rció*n

### Negrita y cursiva

Para escribir texto en cursiva y negrita a la vez, debemos colocar tres asteriscos o guiónes bajos antes y después de la palabra o frase a resaltar (también se puede combinar 2 asteriscos y un guión bajo o dos guónes bajos y un asterisco):

Sintaxis Markdown:

```
Este texto ***está en negrita y cursiva***

Este texto ___está en negrita y cursiva___

Este texto __*está en negrita y cursiva*__

Este texto **_está en negrita y cursiva_**
```

Equivalente HTML:

```
Este texto <em><strong>está en negrita y cursiva<strong><em>

Este texto <em><strong>está en negrita y cursiva<strong><em>

Este texto <em><strong>está en negrita y cursiva<strong><em>

Este texto <em><strong>está en negrita y cursiva<strong><em>
```

Resultará:

Este texto **_está en negrita y cursiva_**

Este texto **_está en negrita y cursiva_**

Este texto **_está en negrita y cursiva_**

Este texto **_está en negrita y cursiva_**

Por otro lado, si queremos escribir en cursiva y negrita una porción de una palabra, sólo deberíamos usar el método de los asteriscos:

Sintaxis Markdown:

```
po***rció***n
```

Equivalente HTML:

```
po<em><strong>rció<strong><em>n
```

Resultará:

po**_rció_**n

---

## Citas

Para colocar una cita debemos colocar un caracter > junto a un espacio delante de la cita

```
> Esto es una cita
```

Lo que se verá de la siguiente manera:

> Esto es una cita

Para colocar una cita con más de un párrafo, debemos separarlos mediante el renglón en blanco de colocando el caracter > en todos los renglones:

```
> Este es el primer párrafo de la cita
>
> Este es el segundo párrafo de la cita
```

Obteniendo:

> Este es el primer párrafo de la cita
>
> Este es el segundo párrafo de la cita

Dentro de una cita podemos colocar citas anidadas. En estas citas los niveles se representan colocando un espacio de tabulador de la siguiente manera:

```
> Esta es una cita
>> Esta es una cita anidada
```

Lo que se verá de la siguiente manera:

> Esta es una cita
>
> > Esta es una cita anidada

El lenguaje Markdown nos permite a su ves, dar algunos estilos de encabezado y tipo de texto dentro de una cita. Por ejemplo:

```
> ## Este es un título de nivel 2 dentro de la cita
>
> - Este es un elemento de lista dentro de la cita
> - Este es otro elemento de lista dentro de la cita
> Este es un texto que contiene **negrita** y _cursiva_
```

Esto generará una cita con la siguiente forma:

> ## Este es un título de nivel 2 dentro de la cita
>
> - Este es un elemento de lista dentro de la cita
> - Este es otro elemento de lista dentro de la cita
>   Este es un texto que contiene **negrita** y _cursiva_

### Tachado

Para colocar texto tachado debemos pone dos símbolo ~ delante y otro detás de la siguiente manera:

```
Este texto está ~~tachado~~
```
Obteniendo:

Este texto está ~~tachado~~


---

## Listas

como la palabra lo dice, son utilizadas para enlistar elementos. Las listas pueden ser:

### Ordenadas

Las listas ordenadas se esciben colocando el numero seguido de un punto y un espacio delante de la frase a enlistar. Se debe tener en cuenta que siempre se inician con el número 1

Sintaxis Markdown:

```
1. Primer elemento
2. Segundo elemento
3. Tercer elemento
```

Equivalente HTML:

```
<ol>
    <li>Primer elemento<li>
    <li>Segundo elemento<li>
    <li>Tercer elemento<li>
<ol>
```

Resultará:

1. Primer elemento
2. Segundo elemento
3. Tercer elemento

### Desordenadas

Las listas desordenadas se esciben colocando un guón medio, un símbolo suma o un asterisco, seguido de un punto y un espacio delante de la frase a enlistar. Se debe tener en cuenta que siempre se debe utilizar el mismo símbolo para todos los elementos de la lista

Sintaxis Markdown:

```
 - Primer elemento
 - Segundo elemento
 - Tercer elemento

 + Primer elemento
 + Segundo elemento
 + Tercer elemento

 * Primer elemento
 * Segundo elemento
 * Tercer elemento
```

Equivalente HTML:

```
<ul>
    <li>Primer elemento<li>
    <li>Segundo elemento<li>
    <li>Tercer elemento<li>
<ul>
```

Resultará:

- Primer elemento
- Segundo elemento
- Tercer elemento

* Primer elemento
* Segundo elemento
* Tercer elemento

- Primer elemento
- Segundo elemento
- Tercer elemento

Dentro de una lista podemos colocar diferentes elementos (otra lista, párrafos, citas, bloques de código e imágenes). Para dar continuidad al formato de las listas los elementos debemos colocarlos con espacios de tabulación y colocando los renglones en blanco para poder hacer el salto de línea como se ejemplifica a continuacón:

1.  Este es el primer elemento de la lista
    - Este es un elemento de la lista anidada
    - Este es otro elemento
2.  Este es el segundo elemento de la lista, el cual contiene un párrafo

    Este es el párrafo contenido

3.  Este es el tercer elemento de la lista, el cual contiene una cita

    > Esta es la cita contenida

4.  Este es el cuarto elemento de la lista, el cual contiene un bloque de código

    ```
    <html>
          <head>
            <title>Este es el bloque de código</title>
          </head>
    ```

5.  Este es el quinto elemento de la lista, el cual contiene el ícono de markdown

    ![Icono de Markdown](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/250px-Markdown-mark.svg.png)

---

## CheckList

Para generar una checklist podemos hacerlo mediante la siguiente estructura:

```
- [x] Esta tarea está realizada
- [ ] Esta no está hecha
```
Lo que se verá de la siguiente manera:

- [x] Esta tarea está realizada
- [ ] Esta no está hecha

---

## Bloques de código

Para escribir código tenemos diferentes formas dependiendo de qué es lo que queremos dejar expresado.

Si queremos escribir sólo una línea de código podemos hacerlo encerrando la línea en backtiks (`)de la siguiente manera:

```
`Esta es una línea de código`
```

Pero en caso de que alguna palabra dentro de la lína utilice los backtiks, se debe encerrar la línea en backtiks dobles:

```
`` Esta es otra `línea` de código``
```

Estas líneas serán visualizadas de la siqguiente manera:

`Esta es una línea de código`

`` Esta es otra `línea` de código``

Markdown nos permite a la vez, poder escribir bloques de código. Para escribir un bloque de código usamos una terna de backtiks adelante y otra al final del código dejando los backtiks en renglones individuales. También podemos declarar el nombre del lenguaje utilizado colocándolo al lado de los backtiks de apertura para que los editores de código puedan interpretar el mismo. Por ejempleo:

```
    ```json
    {
        "nombre": "Pablo",
        "apellido": "Ortega"
    }
    ```
```
Lo que nos dará como resultado:

```json
{
    "nombre": "Pablo",
    "apellido": "Ortega"
}
```

O bien, si quisiéramos colocar código javascript:

```
    ```javascript
    console.log('Ejemplo de código JavaScript')
    ```
```
Retornando:

```javascript
const personas = [
    {
        nombre: 'Nombre 1',
        apellido: 'Apellido 1'
    },
    {
        nombre: 'Nombre 2',
        apellido: 'Apellido 2'
    }
] 
```

---

## Imágenes

Para colocaruna imagen debemos colocar un símbolo de admiracón (cierre)delante, luego entre corchetes ponemos el nombre o una descripciòn de la imagen, finalmente entre paréntesis colocamos la ruta donde está alojada la imagen. Por ejemplo:

```
![Logo Markdown](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/250px-Markdown-mark.svg.png)

```

Lo que nos dará como resultado:

![Logo Markdown](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/250px-Markdown-mark.svg.png)

## Separador horizontal

para crear un separador horizontal debemos colocar tres o más asteriscos, guiónes o guiónes bajos. Tener en cuenta que debe colocarse en un renglon aparte como vemos a continuación:

```

***

---

___

```
Lo que nos dará como resultado:

***
---
___

Debemos tener la consideración de dejar un renglón en blanco antes y otro después del separadr horizontal

## Links

Para colocar un link debemos poner entre corchetes el texto que será visualizadoy a continuación el link al que redirigiremos entre paréntesis. También podemos poner una descripción o referencia para cuando hacemos hover sobre el mismo colocándolo dentro del paréntesis, a continuación del link dejando un espacio y colocándolo entre comillas.

```
Este link nos redireccionará a [google.com](https://www.google.com "Este link nos redireccionará a Google")

```

Este link nos redireccionará a [google.com](https://www.google.com "Este link nos redireccionará a Google")

Por último podemos para colocar una URL o un mail debemos poner el contenido encerrado en paréntesis angulares

```
<https://URL.deEjemplo.com>

<email@ejemplo.com>
```

Lo que resultará:

<https://URL.deEjemplo.com>

<email@ejemplo.com>

## Tablas

Para armar una tabla debemos seguir la siguiente estructura:

```

|Encabezado 1   |Encabezado 2   |Encabezado 3   |
|:---           |:---:          |---:           |
|Primer fila 1  |Primer fila 2  |Primer fila 3  |
|Segunda fila 1 |Aegunda fila 2 |Segunda fila 3 |
|Tercera fila 1 |Tercera fila 2 |Tercera fila 3 |

```

Lo que se verá de la siguiente manera:

|Encabezado 1   |Encabezado 2   |Encabezado 3   |
|:---           |:---:          |---:           |
|Primer fila 1  |Primer fila 2  |Primer fila 3  |
|Segunda fila 1 |Aegunda fila 2 |Segunda fila 3 |
|Tercera fila 1 |Tercera fila 2 |Tercera fila 3 |

Como podemos observar en el ejemplo anterior podemos asignar la orientación de las columnas. colocando los : a la izquierda orientamos la columna a la izquierda y de la misma forma a la derecha. Para que se vea centrada colocamos : a ambos lados del separador.

A su ves dentro de la tabla podemos estilizar el texto utilizando los formatos de negrita, corsiva y encabezados.

## Emojis

Para colocar un emoji podemos colocar el nombre del mismo entre símbolos de dos puntos como se muestra a continuación:

```
:smiley:
```

Con lo que veremos: 

:smiley:

Para colocar emojis podemos consultar la página <https://gist.github.com/rxaviers/7360908>

Sólo debemos tener en cuenta que no todos los lectores de markdown reconocen a los emojis.

## Indices

Para colocar un índice, ya sea superior o inferior podemos hacerlo de la siguiente manera:

```
H~2~O
X^2^
```

También tenemos que tener en cuetna que no todos los lectores de markdown pueden leer este tipo de escritura