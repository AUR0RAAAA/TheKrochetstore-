<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>TheKrochetstore</title>
  <link href="https://fonts.googleapis.com/css2?family=Pacifico&family=Roboto&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Roboto', sans-serif;
      background: #fff8f0;
      color: #333;
    }
    header {
      background: linear-gradient(135deg, #f6c1c7, #f8e1a1);
      padding: 2rem;
      text-align: center;
      color: #4b2e2e;
    }
    header h1 {
      font-family: 'Pacifico', cursive;
      font-size: 3rem;
      margin: 0;
    }
    header p {
      font-style: italic;
      margin-top: 0.5rem;
    }
    .section {
      padding: 2rem;
      max-width: 1200px;
      margin: auto;
    }
    .section h2 {
      text-align: center;
      color: #ba4e4e;
      margin-bottom: 1.5rem;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
    }
    .item {
      background: #fff;
      border-radius: 12px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      overflow: hidden;
      transition: transform 0.3s ease;
    }
    .item:hover {
      transform: scale(1.03);
    }
    .item img {
      width: 100%;
      height: auto;
      display: block;
    }
    .item p {
      padding: 1rem;
      text-align: center;
      font-weight: bold;
    }
    footer {
      background: #f6c1c7;
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>TheKrochetstore</h1>
    <p>Wave your story with the krochetstore</p>
  </header>

  <section class="section">
    <h2>Our Creations</h2>
    <div class="gallery">
      <div class="item">
        <img src="https://via.placeholder.com/300x200?text=Keychain" alt="Keychain" />
        <p>Handmade Keychain</p>
      </div>
      <div class="item">
        <img src="https://via.placeholder.com/300x200?text=Flower" alt="Flower" />
        <p>Crochet Flower</p>
      </div>
      <div class="item">
        <img src="https://via.placeholder.com/300x200?text=Wearable" alt="Wearable" />
        <p>Wearable Art</p>
      </div>
      <div class="item">
        <img src="https://via.placeholder.com/300x200?text=Plushie" alt="Plushie" />
        <p>Crochet Plushie</p>
      </div>
    </div>
  </section>

  <footer>
    Contact us on Instagram @thekrochetstore | Designed with love
  </footer>
</body>
</html>
