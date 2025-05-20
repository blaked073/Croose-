<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Croose+</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #121212;
      color: #ffffff;
    }
    header {
      background-color: #1f1f1f;
      padding: 20px;
      text-align: center;
      font-size: 2em;
      font-weight: bold;
      color: #e50914;
    }
    .movies {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .movie {
      background-color: #1f1f1f;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 0 10px rgba(0,0,0,0.5);
      transition: transform 0.2s;
    }
    .movie:hover {
      transform: scale(1.05);
    }
    .movie img {
      width: 100%;
      height: auto;
      display: block;
    }
    .movie-title {
      padding: 10px;
      font-size: 1em;
      text-align: center;
    }
    a {
      text-decoration: none;
      color: inherit;
    }
  </style>
</head>
<body>
  <header>Croose+</header>  <div class="movies">
    <a href="#">
      <div class="movie">
        <img src="https://via.placeholder.com/300x450?text=Movie+1"
