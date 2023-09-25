<!-- No borrar o modificar -->
[Inicio](./index.md)

## sesion 2


<!-- Su documentación aquí -->
# Actividad: Creando mi primer sitio web
Crea un sitio web compuesto por 3 páginas HTML utilizando la estructura y los elementos que has aprendido. Personaliza el sitio y utiliza diferentes etiquetas HTML.

Las páginas del sitio serán:

Index o página de inicio
Acerca
Contacto

# solucion:

```html

<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PROGRAMACIÓN</title>
</head>
<body>
    <header> 

<h1>Aprende y desrrolla tu aprendizaje</h1>

    </header>

<nav>

<a href="about.html">ACERCA</a>
<a href="contact.html">contacto</a>

</nav>
<main>

<p>Bienvenidos a mi primer sitio web sobre programación</p>
<p> te brindaremos información para aprender programación ¿te unes en esta aventura? </p>

</main>

<footer>
<p>copyright 2023 - Yojan Gil</p>
<p>yojan.david.gil.posada@gmail.com</p>

</footer>

   
   
</body>
</html>

```

## contact:

```html

<!DOCTYPE html>

<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contacto</title>
</head>
<body>
    
<header>

<h1>Contacto</h1>

</header>

<nav>

<a href="index.html">Inicio</a>
<a href="about.html">Acerca</a>

</nav>

<main>

<form>

<label for="nombre">Nombre</label>
<input type="text" id="nombre"><br>

<label for="email">Email</label>
<input type="email" id="email"><br>

<label for="mensaje">Mensaje</label><br>
<textarea id="mensaje"></textarea><br>

<input type="submit" value="Enviar">

</form>

<aside>

<h3>ubicación</h3>
<p>calle 111</p>

</aside>

</main>

<footer>
<p>copyright 2023 - Yojan Gil</p>
</footer>

</body>

</html>

```

## about

```html

<!DOCTYPE html>
<html>

<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Estudia y aprende.

 </title>

</head>

<body>

  <header>
<h1>Somos una empresa que ofrece programas gratuitos para aprender a programar y desarrollar tus habilidades.
 </h1>
</header>

 <nav>
 <a href="index.html">Inicio</a>
 <a href="contact.html">Contacto</a>
  </nav>

    <section>

   <h2> Somos una comunidad de programadores que decidio llevar a cabo una pagina web, mediante esta pagina
  brindamos programas de educación para todo tipo de personas según su nivel de aprendizaje: Basico,
   intermedio o avanzado, Con esto logramos compartir nuestros conocimientos de una forma bastante adsequible
    ya que es totalmente virtual.</h2>

 <p>Fundada en 2010...</p>

<article>

<h3>Mision y Visión</h3>

  <p>
    
Misión: Ser un elemento esencial a la hora de brindar programas y servicios, con el fin de ayudarlos a
lograr sus aspiraciones, ofrecer varios programas de acuerdo a lo que el publico desee estudiar y que
este sea el mejor.

visión: Mejorar las oportunidades a la hora de conseguir trabajo e iniciar un emprendimiento y ofrecer
 la mejor experiencia de cursos virtuales por medio de nuestra plataforma.

</p>

 </article>

 </section>
          
 <footer> 

<p>copyright 2023- Yojan Gil</p>

</footer>


</body>

</html>
```











