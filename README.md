<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Taja Farms | Organic Agro Products</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Inter', sans-serif;
      background-color: #f6fff5;
      color: #333;
    }
    header {
      background-color: #2d6a4f;
      color: white;
      padding: 1rem 2rem;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.2rem;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 1.5rem;
      margin-top: 0.5rem;
    }
    nav a {
      color: #d9f99d;
      text-decoration: none;
      font-weight: 600;
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1607330289092-b41e43fa04f0') center/cover;
      color: white;
      padding: 5rem 2rem;
      text-align: center;
    }
    .hero h2 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
    }
    .section {
      padding: 3rem 2rem;
      max-width: 1000px;
      margin: auto;
    }
    .section h3 {
      font-size: 2rem;
      color: #1b4332;
      margin-bottom: 1rem;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
    }
    .product {
      background: white;
      padding: 1.5rem;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      text-align: center;
    }
    .product img {
      max-width: 100%;
      height: 180px;
      object-fit: cover;
      border-radius: 8px;
    }
    .product h4 {
      margin: 0.5rem 0;
      color: #40916c;
    }
    .product p {
      font-size: 0.95rem;
    }
    footer {
      background: #1b4332;
      color: white;
      text-align: center;
      padding: 2rem 1rem;
    }
    .cta-button {
      display: inline-block;
      margin-top: 1rem;
      padding: 0.7rem 1.5rem;
      background: #52b788;
      color: white;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <header>
    <h1>Taja Farms</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#products">Products</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Purely Organic. Locally Grown.</h2>
    <p>Explore the richness of nature through our farm-fresh seeds, grains & vegetables.</p>
    <a href="#products" class="cta-button">Shop Now</a>
  </section>

  <section id="about" class="section">
    <h3>About Taja Farms</h3>
    <p>Taja Farms is a woman-led agricultural e-commerce venture proudly rooted in Bhadrapur, Jhapa. Founded by a passionate and experienced farmer with over 30 years in sustainable agriculture, the business stands as a symbol of tradition, resilience, and innovation in organic farming.</p>
    <p>Specializing in premium-quality mustard seeds—including Tori and Aalas—Taja Farms also offers a rich selection of seasonal organic vegetables, the rare and nutritious Kalo Nuniya Chamal (black sticky rice), and other wholesome, chemical-free food products.</p>
    <p>Driven by a deep commitment to purity, health, and sustainability, Taja Farms has become a trusted name among health-conscious consumers across the region. Every product reflects decades of hands-on experience, respect for nature, and a genuine dedication to feeding families with safe, organic produce.</p>
  </section>

  <section id="products" class="section">
    <h3>Our Products</h3>
    <div class="products">
      <div class="product">
        <img src="/mnt/data/Brown-Mustard-Seeds Best.jpg" alt="Mustard Seeds">
        <h4>Mustard Seeds (Tori)</h4>
        <p>Premium quality mustard seeds grown organically, ideal for cooking and pickling.</p>
      </div>
      <div class="product">
        <img src="/mnt/data/Kalo Nuniya rice Nice.jpg" alt="Kalo Nuniya Rice">
        <h4>Kalo Nuniya (Black Sticky Rice)</h4>
        <p>Rare Himalayan black rice, rich in antioxidants and tradition.</p>
      </div>
      <div class="product">
        <img src="/mnt/data/Kurilo.webp" alt="Asparagus">
        <h4>Kurilo (Asparagus)</h4>
        <p>Delicious and nutritious asparagus harvested with care and freshness.</p>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1567306226416-28f0efdc88ce" alt="Organic Lemons">
        <h4>Organic Lemons</h4>
        <p>Fresh, juicy lemons grown without chemicals—perfect for health and flavor.</p>
      </div>
      <div class="product">
        <img src="https://images.unsplash.com/photo-1584367369513-7456353e776b" alt="Aalas Flax Seeds">
        <h4>Aalas (Flax Seeds)</h4>
        <p>Nutrient-rich flax seeds packed with Omega-3, fiber and natural oils.</p>
      </div>
    </div>
  </section>

  <section id="contact" class="section">
    <h3>Contact Us</h3>
    <p>📍 Bhadrapur, Jhapa, Nepal</p>
    <p>📞 +977-98XXXXXXXX</p>
    <p>📧 tajafarms@example.com</p>
  </section>

  <footer>
    <p>&copy; 2025 Taja Farms. Grown with love in Jhapa.</p>
  </footer>
</body>
</html>
