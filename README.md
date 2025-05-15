<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>XAMI CREATIONS</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #0a0a0a;
      color: #00ff99;
    }
    header {
      background-color: #101010;
      padding: 20px;
      text-align: center;
      font-size: 2em;
      border-bottom: 2px solid #00ff99;
    }
    nav {
      text-align: center;
      margin: 20px 0;
    }
    nav a {
      color: #00ff99;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    section {
      padding: 20px;
      text-align: center;
    }
    .product-card {
      background-color: #1a1a1a;
      border: 1px solid #00ff99;
      padding: 20px;
      margin: 10px;
      display: inline-block;
      width: 220px;
      border-radius: 10px;
      transition: transform 0.3s;
    }
    .product-card:hover {
      transform: scale(1.05);
      box-shadow: 0 0 10px #00ff99;
    }
    .product-card img {
      width: 100%;
      border-radius: 10px;
    }
    footer {
      text-align: center;
      padding: 20px;
      background-color: #101010;
      border-top: 2px solid #00ff99;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <header>
    XAMI CREATIONS
  </header>
  <nav>
    <a href="#home">Home</a>
    <a href="#shop">Shop</a>
    <a href="#login">Login</a>
    <a href="#contact">Contact</a>
  </nav>
  <section id="home">
    <h2>Welcome to the Futuristic Anime Shopping Experience!</h2>
    <p>Buy and sell all types of products, powered by XAMI CREATIONS.</p>
  </section>
  <section id="shop">
    <h2>Featured Anime Characters</h2>
    <div class="product-card">
      <img src="https://i.imgur.com/Zcdty8Z.png" alt="Gojo Satoru" />
      <h3>Gojo Satoru</h3>
      <p>The strongest sorcerer with limitless power.</p>
    </div>
    <div class="product-card">
      <img src="https://i.imgur.com/MxvHV8I.png" alt="Naruto Uzumaki" />
      <h3>Naruto Uzumaki</h3>
      <p>The determined ninja who never gives up.</p>
    </div>
    <div class="product-card">
      <img src="https://i.imgur.com/0OvUPOI.png" alt="Anime Character 3" />
      <h3>Anime Character 3</h3>
      <p>Description of the character or product.</p>
    </div>
  </section>
  <footer>
    &copy; 2025 XAMI CREATIONS. All rights reserved.
  </footer>
</body>
</html>
