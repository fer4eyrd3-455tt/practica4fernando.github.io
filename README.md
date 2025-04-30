
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tienda de Perfumes</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #fdf6f0;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #d7b8a3;
            color: white;
            text-align: center;
            padding: 2rem 1rem;
        }
        .productos {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 2rem;
        }
        .producto {
            background-color: white;
            border: 1px solid #eee;
            border-radius: 8px;
            box-shadow: 0 2px 6px rgba(0,0,0,0.1);
            margin: 1rem;
            padding: 1rem;
            max-width: 250px;
            text-align: center;
        }
        .producto img {
            width: 100%;
            height: auto;
            border-radius: 4px;
        }
        .producto h3 {
            margin: 0.5rem 0;
        }
        .producto p {
            color: #777;
        }
        .producto .precio {
            color: #b67b5f;
            font-weight: bold;
            margin: 0.5rem 0;
        }
        .producto button {
            background-color: #b67b5f;
            color: white;
            border: none;
            padding: 0.5rem 1rem;
            cursor: pointer;
            border-radius: 4px;
        }
        footer {
            background-color: #d7b8a3;
            color: white;
            text-align: center;
            padding: 1rem;
        }
    </style>
</head>
<body>

    <header>
        <h1>Perfumes de Lujo MARTINEZ</h1>
        <p>Descubre tu fragancia ideal</p>
    </header>

    <section class="productos">
        <div class="producto">
            <img src="https://via.placeholder.com/200x250" alt="Perfume 1">
            <h3>Rosa Encantada</h3>
            <p>Una fragancia floral y delicada para ocasiones especiales.</p>
            <p class="precio">$49.99MX</p>
            <button>Comprar</button>
        </div>
        <div class="producto">
            <img src="https://via.placeholder.com/200x250" alt="Perfume 2">
            <h3>Brisa Nocturna</h3>
            <p>Aromas frescos y elegantes para el día y la noche.</p>
            <p class="precio">$59.99MX</p>
            <button>Comprar</button>
        </div>
        <div class="producto">
            <img src="https://via.placeholder.com/200x250" alt="Perfume 3">
            <h3>Amor Secreto</h3>
            <p>Notas dulces con un toque misterioso.</p>
            <p class="precio">$54.99MX</p>
            <button>Comprar</button>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 Tienda de Perfumes. Todos los derechos reservados.</p>
    </footer>

</body>
</html>
