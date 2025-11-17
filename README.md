# gordex

<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Filmes Infantis</title>

<style>
    body {
        margin: 0;
        background: linear-gradient(to bottom, #aee2ff, #ffffff);
        font-family: "Poppins", sans-serif;
    }

    h1 {
        text-align: center;
        padding: 20px;
        font-size: 35px;
        color: #003e80;
        text-shadow: 2px 2px #ffffff;
    }

    .grid {
        display: grid;
        grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
        gap: 25px;
        padding: 20px;
    }

    .card {
        background: #ffffff;
        border-radius: 15px;
        box-shadow: 0 4px 15px rgba(0,0,0,0.2);
        overflow: hidden;
        transition: transform .3s;
        position: relative;
    }

    .card:hover {
        transform: scale(1.07);
    }

    .thumb {
        width: 100%;
        height: 350px;
        object-fit: cover;
        transition: opacity .4s;
    }

    .video-preview {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 350px;
        opacity: 0;
        pointer-events: none;
        transition: opacity .4s;
    }

    .card:hover .video-preview {
        opacity: 1;
    }

    .info {
        padding: 15px;
        text-align: center;
    }

    .title {
        font-size: 18px;
        font-weight: bold;
        margin-bottom: 10px;
        color: #003e80;
    }

    .btn {
        background-color: #0077ff;
        color: white;
        padding: 10px 15px;
        border-radius: 8px;
        text-decoration: none;
        font-size: 15px;
        transition: .3s;
    }

    .btn:hover {
        background-color: #005bcc;
    }
</style>
</head>

<body>

<h1>🎬 Filmes Infantis – Clique para Assistir</h1>

<div class="grid">

    <!-- FROZEN -->
    <div class="card">
        <img class="thumb" src="https://upload.wikimedia.org/wikipedia/pt/1/1b/Frozen_2013.png">
        <iframe class="video-preview" src="https://www.youtube.com/embed/TbQm5doF_Uc?autoplay=1&mute=1"></iframe>
        <div class="info">
            <div class="title">Frozen</div>
            <a class="btn" href="https://www.youtube.com/watch?v=TbQm5doF_Uc" target="_blank">Assistir</a>
        </div>
    </div>

    <!-- TOY STORY -->
    <div class="card">
        <img class="thumb" src="https://upload.wikimedia.org/wikipedia/pt/d/dc/Toy_Story_p%C3%B4ster.png">
        <iframe class="video-preview" src="https://www.youtube.com/embed/KuWdUimLRK0?autoplay=1&mute=1"></iframe>
        <div class="info">
            <div class="title">Toy Story</div>
            <a class="btn" href="https://www.youtube.com/watch?v=KuWdUimLRK0" target="_blank">Assistir</a>
        </div>
    </div>

    <!-- MOANA -->
    <div class="card">
        <img class="thumb" src="https://upload.wikimedia.org/wikipedia/pt/5/5a/Moana.jpg">
        <iframe class="video-preview" src="https://www.youtube.com/embed/LKFuXETZUsI?autoplay=1&mute=1"></iframe>
        <div class="info">
            <div class="title">Moana</div>
            <a class="btn" href="https://www.youtube.com/watch?v=LKFuXETZUsI" target="_blank">Assistir</a>
        </div>
    </div>

    <!-- DIVERTIDA MENTE -->
    <div class="card">
        <img class="thumb" src="https://upload.wikimedia.org/wikipedia/pt/9/9b/Divertida_Mente_2015.jpg">
        <iframe class="video-preview" src="https://www.youtube.com/embed/seMwpP0yeu4?autoplay=1&mute=1"></iframe>
        <div class="info">
            <div class="title">Divertida Mente</div>
            <a class="btn" href="https://www.youtube.com/watch?v=seMwpP0yeu4" target="_blank">Assistir</a>
        </div>
    </div>

    <!-- CARROS -->
    <div class="card">
        <img class="thumb" src="https://upload.wikimedia.org/wikipedia/pt/3/34/Cars_2006.jpg">
        <iframe class="video-preview" src="https://www.youtube.com/embed/SbXIj2T-_uk?autoplay=1&mute=1"></iframe>
        <div class="info">
            <div class="title">Carros</div>
            <a class="btn" href="https://www.youtube.com/watch?v=SbXIj2T-_uk" target="_blank">Assistir</a>
        </div>
    </div>

    <!-- ENCANTO -->
    <div class="card">
        <img class="thumb" src="https://upload.wikimedia.org/wikipedia/pt/8/88/Encanto_poster.jpg">
        <iframe class="video-preview" src="https://www.youtube.com/embed/CaimKeDcudo?autoplay=1&mute=1"></iframe>
        <div class="info">
            <div class="title">Encanto</div>
            <a class="btn" href="https://www.youtube.com/watch?v=CaimKeDcudo" target="_blank">Assistir</a>
        </div>
    </div>

    <!-- PEQUENA SEREIA -->
    <div class="card">
        <img class="thumb" src="https://upload.wikimedia.org/wikipedia/pt/7/75/The_Little_Mermaid_1989.jpg">
        <iframe class="video-preview" src="https://www.youtube.com/embed/ZGZX5-PAwR8?autoplay=1&mute=1"></iframe>
        <div class="info">
            <div class="title">A Pequena Sereia</div>
            <a class="btn" href="https://www.youtube.com/watch?v=ZGZX5-PAwR8" target="_blank">Assistir</a>
        </div>
    </div>

    <!-- O REI LEÃO -->
    <div class="card">
        <img class="thumb" src="https://upload.wikimedia.org/wikipedia/pt/3/3d/The_Lion_King.png">
        <iframe class="video-preview" src="https://www.youtube.com/embed/lFzVJEksoDY?autoplay=1&mute=1"></iframe>
        <div class="info">
            <div class="title">O Rei Leão</div>
            <a class="btn" href="https://www.youtube.com/watch?v=lFzVJEksoDY" target="_blank">Assistir</a>
        </div>
    </div>

</div>

</body>
</html>
