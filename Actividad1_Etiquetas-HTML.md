# Etiquetas HTML básicas

| Etiqueta | ¿Para qué sirve? | Sintaxis | Ejemplo |
|---|---|---|---|
| `<html>` | Marca el inicio y el contenedor general de todo el documento HTML | `<html>...</html>` | `<html><head>...</head><body>...</body></html>` |
| `<head>` | Guarda información sobre la página (título, metadatos, estilos) que no se ve directamente | `<head>...</head>` | `<head><title>Mi web</title></head>` |
| `<title>` | Define el texto que aparece en la pestaña del navegador | `<title>Texto</title>` | `<title>Mi página web</title>` |
| `<body>` | Contiene todo el contenido visible de la página | `<body>...</body>` | `<body><p>Hola mundo</p></body>` |
| `<div>` | Agrupa y estructura elementos en secciones dentro del documento | `<div>...</div>` | `<div class="contenedor">...</div>` |
| `<span>` | Permite aplicar estilo a una parte específica de un texto, sin romper el flujo del párrafo | `<span>...</span>` | `Esta <span style="color:red;">palabra</span> es roja` |
| `<a>` | Crea enlaces hacia otras páginas o recursos | `<a href="url">Texto</a>` | `<a href="https://ejemplo.com" target="_blank">Visítanos</a>` |
| `<img>` | Inserta imágenes en el documento (etiqueta sin cierre) | `<img src="ruta" alt="texto">` | `<img src="foto.jpg" alt="Mi foto">` |
| `<p>` | Agrupa texto en párrafos para hacerlo más legible y organizado | `<p>Texto</p>` | `<p>Este es un párrafo.</p>` |
| `<br>` | Corta el párrafo iniciando una línea nueva, sin dejar espacio extra | `<br>` | `Línea uno<br>Línea dos` |
| `<hr>` | Traza una línea horizontal para separar secciones de contenido | `<hr>` | `<p>Sección 1</p><hr><p>Sección 2</p>` |
| `<blockquote>` | Sangra un párrafo, usado normalmente para citas | `<blockquote>Texto</blockquote>` | `<blockquote>Esto es una cita.</blockquote>` |
| `<strong>` | Da énfasis fuerte (negrita) a una parte del texto | `<strong>Texto</strong>` | `Quiero destacar <strong>esta palabra</strong>` |
| `<b>` | Aplica negrita al texto como formato físico, sin implicar énfasis semántico | `<b>Texto</b>` | `<b>Texto en negrita</b>` |
| `<i>` | Aplica cursiva al texto | `<i>Texto</i>` | `<i>Texto en cursiva</i>` |
| `<u>` | Subraya el texto | `<u>Texto</u>` | `<u>Texto subrayado</u>` |
| `<em>` | Da énfasis al texto (formato lógico, normalmente se muestra en cursiva) | `<em>Texto</em>` | `<em>Texto enfatizado</em>` |
| `<h1>` | Crea el encabezado principal, el de mayor jerarquía | `<h1>Texto</h1>` | `<h1>Mi página web</h1>` |
| `<ul>` | Crea una lista con viñetas (no numerada) | `<ul>...</ul>` | `<ul><li>Elemento</li></ul>` |
| `<ol>` | Crea una lista numerada | `<ol>...</ol>` | `<ol><li>Paso uno</li></ol>` |
| `<li>` | Define cada elemento dentro de una lista `<ul>` u `<ol>` | `<li>Texto</li>` | `<li>Primer elemento</li>` |
| `<table>` | Organiza la información en filas y columnas, y también sirve para maquetar el aspecto de la página | `<table>...</table>` | `<table><tr><td>Dato</td></tr></table>` |
| `<form>` | Crea un formulario para que el usuario envíe datos (contacto, registro, búsqueda) | `<form action="url">...</form>` | `<form action="/enviar"><input type="text"></form>` |
| `<link>` | Vincula el documento HTML con recursos externos, como hojas de estilo CSS | `<link rel="stylesheet" href="ruta">` | `<link rel="stylesheet" href="estilos.css">` |
