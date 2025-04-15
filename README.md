<!DOCTYPE html><html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>PlayFlix - Assista Filmes Online</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #111;
      color: #fff;
    }
    header {
      background-color: #e50914;
      padding: 20px;
      text-align: center;
      font-size: 2em;
      font-weight: bold;
    }
    .container {
      padding: 20px;
    }
    .movie-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
      gap: 20px;
    }
    .movie {
      background-color: #222;
      padding: 10px;
      border-radius: 8px;
      transition: transform 0.3s;
    }
    .movie:hover {
      transform: scale(1.05);
    }
    .movie iframe {
      width: 100%;
      height: 150px;
      border: none;
      border-radius: 5px;
    }
    .movie-title {
      margin-top: 10px;
      font-weight: bold;
      text-align: center;
    }
  </style>
</head>
<body>
  <header>
    PlayFlix
  </header>
  <div class="container">
    <h2>Filmes em Destaque</h2>
    <div class="movie-grid">
      <div class="movie">
        <iframe src="https://www.youtube.com/embed/6ZfuNTqbHE8" allowfullscreen></iframe>
        <div class="movie-title">Vingadores: Guerra Infinita</div>
      </div>
      <div class="movie">
        <iframe src="https://www.youtube.com/embed/8ugaeA-nMTc" allowfullscreen></iframe>
        <div class="movie-title">Homem-Aranha: Sem Volta para Casa</div>
      </div>
      <div class="movie">
        <iframe src="https://www.youtube.com/embed/eOrNdBpGMv8" allowfullscreen></iframe>
        <div class="movie-title">Os Vingadores</div>
      </div>
    </div>
  </div>
</body>
</html>
