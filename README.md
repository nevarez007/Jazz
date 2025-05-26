<html lang="es">
<head>
  <meta charset="UTF-8">
  <link rel="stylesheet" href="css/estilos.css">
</head>
<body>
  <header>
    <h1>Clase de Jazz</h1>
    <nav>
      <a href="index.html">Inicio</a>
      <a href="clases.html">Clases</a>
      <a href="estilos.html">Estilos</a>
      <a href="contacto.html">Contacto</a>
      <a href="https://es.wikipedia.org/wiki/Danza_jazz" target="_blank">¿Qué es el Jazz?</a>
    </nav>
  </header>

  <main>
    <section>
      <h2>¿Qué es el Jazz?</h2>
      <p>El jazz es un estilo de danza lleno de energía, que mezcla técnica con libertad creativa. Su origen está vinculado a la música jazz, pero hoy en día incorpora movimientos modernos, urbanos y teatrales. Es ideal para mejorar coordinación, expresión y ritmo.</p>
      <img src="media/jazz.jpg" alt="Clase de Jazz" width="400">
    </section>

    <section>
      <h2>Horarios y Precios</h2>
      <table>
        <tr>
          <th>Día</th>
          <th>Horario</th>
          <th>Nivel</th>
          <th>Precio mensual</th>
        </tr>
        <tr>
          <td>Lunes y Miércoles</td>
          <td>5:00 PM - 6:00 PM</td>
          <td>Principiantes</td>
          <td>$320</td>
        </tr>
        <tr>
          <td>Martes y Jueves</td>
          <td>6:00 PM - 7:30 PM</td>
          <td>Intermedios</td>
          <td>$370</td>
        </tr>
      </table>
    </section>

    <section>
      <h2>Inscríbete a Jazz</h2>
      <form>
        <label>Nombre completo: <input type="text" name="nombre"></label><br>
        <label>Edad: <input type="number" name="edad"></label><br>
        <label>Email: <input type="email" name="email"></label><br>
        <label>Selecciona tu nivel:
          <select>
            <option>Principiantes</option>
            <option>Intermedios</option>
          </select>
        </label><br>
        <input type="submit" value="Inscribirme">
      </form>
    </section>

    <section>
      <h2>Video de clase</h2>
      <video src="media/jazz-video.mp4" width="400" controls></video>
    </section>

    <section>
      <h2>Música típica del Jazz</h2>
      <audio src="media/jazz-musica.mp3" controls></audio>
    </section>
  </main>

  <footer>
    <marquee>¡Exprésate con ritmo y energía en nuestras clases de Jazz!</marquee>
    <p>&copy; 2025 Academia Estrella</p>
  </footer>
</body>
</html>
