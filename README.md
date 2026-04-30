<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Inmobiliaria Ejemplo</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Inmobiliaria Ejemplo</h1>
        <nav>
            <ul>
                <li><a href="#about">Nosotros</a></li>
                <li><a href="#properties">Propiedades</a></li>
                <li><a href="#contact">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <section id="about">
        <h2>Quiénes somos</h2>
        <p>Somos una inmobiliaria dedicada a ayudarte a encontrar tu hogar ideal.</p>
    </section>

    <section id="properties">
        <h2>Propiedades en Venta</h2>
        <div class="property">
            <h3>Casa en la playa</h3>
            <p>Precio: $200,000</p>
            <p>Descripción: Hermosa casa en la costa.</p>
        </div>
        <div class="property">
            <h3>Departamento en el centro</h3>
            <p>Precio: $150,000</p>
            <p>Descripción: Moderno departamento, cerca de todo.</p>
        </div>
    </section>

    <section id="contact">
        <h2>Contacto</h2>
        <p>Email: contacto@inmobiliariaejemplo.com</p>
        <p>Teléfono: (123) 456-7890</p>
    </section>

    <footer>
        <p>&copy; 2023 Inmobiliaria Ejemplo. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background: #35424a;
    color: white;
    padding: 20px 0;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

section {
    padding: 20px;
    margin: 10px;
    background: white;
    border-radius: 8px;
}

.property {
    border: 1px solid #ccc;
    padding: 10px;
    margin: 10px 0;
    border-radius: 5px;
}

footer {
    text-align: center;
    padding: 10px 0;
    background: #35424a;
    color: white;
    position: relative;
    bottom: 0;
    width: 100%;
}

