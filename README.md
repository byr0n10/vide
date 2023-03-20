#  <!DOCTYPE html>
<html lang="es">
  <head>
    <title>AppDeGatos</title>
    <link href="style.css" rel="stylesheet">
  </head>
  <body bgcolor="#005faa">
    <center><h1>AppDeGatos</h1></center>
    <main>
      <h3>Imágenes de Gatos:</h3>
      <!-- TODO: Agregar enlace a imágenes de gatos -->
      <p>Haz click aquí para ver más <a href="https://unsplash.com/es/images/animals/kitten" target="_blank" rel="noopener noreferrer">imágenes de gatos.</a></p>

      <a href="#" target="_blank" rel="noopener noreferrer"><img src="https://bit.ly/fcc-relaxing-cat" alt="Un lindo gato naranja recostado sobre su espalda."></a>

      <hr color="#005faa">

      <h3>Listas de Gatos</h3>

      <div>
        <p>Cosas que los gatos <em>aman</em>:</p>
        <ul>
          <li>Menta gatuna</li>
          <li>Apuntadores Láser</li>
          <li><s>Lasaña</s></li>
        </ul>
        <img src="https://images.pexels.com/photos/4079520/pexels-photo-4079520.jpeg?auto=compress&cs=tinysrgb&w=600" width="300" height="200" alt="Lasaña">

        <p>Cosas que los gatos <strong>odian</strong>:</p>
        <ol>
          <li>Tratamientos antipulgas</li>
          <li>Truenos</li>
          <li>Otros gatos</li>
        </ol>
      </div>
      <img src="https://images.pexels.com/photos/45201/kitty-cat-kitten-pet-45201.jpeg?auto=compress&cs=tinysrgb&w=600" alt="Gatos">

      <form action="/enviar-respuesta">
        <!-- Botones de Radio -->
        <label for="interior">
          <input id="interior" type="radio" value="interior" name="interior-exterior">Interior
        </label>
        <br>
        <label for="exterior">
          <input id="exterior" type="radio" value="exterior" name="interior-exterior">Exterior
        </label>
        <br>

        <h2>Ingrese su nombre</h2>
        <input type="text" placeholder="Ingrese su nombre"></label>
        <h2>Ingrese su apellido</h2>
        <input type="text" placeholder="Ingrese su apellido"></label>
        <h2>Ingrese el nombre de su gato</h2>
        <input type="text" placeholder="Ingrese el nombre de su gato" required><br>
        <form action="/uno/juan.txt">
          <h3>¿Cómo suele ser su gato?</h3>
          <input type="checkbox">Amoroso
          <input type="checkbox">Peresoso
          <input type="checkbox">Enérgico
        <br>
        <input type="text" placeholder="URL de la foto de su gato" required><br>
        <button type="submit">Enviar</button>
        <button type="reset">Limpiar</button>
      </form>
    </main>
    <br>
    <footer>
      <p><small>Sin Derechos de Autor - <a href="https://www.freecodecamp.org/espanol/">freeCodeCamp.org</a></small></p>
    </footer>
  </body>
</html>
