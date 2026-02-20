<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Bangarang | MusicStream</title>

    <!-- Favicon -->
    <link rel="icon" type="image/png" href="../assets/favicon.png">

    <!-- CSS NUEVO del reproductor -->
    <link rel="stylesheet" href="../css/pages.css">
    <link rel="stylesheet" href="../css/styles.css">
    <link rel="stylesheet" href="../css/likes.css">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>

<body>
    <nav class="sidebar">

        <ul>
            <li>
                <a href="..">
                    <img src="../images/home4.png" alt="Home">
                    <span>HOME</span>
                </a>
            </li>

            <li>
                <a href="barra busqueda.html">
                    <img src="../images/buscar.jpg" alt="Buscar">
                    <span>BUSCAR</span>
                </a>
            </li>

            <li>
                <a href="#">
                    <img src="../images/playlist.jpg" alt="Playlist">
                    <span>PLAYLIST</span>
                </a>
            </li>

            <li>
                <a href="#">
                    <img src="../images/artistas.jpg" alt="Artistas">
                    <span>ARTISTAS</span>
                </a>
            </li>
            <li>
            <a href="../pages/perfil.html">
                <img src="../images/perfil icono.jpg" alt="Perfil">
                <span>PERFIL</span>
            </a>
            </li>
            <li>
            <a href="carrito.html">
            <img src="../images/cart.png" alt="Carrito">
            <span>CARRITO</span>
            </a>
            </li>
        </ul>

    </nav>

    <div class="main-content">

        <div class="album-container">
    
            <div class="album-header">
                <img src="images/album-cover.jpg" alt="Álbum EDM">
    
                <div class="album-info">
                    <h1>Festival Energy</h1>
                    <p>DJ Aurora</p>
                    <button class="play-btn">▶ Reproducir</button>
                </div>
            </div>
    
            <div class="song-list">
                <h2>Canciones Favoritas ❤️</h2>
    
                <div class="song">
                    <span>1. Neon Lights</span>
                    <span>3:45</span>
                </div>
    
                <div class="song">
                    <span>2. Midnight Drop</span>
                    <span>4:12</span>
                </div>
    
                <div class="song">
                    <span>3. Bass Explosion</span>
                    <span>3:58</span>
                </div>
    
                <div class="song">
                    <span>4. Sky Rave</span>
                    <span>4:30</span>
                </div>
    
            </div>
    
        </div>
    
    </div>
    
</body>
</html>



.main-content {
    margin-left: 220px;
    padding: 50px;
    min-height: 100vh;
}


.album-container {
    max-width: 900px;
    margin: auto;
    color: white;
}


.album-header {
    display: flex;
    gap: 40px;
    align-items: center;
    margin-bottom: 50px;
}

.album-header img {
    width: 250px;
    border-radius: 15px;
    box-shadow: 0 0 30px rgba(138, 43, 226, 0.4);
}

.album-info h1 {
    font-size: 2.5rem;
    margin-bottom: 10px;
}

.album-info p {
    margin-bottom: 20px;
    opacity: 0.7;
}

.play-btn {
    padding: 12px 25px;
    border-radius: 30px;
    border: none;
    background: #8a2be2;
    color: white;
    cursor: pointer;
    transition: 0.3s;
}

.play-btn:hover {
    background: #a855f7;
    transform: scale(1.05);
}

.song-list h2 {
    margin-bottom: 20px;
}

.song {
    display: flex;
    justify-content: space-between;
    padding: 15px;
    border-radius: 10px;
    margin-bottom: 10px;
    background: rgba(255,255,255,0.05);
    transition: 0.3s;
}

.song:hover {
    background: rgba(138, 43, 226, 0.2);
    transform: translateX(5px);
}
