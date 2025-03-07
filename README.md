 # Proyecto de Número Aleatorio con HTML, CSS y JavaScript

Este es un proyecto simple creado utilizando **HTML**, **CSS** y **JavaScript** en un solo archivo. El objetivo principal del proyecto es mostrar un número aleatorio entre 1 y 20 cada vez que se hace clic en un botón. A continuación, se detallan los componentes clave de este proyecto:

## Contenido del Archivo HTML
El archivo HTML tiene una estructura básica con tres secciones principales: el encabezado (`<head>`) y el cuerpo (`<body>`). Dentro del `<head>`, se incluyen elementos como la etiqueta `meta` para el charset, el título de la página y un enlace a una hoja de estilos CSS. En el `<body>`, hay un contenedor centralizado con un título (`<h1>`), un botón (`<button>`) que activa la función de generar números aleatorios, y un elemento para mostrar el resultado (`<p>`).

## Estilos CSS
El archivo CSS incluido en este proyecto proporciona estilos básicos para centrar el contenido de la página, dar formato al texto y agregar una sombra a la caja que contiene el botón y el número aleatorio. Esto mejora la apariencia visual de la aplicación.

## JavaScript
La funcionalidad principal del proyecto está implementada en un script JavaScript ubicado dentro de las etiquetas `<script>`. La función `mostrarNumero()` genera un número aleatorio entre 1 y 20 utilizando `Math.random()` y actualiza el contenido del elemento `<p>` con id "numeroAleatorio" para mostrar el número generado.
