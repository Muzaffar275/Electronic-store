# Electronic-store
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ElectroZone - Online Electronics Store</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Roboto', sans-serif;
    }
    body {
      background-color: #f4f4f4;
      color: #333;
    }
    header {
      background-color: #1e1e2f;
      padding: 1rem 2rem;
      color: white;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header h1 {
      font-size: 1.8rem;
    }
    nav a {
      color: white;
      margin-left: 20px;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1519389950473-47ba0277781c') no-repeat center center/cover;
      height: 60vh;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-shadow: 2px 2px 5px #000;
    }
    .hero h2 {
      font-size: 3rem;
    }
    .products {
      padding: 2rem;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
    }
    .product {
      background: white;
      padding: 1rem;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      text-align: center;
    }
    .product img {
      max-width: 100%;
      height: 180px;
      object-fit: cover;
      border-radius: 5px;
    }
    .product h3 {
      margin: 1rem 0 0.5rem;
    }
    .product p {
      font-size: 0.9rem;
      margin-bottom: 1rem;
    }
    .btn {
      background-color: #1e1e2f;
      color: white;
      border: none;
      padding: 0.5rem 1rem;
      border-radius: 5px;
      cursor: pointer;
    }
    footer {
      background-color: #1e1e2f;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>ElectroZone</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">Products</a>
      <a href="#">Deals</a>
      <a href="#">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Top Gadgets & Accessories</h2>
  </section>

  <section class="products">
    <div class="product">
      <img src="https://images.unsplash.com/photo-1581291518857-4e27b48ff24e" alt="Smartphone">
      <h3>Smartphone X10</h3>
      <p>Latest smartphone with high-speed processor and amazing camera.</p>
      <button class="btn">Buy Now</button>
    </div>
    <div class="product">
      <img src="https://images.unsplash.com/photo-1580894894513-3c4f2b39c4a6" alt="Wireless Earbuds">
      <h3>Wireless Earbuds</h3>
      <p>Noise-cancelling, long battery life, and ultra-portable design.</p>
      <button class="btn">Buy Now</button>
    </div>
    <div class="product">
      <img src="https://images.unsplash.com/photo-1517059224940-d4af9eec41e5" alt="Smartwatch">
      <h3>Smartwatch Pro</h3>
      <p>Track your health, receive notifications, and more on your wrist.</p>
      <button class="btn">Buy Now</button>
    </div>
    <div class="product">
      <img src="https://images.unsplash.com/photo-1518770660439-4636190af475" alt="Laptop">
      <h3>Ultra Laptop Z</h3>
      <p>Lightweight, powerful, and perfect for work and play.</p>
      <button class="btn">Buy Now</button>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 ElectroZone. All rights reserved.</p>
  </footer>
</body>
</html>
