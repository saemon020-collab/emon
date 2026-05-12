# emon
My T-shirt Store Website
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>TrashForm Bangladesh - Customized T-Shirts</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f5f5f5;
      color: #333;
    }
    header {
      background-color: #222;
      color: white;
      padding: 15px 20px;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }
    header h1 {
      margin: 0;
    }
    nav a {
      color: white;
      margin-left: 15px;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      background: url('https://i.imgur.com/ILONbYv.jpg') center/cover no-repeat;
      height: 300px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-size: 1.8rem;
      text-align: center;
      padding: 0 20px;
    }
    .container {
      max-width: 1100px;
      margin: 20px auto;
      padding: 0 20px;
    }
    .brand-info {
      text-align: center;
      margin-bottom: 30px;
    }
    .brand-info blockquote {
      font-style: italic;
      font-size: 1.2rem;
      color: #555;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fill,minmax(200px,1fr));
      gap: 20px;
    }
    .product-card {
      background: white;
      padding: 15px;
      box-shadow: 0 0 8px rgba(0,0,0,0.1);
      border-radius: 8px;
      text-align: center;
    }
    .product-card img {
      max-width: 100%;
      border-radius: 6px;
    }
    footer {
      background-color: #222;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
    .contact-info {
      margin-top: 40px;
      background: white;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 8px rgba(0,0,0,0.1);
    }
    .contact-info h2 {
      text-align: center;
      margin-bottom: 15px;
    }
    .contact-info p {
      margin: 8px 0;
      font-size: 1rem;
      text-align: center;
    }
    .btn-contact {
      display: inline-block;
      margin-top: 10px;
      background-color: #0078ff;
      color: white;
      padding: 10px 25px;
      border-radius: 4px;
      text-decoration: none;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <header>
    <h1>TrashForm Bangladesh</h1>
    <nav>
      <a href="#products">Products</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    BRING YOUR THOUGHTS INTO YOUR T-SHIRTS! Customized Quality T-Shirts
  </section>

  <main class="container">
    <section class="brand-info">
      <h2>Your Personality, Translated Into Style</h2>
      <blockquote>"Your personality, translated into style."</blockquote>
      <p><strong>Location:</strong> Mirpur 1, Dhaka, Bangladesh, 1216</p>
      <p><strong>Phone:</strong> 01745-123333</p>
      <p><strong>Email:</strong> <a href="mailto:sarowarefti51@gmail.com">sarowarefti51@gmail.com</a></p>
    </section>

    <section id="products">
      <h2>Our Customized T-Shirts</h2>
      <div class="products">
        <div class="product-card">
          <img src="https://i.imgur.com/JuSRKhT.jpg" alt="SpongeBob T-Shirt" />
          <h3>SpongeBob Custom T-Shirt</h3>
        </div>
        <div class="product-card">
          <img src="https://i.imgur.com/4XrXQV7.jpg" alt="White Pocket T-Shirt" />
          <h3>White Pocket Design</h3>
        </div>
        <div class="product-card">
          <img src="https://i.imgur.com/oBxoIDi.jpg" alt="Pink Printed T-Shirt" />
          <h3>Pink Printed T-Shirt</h3>
        </div>
        <div class="product-card">
          <img src="https://i.imgur.com/IohJzgn.jpg" alt="Black Rose Print T-Shirt" />
          <h3>Black Rose Print</h3>
        </div>
      </div>
    </section>

    <section id="contact" class="contact-info">
      <h2>Contact Us</h2>
      <p>Phone: 01745-123333</p>
      <p>Email: <a href="mailto:sarowarefti51@gmail.com">sarowarefti51@gmail.com</a></p>
      <p>Facebook: <a href="https://facebook.com/TrashFormBangladesh" target="_blank">TrashForm Bangladesh</a></p>
      <a href="https://m.me/TrashFormBangladesh" target="_blank" class="btn-contact">Message Us on Facebook</a>
    </section>
  </main>

  <footer>
    &copy; 2024 TrashForm Bangladesh | Customized T-Shirts Made For You
  </footer>
</body>
</html>
