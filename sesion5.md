<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 5 


<!-- Su documentación aquí -->

# Actividad: Diseñar un formulario de pedido de un producto
Objetivo:

Aplicar los conocimientos sobre los tipos de etiquetas HTML para diseñar un formulario de pedido de un producto.

Instrucciones:

Crear un nuevo documento HTML.
Crear un formulario con los siguientes campos:
Nombre del producto
Cantidad
Precio unitario
Precio total
Dirección de envío
Información de contacto (nombre, correo electrónico, número de teléfono)
Agregar los siguientes campos relacionados al formulario:
Método de pago
Fecha de entrega
Comentarios
Utilizar las etiquetas HTML apropiados para cada campo.

# solucion:

```html

<!DOCTYPE html>
<html lang="en">

<head>
<meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Document</title>
</head>

<body>
<h1><span style="color: rgb(12, 12, 12);">Formulario.</span></p>
</h1>


<form>

<div>

 <label for="idnombredelproducto">Nombre del producto:</label>
 <input type="text" name="nombre" placeholder="Nombre del producto" id="idnombredelproducto">

</div>
<br>

<div>

<label for="idcantidad">Cantidad:</label>
<input type="number" name="Cantidad" placeholder="Cantidad" id="idcantidad">

 </div>

<br>

<div>

<label for="idpreciounitario">Precio unitario:</label>
<input type="number" name="Precio unitario" placeholder="Precio unitario" id="idpreciounitario">

</div>

<br>

<div>

<label for="idpreciototal">Precio total:</label>
<input type="number" name="Precio total" placeholder="Precio total" id="idpreciototal">


</div>

<br>

<div>

<label for="iddirecciondeenvio">Dirección de envio:</label>
<input type="text" name="nombre" placeholder="Dirección de envio" required id="iddirecciondeenvio">

</div>

<br>

<div>

<h4><span style="color: rgb(10, 10, 10);">informacion de contacto:</span></p>
</h4>

<label for="idnombre">Nombre:</label>
<input type="text" name="nombre" placeholder="Nombre" id="idnombre">

</div>
<br>

<div>

<label for="idcorreoelectronico">Correo electronico:</label>
<input type="text" name="correo electronico" placeholder="Correo electronico" id="idcorreoelectronico">



</div>

<br>

<div>

<label for="idnumerodetelefono">Núero de telefono:</label>
<input type="text" name="número de telefono" placeholder="Núero de telefono" id="idnumerodetelefono">


</div>

<br>

<div>

<h4>Metodo de pago:</h4>

<select name="Pago" id="pago">

<option value="Tarjeta de credito">Tarjeta de credito</option>
<option value="Efectivo">Efectivo</option>
<option value="Nequi">Nequi</option>

 </select>

</div>

<br>

<div>

<input type="date" name="fecha" id="fecha">
<label for="fecha">Fecha de entrega</label>

</div>

<br>

<div>

 <textarea name="comentarios" id="comentarios" placeholder="Ingrese sus comentarios aquí" rows="10" cols="50"></textarea>




</div>

<input type="submit" value="enviar">

 </form>


</body>

</html>
```




