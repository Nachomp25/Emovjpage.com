<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EMOVJ.Com</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            background-color: #1e1e1e;
            color: #dcdcdc;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #111;
            padding: 10px 20px;
            display: flex;
            align-items: center;
        }
        header img {
            height: 24px;
            margin-right: 10px;
        }
        header h1 {
            margin: 0;
            font-size: 1.2em;
        }
        header .search-bar {
            margin-left: auto;
            display: flex;
            align-items: center;
        }
        header .search-bar input {
            background-color: #333;
            border: 1px solid #444;
            color: #dcdcdc;
            padding: 5px;
            border-radius: 5px;
        }
        header .icons img {
            height: 24px;
            margin-left: 10px;
        }
        main {
            padding: 20px;
        }
        .main-banner {
            position: relative;
            text-align: center;
            color: white;
        }
        .main-banner img {
            width: 100%;
            border-radius: 10px;
        }
        .main-banner .content {
            position: absolute;
            bottom: 20px;
            left: 20px;
        }
        .main-banner .content h2 {
            margin: 0;
        }
        .main-banner .content p {
            margin: 5px 0 10px;
        }
        .main-banner .content button {
            background-color: #ffc107;
            border: none;
            padding: 10px 20px;
            margin-right: 10px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1em;
        }
        .main-banner .content button:last-child {
            background-color: #28a745;
        }
        .clips, .where-to-find-me {
            margin-top: 40px;
        }
        .clips h2, .where-to-find-me h2 {
            margin-bottom: 10px;
        }
        .clips .clip, .where-to-find-me .link {
            background-color: #333;
            padding: 10px;
            margin-bottom: 10px;
            border-radius: 10px;
        }
        .clips .clip img {
            width: 100%;
            border-radius: 10px;
        }
        .clips .clip .clip-title {
            margin: 10px 0;
        }
        .where-to-find-me .link {
            display: flex;
            align-items: center;
        }
        .where-to-find-me .link img {
            height: 40px;
            margin-right: 10px;
        }
        .footer {
            margin-top: 40px;
            text-align: center;
            color: #bbb;
        }
    </style>
</head>
<body>
    <header>
        <img src="https://via.placeholder.com/24" alt="Logo">
        <h1>EMOVJ.Com</h1>
        <div class="search-bar">
            <input type="text" placeholder="Search">
            <div class="icons">
                <img src="https://via.placeholder.com/24" alt="User Icon">
                <img src="https://via.placeholder.com/24" alt="Settings Icon">
            </div>
        </div>
    </header>
    <main>
        <div class="main-banner">
            <img src="https://via.placeholder.com/800x400" alt="Banner Image">
            <div class="content">
                <h2>EMOVJ</h2>
                <p>Videojugador desde que nací. Creador de contenido oficial de Warframe. Amo los clásicos aunque juego de todo un poco. Me encanta dibujar con el pie UwU</p>
                <button>Subscribe</button>
                <button>Join</button>
            </div>
        </div>
        <section class="clips">
            <h2>Algunos EMOVJclips</h2>
            <div class="clip">
                <img src="https://via.placeholder.com/400x200" alt="Clip Image">
                <p class="clip-title">Salvados por la testosterona</p>
            </div>
            <div class="clip">
                <div class="alert">
                    <p>Tenemos sorteo en mi canal de Twitch, se sorteará el día 25 de mayo año 2024 así que pasate por ahí.</p>
                    <p>2024-05-20 20:30:39</p>
                </div>
            </div>
        </section>
        <section class="where-to-find-me">
            <h2>Donde encontrarme</            <div class="link">
                <img src="https://via.placeholder.com/40" alt="Twitch Logo">
                <p>
                    <strong>Twitch</strong><br>
                    Videojugador desde que nací (bueno, no tanto), creador de contenido oficial de Warframe. Amo los clásicos aunque juego de todo un poco. Me encanta dibujar con el pie UwU<br>
                    <a href="https://twitch.tv/emovj">twitch.tv/emovj</a>
                </p>
            </div>
            <div class="link">
                <img src="https://via.placeholder.com/40" alt="YouTube Logo">
                <p>
                    <strong>EMOVJ</strong><br>
                    Soy EMO, creador de contenido oficial de Warframe y adicto al té verde! En este canal encontrarás video-guías y de opinión acerca de Warframe, de otros juegos...<br>
                    <a href="https://youtube.com/channel/UCmh5igQMURLHcQZ4_L5OOaA">youtube.com/channel/UCmh5igQMURLHcQZ4_L5OOaA</a>
                </p>
            </div>
            <div class="link">
                <img src="https://via.placeholder.com/40" alt="YouTube Logo">
                <p>
                    <strong>Emocion Videojuegos</strong><br>
                    Sí, soy yo en otro canal XD. En este canal se resubirán todos los juegos clásicos que vamos reviviendo en los Clásicos en Twitch! Aunque también planeo tra...<br>
                    <a href="https://youtube.com/channel/UC0mm3zJh_i0-0wmzUZAxO3g">youtube.com/channel/UC0mm3zJh_i0-0wmzUZAxO3g</a>
                </p>
            </div>
        </section>
    </main>
    <footer>
        <div class="footer">
            <p>© 2024 EMOVJ. Todos los derechos reservados.</p>
        </div>
    </footer>
</body>
</html>
