# Brandon-Casale<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>LED Haven - Featured Products</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <div class="logo">LED Haven</div>
    <nav>
      <ul>
        <li><a href="#featured">Featured Product</a></li>
        <li><a href="#shop">Shop All</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="hero">
    <h1>Transform Your Space with LED Magic</h1>
    <p>Discover innovative LED products to light up your life.</p>
    <a href="#shop" class="shop-now">Shop Now</a>
  </section>

  <section id="featured">
    <h2>Featured Product</h2>
    <div class="product">
      <img src="featured-product.jpg" alt="LED Turntable Clock">
      <div class="product-info">
        <h3>LED Turntable Clock</h3>
        <p>A stylish LED clock with a vintage turntable design. Perfect for any modern space.</p>
        <p class="price">$49.99</p>
        <a href="https://yourshopifyurl.com/product/led-turntable-clock" class="buy-now">Buy Now</a>
      </div>
    </div>
  </section>

  <section id="shop">
    <h2>Shop All Products</h2>
    <div class="product-grid">
      <div class="product-card">
        <img src="led-strip.jpg" alt="LED Strip Lights">
        <h3>LED Strip Lights</h3>
        <p>Bring colorful ambiance to any space.</p>
        <p class="price">$29.99</p>
        <a href="https://yourshopifyurl.com/product/led-strip-lights" class="buy-now">Buy Now</a>
      </div>
      <div class="product-card">
        <img src="led-lamp.jpg" alt="LED Desk Lamp">
        <h3>LED Desk Lamp</h3>
        <p>Sleek and adjustable lighting for your desk.</p>
        <p class="price">$39.99</p>
        <a href="https://yourshopifyurl.com/product/led-desk-lamp" class="buy-now">Buy Now</a>
      </div>
      <!-- Add more products as needed -->
    </div>
  </section>

  <footer>
    <p>&copy; 2024 LED Haven. All rights reserved.</p>
    <div class="social-links">
      <a href="#">Facebook</a>
      <a href="#">Instagram</a>
      <a href="#">Twitter</a>
    </div>
  </footer>
</body>
</html>body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  color: #333;
}

header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #222;
  color: #fff;
  padding: 10px 20px;
}

header .logo {
  font-size: 1.5em;
  font-weight: bold;
}

header nav ul {
  list-style: none;
  display: flex;
  gap: 15px;
}

header nav ul li a {
  color: #fff;
  text-decoration: none;
}

#hero {
  text-align: center;
  padding: 50px 20px;
  background: linear-gradient(45deg, #3b82f6, #9333ea);
  color: #fff;
}

#hero .shop-now {
  display: inline-block;
  margin-top: 20px;
  padding: 10px 20px;
  background-color: #fff;
  color: #333;
  text-decoration: none;
  border-radius: 5px;
}

#featured, #shop {
  padding: 20px;
  text-align: center;
}

#featured .product {
  display: flex;
  gap: 20px;
  justify-content: center;
  align-items: center;
}

#featured img {
  width: 200px;
}

.product-info {
  max-width: 300px;
  text-align: left;
}

.product-grid {
  display: flex;
  gap: 20px;
  justify-content: center;
  flex-wrap: wrap;
}

.product-card {
  border: 1px solid #ddd;
  border-radius: 5px;
  padding: 10px;
  width: 200px;
}

.product-card img {
  width: 100%;
}

footer {
  background-color: #222;
  color: #fff;
  text-align: center;
  padding: 10px 20px;
  margin-top: 20px;
}
