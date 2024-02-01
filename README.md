# ASIX1M4UF1-A3Apuntes

Actividad 3, apuntes de M4

## GITHUB

Es una plataforma de desarrollo colaborativo para alojar proyectos en la nube.

**Repositorios.**

Un repositorio es el lugar donde puedes almacenar el código, los archivos y el historial de revisiones de cada archivo.

**GitHub Pages**

GitHub Pages es un servicio de alojamiento de sitio estático que toma archivos HTML, CSS y JavaScript directamente desde un repositorio en GitHub.

## MARKDOWN:

Para poner en cursiva el texto se puede usar el asterisco o el guión bajo. El texto que queramos poner en cursiva debe llevar un (*) por delante y por atrás.

Este texto está en *cursiva*.

Este texto está en _cursiva_.

Para poner en negrita el texto se puede usar el asterisco o el guión bajo. El texto que queramos poner en cursiva debe llevar dos (*) por delante y dos por atrás.

Este texto está en **negrita**.

Este texto está en __negrita__.

Para poner en negrita y cursiva el texto se combina el método de poner en negirta y en cursiva.

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

[] Opcion 1

[X] Opcion 2

[] Opcion 3

## HTML:

Estructura HTML:

Cualquier página web debe contener al menos este código para desarrollarse correctamente.

```
- <!DOCTYPE html>: se utiliza para indicar la versión HTML 5.0 (la usada actualmente).
- <html> </html>: es el elemento raíz y es el más importante dentro de la estructura HTML, pues es el que contendrá el resto de las etiquetas de atributos de la página web. 
- <head> </head>: es la etiqueta principal que incluye metadatos; son atributos que no se muestran al usuario, solo describen referencias de la página, por ejemplo, título o página CSS.
- <body> </body>: es la etiqueta para desarrollar todo el cuerpo de la página web y engloba datos desde textos hasta enlaces.
```

Ejemplo.

```
<html>
    <head>
    </head>
    <body>
        <p>Esto es un párrafo</p>
    </body>
</html>
```

Etiquetas HTML:

```
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

## CSS:

El CSS es un lenguaje que se utiliza para dar instrucciones referentes a la apariencia de una página.

Formas de insertar CSS en un documento HTML:

- CSS interno

El CSS interno requiere que se añada la etiqueta style en la sección head del documento HTML.

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

Para enlazar un archivo css externo se usará la etiqueta link en el head para enlazar el css al html.

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

## Diseño responsive

El diseño web responsive es una técnica de diseño web que busca la correcta visualización de una misma página en distintos dispositivos. Desde ordenadores de escritorio a móviles.

Se trata de redimensionar y colocar los elementos de la web de forma que se adapten al ancho de cada dispositivo permitiendo una correcta visualización y una mejor experiencia de usuario.

- Comandos diseño responsive

El primer comando a mostrar y uno de los más importantes es el display, que sirve para colocar los div como si fueran celdas o bloques.

Ejemplo.

```
.flex {
    display: flex;
}
```

Otro comando importante en un diseño responsive es el comando float, que sirve para colocar en un lado u otro del contenedor.

Ejemplo.

```
.left {
    float: left;
}
```

- Mediaquery

Las mediaqueries permiten aplicar estilos CSS según el tipo de dispositivo, lo cúal va por el tamaño o resolución de la pantalla o del ancho del viewport del navegador.

Ejemplo.

```
@media only screen and (max-width: 700px){
    img{
        width: 600px;
    }
    .column2{
        width: 100%;
    }
}
```