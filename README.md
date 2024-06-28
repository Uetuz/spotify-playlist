<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Playlist de Spotify</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background: linear-gradient(to right, #ff7e5f, #feb47b);
            color: #ffffff;
        }
        .container {
            max-width: 600px;
            width: 100%;
            padding: 20px;
            background: rgba(255, 255, 255, 0.1);
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.2);
            border-radius: 12px;
            backdrop-filter: blur(10px);
            text-align: center;
        }
        h1 {
            margin-bottom: 20px;
            font-size: 2em;
        }
        iframe {
            border: none;
        }
        .footer {
            margin-top: 20px;
            font-size: 0.9em;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Disfruta de la Playlist</h1>
        <iframe style="border-radius:12px" src="https://open.spotify.com/embed/playlist/37i9dQZF1E4vigwx6FRO5h?utm_source=generator" width="100%" height="352" allowfullscreen="" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>
        <div class="footer">Powered by Spotify</div>
    </div>
</body>
</html>

