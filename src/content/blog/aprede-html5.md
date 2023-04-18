---
title: "Aprende HTML5 de una vez por todas"
excerpt: "Guia para aprender HTML5"
publishDate: "2023-04-12T11:39:36.050Z"
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

**HTML** (*HyperText Markup Language*) es un lenguaje de marcado utilizado para estructurar y dar formato al contenido de una página web, fue creado por **Tim Berners-Lee** y su equipo en el **CERN** (Organización Europea para la Investigación Nuclear) a principios de la década de 1990. La primera especificación de HTML se publicó en 1993 como una propuesta para un lenguaje de marcado de hipertexto estándar. Con **HTML,** puedes crear textos, imágenes, enlaces, listas y muchos otros elementos que componen una página web. Además, con **HTML5**, se han introducido nuevas etiquetas semánticas que te permiten crear sitios web más accesibles y fáciles de entender para los motores de búsqueda.

En esta guía, nos centraremos en las etiquetas **HTML5** más importantes, incluyendo las etiquetas semánticas y las más utilizadas. Comenzaremos por aprender los conceptos básicos de **HTML** y cómo crear una página web desde cero. A lo largo del camino, te daremos consejos y ejemplos para que puedas comprender y aplicar cada etiqueta y atributo correctamente.

La creación de páginas web es una habilidad cada vez más importante en la era digital en la que vivimos. Para ello, es fundamental conocer el lenguaje de marcado **HTML5**, el cual nos permite estructurar el contenido de nuestras páginas y definir su apariencia visual. Sin embargo, aprender todas las etiquetas de **HTML5** de una sola vez puede ser abrumador, especialmente para aquellos que son nuevos en el desarrollo web. Es por eso que en esta guía, nos centraremos en presentar las etiquetas **HTML5** de manera organizada y lógica, agrupándolas por categorías o tipos. En este sentido, veremos las etiquetas semánticas, las más comunes y las que se utilizan para multimedia, formularios y tablas, de manera que al finalizar tendrás una comprensión sólida de las etiquetas **HTML5** y podrás empezar a crear tus propias páginas web.

*¡Asi que...Comencemos con HTML y construyamos juntos una web más hermosa y funcional!*

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


## Etiquetas Básicas
Estas son las etiquetas más fundamentales en HTML y son necesarias para cualquier página web. 

1. `<!DOCTYPE hmtl>`: Esta etiqueta define la versión del lenguaje de marcado que se está utilizando en la página web. No tiene atributos.
   
2. `<html>`: Esta etiqueta envuelve todo el contenido de la página web y le dice al navegador que el contenido está escrito en HTML. Tiene un atributo opcional llamado "lang" que se utiliza para especificar el idioma de la página.
por ejemplo: *`lang="es"`* para español, *`lang="en"`* para inglés y así susecivamente, el codigo con este atributo vería así:
```html
<!DOCTYPE html lang="en">
```

3. `<head>`: Esta etiqueta se utiliza para contener información que no se muestra directamente en la página web, como metadatos, enlaces a hojas de estilo y scripts. No tiene atributos.

4. `meta charset`: La etiqueta *`meta charset`* se utiliza para especificar la codificación de caracteres que se utiliza en el documento HTML, esta etiqueta va dentro de la etiqueta `<head>`.
El atributo charset indica el conjunto de caracteres que se utiliza para codificar el texto del documento HTML. *`meta charset="UTF-8"`* especifica que se utiliza la codificación UTF-8, que puede representar prácticamente cualquier carácter en Unicode. Esta etiqueta es importante para asegurarse de que los caracteres se muestren correctamente en el navegador y debe estar presente en el encabezado de todos los documentos HTML.
Así se vería esta etiqueta: 
```html
<meta charset="UTF-8">
```
5. `<title>`: Esta etiqueta se utiliza para definir el título de la página web que se muestra en la pestaña del navegador. No tiene atributos.

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
Continuemos.. 
## Etiquetas de Texto
Estas etiquetas se utilizan para mostrar texto en la página web.

1. `<p>`:  Esta etiqueta se utiliza para definir un párrafo de texto. Es la forma más común de presentar texto en una página web. No tiene atributos, ejemplo:

```html
  <p>Este es un parrafo</p>
```
   
2. `<h1> a <h6>`: Estas etiquetas se utilizan para definir los encabezados de la página, desde el título principal (h1) hasta los subtítulos (h2, h3, etc.). El número indica el nivel de importancia del encabezado. Por ejemplo, `<h1>` es el encabezado más importante y `<h6>` es el menos importante. No tienen atributos.<br>
Ejemplo:
    # Titulo con `<h1>`
    ## Titulo con `<h2>`
    ### Titulo con `<h3>`
    #### Titulo con `<h4>`
    ##### Titulo con `<h5>`
    ###### Titulo con `<h6>`
    Cabe aclarar que en una sola pagina no debe haber mas de una etiqueta `<h1>`, esto se hace por buenas práticas ya que eso afectaria  el `SEO` de la página.

3. `<strong>`: Esta etiqueta se utiliza para enfatizar un texto y hacerlo más fuerte. Por defecto, el texto se muestra en negrita. No tiene atributos.
   
   ```html
      <p>Este texto está en <strong> Negrita </strong> </p>
   ```
   Este texto está en **Negrita**

4. `<em>`: Esta etiqueta se utiliza para enfatizar un texto y hacerlo más importante. Por defecto, el texto se muestra en cursiva. No tiene atributos.
   ```html
      <p>Este texto está en <em> Cursiva </em> </p>
   ```
   Este texto está cursiva *Cursiva*

5. `<u>`: Esta etiqueta se utiliza para subrayar un texto. No se recomienda su uso porque se confunde con un enlace hipertexto. No tiene atributos.
    ```html
      <p>Este texto está <em> Subrayado </em> </p>
   ```
   Este texto está <u>Subrayado</u>

6. `<br>`: Esta etiqueta se utiliza para insertar un salto de línea en el texto. No tiene atributos.
   
7. `<hr>`: Esta etiqueta se utiliza para insertar una línea horizontal en la página. Es útil para separar secciones de contenido. Los atributos que puede tener son `align`, `color` y `width`.

     - `align`: especifica la alineación horizontal de la línea horizontal en relación con el elemento contenedor. Los valores posibles son "*left*", "*right*" o "*center*". 
     - `color`: define el color de la línea horizontal. Se puede especificar un valor de color en formato hexadecimal o en nombres de colores predefinidos como "*red*", "*green*", "*blue*", etc.
     - `width`: establece el ancho de la línea horizontal. Se puede especificar un valor en píxeles o en porcentaje.

8. `<bloquote>`: Esta etiqueta se utiliza para citar un bloque de texto. El texto se muestra con una sangría en ambos lados. Un atributo importante que puede tener es `cite`.
   
      - `cite`: este atributo se utiliza para especificar la fuente de la cita. Es decir, si estás citando a alguien o haciendo referencia a una fuente externa, puedes utilizar este atributo para enlazar a la fuente original. El valor del atributo debe ser una URL válida.
  
    Es importante mencionar que el uso del atributo cite es opcional en la etiqueta `<blockquote>`. Sin embargo, si se utiliza, es importante que la URL especificada en el atributo sea una fuente válida y confiable para que los lectores puedan verificar la información citada.

9. `span`: también es una etiqueta de texto importante que se utiliza para aplicar estilos a pequeñas secciones de texto o agrupar elementos de texto para aplicarles un estilo común. La etiqueta `<span>` no tiene un significado semántico en sí misma, pero se utiliza en conjunto con CSS para aplicar estilos. No tiene atributos obligatorios, pero se puede utilizar el atributo "*class*" o "*id*" para identificar el elemento y aplicarle estilos específicos con CSS.

Es importante mencionar que hay muchas más etiquetas de texto en HTML5, pero estas son algunas de las más utilizadas.

## Etiquetas de Imagen
Estas etiquetas se utilizan para insertar imágenes en la página web.

1. `img`: Esta etiqueta se utiliza para insertar imágenes en la página web. El atributo `src` se utiliza para especificar la *"URL"* de la imagen que se va a mostrar. Otros atributos importantes incluyen *"alt"* *(texto alternativo que se muestra si la imagen no se puede cargar o si el usuario está usando un lector de pantalla)*, *"width"* y *"height"* *(especifican el ancho y alto de la imagen, respectivamente)*. La etiqueta `<img>` no tiene una etiqueta de cierre, ya que se considera un elemento vacío.

2. `<figure>`: Esta etiqueta se utiliza para agrupar imágenes u otros elementos multimedia junto con su descripción o leyenda. Por lo general, se utiliza junto con la etiqueta `<figcaption>` para agregar una descripción o leyenda a la imagen o elemento multimedia. Los atributos que puede tener la etiqueta `<figure>` son class e id, que se utilizan para aplicar estilos específicos a los elementos en la página web y para identificarlos mediante JavaScript o CSS.




