# Venta-de-Autos
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Nova Cars</title>
  <meta name="description" content="Nova Cars - Autos eléctricos de última generación. Explora nuestros modelos innovadores.">
  <meta name="keywords" content="autos eléctricos, Nova Cars, innovación, tecnología">
  <meta name="author" content="Nova Cars">
  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background-color: #fff;
      color: #111;
    }

    header {
      background: linear-gradient(to bottom, #c80000, #8b0000);
      color: #fff;
      padding: 20px;
    }

    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
    }

    .logo-container {
      display: flex;
      align-items: center;
      gap: 10px;
    }

    .logo-img {
      height: 40px;
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 20px;
      margin: 0;
      padding: 0;
    }

    nav ul li a {
      color: #fff200;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }

    nav ul li a:hover {
      color: #ffd700;
    }

    .hero {
      text-align: left;
      padding: 50px 20px;
    }

    .hero h1 {
      font-size: 3rem;
      margin: 0;
      color: #fff200;
      text-shadow: 2px 2px #000;
    }

    .hero p {
      font-size: 1.2rem;
      margin: 10px 0 30px;
      color: white;
    }

    .hero button {
      background-color: #ffd700;
      color: #8b0000;
      border: none;
      padding: 10px 20px;
      border-radius: 20px;
      cursor: pointer;
      font-size: 1rem;
      font-weight: bold;
      transition: background-color 0.3s ease;
    }

    .hero button:hover {
      background-color: #fff200;
    }

    .hero video {
      width: 100%;
      max-height: 400px;
      object-fit: cover;
      border-radius: 10px;
      margin-top: 20px;
      border: 5px solid #fff200;
    }

    section {
      padding: 40px 20px;
    }

    .modelos h2,
    .tecnologia h2,
    .galeria h2,
    .contacto h2 {
      font-size: 2.5rem;
      margin-bottom: 20px;
      color: #c80000;
    }

    .modelos-grid,
    .galeria-grid {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
    }

    .modelo,
    .galeria-item {
      flex: 1 1 45%;
      background-color: #ffeaea;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(200, 0, 0, 0.2);
    }

    .modelo img,
    .galeria-item img {
      width: 100%;
      border-radius: 10px;
      border: 3px solid #c80000;
    }

    .modelo h3 {
      margin-top: 10px;
      font-size: 1.5rem;
      color: #8b0000;
    }

    .tecnologia p,
    .contacto p {
      font-size: 1.1rem;
      max-width: 800px;
    }

    .contacto button {
      background-color: #ffd700;
      color: #8b0000;
      border: none;
      padding: 10px 20px;
      border-radius: 20px;
      cursor: pointer;
      font-size: 1rem;
      font-weight: bold;
      margin-top: 20px;
      transition: background-color 0.3s ease;
    }

    .contacto button:hover {
      background-color: #fff200;
    }

    footer {
      background-color: #8b0000;
      color: white;
      text-align: center;
      padding: 20px;
    }

    @media (max-width: 768px) {
      nav {
        flex-direction: column;
        align-items: flex-start;
        gap: 10px;
      }

      .modelos-grid,
      .galeria-grid {
        flex-direction: column;
      }

      .modelo,
      .galeria-item {
        flex: 1 1 100%;
      }

      .hero {
        padding: 30px 10px;
      }

      .hero h1 {
        font-size: 2rem;
      }

      .hero video {
        max-height: 250px;
      }
    }
  </style>
</head>
<body>
  <header>
    <nav>
      <div class="logo-container">
        <img src="Nova Cars.png"Logo Nova Cars" class="logo-img" />
        <strong>Nova Cars</strong>
      </div>
      <ul>
        <li><a href="#modelos">Modelos</a></li>
        <li><a href="#tecnologia">Tecnología</a></li>
        <li><a href="#galeria">Galería</a></li>
        <li><a href="#contacto">Contacto</a></li>
      </ul>
    </nav>
    <div class="hero">
      <h1>Innovación<br>sobre ruedas</h1>
      <p>Descubre el futuro de los autos eléctricos con Nova Cars.</p>
      <button onclick="document.querySelector('#modelos').scrollIntoView({ behavior: 'smooth' });">Explorar Modelos</button>
      <video autoplay loop muted>
        <source src="soy ... veloz !!!.wmv.mp4" type="video/mp4">
        Tu navegador no soporta la etiqueta de video.
      </video>
      <audio controls autoplay loop>
        <source src="soy ... veloz !!!.wmv.mp4" type="audio/mp3">
      </audio>
    </div>
  </header>

  <main>
    <section class="modelos" id="modelos">
      <h2>Modelos Destacados</h2>
      <div class="modelos-grid">
        <div class="modelo">
          <img src="https://motor.elpais.com/wp-content/uploads/2016/11/Renault-Trezor-1.jpg" alt="Auto Modelo 1">
          <h3>Modelo X</h3>
          <p>El auto del futuro, disponible ahora.</p>
        </div>
        <div class="modelo">
          <img src="https://cidef.cl/wp-content/uploads/2023/09/aeolus-y3-03.jpg" alt="Auto Modelo 2">
          <h3>Modelo Z</h3>
          <p>Diseñado para la velocidad y eficiencia.</p>
        </div>
      </div>
    </section>

    <section class="tecnologia" id="tecnologia">
      <h2>Tecnología Avanzada</h2> 
      <p>Los autos eléctricos no solo se benefician del uso de fuentes de energía más limpias, sino que también incorporan tecnologías avanzadas en términos de eficiencia energética, autonomía y diseño. Además, muchas de estas soluciones están complementadas por sistemas de recarga rápida y el impulso de energías renovables, como la solar y la eólica, lo que incrementa su sostenibilidad. De esta manera, los vehículos eléctricos representan una parte crucial de la transición hacia un futuro más verde y sostenible, al reducir la dependencia de recursos no renovables y promover un entorno más saludable para las futuras generaciones.
      </p>
      <p>Con tecnología de punta, los autos Nova Cars están preparados para un rendimiento sin igual.</p>
    </section>

    <section class="galeria" id="galeria">
      <h2>Galería</h2>
      <div class="galeria-grid">
        <div class="galeria-item">
          <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/62/Nissan_GT-R_T-spec_MY2024%2C_front%2C_2023.jpg/250px-Nissan_GT-R_T-spec_MY2024%2C_front%2C_2023.jpg" alt="Galería 1">
        </div>
        <div class="galeria-item">
          <img src="https://carwow-es-wp-2.imgix.net/Koenigsegg-Jesko_Absolut-2021-1280-02.jpg?auto=format&cs=tinysrgb&fit=crop&h=&ixlib=rb-1.1.0&q=60&w=1600" alt="Galería 2">
        </div>
        <div class="galeria-item">
          <img src="https://e00-expansion.uecdn.es/assets/multimedia/imagenes/2022/05/30/16539089934470.jpg" alt="Galería 3">
        </div>
      </div>
    </section>

    <section class="contacto" id="contacto">
      <h2>Contacto</h2>
      <p>¿Interesado en saber más? Contáctanos para una prueba de manejo.</p>
      <button onclick="window.location.href='mailto:contacto@novacars.com';">Enviar Correo</button>
    </section>
  </main>

  <footer>
    <p>© 2025 Nova Cars. Todos los derechos reservados.</p>
  </footer>
</body>
</html>

  </footer>
</body>
</html>
