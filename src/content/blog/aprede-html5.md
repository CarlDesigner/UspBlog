---
title: "Aprende HTML5 de una vez por todas"
excerpt: "Guia para aprender HTML5"
publishDate: "2023-04-30T11:39:36.050Z"
image: "https://res.cloudinary.com/do66lfayc/image/upload/v1681318858/BlogUsp/aprendehtml5_zq6d5u.jpg"
# category slug: choose from "./src/data/category.js"
category: "web-development"
# remove this line to publish
draft: false
# author slug: choose from "./src/data/authors.js"
author: "carlos-fajardo"
tags: [html5, web development, programmer]
---

# **¡Bienvenidos a la guía de HTML5 para desarrolladores web autodidactas!**

En este tutorial, aprenderás todo lo que necesitas saber para crear sitios web utilizando el lenguaje de marcado HTML5. Desde las etiquetas básicas hasta las más avanzadas, te guiaré a través de los conceptos esenciales que necesitas conocer para comenzar tu viaje en el desarrollo web.


### Introducción

**HTML** (*HyperText Markup Language*) es un lenguaje de marcado utilizado para estructurar y dar formato al contenido de una página web, fue creado por **Tim Berners-Lee** y su equipo en el **CERN** (Organización Europea para la Investigación Nuclear) a principios de la década de 1990. La primera especificación de HTML se publicó en 1993 como una propuesta para un lenguaje de marcado de hipertexto estándar. Con **HTML,** puedes crear textos, imágenes, enlaces, listas y muchos otros elementos que componen una página web. Además, con **HTML5**, se han introducido nuevas etiquetas semánticas que te permiten crear sitios web más accesibles y fáciles de entender para los motores de búsqueda.

En esta guía, nos centraremos en las etiquetas **HTML5** más importantes, incluyendo las etiquetas semánticas y las más utilizadas. Comenzaremos por aprender los conceptos básicos de **HTML** y cómo crear una página web desde cero. A lo largo del camino, te daremos consejos y ejemplos para que puedas comprender y aplicar cada etiqueta y atributo correctamente.

La creación de páginas web es una habilidad cada vez más importante en la era digital en la que vivimos. Para ello, es fundamental conocer el lenguaje de marcado **HTML5**, el cual nos permite estructurar el contenido de nuestras páginas y definir su apariencia visual. Sin embargo, aprender todas las etiquetas de **HTML5** de una sola vez puede ser abrumador, especialmente para aquellos que son nuevos en el desarrollo web. Es por eso que en esta guía, nos centraremos en presentar las etiquetas **HTML5** de manera organizada y lógica, agrupándolas por categorías o tipos. En este sentido, veremos las etiquetas semánticas, las más comunes y las que se utilizan para multimedia, formularios y tablas, de manera que al finalizar tendrás una comprensión sólida de las etiquetas **HTML5** y podrás empezar a crear tus propias páginas web.

*¡Asi que...Comencemos con HTML y construyamos juntos una web más hermosa y funcional!* 🚀

---

### Sintaxis HTML

```html
    <etiqueta atributo="valor"Contenido></etiqueta>
```

Esta es la sintaxis basica de html, donde:

- `<etiqueta>` se refiere al nombre de la etiqueta HTML que se está creando, como `<p>` para párrafos, `<h1>` para encabezados, entre otros.

- `atributo` es una propiedad que se puede agregar a la etiqueta para proporcionar información adicional sobre el elemento. Por ejemplo, el atributo `class` se utiliza para asignar una clase CSS al elemento, mientras que el atributo `id` se utiliza para darle un identificador único al elemento.
  
- `valor` es el valor asignado al atributo.

- `Contenido` se refiere al contenido que se encuentra dentro de la etiqueta, como texto, imágenes u otros elementos HTML.
  
Por ejemplo, si quisieras crear un párrafo con un estilo CSS personalizado, podrías usar la etiqueta `<p>` con el atributo `class` y el valor `mi-clase`, y luego agregar el contenido del párrafo dentro de la etiqueta, de la siguiente manera:

```html
<p class="mi-clase">Este es mi contenido de párrafo</p>
```


## Etiquetas Básicas <⁄>
Estas son las etiquetas más fundamentales en HTML y son necesarias para cualquier página web. 

1. `<!DOCTYPE hmtl>`: Esta etiqueta define la versión del lenguaje de marcado que se está utilizando en la página web. No tiene atributos.
<br>

2. `<html>`: Esta etiqueta envuelve todo el contenido de la página web y le dice al navegador que el contenido está escrito en HTML. Tiene un atributo opcional llamado "lang" que se utiliza para especificar el idioma de la página.
por ejemplo: *`lang="es"`* para español, *`lang="en"`* para inglés y así susecivamente, el codigo con este atributo vería así:
```html
<!DOCTYPE html lang="en">
```

3. `<head>`: Esta etiqueta se utiliza para contener información que no se muestra directamente en la página web, como metadatos, enlaces a hojas de estilo y scripts. No tiene atributos.
<br>

4. `meta charset`: La etiqueta *`meta charset`* se utiliza para especificar la codificación de caracteres que se utiliza en el documento HTML, esta etiqueta va dentro de la etiqueta `<head>`.
El atributo charset indica el conjunto de caracteres que se utiliza para codificar el texto del documento HTML. *`meta charset="UTF-8"`* especifica que se utiliza la codificación UTF-8, que puede representar prácticamente cualquier carácter en Unicode. Esta etiqueta es importante para asegurarse de que los caracteres se muestren correctamente en el navegador y debe estar presente en el encabezado de todos los documentos HTML.
Así se vería esta etiqueta: 
```html
<meta charset="UTF-8">
```
5. `<title>`: Esta etiqueta se utiliza para definir el título de la página web que se muestra en la pestaña del navegador. No tiene atributos.
<br>

6. `<body>`: Esta etiqueta envuelve todo el contenido visible de la página web, como texto, imágenes, videos y otros elementos HTML. No tiene atributos.

Es importante tener en cuenta que estas etiquetas básicas son la base de cualquier página web en HTML5 y es necesario incluirlas en todas tus páginas, Aquí un ejemplo básico de la estructura de un documento HTML5 con las etiquetas ya mencionadas:

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8">
    <title>Título de la página</title>
  </head>
  <body>
    <!-- aquí el contenido de la pagina html -->
  </body>
</html>
```
Continuemos...
## Etiquetas de Texto 📝
Estas etiquetas se utilizan para mostrar texto en la página web.

1. `<p>`:  Esta etiqueta se utiliza para definir un párrafo de texto. Es la forma más común de presentar texto en una página web. No tiene atributos, ejemplo:

```html
  <p>Este es un parrafo</p>
```
   
2. `<h1> a <h6>`: Estas etiquetas se utilizan para definir los encabezados de la página, desde el título principal (h1) hasta los subtítulos (h2, h3, etc.). El número indica el nivel de importancia del encabezado. Por ejemplo, `<h1>` es el encabezado más importante y `<h6>` es el menos importante. No tienen atributos.
Ejemplo:
    # Titulo con `<h1>`
    ## Titulo con `<h2>`
    ### Titulo con `<h3>`
    #### Titulo con `<h4>`
    ##### Titulo con `<h5>`
    ###### Titulo con `<h6>`
    Cabe aclarar que en una sola pagina no debe haber mas de una etiqueta `<h1>`, esto se hace por buenas práticas ya que eso afectaria  el `SEO` de la página.
    <br>

3. `<strong>`: Esta etiqueta se utiliza para enfatizar un texto y hacerlo más fuerte. Por defecto, el texto se muestra en negrita. No tiene atributos.

   ```html
      <p>Este texto está en <strong> Negrita </strong> </p>
   ```
   Este texto está en **Negrita**
   <br>

4. `<em>`: Esta etiqueta se utiliza para enfatizar un texto y hacerlo más importante. Por defecto, el texto se muestra en cursiva. No tiene atributos.

   ```html
      <p>Este texto está en <em> Cursiva </em> </p>
   ```
   Este texto está en *Cursiva*
   <br>

5. `<u>`: Esta etiqueta se utiliza para subrayar un texto. No se recomienda su uso porque se confunde con un enlace hipertexto. No tiene atributos.
    ```html
      <p>Este texto está <em> Subrayado </em> </p>
   ```
   Este texto está <u>Subrayado</u>
   <br>

6. `<br>`: Esta etiqueta se utiliza para insertar un salto de línea en el texto. No tiene atributos.
<br>
   
7. `<hr>`: Esta etiqueta se utiliza para insertar una línea horizontal en la página. Es útil para separar secciones de contenido. Los atributos que puede tener son `align`, `color` y `width`.

 - `align`: especifica la alineación horizontal de la línea horizontal en relación con el elemento contenedor. Los valores posibles son "*left*", "*right*" o "*center*". 
 - `color`: define el color de la línea horizontal. Se puede especificar un valor de color en formato hexadecimal o en nombres de colores predefinidos como "*red*", "*green*", "*blue*", etc.
 - `width`: establece el ancho de la línea horizontal. Se puede especificar un valor en píxeles o en porcentaje.
<br>

8. `<bloquote>`: Esta etiqueta se utiliza para citar un bloque de texto. El texto se muestra con una sangría en ambos lados. Un atributo importante que puede tener es `cite`.
   
  - `cite`: este atributo se utiliza para especificar la fuente de la cita. Es decir, si estás citando a alguien o haciendo referencia a una fuente externa, puedes utilizar este atributo para enlazar a la fuente original. El valor del atributo debe ser una URL válida.
  
    Es importante mencionar que el uso del atributo cite es opcional en la etiqueta `<blockquote>`. Sin embargo, si se utiliza, es importante que la URL especificada en el atributo sea una fuente válida y confiable para que los lectores puedan verificar la información citada.
  Aquí te dejo un ejemplo de cómo usar la etiqueta `<blockquote>`:
  ```html
  <blockquote>
    <p>"La verdadera felicidad no es otra cosa que la satisfacción de haber hecho todo lo que se debe y todo lo que se puede por los demás y por nosotros mismos."</p>
    <cite>– Alejandro Magno</cite>
  </blockquote>
  ```

<br>

9. `span`: también es una etiqueta de texto importante que se utiliza para aplicar estilos a pequeñas secciones de texto o agrupar elementos de texto para aplicarles un estilo común. La etiqueta `<span>` no tiene un significado semántico en sí misma, pero se utiliza en conjunto con CSS para aplicar estilos. No tiene atributos obligatorios, pero se puede utilizar el atributo "*class*" o "*id*" para identificar el elemento y aplicarle estilos específicos con CSS.

Es importante mencionar que hay muchas más etiquetas de texto en HTML5, pero estas son algunas de las más utilizadas.

## Etiquetas de Imagen 📷
Estas etiquetas se utilizan para insertar imágenes en la página web.

1. `img`: Esta etiqueta se utiliza para insertar imágenes en la página web. El atributo `src` se utiliza para especificar la *"URL"* de la imagen que se va a mostrar. Otros atributos importantes incluyen *"alt"* *(texto alternativo que se muestra si la imagen no se puede cargar o si el usuario está usando un lector de pantalla)*, *"width"* y *"height"* *(especifican el ancho y alto de la imagen, respectivamente)*. La etiqueta `<img>` no tiene una etiqueta de cierre, ya que se considera un elemento vacío.
Aquí te dejo un ejemplo de cómo usar la etiqueta `<img>`:
```html
<img src="ruta/de/la/imagen.jpg" alt="Descripción de la imagen">
```
<br>

2. `<figure>`: Esta etiqueta se utiliza para agrupar imágenes u otros elementos multimedia junto con su descripción o leyenda. Por lo general, se utiliza junto con la etiqueta `<figcaption>` para agregar una descripción o leyenda a la imagen o elemento multimedia. Los atributos que puede tener la etiqueta `<figure>` son class e id, que se utilizan para aplicar estilos específicos a los elementos en la página web y para identificarlos mediante JavaScript o CSS.
<br>

3. `figcaption`: utiliza para agregar una descripción o leyenda a una imagen o elemento multimedia que está dentro de una etiqueta `<figure>`. Esta etiqueta debe colocarse inmediatamente después de la etiqueta `<img>` o el elemento multimedia.

Los atributos que puede tener la etiqueta `<figcaption>` son class, id, que se utilizan para aplicar estilos específicos a los elementos en la página web y para identificarlos mediante JavaScript o CSS.

Aquí te dejo un ejemplo de cómo usar la etiqueta `<figure>` con `<figcaption>`:
```html
<figure>
  <img src="ejemplo.jpg" alt="Ejemplo">
  <figcaption>Esta es una imagen de ejemplo</figcaption>
</figure>
```

## Etiquetas de Enlace 🔗
Estas etiquetas se utilizan para crear enlaces a otras páginas web o a otros recursos dentro de la página.

1. `<a>`: Esta etiqueta se utiliza para crear un enlace a otra página web o a otro recurso dentro de la página actual. El atributo `"href"` especifica la dirección *URL* del destino del enlace. También puede tener otros atributos como `"target"` para indicar si el enlace debe abrirse en una nueva pestaña o ventana del navegador, y `"title"` para proporcionar información adicional sobre el enlace. Ejemplo:
```html
<a href="https://www.ejemplo.com" target="_blank" title="Enlace de ejemplo">Visita Ejemplo.com</a>
```
<br>

2. `<link>`: Esta etiqueta se utiliza para enlazar un documento externo con la página actual, como una hoja de estilos *CSS*. El atributo `"href"` especifica la dirección *URL* del documento externo y el atributo `"rel"` especifica la relación entre el documento actual y el documento externo. Ejemplo: 
```html
<link rel="stylesheet" href="estilos.css">
```
<br>

3. `<nav>`: Esta etiqueta se utiliza para definir una sección de navegación en la página web. Se puede utilizar para crear menús de navegación. Ejemplo: 
```html
<nav>
  <ul>
    <li><a href="inicio.html">Inicio</a></li>
    <li><a href="servicios.html">Servicios</a></li>
    <li><a href="contacto.html">Contacto</a></li>
  </ul>
</nav>
```

## Etiquetas de Lista 📌
Estas etiquetas se utilizan para crear listas de elementos, ya sea numeradas o sin numerar.

1. `<ul>`: Esta etiqueta se utiliza para crear una lista sin numerar. Los elementos de la lista se indican con la etiqueta `<li>`. Los atributos que puede tener son *class* e *id*. Ejemplo:
```html
<ul>
  <li>Elemento 1</li>
  <li>Elemento 2</li>
  <li>Elemento 3</li>
</ul>
```
<br>

2. `<ol>`: Esta etiqueta se utiliza para crear una lista numerada. Los elementos de la lista se indican con la etiqueta `<li>`. Los atributos que puede tener son *start*, *type*, *class* e *id*.
```html
<ol>
  <li>Elemento 1</li>
  <li>Elemento 2</li>
  <li>Elemento 3</li>
</ol>
```
- `start` se utiliza en las etiquetas `<ol>` para establecer el número de inicio de la lista numerada. Por ejemplo, si se establece *"start"* en *"3"*, la lista comenzará en el número 3 en lugar del número 1. Este atributo acepta valores numéricos positivos.

- `type` también se utiliza en las etiquetas `<ol>` para especificar el tipo de numeración que se usará. Hay diferentes valores que se pueden utilizar, como *"1"* (para números arábigos), *"a"* (para letras minúsculas), *"A"* (para letras mayúsculas), *"i"* (para números romanos en minúsculas), *"I"* (para números romanos en mayúsculas), entre otros. Por ejemplo, para crear una lista numerada con letras mayúsculas, se puede establecer `type` en *"A"*. Para las etiquetas `<ul>`, el atributo `type` no tiene ningún efecto y no se recomienda su uso. Ejemplo:
```html
<ol start="3" type="A">
  <li>Elemento 3A</li>
  <li>Elemento 3B</li>
  <li>Elemento 3C</li>
</ol>
```
<br>

3. `<li>`: Esta etiqueta se utiliza para indicar un elemento de una lista `<ul>` o `<ol>`. No puede ser utilizada fuera de estas etiquetas. Los atributos que puede tener son value, class e id. Ejemplo:
```html
<ol>
  <li value="10">Item 1</li>
  <li>Item 2</li>
  <li value="20">Item 3</li>
</ol>
```
En este ejemplo, el primer elemento de la lista tiene un valor de *10*, el segundo elemento sigue con un valor de *11* *(por defecto)* y el tercer elemento tiene un valor de *20*.

## Etiquetas de Formulario 📑
Estas etiquetas se utilizan para crear formularios que permiten a los usuarios enviar información a través de la página web.

1. `<form>`: Esta etiqueta se utiliza para crear un formulario en la página web. Sus atributos más comunes son `action`, `method` y `enctype`. El atributo `action` especifica la página a la que se enviará el formulario. El atributo `method` especifica el método *HTTP* que se utilizará para enviar los datos del formulario. El atributo `enctype` especifica el tipo de codificación que se utilizará para enviar los datos del formulario. Ejemplo:
```html
<form action="procesar.php" method="POST" enctype="multipart/form-data">
  <!-- elementos del formulario -->
</form>
```
<br>

2. `<input>`: Esta etiqueta se utiliza para crear diferentes tipos de campos de entrada de datos en un formulario, tiene un atributo llamado `type`, Algunos de los valores que puede tomar el atributo `type` son *text*, *password*, *checkbox*, *radio*, *submit*, *reset*, *file* y *hidden*.
   
- **type="text"**: Este valor se utiliza para crear un campo de texto normal, en el que el usuario puede escribir texto.
- **type="password"**: Este valor se utiliza para crear un campo de contraseña, en el que el texto se muestra oculto mientras se escribe.
- **type="checkbox"**: Este valor se utiliza para crear una casilla de verificación, en la que el usuario puede seleccionar o deseleccionar una opción.
- **type="radio"**: Este valor se utiliza para crear un botón de opción, en el que el usuario puede seleccionar una opción de varias opciones exclusivas.
- **type="submit"**: Este valor se utiliza para crear un botón de envío, que se utiliza para enviar los datos del formulario al servidor.
- **type="reset"**: Este valor se utiliza para crear un botón de restablecimiento, que se utiliza para borrar los datos del formulario.
- **type="file"**: Este valor se utiliza para permitir al usuario seleccionar y cargar un archivo desde su computadora.
- **type="hidden"**: Este valor se utiliza para crear un campo oculto que no es visible para el usuario, pero que puede ser enviado junto con otros datos del formulario al servidor.
  
<br>

3. `<label>`: Esta etiqueta se utiliza para etiquetar un campo de entrada de datos en un formulario. Se asocia con un campo de entrada mediante el atributo *for* que debe tener el mismo valor que el atributo *id* del campo de entrada. Ejemplo:
```html
<label for="nombre">Nombre:</label>
<input type="text" name="nombre" id="nombre">
```
<br>

4. `<textarea>`: Esta etiqueta se utiliza para crear un campo de entrada de texto de varias líneas en un formulario. El número de filas y columnas del campo se puede especificar mediante los atributos *rows* y *cols*. Ejemplo:
```html
<textarea name="comentarios" rows="5" cols="30">Introduce tus comentarios aquí</textarea>
```
<br>

5. `<button>`: Esta etiqueta se utiliza para crear un botón en un formulario. El atributo *type* especifica el tipo de botón que se creará (por ejemplo, *submit* o *reset*). Ejemplo:
```html
<button type="submit" name="submit">Enviar</button>
```
<br>

## Etiquetas Semánticas 🤔
Estas son las etiquetas HTML5 que se utilizan para dar significado y estructura semántica al contenido de una página web

1. `<header>`: Esta etiqueta se utiliza para identificar la sección de encabezado de una página web o de una sección de contenido. Suele incluir el logo y la navegación principal. Algunos de los atributos que puede tener son *class* y *id*. Ejemplo:
```html
<header>
  <img src="logo.png" alt="Logo de la página">
  <nav>
    <ul>
      <li><a href="#">Inicio</a></li>
      <li><a href="#">Acerca de</a></li>
      <li><a href="#">Contacto</a></li>
    </ul>
  </nav>
</header>
```
<br>

2. `<nav>`: Esta etiqueta se utiliza para identificar la sección de navegación de una página web o de una sección de contenido. Suele incluir enlaces a otras secciones de la página o a otras páginas relacionadas. Algunos de los atributos que puede tener son *class* y *id*.
Ejemplo:
```html
<nav>
  <ul>
    <li><a href="#">Inicio</a></li>
    <li><a href="#">Acerca de</a></li>
    <li><a href="#">Contacto</a></li>
  </ul>
</nav>
```
<br>

3. `<section>`: Esta etiqueta se utiliza para agrupar contenido relacionado en una página web. Puede ser una sección de contenido, un capítulo de un libro, una sección de noticias, etc. Algunos de los atributos que puede tener son *class* y *id*.
Ejemplo:
```html
<section>
  <h2>Sección de noticias</h2>
  <article>
    <h3>Título de la noticia</h3>
    <p>Contenido de la noticia</p>
  </article>
  <article>
    <h3>Título de otra noticia</h3>
    <p>Contenido de la otra noticia</p>
  </article>
</section>
```
<br>

4. `<article>`: Esta etiqueta se utiliza para identificar un contenido independiente, como un artículo, una entrada de blog, un comentario, etc. Debe tener sentido por sí solo y puede ser distribuido o reutilizado independientemente del resto de la página. Algunos de los atributos que puede tener son *class* y *id*.
Ejemplo:
```html
<article>
  <h2>Título del artículo</h2>
  <p>Contenido del artículo</p>
  <p>Autor: Juan Pérez</p>
  <time datetime="2022-04-30">30 de abril de 2022</time>
</article>
```
<br>

5. `<aside>`: Esta etiqueta se utiliza para identificar contenido relacionado o complementario al contenido principal de una página web. Puede incluir publicidad, enlaces a contenido relacionado, una barra lateral, etc. Algunos de los atributos que puede tener son *class* y *id*.
Ejemplo:
```html
<article>
  <h2>Título del artículo</h2>
  <p>Contenido del artículo</p>
  <aside>
    <h3>Artículos relacionados</h3>
    <ul>
      <li><a href="#">Artículo relacionado 1</a></li>
      <li><a href="#">Artículo relacionado 2</a></li>
      <li><a href="#">Artículo relacionado 3</a></li>
    </ul>
  </aside>
</article>
```
<br>

6. `<footer>`: Esta etiqueta se utiliza para definir el pie de página de una página web. El pie de página generalmente incluye información de contacto, derechos de autor y enlaces a otras páginas. Los atributos que puede tener son *global attributes*.
Ejemplo:
```html
<footer>
   <p>Derechos de autor © 2023 - Mi sitio web</p>
   <nav>
      <ul>
         <li><a href="contacto.html">Contacto</a></li>
         <li><a href="acerca.html">Acerca de</a></li>
      </ul>
   </nav>
</footer>
```
<br>

7. `<main>`: Esta etiqueta se utiliza para indicar la sección principal o el contenido principal de una página web. Es importante incluir esta etiqueta para mejorar la accesibilidad y la estructura semántica de la página. Algunos de sus atributos son *id* y *class*. Ejemplo:
```html
<body>
  <header>
    <!-- encabezado de la página -->
  </header>
  
  <main>
    <!-- contenido principal de la página -->
  </main>

  <footer>
    <!-- pie de la página -->
  </footer>
</body>
```
<br>
¡Listo! Ya hemos concluido con la explicación de las etiquetas de HTML5. Espero que esta información haya sido útil y te haya permitido comprender mejor cómo utilizar estas etiquetas para crear páginas web estructuradas y semánticas.

## Conclusión ✅
En conclusión, las etiquetas **HTML** son elementos fundamentales en la creación de una página web. Cada etiqueta tiene una función específica y, en conjunto, permiten crear una estructura coherente y organizada para el contenido de la página. Las etiquetas de texto permiten mostrar y dar formato al contenido de la página, mientras que las etiquetas de imagen y enlace permiten añadir elementos visuales y enlazar a otras páginas o recursos. Las etiquetas de lista, formulario y tabla permiten organizar el contenido de manera más específica y permiten al usuario interactuar con la página.

Además, con la introducción de las etiquetas semánticas en **HTML5**, se ha logrado dar un significado más claro y estructurado al contenido de la página, lo que ayuda a los motores de búsqueda a indexar el contenido de manera más precisa y a mejorar la accesibilidad de la página para personas con discapacidades.

Es importante tener en cuenta que las etiquetas **HTML** deben utilizarse de manera correcta y coherente para garantizar que la página web sea legible, accesible y fácil de mantener. Se deben seguir buenas prácticas de diseño y desarrollo web para crear una página web eficiente, rápida y amigable para el usuario.

A continuación un ejemplo de la estructura de una pagina web utilizando algunas de las etiquetas **HTML5** que hemos visto anteriormente

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mi primera página web</title>
</head>
<body>
  <header>
    <h1>Encabezado de mi página</h1>
    <nav>
      <ul>
        <li><a href="#">Inicio</a></li>
        <li><a href="#">Productos</a></li>
        <li><a href="#">Servicios</a></li>
        <li><a href="#">Contacto</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section>
      <h2>Productos destacados</h2>
      <ul>
        <li>
          <figure>
            <img src="producto1.jpg" alt="Producto 1">
            <figcaption>Producto 1</figcaption>
          </figure>
          <p>Descripción del producto 1</p>
        </li>
        <li>
          <figure>
            <img src="producto2.jpg" alt="Producto 2">
            <figcaption>Producto 2</figcaption>
          </figure>
          <p>Descripción del producto 2</p>
        </li>
      </ul>
    </section>

    <section>
      <h2>Formulario de contacto</h2>
      <form action="enviar.php" method="POST">
        <label for="nombre">Nombre:</label>
        <input type="text" id="nombre" name="nombre" required>
        <br>
        <label for="email">Correo electrónico:</label>
        <input type="email" id="email" name="email" required>
        <br>
        <label for="mensaje">Mensaje:</label>
        <textarea id="mensaje" name="mensaje" required></textarea>
        <br>
        <button type="submit">Enviar</button>
      </form>
    </section>
  </main>

  <aside>
    <h2>Información adicional</h2>
    <p>Texto de ejemplo para la sección de información adicional.</p>
  </aside>

  <footer>
    <p>Derechos de autor © 2022 Mi empresa. Todos los derechos reservados.</p>
  </footer>
</body>
</html>
```
<br>

Espero que hayan disfrutado de esta guia de **HTML5** y el ejemplo de la página web que hemos creado juntos usando algunas de las etiquetas de **HTML** que hemos aprendido. Pero esto es solo el comienzo, ya que seguiremos publicando más contenido relacionado con **HTML** en el futuro. 🚀

Estén atentos a nuestros próximos artículos donde compartiremos algunos trucos y consejos para mejorar en **HTML** y también publicaremos una guía para aprender a estilizar **HTML** con **CSS3**.

¡Manténganse conectados devs! 🔌 👥 

>Nunca pares de aprender, siempre hay algo nuevo que descubrir y mejorar en tu camino como desarrollador web.