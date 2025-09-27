<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Simple Shopy - Your Online Store</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f8f8f8;
      color: #333;
    }
    header {
      background: #4CAF50;
      color: white;
      padding: 15px;
      text-align: center;
    }
    header img {
      height: 60px;
      display: block;
      margin: 0 auto 10px;
    }
    nav {
      background: #333;
      display: flex;
      justify-content: center;
    }
    nav a {
      color: white;
      padding: 14px 20px;
      text-decoration: none;
      display: block;
    }
    nav a:hover {
      background: #575757;
    }
    .container {
      max-width: 1100px;
      margin: auto;
      padding: 20px;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .product-card {
      background: white;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      padding: 15px;
      text-align: center;
    }
    .product-card img {
      width: 100%;
      border-radius: 8px;
    }
    .product-card h3 {
      margin: 10px 0;
    }
    .price {
      color: #4CAF50;
      font-weight: bold;
      margin-bottom: 10px;
    }
    .btn {
      background: #4CAF50;
      color: white;
      border: none;
      padding: 10px 15px;
      border-radius: 5px;
      cursor: pointer;
    }
    .btn:hover {
      background: #45a049;
    }
    footer {
      background: #333;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <header>
    <img src="logo.png" alt="Simple Shopy Logo">
    <h1>Simple Shopy</h1>
    <p>Your trusted online dropshipping store</p>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#products">Products</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="container">
    <section id="products">
      <h2>Featured Products</h2>
      <div class="products">
        <div class="product-card">
          <img src="https://via.placeholder.com/250" alt="Product 1">
          <h3>Smart Watch</h3>
          <p class="price">₹1999</p>
          <button class="btn">Add to Cart</button>
        </div>

        <div class="product-card">
          <img src="https://via.placeholder.com/250" alt="Product 2">
          <h3>Wireless Earbuds</h3>
          <p class="price">₹1499</p>
          <button class="btn">Add to Cart</button>
        </div>

        <div class="product-card">
          <img src="https://via.placeholder.com/250" alt="Product 3">
          <h3>Phone Case</h3>
          <p class="price">₹299</p>
          <button class="btn">Add to Cart</button>
        </div>
      </div>
    </section>

    <section id="about">
      <h2>About Us</h2>
      <p>Welcome to <b>Simple Shopy</b>, your trusted dropshipping store. We bring you the latest trending products at the best prices, delivered straight to your door!</p>
    </section>

    <section id="contact">
      <h2>Contact Us</h2>
      <p>Email: support@simpleshopy.com</p>
      <p>Phone: +91 98765 43210</p>
    </section>
  </div>

  <footer>
    <p>© 2025 Simple Shopy. All rights reserved.</p>
  </footer>
</body>
</html>
