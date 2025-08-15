

<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eduwrxz - Canal</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #121212;
            color: #fff;
        }

        header {
            background-color: #1f1f1f;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
        }

        nav {
            display: flex;
            justify-content: center;
            gap: 20px;
            background-color: #1a1a1a;
            padding: 10px 0;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            color: #ff4081;
        }

        .section {
            padding: 40px 20px;
            text-align: center;
        }

        .figurinha {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-bottom: 20px;
        }

        .figurinha img {
            width: 120px;
            border-radius: 10px;
            transition: transform 0.3s;
        }

        .figurinha img:hover {
            transform: scale(1.1);
        }

        .videos iframe {
            margin: 10px;
            max-width: 100%;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #1f1f1f;
            color: #aaa;
        }
    </style>
</head>
<body>

    <header>
        <h1>Eduwrxz</h1>
        <p>Canal de vídeos e conteúdos musicais</p>
    </header>

    <nav>
        <a href="#videos">Vídeos</a>
        <a href="#cantoras">Cantoras</a>
        <a href="#contato">Contato</a>
    </nav>

    <section id="cantoras" class="section">
        <h2>Figurinhas das Cantoras</h2>
        <div class="figurinha">
            <img src="https://upload.wikimedia.org/wikipedia/commons/8/87/Anitta_2020.jpg" alt="Anitta">
            <img src="https://upload.wikimedia.org/wikipedia/commons/6/65/Sabrina_Carpenter_2019.jpg" alt="Sabrina Carpenter">
            <img src="https://upload.wikimedia.org/wikipedia/commons/5/57/Ariana_Grande_2019.png" alt="Ariana Grande">
        </div>
    </section>

    <section id="videos" class="section">
        <h2>Todos os Vídeos</h2>
        <div class="videos">
            <!-- Exemplo de vídeo fixo -->
            <iframe width="560" height="315" src="https://www.youtube.com/embed?listType=user_uploads&list=eduwrxz" 
            title="YouTube video player" frameborder="0" allowfullscreen></iframe>
        </div>
    </section>

    <section id="contato" class="section">
        <h2>Contato</h2>
        <p>Email: felpseduardo2eu@gmail.com</p>
    </section>

    <footer>
        <p>© 2025 Eduwrxz. Todos os direitos reservados.</p>
    </footer>

</body>
</html>

