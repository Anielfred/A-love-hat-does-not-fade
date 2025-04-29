<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Chapter 1: The Beginning</title>
  <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&family=Open+Sans&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Open Sans', sans-serif;
      background: linear-gradient(to bottom, #fcefee, #ffe5ec);
      color: #333;
      padding-bottom: 60px;
    }
    .background-image {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      z-index: -1;
      overflow: hidden;
      pointer-events: none;
    }
    .background-image img {
      position: absolute;
      opacity: 0.4;
      border-radius: 20px;
      animation: float 30s infinite ease-in-out;
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
    }
    @keyframes float {
      0% { transform: translateY(0px); }
      50% { transform: translateY(-30px); }
      100% { transform: translateY(0px); }
    }
    header {
      background: linear-gradient(to right, #ff9ebf, #ffb6c1);
      padding: 20px;
      text-align: center;
      box-shadow: 0 2px 10px rgba(0,0,0,0.15);
    }
    header h1 {
      font-family: 'Great Vibes', cursive;
      font-size: 3em;
      color: white;
      margin: 0;
    }
    .chapter {
      padding: 40px;
      max-width: 800px;
      margin: auto;
      background-color: rgba(255, 255, 255, 0.9);
      border-radius: 15px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.1);
      margin-top: 40px;
    }
    .chapter h2 {
      font-family: 'Great Vibes', cursive;
      color: #d63384;
      text-align: center;
      font-size: 2.5em;
    }
    .chapter p {
      line-height: 1.8;
      text-align: justify;
      font-size: 1.1em;
    }
    .back-link {
      display: block;
      text-align: center;
      margin-top: 30px;
      font-size: 1.1em;
    }
    .back-link a {
      color: #b30059;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <div class="background-image">
    <img src="images/mimi1.jpg" style="top: 10%; left: 5%; width: 180px;">
    <img src="images/mimi2.jpg" style="top: 60%; left: 60%; width: 160px;">
    <img src="images/mimi3.jpg" style="top: 30%; left: 30%; width: 140px;">
  </div>

  <header>
    <h1>Chapter 1: The Beginning</h1>
  </header>

  <div class="chapter">
    <h2>The Beginning</h2>
    <p>From the moment we met, something sparked inside me—a quiet but powerful pull toward you, Mimi. Our journey began with smiles, laughter, and the nervous joy of discovering each other. Even though distance stretched between us, our hearts found a way to meet every day. I still remember our first late-night talks, the way you made me feel seen, understood, and cared for. You gave me something rare and precious—love, pure and beautiful.</p>
  </div>

  <div class="back-link">
    <a href="README.md">&larr; Back to Chapters</a>
  </div>
</body>
</html>
