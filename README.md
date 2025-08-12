<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Loja de Beats</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Montserrat', sans-serif;
    }
    body {
      background-color: #0f0f0f;
      color: #fff;
    }
    header {
      padding: 20px;
      text-align: center;
      background: #111;
      border-bottom: 1px solid #222;
    }
    header h1 {
      font-size: 2rem;
      font-weight: 700;
    }
    .container {
      max-width: 1100px;
      margin: auto;
      padding: 30px 20px;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
    }
    .beat-card {
      background: #1a1a1a;
      border-radius: 10px;
      overflow: hidden;
      display: flex;
      flex-direction: column;
      box-shadow: 0 0 10px rgba(0,0,0,0.5);
      transition: transform 0.2s;
    }
    .beat-card:hover {
      transform: scale(1.02);
    }
    .beat-card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }
    .beat-info {
      padding: 15px;
      flex: 1;
    }
    .beat-info h2 {
      font-size: 1.2rem;
      margin-bottom: 10px;
    }
    audio {
      width: 100%;
      margin: 10px 0;
    }
    .buy-btn {
      background: #ff6600;
      color: #fff;
      padding: 10px;
      border: none;
      width: 100%;
      cursor: pointer;
      font-weight: 700;
      transition: background 0.3s;
    }
    .buy-btn:hover {
      background: #e65c00;
    }
  </style>
</head>
<body>

<header>
  <h1>🔥 Loja de Beats 🔥</h1>
</header>

<div class="container">
  <!-- Beat 1 -->
  <div class="beat-card">
    <img src="https://via.placeholder.com/400x200.png?text=Beat+1" alt="Beat 1">
    <div class="beat-info">
      <h2>Trap Beat #1</h2>
      <audio controls>
        <source src="beat1.mp3" type="audio/mpeg">
        Seu navegador não suporta áudio.
      </audio>
      <button class="buy-btn" onclick="window.location.href='https://www.paypal.com'">Comprar - R$99</button>
    </div>
  </div>

  <!-- Beat 2 -->
  <div class="beat-card">
    <img src="https://via.placeholder.com/400x200.png?text=Beat+2" alt="Beat 2">
    <div class="beat-info">
      <h2>Lo-Fi Beat #1</h2>
      <audio controls>
        <source src="beat2.mp3" type="audio/mpeg">
        Seu navegador não suporta áudio.
      </audio>
      <button class="buy-btn" onclick="window.location.href='https://www.paypal.com'">Comprar - R$79</button>
    </div>
  </div>

  <!-- Beat 3 -->
  <div class="beat-card">
    <img src="https://via.placeholder.com/400x200.png?text=Beat+3" alt="Beat 3">
    <div class="beat-info">
      <h2>Drill Beat #1</h2>
      <audio controls>
        <source src="beat3.mp3" type="audio/mpeg">
        Seu navegador não suporta áudio.
      </audio>
      <button class="buy-btn" onclick="window.location.href='https://www.paypal.com'">Comprar - R$89</button>
    </div>
  </div>
</div>

</body>
</html>

