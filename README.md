<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Animal Help & Care</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: 'Segoe UI', sans-serif;
      background: #fafafa;
      color: #333;
    }

    /* Header */
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px 30px;
      background-color: #fff;
      border-bottom: 1px solid #ddd;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    .logo {
      font-size: 1.8em;
      font-weight: bold;
      color: #e74c3c;
    }
    nav ul {
      list-style: none;
      display: flex;
      gap: 25px;
    }
    nav a {
      text-decoration: none;
      color: #333;
      font-weight: 500;
      padding: 8px;
    }

    .buttons {
      display: flex;
      gap: 10px;
    }
    .btn {
      padding: 8px 16px;
      border: none;
      cursor: pointer;
      font-weight: bold;
      border-radius: 4px;
    }
    .donate { background: #f39c12; color: white; }
    .adopt { background: #27ae60; color: white; }

    /* Hero Section */
    .hero {
      height: 400px;
      background: url('https://www.carecredit.com/sites/cc/image/article_hero_lab_retriever.jpg') center/cover no-repeat;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      position: relative;
      color: white;
    }
    .hero::after {
      content: "";
      position: absolute;
      top: 0; left: 0; right: 0; bottom: 0;
      background: rgba(0, 0, 0, 0.4);
      z-index: 1;
    }
    .hero-content {
      position: relative;
      z-index: 2;
    }
    .hero h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
    }
    .hero p {
      font-size: 1.2rem;
      margin-bottom: 20px;
    }
    .hero .btn {
      background-color: #3498db;
      color: white;
    }

    /* News Section */
    .news {
      padding: 50px 30px;
      background: #fff;
      text-align: center;
    }
    .news h2 {
      margin-bottom: 30px;
      font-size: 1.8rem;
    }
    .news-item {
      text-align: left;
      max-width: 800px;
      margin: 0 auto 15px;
      font-size: 1rem;
    }

    /* Footer */
    footer {
      background: #2c2c2c;
      color: #ccc;
      text-align: center;
      padding: 20px;
    }
    footer a {
      color: #ccc;
      margin: 0 10px;
      text-decoration: none;
    }
  </style>
</head>
<body>

  <header>
<img src="https://sdmntprwestus2.oaiusercontent.com/files/00000000-93f8-61f8-b27e-121f44944c26/raw?se=2025-06-06T17%3A50%3A06Z&sp=r&sv=2024-08-04&sr=b&scid=ac5f2fb3-c298-5f9c-8f30-6182dab20ba7&skoid=30ec2761-8f41-44db-b282-7a0f8809659b&sktid=a48cca56-e6da-484e-a814-9c849652bcb3&skt=2025-06-06T02%3A13%3A32Z&ske=2025-06-07T02%3A13%3A32Z&sks=b&skv=2024-08-04&sig=N7bFowVUAUc/UyPaRpojehYl%2BjO%2BjAM6RpAFc1wgQso%3D" style="width:75px;height:75px;">
  <div class="logo">FurEver Care</div>
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Campaigns</a></li>
        <li><a href="#">Animals</a></li>
        <li><a href="#">News</a></li>
        <li><a href="#">Get Involved</a></li>
        <li><a href="#">About Us</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </nav>
    <div class="buttons">
      <button class="btn donate">Donate</button>
      <button class="btn adopt">Adopt</button>
    </div>
  </header>

  <section class="hero">
    <div class="hero-content">
      <h1>Pawradise Rescue</h1>
      <p>Together, let's end silent suffering</p>
      <button class="btn">Learn More</button>
    </div>
  </section>

  <section class="news">
    <h2>Latest Animal News</h2>
    <div class="news-item">
      🐾 <strong>June 6, 2025:</strong> New rescue mission saves 35 dogs from illegal breeders.
    </div>
    <div class="news-item">
      🐾 <strong>June 2, 2025:</strong> Wildlife rehab center opens new wing for orphaned foxes.
    </div>
    <div class="news-item">
      🐾 <strong>May 28, 2025:</strong> Summer care tips for street animals during heatwaves.
    </div>
  </section>

  <footer>
    © 2025 Animal Help & Care. All rights reserved. <br/>
    Follow us on: 
    <a href="#">Instagram</a> | 
    <a href="#">Facebook</a> | 
    <a href="#">LinkedIn</a>
  </footer>

</body>
</html>
