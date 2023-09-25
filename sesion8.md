<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 8 
# Actividad: Aplicando estilos con selectores CSS
El objetivo de esta actividad es crear la estructura HTML básica de una página web y aplicar diferentes selectores CSS para modificar su presentación.

Pasos:

Crea el esqueleto de una página web simple con la siguiente estructura:

Encabezado <header>
Tres párrafos <p>
Una imagen <img>
Un pie de página <footer>
Aplica los siguientes estilos usando selectores de etiqueta:

Color rojo a los encabezados <h1>
Color azul a los párrafos <p>
Borde grueso negro a la imagen <img>
Aplica los siguientes estilos usando seleccionadores de clase:

Color verde a los elementos con la clase ".destacado"
Tamaño de fuente grande a los elementos con la clase ".grande"
Aplica los siguientes estilos usando seleccionadores de ID:

Color amarillo al elemento con ID "#principal"
Sombra al elemento con ID "#sombras"
Aplica los siguientes estilos usando seleccionadores descendientes:

Color gris a los párrafos dentro de un <div>
Centrar el contenido de la sección <section>


# Solucion: 

```html 
<!DOCTYPE html>
 <html lang="en">

 <head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

 <title>Document</title>

 <style>

  h1{  
 color: red;
 
 }
 
 p{
  color: blue;
 }
 
 img {
 border:  2px solid #000;
 
 }
 
 .destacado {
 color:green;
 
 }
 
 .grande {
 font-size: 24px;
 }
 
 
 #principal {
   color: yellow; 
 }
 
 #sombras {
   box-shadow:  2px 2px 4px rgba(0, 0, 0, 0.2), 0 0 0 2px rgba(255, 0, 0, 0.5); 
 }
 
 div p {
   color: gray;
 
 }
 
 section {
   text-align: center;
 
 }
 
 
 </style>

 </head>

 <body>

<header>
   <h1> Encabezado</h1>
</header>

<section>
<p>Parrafo 1</p>

<p>parrafo 2</p>

<p>parrafo 3</p>

<img src="https://4.bp.blogspot.com/-BNvg2u6anPs/VDWKW3YQZHI/AAAAAAACVEQ/zHhj3DY8egk/s1600/paisajes%2Bnaturales%2Bfotos%2Bnuevas.jpg" width="500"
alt="Imagen">

</section>

<footer>
  <p>Pie de pagina</p>
</footer>


 </body>

 </html>
```
 






