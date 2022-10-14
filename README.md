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