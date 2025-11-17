# gordex

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lista de Filmes</title>

    <style>
        body {
            font-family: Arial, Helvetica, sans-serif;
            background: #111;
            color: white;
            margin: 0;
            padding: 20px;
        }

        h1 {
            text-align: center;
            margin-bottom: 40px;
            color: #00e5ff;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 25px;
        }

        .card {
            background: #1c1c1c;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.6);
            transition: 0.3s;
        }

        .card:hover {
            transform: scale(1.05);
        }

        .card img {
            width: 100%;
            height: 350px;
            object-fit: cover;
        }

        .card h2 {
            padding: 15px;
            margin: 0;
            font-size: 1.3em;
            color: #00e5ff;
        }

        .card p {
            padding: 0 15px 20px 15px;
            margin: 0;
            opacity: 0.8;
            font-size: 0.95em;
        }
    </style>
</head>
<body>

    <h1>Lista de Filmes</h1>

    <div class="grid">

        <div class="card">
            <img src="IMAGEM-GERAR-BLADE-RUNNER" alt="Blade Runner">
            <h2>Blade Runner (1982)</h2>
            <p>Ficção científica futurista em uma distopia cyberpunk.</p>
        </div>

        <div class="card">
            <img src="IMAGEM-GERAR-JURASSIC-PARK" alt="Jurassic Park">
            <h2>Jurassic Park (1993)</h2>
            <p>Clássico sobre o parque de dinossauros recriados geneticamente.</p>
        </div>

        <div class="card">
            <img src="IMAGEM-GERAR-RATATOUILLE" alt="Ratatouille">
            <h2>Ratatouille (2007)</h2>
            <p>Um rato com o sonho de ser chef em Paris.</p>
        </div>

        <div class="card">
            <img src="IMAGEM-GERAR-ARRIVAL" alt="Arrival">
            <h2>Arrival (2016)</h2>
            <p>Contato com alienígenas e desafios de comunicação.</p>
        </div>

        <div class="card">
            <img src="IMAGEM-GERAR-SPIRITED-AWAY" alt="Spirited Away">
            <h2>A Viagem de Chihiro (2001)</h2>
            <p>Aventura mágica do Studio Ghibli.</p>
        </div>

        <div class="card">
            <img src="IMAGEM-GERAR-WWDIS" alt="What We Do in the Shadows">
            <h2>What We Do in the Shadows (2014)</h2>
            <p>Mockumentary cômico sobre vampiros dividindo apartamento.</p>
        </div>

        <div class="card">
            <img src="IMAGEM-GERAR-DARK-KNIGHT" alt="The Dark Knight">
            <h2>The Dark Knight (2008)</h2>
            <p>Batman enfrenta o Coringa em um dos melhores filmes de heróis.</p>
        </div>

        <div class="card">
            <img src="IMAGEM-GERAR-CORALINE" alt="Coraline">
            <h2>Coraline (2009)</h2>
            <p>Uma menina encontra um mundo paralelo aparentemente perfeito.</p>
        </div>

        <div class="card">
            <img src="IMAGEM-GERAR-INCEPTION" alt="Inception">
            <h2>Inception (2010)</h2>
            <p>Assalto dentro dos sonhos com camadas de realidade.</p>
        </div>

        <div class="card">
            <img src="IMAGEM-GERAR-REVENANT" alt="The Revenant">
            <h2>The Revenant (2015)</h2>
            <p>Um homem luta pela sobrevivência na neve após ser traído.</p>
        </div>

    </div>

</body>
</html>
