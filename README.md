# gordex
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Filmes Infantis</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f8ff;
            margin: 0;
            padding: 0;
        }
        h1 {
            text-align: center;
            color: #2c3e50;
            padding: 20px;
        }
        .movie-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            padding: 20px;
        }
        .movie {
            text-align: center;
            width: 200px;
            cursor: pointer;
            transition: transform 0.2s ease;
        }
        .movie img {
            width: 200px;
            height: 300px;
            border-radius: 10px;
        }
        .movie:hover {
            transform: scale(1.05);
        }
        .movie-title {
            margin-top: 10px;
            color: #34495e;
            font-size: 16px;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <h1>Filmes Infantis</h1>
    <div class="movie-container">
        <!-- Filme 1 -->
        <div class="movie" onclick="window.location.href='https://www.youtube.com/watch?v=2e0tvlLlIHw'">
            <img src="https://upload.wikimedia.org/wikipedia/pt/6/64/Frozen_2_poster.jpg" alt="Frozen II">
            <div class="movie-title">Frozen II</div>
        </div>

        <!-- Filme 2 -->
        <div class="movie" onclick="window.location.href='https://www.youtube.com/watch?v=5c9lAfmScpM'">
            <img src="https://upload.wikimedia.org/wikipedia/pt/d/d0/Coco_2017_cartaz.jpg" alt="Coco">
            <div class="movie-title">Coco</div>
        </div>

        <!-- Filme 3 -->
        <div class="movie" onclick="window.location.href='https://www.youtube.com/watch?v=XVzVKztP_EA'">
            <img src="https://upload.wikimedia.org/wikipedia/pt/0/09/Minions_2015_poster.jpg" alt="Minions">
            <div class="movie-title">Minions</div>
        </div>

        <!-- Filme 4 -->
        <div class="movie" onclick="window.location.href='https://www.youtube.com/watch?v=ZoX8u5Ug6qI'">
            <img src="https://upload.wikimedia.org/wikipedia/pt/9/95/Uma_Aventura_Épica_cartaz.jpg" alt="Uma Aventura Épica">
            <div class="movie-title">Uma Aventura Épica</div>
        </div>

        <!-- Filme 5 -->
        <div class="movie" onclick="window.location.href='https://www.youtube.com/watch?v=MtN1YnoL46Q'">
            <img src="https://upload.wikimedia.org/wikipedia/pt/a/af/Carros_2_cartaz.jpg" alt="Carros 2">
            <div class="movie-title">Carros 2</div>
        </div>

        <!-- Filme 6 -->
        <div class="movie" onclick="window.location.href='https://www.youtube.com/watch?v=4pWz3wZ2zT4'">
            <img src="https://upload.wikimedia.org/wikipedia/pt/6/6a/O_Rei_Le%C3%A3o_2019_cartaz.jpg" alt="O Rei Leão">
            <div class="movie-title">O Rei Leão</div>
        </div>
    </div>
</body>
</html>
