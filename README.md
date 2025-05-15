# XAZ
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>XAZ - Todo lo que necesitas</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      line-height: 1.6;
      background-color: #f7f7f7;
      color: #333;
    }

    header {
      background: #111;
      color: #fff;
      padding: 1rem 2rem;
      text-align: center;
    }

    header h1 {
      font-size: 2.5rem;
      margin-bottom: 0.3rem;
    }

    header p {
      font-size: 1.2rem;
      color: #ccc;
    }

    .hero {
      background: url('https://source.unsplash.com/1600x600/?shopping,products') no-repeat center center/cover;
      height: 60vh;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-shadow: 2px 2px 6px rgba(0, 0, 0, 0.7);
      text-align: center;
      padding: 0 2rem;
    }

    .hero h2 {
      font-size: 3rem;
      max-width: 800px;
    }

    .section {
      padding: 2rem;
      text-align: center;
    }

    .section h3 {
      font-size: 2rem;
      margin-bottom: 1rem;
    }

    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1.5rem;
      margin-top: 1rem;
    }

    .product {
      background: #fff;
      padding: 1rem;
      border-radius: 8px;
      box-shadow: 0 0 8px rgba(0,0,0,0.1);
    }

    .product img {
      width: 100%;
      border-radius: 5px;
      margin-bottom: 0.5rem;
    }

    .product h4 {
      font-size: 1.2rem;
      margin-bottom: 0.5rem;
    }

    .product p {
      color: #666;
      font-size: 0.95rem;
    }

    .footer {
      background: #111;
      color: #aaa;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }

    @media (max-width: 600px) {
      .hero h2 {
        font-size: 2rem;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>XAZ</h1>
    <p>¡Todo para todos, en un solo lugar!</p>
  </header>

  <div class="hero">
    <h2>Descubre miles de productos para tu día a día</h2>
  </div>

  <section class="section">
    <h3>Productos Destacados</h3>
    <div class="products">
      <div class="product">
        <img src="https://source.unsplash.com/400x300/?tech" alt="Producto 1">
        <h4>Electrónica</h4>
        <p>Celulares, audífonos, laptops y más tecnología al mejor precio.</p>
      </div>
      <div class="product">
        <img src="https://source.unsplash.com/400x300/?fashion" alt="Producto 2">
        <h4>Moda</h4>
        <p>Ropa, zapatillas y accesorios para todos los estilos.</p>
      </div>
      <div class="product">
        <img src="https://source.unsplash.com/400x300/?home" alt="Producto 3">
        <h4>Hogar</h4>
        <p>Muebles, cocina, decoración y todo para tu casa.</p>
      </div>
      <div class="product">
        <img src="https://source.unsplash.com/400x300/?toys" alt="Producto 4">
        <h4>Juguetes</h4>
        <p>Para niños, niñas y coleccionistas. Diversión garantizada.</p>
      </div>
    </div>
  </section>

  <footer class="footer">
    &copy; 2025 XAZ. Todos los derechos reservados.
  </footer>

</body>
</html>
