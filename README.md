# Proyecto-Pagina-Web-Cafeteria

Este es un proyecto de página web para una cafetería que he desarrollado para la asignatura de Lenguaje de Marcas. He elegido hacer una página web para una cafetería porque me encanta el ambiente de las cafeterías y creo que una página web de ello tiene muchas posibilides y me puede servir en un futuro.

## Características
La página web se divide en las siguientes secciones:

Inicio: esta sección incluye una imagen principal y un mensaje de bienvenida para dar la bienvenida a los visitantes de la página web. También incluye un menú de navegación que permite acceder a las diferentes secciones de la página.

Nuestros productos: esta sección muestra los productos disponibles en la cafetería. Los productos se dividen en diferentes categorías (bebidas calientes, bebidas frías, pasteles, etc.) y se muestra una imagen y una descripción breve de cada producto.

Acerca de nosotros: esta sección incluye información sobre la cafetería, como su historia, sus valores y su equipo de trabajo. También incluye fotos del local y del equipo de trabajo para dar a los visitantes una idea de cómo es la cafetería.

Contáctanos: esta sección incluye un formulario para que los visitantes puedan enviar consultas o comentarios a la cafetería. También incluye información de contacto, como la dirección de la cafetería y el número de teléfono.

Ubicación: esta sección muestra la ubicación de la cafetería en un mapa de Google Maps. Los visitantes pueden hacer zoom y moverse por el mapa para ver la ubicación de la cafetería en relación a su ubicación actual.

## Tecnologías
La página web fue desarrollada con las siguientes tecnologías:

HTML: se utilizó HTML para crear la estructura de la página web y definir el contenido de cada sección.

CSS: se utilizó CSS para dar estilo a la página web y hacerla más atractiva visualmente. También se utilizó CSS para hacer que la página web sea responsive y se adapte a diferentes tamaños de pantalla.

## Esquema
### Menu General
~~~
El menú esta dotado de 4 opciones cada una con su CSS particular
<link rel="stylesheet" type="text/css" href="indexstyle.css" title="style" />
~~~
### Formulario
~~~
El formulario es muy completo y tiene un diseño muy cuidado consta de varios inputs obligatorios y de varios tipos explicados:
<div class  ="recuadro-formulario">
            <form method="post">
            <div id="contenedores-contenido">
              <br>
                <label for="name"><b>Nombre de la reserva:</b></label>
                <input type="text" id="name" name="nombre" placeholder="Introduce tu nombre" title="Pon tu nombre aquí" required style="width: 95%;">
    
                <label for="email"><b>Correo electrónico:</b></label>
                <input type="email" id="email" name="correo" placeholder="ejemplo@ejemplo.com" title="Pon tu correo electrónico" required style="width: 95%;">
    
                <label for="telephone"><b>Teléfono:</b></label>
                <input type="tel" id="telephone" name="telefono" placeholder="999 999 999" title="Pon tu numero de contacto" required>
    
                <label for="date"><b>Fecha:</b></label>
                <input type="date" id="date" name="Fecha de reserva">

                <label for="time"><b>Hora:</b></label>
                <input type="time" id="time" name="Hora de reserva">
                
                <label for="personas"><b>Personas:</b></label>
                  <select id="personas" name="personas" title="Selecciona el numero de personas" required>
                  <option value="">0</option>
                  <option value="1">1</option>
                  <option value="2">2</option>
                  <option value="3">3</option>
                  <option value="4">4</option>
                  <option value="5">5</option>
                  <option value="6">6</option>
                  <option value="7">7</option>
                  <option value="8">8</option>
                  <option value="9">9</option>
                  <option value="10">10</option>
                  <option value="11">11</option>
                  <option value="12">12</option>
                  </select>
                <br>
                <br>

                <label for="message"><b>Mensaje (opcional):</b></label>
                <br>
                <textarea id="message" name="Mensaje"></textarea>

                <label for="restaurante"><b>Ubicacion:</b></label>
                <select id="restaurante" name="restaurante" title="Selecciona la cafeteria que prefieras" required>
                    <option value=""><b>Selecciona una cafeteria</b></option>
                    <option value="Palma01">Palma(Plaza España)</option>
                    <option value="Palma02">Palma()</option>
                    <option value="Palma03">Palma()</option>
                    <option value="Manacor01">Manacor()</option>
                    <option value="Inca01">Inca()</option>
                    <option value="Llucmajor01">Llucmajor()</option>
                </select>
            </div>   
                <div id="botones">
                    <input type="reset" value="Limpiar">
                    <input type="submit" value="Enviar">   
                </div>
            </div>
            </form>
</div>
~~~
### Carta 
~~~
Podriamos decir que el apartado de la carta esta hecha como si fuera una tabla:
<div class="recuadro">
  <header>
    <br>
    <img src="cafecarta.png" alt="cartaimg">
    <div class="capa-blanca">
    </div>
    <div id="titulo">
      <h1>Mallorca Coffe Cup</h1>
      
      <p>Nuestro café es excepcional, ¡ven a probarlo!</p>
      <br>
      <br>
    </div>
  </header>

    <table>
    <thead>
      <tr>
        <th>Categoría</th>
        <th>Producto</th>
        <th>Precio</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td></td>
        <td></td>
      </tr>
      <tr>
        <td rowspan="6">Cafés</td>
        <td>Espresso</td>
        <td>€2.50</td>
      </tr>
      <tr>
        <td>Americano</td>
        <td>€3.00</td>
      </tr>
      <tr>
        <td>Café con leche</td>
        <td>€3.50</td>
      </tr>
      <tr>
        <td>Cappuccino</td>
        <td>€4.00</td>
      </tr>
      <tr>
        <td>Latte</td>
        <td>€4.50</td>
      </tr>
      <tr>
        <td>Mocha</td>
        <td>€5.00</td>
      </tr>
      <tr>
        <td></td>
        <td></td>
      </tr>
      <tr>
        <td></td>
        <td></td>
      </tr>
      <tr>
        <td rowspan="4">Tés</td>
        <td>Té negro</td>
        <td>€3.00</td>
      </tr>
      <tr>
        <td>Té verde</td>
        <td>€3.50</td>
      </tr>
      <tr>
        <td>Té de hierbabuena</td>
        <td>€4.00</td>
      </tr>
      <tr>
        <td>Té chai</td>
        <td>€4.00</td>
      </tr>
      <tr>
        <td></td>
        <td></td>
      </tr><tr>
        <td></td>
        <td></td>
      </tr>
      <tr>
        <td rowspan="6">Bebidas Frías</td>
        <td>Refresco</td>
        <td>€2.50</td>
      </tr>
      <tr>
        <td>Zumo de naranja</td>
        <td>€3.00</td>
      </tr>
      <tr>
        <td>Limonada</td>
        <td>€3.50</td>
      </tr>
      <tr>
        <td>Té helado</td>
        <td>€4.00</td>
      </tr>
      <tr>
        <td>Frappuccino</td>
        <td>€4.50</td>
      </tr>
      <tr>
        <td>Batido de chocolate</td>
        <td>€5.00</td>
      </tr>
      <tr>
        <td></td>
        <td></td>
      </tr>
      <tr>
        <td></td>
        <td></td>
      </tr>
      <tr>
        <td rowspan="6">Pastelería</td>
        <td>Croissant</td>
        <td>€2.00</td>
      </tr>
      <tr>
        <td>Muffin de arándanos</td>
        <td>€2.50</td>
      </tr>
      <tr>
        <td>Donut</td>
        <td>€3.00</td>
      </tr>
      <tr>
        <td>Tarta de zanahoria</td>
        <td>€4.00</td>
      </tr>
      <tr>
        <td>Tarta de chocolate</td>
        <td>€4.50</td>
      </tr>
      <tr>
        <td>Cheesecake</td>
        <td>€5.00</td>
      </tr>
    </tbody>
  </table>
~~~
#### Nota
~~~
Por último a destacar el apartado de nuestras localizaciones he implementado un frame de google maps para añadir el mapa original:
<div class="mapas-derecha">
      <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d158077.66290624277!2d2.947938!3d39.600019!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x1297be989d2c9303%3A0x9e747b234fb76cc9!2sPalma%2C%20Balearic%20Islands%2C%20Spain!5e0!3m2!1sen!2sus!4v1679287821101!5m2!1sen!2sus" width="700" height="550" style="border: 0;" allowfullscreen="" loading="lazy"></iframe><hr>
      <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d79340.52726841029!2d2.801767!3d39.721027!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x1296e2079da0bb27%3A0xb56a7dcf1f8d986c!2sInca%2C%20Balearic%20Islands%2C%20Spain!5e0!3m2!1sen!2sus!4v1679288100809!5m2!1sen!2sus" width="700" height="550" style="border:0;" allowfullscreen="" loading="lazy"></iframe><hr>
      <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d158496.78222458196!2d2.825924!3d39.489239!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x12978556e96b7e59%3A0xbfe0e2e65d0477f5!2sLlucmajor%2C%20Balearic%20Islands%2C%20Spain!5e0!3m2!1sen!2sus!4v1679288240872!5m2!1sen!2sus" width="700" height="550" style="border:0;" allowfullscreen="" loading="lazy"></iframe><hr>
      <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d158219.9756413355!2d3.213096!3d39.569601!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x12964b68d7f89957%3A0x406c1a3d94bb7c0!2sManacor%2C%20Balearic%20Islands%2C%20Spain!5e0!3m2!1sen!2sus!4v1679288466447!5m2!1sen!2sus" width="700" height="550" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
    </div>
~~~
