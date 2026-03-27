<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Mundo Fútbol</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #0b3d0b;
            color: white;
        }

        header {
            background: #145214;
            padding: 20px;
            text-align: center;
        }

        nav {
            background: #1f7a1f;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 10px;
            text-decoration: none;
            font-weight: bold;
        }

        section {
            padding: 20px;
        }

        footer {
            background: #145214;
            text-align: center;
            padding: 10px;
        }

        .card {
            background: #1f7a1f;
            padding: 15px;
            margin: 10px 0;
            border-radius: 10px;
        }

        button {
            background: #2ecc71;
            border: none;
            padding: 10px;
            color: white;
            cursor: pointer;
            border-radius: 5px;
        }

        button:hover {
            background: #27ae60;
        }
    </style>
</head>

<body>

<header>
    <h1>⚽ Mundo Fútbol</h1>
    <p>Noticias, equipos y jugadores</p>
</header>

<nav>
    <a href="#">Inicio</a>
    <a href="#">Equipos</a>
    <a href="#">Jugadores</a>
    <a href="#">Contacto</a>
</nav>

<section>
    <h2>Últimas Noticias</h2>

    <div class="card">
        <p>🔥 Gran partido este fin de semana</p>
        <button onclick="verNoticia()">Leer más</button>
    </div>

    <div class="card">
        <p>⚽ Nuevo fichaje estrella</p>
        <button onclick="verNoticia()">Leer más</button>
    </div>
</section>

<section>
    <h2>Equipos Populares</h2>
    <ul>
        <li>Barcelona</li>
        <li>Real Madrid</li>
        <li>Manchester United</li>
    </ul>
</section>

<footer>
    <p>© 2026 Página de Fútbol</p>
</footer>

<script>
    function verNoticia() {
        alert("Aquí puedes agregar noticias reales más adelante ⚽");
    }

    window.onload = function() {
        alert("Bienvenido a tu página de fútbol ⚽");
    }
</script>

</body>
</html>
