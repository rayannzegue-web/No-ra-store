<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Noéra – Timeless Luxury Watches | Cameroon & Beyond</title>
  <meta name="description" content="Discover timeless elegance with Noéra luxury watches. Authentic, premium timepieces delivered across Cameroon and worldwide."/>
  
  <!-- Google Fonts: Elegant serif + sans-serif -->
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Montserrat:wght@300;400;600&display=swap" rel="stylesheet"/>
  
  <style>
    :root {
      --bg-dark: #0f0f0f;
      --text-light: #f5f5f5;
      --gold: #d4af37;
      --gray: #888;
    }
    * { margin:0; padding:0; box-sizing:border-box; }
    body {
      font-family: 'Montserrat', sans-serif;
      background: var(--bg-dark);
      color: var(--text-light);
      line-height: 1.6;
    }
    header {
      position: fixed;
      top: 0; left: 0; right: 0;
      background: rgba(0,0,0,0.7);
      backdrop-filter: blur(10px);
      z-index: 1000;
      padding: 1rem 5%;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    .logo {
      font-family: 'Playfair Display', serif;
      font-size: 2rem;
      color: var(--gold);
      text-decoration: none;
    }
    nav a {
      color: var(--text-light);
      margin-left: 2rem;
      text-decoration: none;
      font-weight: 500;
      transition: color 0.3s;
    }
    nav a:hover { color: var(--gold); }

    .hero {
      height: 100vh;
      background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.7)), url('https://images.unsplash.com/photo-1524592094714-0f25c5025c32?auto=format&fit=crop&q=80') center/cover no-repeat;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 0 5%;
    }
    .hero h1 {
      font-family: 'Playfair Display', serif;
      font-size: 4.5rem;
      margin-bottom: 1rem;
      color: white;
    }
    .hero p {
      font-size: 1.4rem;
      max-width: 700px;
      margin-bottom: 2rem;
      color: #ddd;
    }
    .btn {
      background: var(--gold);
      color: black;
      padding: 1rem 2.5rem;
      border: none;
      border-radius: 50px;
      font-size: 1.1rem;
      font-weight: 600;
      text-decoration: none;
      transition: all 0.3s;
    }
    .btn:hover {
      background: #fff;
      transform: translateY(-3px);
    }

    section { padding: 6rem 5%; }
    h2 {
      font-family: 'Playfair Display', serif;
      font-size: 3rem;
      text-align: center;
      margin-bottom: 3rem;
      color: var(--gold);
    }

    .products-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 2.5rem;
      max-width: 1200px;
      margin: 0 auto;
    }
    .product-card {
      background: #1a1a1a;
      border-radius: 12px;
      overflow: hidden;
      transition: transform 0.4s, box-shadow 0.4s;
      text-align: center;
    }
    .product-card:hover {
      transform: translateY(-15px);
      box-shadow: 0 20px 40px rgba(212,175,55,0.15);
    }
    .product-card img {
      width: 100%;
      height: 320px;
      object-fit: cover;
    }
    .product-info {
      padding: 1.5rem;
    }
    .product-info h3 {
      font-size: 1.4rem;
      margin-bottom: 0.5rem;
    }
    .price {
      font-size: 1.3rem;
      color: var(--gold);
      margin: 0.5rem 0;
    }
    .old-price {
      text-decoration: line-through;
      color: var(--gray);
      margin-left: 0.8rem;
      font-size: 1rem;
    }
    .btn-add {
      background: transparent;
      border: 1px solid var(--gold);
      color: var(--gold);
      padding: 0.7rem 1.5rem;
      border-radius: 50px;
      cursor: pointer;
      margin-top: 1rem;
      transition: all 0.3s;
    }
    .btn-add:hover {
      background: var(--gold);
      color: black;
    }

    footer {
      background: #000;
      padding: 3rem 5% 1.5rem;
      text-align: center;
      border-top: 1px solid #333;
    }
    .contact-info {
      margin: 1.5rem 0;
      font-size: 1.1rem;
    }
    .contact-info a {
      color: var(--gold);
      text-decoration: none;
      margin: 0 1rem;
    }
    .social a { color: white; margin: 0 1rem; font-size: 1.5rem; }
    .copyright { margin-top: 2rem; color: #666; font-size: 0.9rem; }
  </style>
</head>
<body>

  <header>
    <a href="#" class="logo">Noéra</a>
    <nav>
      <a href="#shop">Shop All</a>
      <a href="#new">New Arrivals</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Discover Timeless Elegance</h1>
    <p>Premium luxury watches crafted with precision. Serving Cameroon and customers worldwide with authenticity guaranteed.</p>
    <a href="#shop" class="btn">Shop All Watches</a>
  </section>

  <section id="new">
    <h2>New Arrivals</h2>
    <div class="products-grid">
      <!-- Replace these with your real products later -->
      <div class="product-card">
        <img src="https://images.unsplash.com/photo-1541783245831-57d6fb0926d3?auto=format&fit=crop&q=80&w=800" alt="Elegant Black Watch">
        <div class="product-info">
          <h3>Classic Chronograph</h3>
          <p class="price">XAF 85,000 <span class="old-price">XAF 120,000</span></p>
          <button class="btn-add">Order via WhatsApp</button>
        </div>
      </div>

      <div class="product-card">
        <img src="https://images.unsplash.com/photo-1523177577-2923e2f37c74?auto=format&fit=crop&q=80&w=800" alt="Gold Luxury Watch">
        <div class="product-info">
          <h3>Gold Edition Automatic</h3>
          <p class="price">XAF 145,000</p>
          <button class="btn-add">Order via WhatsApp</button>
        </div>
      </div>

      <div class="product-card">
        <img src="https://images.unsplash.com/photo-1547996160-81dfa63595aa?auto=format&fit=crop&q=80&w=800" alt="Silver Watch">
        <div class="product-info">
          <h3>Minimalist Silver</h3>
          <p class="price">XAF 65,000 <span class="old-price">XAF 95,000</span></p>
          <button class="btn-add">Order via WhatsApp</button>
        </div>
      </div>

      <!-- Add more cards as needed -->
    </div>
  </section>

  <footer id="contact">
    <h2>Contact Us</h2>
    <div class="contact-info">
      <p>Email: <a href="mailto:djinabrightly25@gmail.com">djinabrightly25@gmail.com</a></p>
      <p>WhatsApp: <a href="https://wa.me/237650589292" target="_blank">+237 650 589 292</a> (Click to chat directly)</p>
      <p>We serve Cameroon and international customers with fast, secure delivery.</p>
    </div>
    <div class="copyright">
      © 2026 Noéra – All Rights Reserved.
    </div>
  </footer>

</body>
</html>