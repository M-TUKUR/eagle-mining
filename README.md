<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Eagle Mining Ltd</title>

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f4f6f8;
      color: #333;
    }

    header {
      background: #1b1b1b;
      color: #fff;
      padding: 20px;
      text-align: center;
    }

    nav a {
      color: #fff;
      margin: 0 12px;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    .hero {
      background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)),
      url("https://images.unsplash.com/photo-1581091870627-3f5b94a5a2b2");
      background-size: cover;
      background-position: center;
      color: #fff;
      padding: 80px 20px;
      text-align: center;
    }

    .hero h1 {
      font-size: 42px;
    }

    .container {
      padding: 40px 20px;
      max-width: 1100px;
      margin: auto;
    }

    .departments {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .card {
      background: #fff;
      padding: 25px;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }

    .card h3 {
      color: #0a5c36;
    }

    .advert {
      background: #0a5c36;
      color: #fff;
      padding: 35px;
      text-align: center;
      border-radius: 8px;
      margin: 40px 0;
    }

    footer {
      background: #1b1b1b;
      color: #ccc;
      text-align: center;
      padding: 15px;
    }
  </style>
</head>

<body>

<header>
  <h2>Eagle Mining Ltd</h2>
  <nav>
    <a href="#home">Home</a>
    <a href="#departments">Departments</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section class="hero" id="home">
  <h1>Responsible & Sustainable Mining</h1>
  <p>Exploration • Extraction • Processing</p>
</section>

<section class="container" id="departments">
  <h2>Our Departments</h2>

  <div class="departments">
    <div class="card">
      <h3>Exploration Department</h3>
      <p>Geological surveys, drilling analysis, and resource evaluation.</p>
    </div>

    <div class="card">
      <h3>Mining Operations</h3>
      <p>Extraction, blasting, equipment handling, and site management.</p>
    </div>

    <div class="card">
      <h3>Processing & Refining</h3>
      <p>Crushing, separation, and mineral refinement.</p>
    </div>

    <div class="card">
      <h3>Health, Safety & Environment (HSE)</h3>
      <p>Safety compliance and environmental protection.</p>
    </div>

    <div class="card">
      <h3>Logistics & Supply Chain</h3>
      <p>Transportation, storage, and export coordination.</p>
    </div>

    <div class="card">
      <h3>Administration & Finance</h3>
      <p>HR, finance, procurement, and administration.</p>
    </div>
  </div>
</section>

<section class="container">
  <div class="advert">
    <h2>Advertisement Space</h2>
    <p>Mining equipment • Investors • Service providers</p>
  </div>
</section>

<section class="container" id="about">
  <h2>About Us</h2>
  <p>
    Eagle Mining Ltd is committed to ethical mining practices, community
    development, and sustainable resource management.
  </p>
</section>

<section class="container" id="contact">
  <h2>Contact Us</h2>
  <p>Email: info@eaglemining.com</p>
  <p>Phone: +234 800 000 0000</p>
</section>

<footer>
  © 2026 Eagle Mining Ltd. All Rights Reserved.
</footer>

</body>
</html>
