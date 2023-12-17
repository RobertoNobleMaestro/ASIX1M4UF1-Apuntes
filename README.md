# ASIX1M4UF1-Apuntes

## Primer tema GitHub

### Crear repositorio

Para crear un repositorio hay que ir a [Enlace a la pagina principal](https://github.com/ "Github")

Después hay que darle al más que esta arriba a la derecha.

![Imagen de github](https://github.com/RobertoNobleMaestro/ASIX1M4UF1-Apuntes/blob/main/img/captura_pagina_principal.png "boton más github")

Después saldra un desplegable y hay que darle a "new repository"

![Crear repositorio de github](https://github.com/RobertoNobleMaestro/ASIX1M4UF1-Apuntes/blob/main/img/desplegable_github.png "deplegable github")

Una vez dentro hay que poner el nombre, y marcar la opción de "add a readme file"

![Crear repositorio de github](https://github.com/RobertoNobleMaestro/ASIX1M4UF1-Apuntes/blob/main/img/desplegable_github.png "deplegable github")

### Añadir pagina web a github pages

## Segundo tema MARKDOWN

* Para hacer un texto en cursiva se hace así: *cursiva*
* Esta es otra variante para hacer un texto en cursiva: *cursiva*
* Para hacer un texto en negrita se hace así: **negrita**
* Esta es otra variante para hacer un texto en negrita se hace con dos _: **negrita**
* Este texto esta en negrita y en cursiva por lo tanto se hace con el * y con la_ ***negrita y cursiva***.

Para hacer un indice ordenado se tiene que esrcribir asi:```1.```, y asi con el 2, 3 etc

1. Primera opción de menú.
2. Segunda opción de menú.
3. Tercera opción de menú.

Para hacer una lista desordenada hay que poner un asterisco detrás del texto o un guión.

* Primera opción de lista desordenada.
* Segunda opción de lista desordenada.


Este es un ejemplo de como se podria combinar las dos maneras de hacer listas:

- Tercera opción de lista desordenada.
    1. Primer submenú
    2. Segundo submenú
* Cuarta opción de lista desordenada.
  * Primer submenú
  * Segundo submenú
+ Quinta opción de lista desordenada.
* Sexta opción de lista desordenada.



Esto sirve para visualizar el codigo y que no se ejecute, se tiene que hacer con 6 comillas y entre medio poner el codigo ` `````` `:

```
<html>
    <head>
    </head>
    <body>
        <p>Esto es un párrafo</p>
    </body>
</html> 
```
Con este codigo se creara un enlace a una pagina o a un documento
```[Esto es un enlace](https://joan23.fje.edu "Enlace a la web del cole")```

Ejemplo:

[Esto es un enlace](https://joan23.fje.edu "Enlace a la web del cole")

De esta manera se pone una imagen en el documento

```![Esto es una imagen del cielo](https://github.com/RobertoNobleMaestro/ASIX1M4UF1-A3-Apuntes/blob/main/cielo.jpg "Este es el cielo de murcia")```

Ejemplo:

![Esto es una imagen del cielo](https://github.com/RobertoNobleMaestro/ASIX1M4UF1-A3-Apuntes/blob/main/cielo.jpg "Este es el cielo de murcia")

Las tablas en Markdown se hace con esto | y en medio va la información, para fijar el ancho de las columnas hay que poner esto ```|:-------:|```, los guiones simbolizan el ancho 

|Primera col|Segunda col|Tres col|
|---------------|:----------:|---------:|
|Col 2 es|Centrada|35€|
|Col 3 es|Derecha|134€|
|Estilo cebra|Gris|Blanco|
|Clase|ASIX1|M4|

Esto hace posible poder poner varias opciones y poder marcar la que quiera el usuario, se crearia asi y para marcar la opcion se pone una X dentro de los corchetes```-[X] Opción B```

-[] Opción A

-[X] Opción B

-[] Opción C

## Tercer tema HTML

```<p> Contenido visible</p>```

### Anidar etiquetas

Anidar significa añadir una etiqueta dentro de otro o estructura.

Ej:

```
<p>hola buenas<strong>tardes</strong></p>
```

La etiqueta ```<img>``` no se puede anidar, Su estructura típica es simplemente:

```<img src="ruta_de_la_imagen" alt="texto_alternativo">```

```
<!DOCTYPE html> <- Tipo de documento que es y el lenguaje que va a usar.
<html lang="en"> <- Dentro de esta etiqueta es donde esta toda la estructura.
<head> <- En esta etiqueta es donde metemos todo lo que no puede ver el visitante.
    <meta charset="UTF-8"> <- Esta etiqueta asegura la correcta interpretación de caracteres especiales en la página web.
    <script src="https://kit.fontawesome.com/d58f8b3dda.js" crossorigin="anonymous"></script> <-- sirve para poner el paquete de iconos de fontawesome  
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> <-Esta etiqueta meta establece la escala inicial y el ancho de la ventana gráfica para optimizar la visualización en dispositivos móviles.
    <title>Document</title> <- en esta etiqueta se pone el titulo de la pagina (en la pestaña)
</head>
<body> <- Aqui es donde se pondra toda la estructura de la pagina 
    <i class="fa-solid fa-phone"></i> <-- Icono de fontawesome
</body>
</html> 
```

* Etiquetas bloque

**Todo lo que pongamos dentro de la etiqueta bloque se pondrá debajo el contenido cuando renderizemos en el navegador.**
    *Tablas
    * Titulos
    *Parrafos
    * Listas

* Etiquetas linea

**Todo el contenido es una unica linea**
    *Imagenes
    * Enlaces
    * Estilos

#### Etiquetas HTML

* Esto es un encabezado ```<h1>Lorem ipsum dolor sit</h1>```.
* Esto es un contenedor sirve para meter dentro cosas como por ejemplo texto ```<div><h1></h1></div>```.
* Esto es un subtitulo ```<h3>amet consectetur adipisicing elit. Debitis qui accusantium maiores reprehenderit.</h3>```
* Esto es un parrafo ```<p>Molestias eos distinctio repellendus, accusamus voluptatibus fugit reprehenderit</p>```
* Esto es una lista ordenada ```<ol>Lista ordenada<ol>```
* Esto sirve para subrayar un texto ```<u>Subrayar</u>```
* Esto es un elemento de cualquier lista ```<li>Elemento<li>```
* Esto es una lista desordenada ```<lu>Lista desordenada<lu>```
* Esta etiqueta sirve para hacer un salto de linea ```<br>```
* Sirve para poner un enlace (alt es para poner una descripción y target _blank es para abrir una pestaña al lado de las otras) ```<a href="https://www.google.com/" alt="Para ir a google" target="_blank">Google<a>```
* Esto es un comentario para HTML ```<!--Hola-->```
* Esta etiqueta sirve para hacer una linea horizontal ```<hr>```

#### Como hacer una tabla

```
<body> 
    <table border="1">
        <thead>
            <tr>
                <th>Puesto</th>
                <th>Atleta</th>   
                <th>Tiempo</th>
            </tr>        
        </thead>
        <tbody>
            <tr>
                <td>1r</td>  
                <td>Alejandro Perez</td>  
                <td>2:01:15</td>  
            </tr> 
            <tr>
                <td>2n</td>  
                <td>Torcuato Garcia</td>  
                <td>2:15:15</td>  
            </tr> 
            <tr>
                <td>3r</td>  
                <td>Wenseslao Perez</td>  
                <td>3:12:05</td>  
            </tr> 
        </tbody>
        <tfoot>
            <tr>
                <th>Puesto</th>
                <th>Atleta</th>   
                <th>Tiempo</th>
            </tr>  
        </tfoot>
    </table>
</body>
```

## Cuarto tema CSS

CSS se utiliza para dar estilo a la estructura HTML.

### Maneras de aplicar css a HTML

Hay tres maneras para aplicar css en HTML:

#### 1. En linea

Esta manera de aplicar css se utiliza de manera directa en el HTML, se aplica en la etiqueta que tu quieras y se hace con style.

Ejemplo:

```
<body>
<p style="color:red"> <-- Estos hace que se vea en rojo la letra
</p>
</body>
```

#### 2. Interno

Al aplicar de esta manera el css en el HTML se aplicara solamente al documento y por lo tanto si hay más HTML's no les afectará.

```
<!DOCTYPE html> 
<html lang="en"> 
<head> 
    <meta charset="UTF-8"> 
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
    <title>Document</title> 
    <style>
        tbody{
            color: #00ffff;
        }    
    </style>
</head>
<body> 
    <table border="1">
        <thead>
            <tr>
                <th>Puesto</th>
                <th>Atleta</th>   
                <th>Tiempo</th>
            </tr>        
        </thead>
        <tbody>
            <tr>
                <td>1r</td>  
                <td>Alejandro Perez</td>  
                <td>2:01:15</td>  
            </tr> 
            <tr>
                <td>2n</td>  
                <td>Torcuato Garcia</td>  
                <td>2:15:15</td>  
            </tr> 
            <tr>
                <td>3r</td>  
                <td>Wenseslao Perez</td>  
                <td>3:12:05</td>  
            </tr> 
        </tbody>
        <tfoot>
            <tr>
                <th>Puesto</th>
                <th>Atleta</th>   
                <th>Tiempo</th>
            </tr>  
        </tfoot>
    </table>
</body>
</html>
```

#### 3. Externo

Este se utiliza desde otro archivo CSS afectará este archivo a todos los HTML que estén vinculados.

Se vincula de la siguiente manera: ```<link rel="stylesheet" href="nombre_del_archivo_css">```

El cambio de color se puede hacer de las siguientes maneras:

1. Ejemplo de RGB numérico: ```<p style="color: rgb(255,0,0)">Numerico</p>```
2. Ejemplo de RGB hexadecimal:```<p style="color: #ff0000">Hexadecimal</p>```
3. Ejemplo de RGB poniendo el nombre: ```<p style="color: red">Nombre</p>```

### Estilos de CCS

Los estilos de CSS se encargan de que el documento HTML tenga diferentes estilos dependiendo de los estilos que quieras añadir

* ```Width``` (ancho): Controla el tamaño horizontal del elemento.
* ```height``` (alto): Controla el tamaño vertical del elemento.
* ```background-color``` (color de fondo): Define el color detrás del contenido.
* ```color```: Establece el color del texto dentro del elemento.
* ```text-align```(alineación de texto): Alinea el texto dentro del elemento.
* ```padding``` (relleno): Agrega espacio alrededor del contenido dentro del elemento.
* ```border``` (borde): Es una línea alrededor del contenido.
* ```margin``` (margen): Es el espacio fuera del elemento, que lo separa de otros elementos.
* ```text-decoration``` (decoración de texto): Puede subrayar o tachar el texto, o se puede poner que no tenga decoración el texto.
* ```border-radius``` (radio del borde): suaviza las esquinas del borde.
* ```font-size``` (tamaño de fuente): Controla el tamaño del texto.

### Selectores de CCS

#### Selector de tipo

Selecciona todos los elementos de un tipo específico, como p para párrafos o h1 para encabezados de nivel 1.

```p {
  color: blue;
}
```

#### Selector de Clase

Selecciona elementos que tienen un atributo de clase específico.

```.mi-clase {
  font-size: 16px;
}
```

#### Selector de ID

Selecciona un elemento con un ID específico.

```#mi-id {
  background-color: yellow;
}
```

#### Selector de Descendencia

 Selecciona elementos secundarios de otro elemento.

```div p {
  font-style: italic;
}
```

#### Selector de Atributo

Selecciona elementos con un atributo específico.

```hr {
  border: 1px solid black;
}
```

#### Selector Universal

 Selecciona todos los elementos

```* {
  margin: 0;
  padding: 0;
}`
```
