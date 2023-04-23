# Estructura de una página

1. [Estructura de una página](#estructura-de-una-página)
2. [Contenedores de elementos](#contenedores-de-elementos) 
3. [Etiquetas de enlaces](#etiquetas-de-enlaces)
4. [Etiquetas de imágenes](#etiquetas-de-imágenes)
5. [Listas](#listas) 
6. [Tablas](#tablas) 
7. [Elementos de citas](#elementos-de-citas)
8. [Formularios](#formularios) 
--- 
## Estructura de una página
La estructura básica de una página web puede variar según la necesidad y el contenido que se quiera presentar.A continuación, te presento una posible estructura para un portafolio que cumpla con las características mensionadas:

- Encabezado: Crea un encabezado que incluya tu nombre o el nombre de tu negocio y un menú de navegación con enlaces a las diferentes secciones de tu portafolio.

- Sección de presentación: Crea una sección que incluya una imagen tuya o de tu negocio y un breve párrafo que presente quién eres y qué haces.

- Sección de habilidades: Crea una sección que muestre tus habilidades y competencias relevantes para tu área de trabajo o negocio. Puedes utilizar una lista o una tabla para organizar esta información.

- Sección de proyectos: Crea una sección que muestre tus proyectos más destacados, con una breve descripción de cada uno y enlaces a los mismos. Puedes utilizar una tabla o una lista para organizar esta información.

- Sección de testimonios: Crea una sección que incluya testimonios o comentarios de clientes satisfechos con tus servicios o productos.

- Sección de contacto: Crea una sección que incluya tus datos de contacto, como tu dirección de correo electrónico y tus redes sociales.

- Pie de página: Crea un pie de página que incluya información adicional, como un enlace a tu currículum o un mensaje de agradecimiento por visitar tu sitio web.

Asegúrate de utilizar las etiquetas de enlaces y las etiquetas de imágenes de forma apropiada, y de estructurar tu página web utilizando la estructura básica que hemos visto anteriormente. Además, asegúrate de utilizar un diseño atractivo y profesional que refleje tu estilo y personalidad.

Recuerda que este es solo un ejemplo de estructura para un portafolio. Puedes ajustarlo a tus necesidades y preferencias personales. ¡Éxito en tu proyecto!

---
## Contenedores de elementos 
En HTML, los contenedores son elementos que se utilizan para agrupar y organizar otros elementos dentro de una página web. Estos elementos se conocen como contenedores porque su función principal es "contener" otros elementos, es decir, proporcionar un área específica en la que se pueden ubicar otros elementos.

- `<div>`: Esta etiqueta es un contenedor genérico que se utiliza para agrupar y estructurar el contenido.

- `<header>`: Este elemento se utiliza para el encabezado de la página, que generalmente incluye el logotipo, el nombre del sitio web y el menú de navegación.

- `<nav>`: Aquí se encuentra el menú de navegación del sitio web, que permite al usuario moverse entre las diferentes páginas o secciones.

- `<main>`: Esta etiqueta se utiliza para el contenido principal de la página, que puede ser un artículo, una lista de productos, una galería de imágenes, entre otros.

- `<aside>`: Este elemento se utiliza para incluir contenido secundario o complementario al contenido principal. Por ejemplo, una barra lateral que muestra artículos relacionados o publicidad.

- `<section>`: Esta etiqueta se utiliza para dividir el contenido principal en secciones diferentes y definidas. Por ejemplo, una página de un producto puede tener una sección para la descripción del producto, otra para las especificaciones y otra para los comentarios de los usuarios.

- `<article>`: Esta etiqueta se utiliza para definir un contenido independiente que puede ser reutilizado en otros sitios. Por ejemplo, un artículo de noticias o un post de blog.

- `<footer>`: Este elemento se utiliza para el pie de página de la página web, que puede incluir información de contacto, enlaces a redes sociales, copyright, entre otros.

Ejemplo: 
~~~html

~~~

Es importante destacar que no es necesario utilizar todas las etiquetas en una página web, y que la estructura puede variar según las necesidades y el contenido que se quiera presentar.

Hay muchos otros elementos de contenedor en HTML, pero estos son algunos de los más comunes. Utilizar los elementos de contenedor adecuados puede ayudarte a organizar tu código y hacer que sea más fácil de mantener y actualizar en el futuro.


---
## Etiquetas de enlaces
Las etiquetas de enlaces en HTML se utilizan para crear hipervínculos en una página web. La etiqueta principal es la etiqueta <a>, que significa "ancla". Esta etiqueta se utiliza junto con el atributo "href" para especificar la dirección web a la que debe dirigirse el enlace. Por ejemplo:

~~~html
<a href="https://www.google.com">Ir a Google</a>
~~~

Esta etiqueta de enlace se mostrará como "Este es un enlace" en la página web, y cuando se hace clic en él, el navegador dirigirá al usuario a la dirección especificada en el atributo "href". También es posible agregar otros atributos a la etiqueta de enlace para especificar cómo se debe mostrar el enlace, como "target" para especificar si se debe abrir en una nueva pestaña o ventana del navegador.

Además, también se pueden utilizar etiquetas secundarias dentro de la etiqueta `<a>` para agregar más información al enlace, como la etiqueta `<img>` para agregar una imagen como enlace, o la etiqueta `<span>` para agregar texto adicional al enlace. Por ejemplo:

~~~html
<a href="https://www.ejemplo.com">
    <img src="imagen.jpg" alt="Texto alternativo">
    <span>Este es un enlace con imagen</span>
</a>
~~~

En este ejemplo, el enlace incluye una imagen y un texto adicional que se mostrará junto a ella. El atributo "alt" en la etiqueta `<img>` se utiliza para proporcionar un texto alternativo que se mostrará si la imagen no se carga correctamente o si el usuario utiliza un lector de pantalla para navegar por la página.

Ejemplo de encabezado con menú de navegación:

~~~html
    <header>
        <div>
            <h2>ALEXROEL</h2>
        </div>
        <nav>
            <a href="index.html">Inicio</a>
            <a href="https://www.google.com/" title="Página de Google" target="_blank">Ir a Google</a>
            <a href="other.html">Otra Página</a>
            <a href="#hola">Hola mundo con HTML</a>
        </nav>
    </header>
~~~


---
## Etiquetas de imágenes
En HTML, se pueden usar las siguientes etiquetas para incluir imágenes:

- `<img>`: Esta etiqueta se utiliza para insertar una imagen en la página web. Puede tener los siguientes atributos:
- `src`: Especifica la ubicación de la imagen. Puede ser una URL o una ruta de archivo local.
- `alt`: Especifica un texto alternativo que se muestra si la imagen no se puede cargar o si el usuario utiliza un lector de pantalla.
- `width` y `height`: Especifican el ancho y la altura de la imagen en píxeles.
- `title`: Especifica un texto que se muestra cuando el usuario pasa el cursor sobre la imagen.
- `<figure>` y `<figcaption>`: Estas etiquetas se utilizan para agrupar una imagen y su título o leyenda.
- `<figure>`: Envuelve la imagen y su título o leyenda.
- `<figcaption>`: Especifica el título o la leyenda de la imagen.
Ejemplo:

~~~html
<figure>
  <img src="https://loremflickr.com/320/240" alt="Descripción de la imagen">
  <figcaption>Título o leyenda de la imagen</figcaption>
</figure>
~~~

Estrucutura de Inicio:

~~~html
    <!-- Sección de bienvenida-->
        <section>
            <h1>Bienvenidos a mi página</h1>

            <p>
                Mi nombre es Alex Roel y en este blog
                podrás encontrar todo tipo de contenido.
                Desde tutoriales sobre programación,
                hasta artículos de opinión sobre
                temas de actualidad.
            </p>

            <img src="img/alexroel.png" alt="Foto de alex roel" width="300" title="Foto de Alex Roel">
        </section>
~~~

---
## Listas 

En HTML, las listas se pueden crear usando tres tipos de etiquetas: `<ul>`, `<ol>` y `<dl>`.

La etiqueta `<ul>` se utiliza para crear una lista no ordenada, es decir, una lista en la que los elementos no tienen una numeración o un orden específico. Esta etiqueta debe contener una o varias etiquetas `<li>`, que indican cada uno de los elementos de la lista. Por ejemplo:

~~~html
<ul>
  <li>Elemento 1</li>
  <li>Elemento 2</li>
  <li>Elemento 3</li>
</ul>
~~~

La etiqueta `<ol>` se utiliza para crear una lista ordenada, es decir, una lista en la que los elementos tienen una numeración o un orden específico. Esta etiqueta también debe contener una o varias etiquetas `<li>`. Por ejemplo:

~~~html
<ol>
  <li>Primer elemento</li>
  <li>Segundo elemento</li>
  <li>Tercer elemento</li>
</ol>
~~~

La etiqueta `<dl>` se utiliza para crear una lista de definiciones, es decir, una lista en la que cada elemento consta de una palabra o término y su definición. Cada elemento de la lista se crea con las etiquetas `<dt>` y `<dd>`. La etiqueta `<dt>` se utiliza para la palabra o término, mientras que la etiqueta `<dd>` se utiliza para la definición correspondiente. Por ejemplo:

~~~html
<dl>
  <dt>Café</dt>
  <dd>- bebida caliente negra</dd>
  <dt>Leche</dt>
  <dd>- bebida fría blanca</dd>
</dl>
~~~

---
## Tablas
En HTML, se pueden crear tablas para mostrar información tabular utilizando la etiqueta `<table>`. Dentro de esta etiqueta se pueden colocar etiquetas `<tr>` para cada fila y `<td>` para cada celda en la fila.

A continuación, se presenta un ejemplo básico de cómo crear una tabla con dos filas y dos columnas:

~~~html
    <section id="proyectos">
        <h2>Proyectos</h2>
        <!--  Esta etiqueta define una tabla, que se utiliza para mostrar datos en filas y columnas. -->
        <table>

            <!-- <tr>: Esta etiqueta define una fila en una tabla.-->
            <tr>
                <!-- <th>: Esta etiqueta define una celda de encabezado en una tabla.-->
                <th>Proyecto</th>
                <th>Descripción</th>
            </tr>
            <tr>
                <!-- <td>: Esta etiqueta define una celda en una tabla. -->
                <td>Nombre del Proyecto 1</td>
                <td>Breve descripción del proyecto 1</td>
            </tr>
            <tr>
                <td>Nombre del Proyecto 2</td>
                <td>Breve descripción del proyecto 2</td>
            </tr>
            <tr>
                <td>Nombre del Proyecto 3</td>
                <td>Breve descripción del proyecto 3</td>
            </tr>
        </table>
    </section>
~~~
---
## Elementos de citas
En HTML, los elementos de citas se utilizan para agregar citas o referencias a otros trabajos dentro del contenido de una página web. Hay dos elementos de citas principales: `<blockquote>` y `<cite>`.

- `<blockquote>`: Este elemento se utiliza para citas largas, que suelen tener varias líneas de texto. Puede incluir cualquier tipo de contenido, incluidos otros elementos HTML, como encabezados, párrafos y listas. Se recomienda que se utilice el atributo cite para agregar la fuente de la cita.

- `<cite>`: Este elemento se utiliza para indicar la fuente de una cita o referencia. Por lo general, se usa dentro de un elemento de citas como `<blockquote>` o `<q>`. Sin embargo, también se puede utilizar para agregar la fuente de una obra, como un libro o un artículo, cuando se menciona en el contenido de la página web.

~~~html
    <!-- <article id="testimonios"> define una sección para testimonios. -->
    <article id="testimonios">
        <h2>Testimonios</h2>
        <!-- <blockquote>: Esta etiqueta define una cita o testimonio, que se utiliza para destacar opiniones de clientes o usuarios. -->
        <blockquote>
            <p>"Cita o testimonio de un cliente satisfecho con tus servicios o productos."</p>
            <!-- <cite>: Esta etiqueta define el autor de una cita o testimonio. -->
            <cite>Nombre del cliente</cite>
        </blockquote>

        <blockquote>
            <p>"Cita o testimonio de otro cliente satisfecho con tus servicios o productos."</p>
            <cite>Nombre del cliente</cite>
        </blockquote>
    </article>
~~~

---
## Formularios 
Los formularios en HTML se utilizan para recopilar información del usuario, como nombres, correos electrónicos, contraseñas y otros tipos de datos. Los elementos que se utilizan en los formularios son los siguientes:

- `<form>`: este es el elemento principal que se utiliza para crear un formulario. Contiene todos los elementos que se utilizan en el formulario y se puede configurar para enviar los datos del formulario a una página de destino.
- `<input>`: este elemento se utiliza para crear campos de entrada de datos, como campos de texto, botones de opción, botones de radio, casillas de verificación, botones de envío y otros tipos de entradas.
- `<label>`: este elemento se utiliza para etiquetar un elemento de entrada y proporcionar una descripción de lo que se espera que el usuario ingrese en ese campo.
- `<select>`: este elemento se utiliza para crear una lista desplegable de opciones donde el usuario puede seleccionar una opción.
- `<option>`: este elemento se utiliza para crear opciones en una lista desplegable.
- `<textarea>`: este elemento se utiliza para crear un campo de entrada de texto grande que permite al usuario ingresar varias líneas de texto.
- `<button>`: este elemento se utiliza para crear un botón que el usuario puede hacer clic para enviar el formulario o realizar una acción específica.

~~~html
    <section id="contacto">
        <h2>Contacto</h2>
        <p>Puedes contactarme a través de este formulario:</p>
        <!-- <form>: Esta etiqueta define un formulario, que se utiliza para recopilar información de los usuarios. -->
        <form action="">
            <!-- <label>: Esta etiqueta define una etiqueta de texto para un elemento de formulario. -->
            <label for="nombre">Nombre:</label>
            <input type="text" id="nombre" name="nombre" required>
            <br>
            <label for="correo">Correo electrónico:</label>
            <input type="email" id="correo" name="correo" required>
            <br>
            <label for="mensaje">Mensaje:</label>
            <!-- <textarea> crea un área de texto donde se puede escribir -->
            <textarea id="mensaje" name="mensaje" required></textarea>
            <br>
            <button type="submit">Enviar mensaje</button>
        </form>
    </section>
~~~



