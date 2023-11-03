# ASIX1M4UF1-A3Apuntes

Actividad 3, apuntes de M4

#### GITHUB



#### MARKDOWN:

Este texto está en *cursiva*.
Este texto está en _cursiva_.
Este texto está en **negrita**.
Este texto está en __negrita__.
Este texto está en **_negrita y cursiva_**.

1. Primera opción de menú.
2. Segunda opción de menú.
3. Tercera opción de menú.

* Primera opción de lista desordenada
* Segunda opción de lista desordenada
- Tercera opción de lista desordenada
    1. Primer submenú
    2. Segundo submenú
- Cuarta opción de lista desordenada
    * Tercer submenú
    * Cuarto submenú
+ Quinta opción de lista desordenada
+ Sexta opción de lista desordenada

[Esto es un enlace](http://joan23.fje.edu "Enlace a la web del cole")

![Esto es una imagen](https://raw.githubusercontent.com/polettex/ASIX1M4UF1-A3Apuntes/aa7c1c85a0b76f082bbb92d680a2d3d35fd5964d/planeta.jpg "Enlace de la imagen")

|Primera Col.|Segunda Col.|Tercera Col.|
|---------------|:------------:|---------------|
|Col 2 es|Centrada|35€|
|Estilo Cebra|Gris|Blanco|
|Clase |ASIX1|M4|

- [] Opcion 1

- [X] Opcion 2

- [] Opcion 3

#### HTML:

Estructura HTML:

```
<html>
    <head>
    </head>
    <body>
        <p>Esto es un párrafo</p>
    </body>
</html>
```

```
Etiquetas HTML:

- Esto es un encabezado <h1>
- Esto es un subtitulo <h3>
- Esto sirve para crear enlaces <a>
- Esto sirve para insertar imagenes <img>
- Esto sirve para subrayar <u>
- Esto sirve para poner el texto en negrita <strong>
- Esto sirve para crear parrafos <p>
- Esto sirve para hacer una linea horizontal <hr>
- Esto sirve para hacer un salto de linea <br>
- Esto sirve para crear una lista ordenada <ol>
- Esto sirve para crear una lista desordenada <ul>
- Esto sirve para crear los puntos de una lista <li>

```

#### CSS:

El CSS es un lenguaje que se utiliza para dar instrucciones referentes a la apariencia de una página.

Formas de insertar CSS en un documento HTML:

- CSS interno

El CSS interno requiere que se añada la etiqueta <style> en la sección <head> del documento HTML.

Ejemplo.

```
<!DOCTYPE html>
<html>
<head>
    <style>
        body {
            background-color: blue;
            }
        h1 {
            color: red;
            padding: 60px;
        } 
    </style>
</head>
<body>
    <h1>Ejemplo</h1>
    <p>Esto es un párrafo</p>
</body>
</html>
```

- CSS Externo

Con el CSS externo, se enlazará la página web a un archivo css externo. Este tipo de CSS es un método más eficiente, especialmente para estilizar un sitio web grande.

Para enlazar un archivo css externo se usará la etiqueta <link> en el head para enlazar el css al html.

Ejemplo.

```
<!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" type="text/css" href="style.css"/>
</head>
<body>
    <h1>Ejemplo</h1>
    <p>Esto es un párrafo</p>
</body>
</html>
```

- CSS Inline

El CSS inline se utiliza para dar estilo a un elemento HTML específico. Para este tipo de estilo CSS, sólo se tiene que añadir el atributo style a cada etiqueta HTML. 

Este tipo de CSS no es realmente recomendable, ya que cada etiqueta HTML debe ser estilizada individualmente.

Ejemplo.

```
<html>
<head>
</head>
<body style="background-color:black;">
    <h1 style="color:white;padding:30px;">Ejemplo</h1>
    <p style="color:white;">Esto es un párrafo.</p>
</body>
</html>
```