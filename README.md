<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nuvella Moda</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            font-family: 'Poppins', sans-serif;
            background-color: #fff;
            color: #333;
        }

        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 50px;
            background-color: #f6e6ff;
        }

        header .logo {
            font-size: 24px;
            font-weight: 600;
            color: #9b59b6;
        }

        nav ul {
            list-style: none;
            display: flex;
            gap: 20px;
        }

        nav ul li a {
            text-decoration: none;
            color: #9b59b6;
            font-weight: 500;
        }

        .hero {
            text-align: center;
            padding: 100px 20px;
            background-color: #f9f0ff;
        }

        .hero h1 {
            font-size: 48px;
            color: #9b59b6;
        }

        .hero p {
            font-size: 20px;
            margin: 20px 0;
        }

        .hero .btn {
            text-decoration: none;
            padding: 12px 30px;
            background-color: #d8b3ff;
            color: #fff;
            border-radius: 25px;
            font-weight: 600;
        }

        .products {
            padding: 60px 20px;
            text-align: center;
        }

        .products h2 {
            font-size: 36px;
            color: #9b59b6;
            margin-bottom: 40px;
        }

        .product-grid {
            display: flex;
            justify-content: center;
            gap: 40px;
            flex-wrap: wrap;
        }

        .product-card {
            border: 1px solid #f1e4ff;
            padding: 20px;
            border-radius: 15px;
            width: 200px;
            transition: transform 0.3s;
        }

        .product-card:hover {
            transform: translateY(-10px);
        }

        .product-card img {
            width: 100%;
            border-radius: 10px;
        }

        .product-card h3 {
            margin: 15px 0 5px 0;
            color: #9b59b6;
        }

        .product-card p {
            color: #555;
        }

        .contact {
            background-color: #f9f0ff;
            padding: 60px 20px;
            text-align: center;
        }

        footer {
            background-color: #f6e6ff;
            padding: 20px;
            text-align: center;
            color: #9b59b6;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">Nuvella Moda</div>
        <nav>
            <ul>
                <li><a href="#maquillaje">Maquillaje</a></li>
                <li><a href="#ropa">Ropa</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <h1>Bienvenida a Nuvella Moda</h1>
        <p>Descubre lo más femenino en ropa y maquillaje</p>
        <a href="#maquillaje" class="btn">Explorar</a>
    </section>

    <section id="maquillaje" class="products">
        <h2>Maquillaje</h2>
        <div class="product-grid">
            <div class="product-card">
                <img src="https://via.placeholder.com/200x200.png?text=Labial" alt="Labial">
                <h3>Labial Rosa</h3>
                <p>$12.99</p>
            </div>
            <div class="product-card">
                <img src="https://via.placeholder.com/200x200.png?text=Sombra" alt="Sombra">
                <h3>Sombra Lila</h3>
                <p>$15.99</p>
            </div>
        </div>
    </section>

    <section id="ropa" class="products">
        <h2>Ropa</h2>
        <div class="product-grid">
            <div class="product-card">
                <img src="https://via.placeholder.com/200x200.png?text=Vestido" alt="Vestido">
                <h3>Vestido Lila</h3>
                <p>$29.99</p>
            </div>
            <div class="product-card">
                <img src="https://via.placeholder.com/200x200.png?text=Blusa" alt="Blusa">
                <h3>Blusa Blanca</h3>
                <p>$19.99</p>
            </div>
        </div>
    </section>

    <section id="contacto" class="contact">
        <h2>Contacto</h2>
        <p>Email: info@nuvellamoda.com</p>
        <p>Teléfono: +591 123 456 789</p>
    </section>

    <footer>
        <p>&copy; 2025 Nuvella Moda. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
