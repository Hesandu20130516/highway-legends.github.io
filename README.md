# highway-legends.github.io
“Realistic bus racing game website showcasing game modes, gallery, and demo"
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Highway Legends</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0; padding: 0;
      background: #111;
      color: #eee;
      line-height: 1.6;
    }
    header {
      background: #222;
      padding: 2rem;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 3rem;
      color: #f39c12;
      text-shadow: 2px 2px 5px #000;
    }
    .hero-image {
      width: 100%;
      max-height: 350px;
      object-fit: cover;
      display: block;
      margin: 0 auto;
      border-bottom: 4px solid #f39c12;
    }
    section {
      max-width: 900px;
      margin: 2rem auto;
      padding: 0 1rem;
    }
    h2 {
      color: #f39c12;
      border-bottom: 2px solid #f39c12;
      padding-bottom: 0.5rem;
    }
    .game-modes ul {
      list-style: none;
      padding-left: 0;
    }
    .game-modes li {
      margin: 0.5rem 0;
      background: #333;
      padding: 0.5rem 1rem;
      border-radius: 5px;
    }
    .play-button {
      display: block;
      width: 200px;
      margin: 1rem auto 2rem;
      padding: 1rem;
      text-align: center;
      background: #f39c12;
      color: #111;
      font-weight: bold;
      text-decoration: none;
      border-radius: 5px;
      box-shadow: 0 0 10px #f39c12;
      transition: background 0.3s;
    }
    .play-button:hover {
      background: #d48806;
      box-shadow: 0 0 15px #d48806;
    }
    .gallery {
      display: flex;
      flex-wrap: wrap;
      gap: 1rem;
      justify-content: center;
    }
    .gallery img {
      max-width: 200px;
      border-radius: 8px;
      border: 2px solid #f39c12;
      box-shadow: 0 0 10px #f39c12;
    }
    .about {
      background: #222;
      padding: 1rem;
      border-radius: 8px;
      text-align: center;
      color: #ccc;
    }
    footer {
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
      color: #666;
      border-top: 1px solid #333;
      margin-top: 3rem;
    }
  </style>
</head>
<body>

<header>
  <h1>Highway Legends</h1>
  <img class="hero-image" src="https://i.imgur.com/5Yc6h3g.jpg" alt="Highway Legends Bus Racing" />
</header>

<section class="game-modes">
  <h2>Game Modes</h2>
  <ul>
    <li>Tour Mode - Explore Sri Lankan highways</li>
    <li>Race Mode - Compete with other buses and cars</li>
    <li>Free Mode - Drive freely with no objectives</li>
  </ul>
</section>

<a class="play-button" href="https://highwaylegends.github.io/demo" target="_blank" rel="noopener noreferrer">Play Now (Demo)</a>

<section class="gallery">
  <h2>Gallery</h2>
  <img src="https://i.imgur.com/6i6Z3Z5.jpg" alt="AC Luxury Bus" />
  <img src="https://i.imgur.com/cEKz2sl.jpg" alt="Highway Traffic" />
  <img src="https://i.imgur.com/hVnTRtS.jpg" alt="Nitro Boost" />
</section>

<section class="about">
  <h2>About</h2>
  <p>Created by Hesandu Illankoon</p>
  <p>Email: <a href="mailto:Hesillankoon@gmail.com" style="color:#f39c12;">Hesillankoon@gmail.com</a></p>
</section>

<footer>
  &copy; 2025 Highway Legends. All rights reserved.
</footer>

</body>
</html>
