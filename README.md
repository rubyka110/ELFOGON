<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pagani Replica</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#">Inicio</a></li>
                <li><a href="#">Modelos</a></li>
                <li><a href="#">Historia</a></li>
                <li><a href="#">Contacto</a></li>
            </ul>
        </nav>
    </header>
    <section class="hero">
        <h1>Bienvenidos a Pagani Automobili</h1>
        <p>Donde la ingeniería se encuentra con el arte</p>
    </section>
    <footer>
        <p>&copy; 2025 Pagani Automobili</p>
    </footer>
</body>
</html>
/* styles.css */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #1a1a1a;
    color: white;
}

header {
    background-color: #000;
    padding: 10px 0;
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
    font-weight: bold;
}

.hero {
    background: url('tu-imagen.jpg') no-repeat center center/cover;
    text-align: center;
    padding: 100px 20px;
}

.hero h1 {
    font-size: 3em;
    margin: 0;
}

.hero p {
    font-size: 1.5em;
}

footer {
    text-align: center;
    padding: 20px;
    background-color: #000;
}
