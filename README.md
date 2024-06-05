<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Islas Mellizas - Refacciones Marítimas</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f8ff;
        }
        header {
            background-color: #004080;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            background-color: #0059b3;
            overflow: hidden;
        }
        nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #003366;
        }
        .container {
            padding: 20px;
        }
        .catalogo {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .producto {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 4px;
            margin: 10px;
            padding: 20px;
            text-align: center;
            width: 200px;
        }
        .producto img {
            max-width: 100%;
            height: auto;
            border-radius: 4px;
        }
        .producto h3 {
            margin: 10px 0;
        }
        .producto p {
            color: #555;
        }
        .producto .precio {
            color: #e91e63;
            font-weight: bold;
            margin: 10px 0;
        }
        footer {
            background-color: #004080;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Islas Mellizas</h1>
        <p>Refacciones Marítimas de Calidad</p>
    </header>
    <nav>
        <a href="#home">Inicio</a>
        <a href="#catalogo">Catálogo</a>
        <a href="#contacto">Contacto</a>
    </nav>
    <div class="container">
        <section id="catalogo">
            <h2>Catálogo de Productos</h2>
            <div class="catalogo">
                <div class="producto">
                    <img src="producto1.jpg" alt="Producto 1">
                    <h3>Producto 1</h3>
                    <p>Descripción breve del producto 1.</p>
                    <p class="precio">$100.00</p>
                </div>
                <div class="producto">
                    <img src="producto2.jpg" alt="Producto 2">
                    <h3>Producto 2</h3>
                    <p>Descripción breve del producto 2.</p>
                    <p class="precio">$200.00</p>
                </div>
                <div class="producto">
                    <img src="producto3.jpg" alt="Producto 3">
                    <h3>Producto 3</h3>
                    <p>Descripción breve del producto 3.</p>
                    <p class="precio">$300.00</p>
                </div>
                <!-- Agrega más productos según sea necesario -->
            </div>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Islas Mellizas. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
