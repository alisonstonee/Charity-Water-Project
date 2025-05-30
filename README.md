# LiveLab 4: Responsive Website
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Charity: Water - Landing Page</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      line-height: 1.6;
      color: #333;
    }

    .hero {
      background-color: #8dc2d3;
      color: #fff;
      padding: 60px 20px;
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      justify-content: space-between;
    }

    .hero-text {
      flex: 1;
      max-width: 600px;
    }

    .hero-text h1 {
      font-size: 36px;
      margin-bottom: 20px;
    }

    .hero-text p {
      font-size: 16px;
    }

    .cta-buttons {
      margin-top: 20px;
    }

    .cta-buttons a {
      text-decoration: none;
      padding: 10px 20px;
      margin-right: 10px;
      border-radius: 5px;
      font-weight: bold;
      display: inline-block;
      transition: 0.3s ease;
    }

    .cta-blue {
      background-color: white;
      color: navy;
      border: 2px solid navy;
    }

    .cta-yellow {
      background-color: #f7c948;
      color: white;
    }

    .cta-buttons a:hover {
      background-color: #ffd700;
      color: #000;
    }

    .hero-image {
      flex: 1;
      text-align: center;
    }

    .hero-image img {
      max-width: 100%;
      height: auto;
      border-radius: 10px;
    }

    .story {
      padding: 40px 20px;
      background-color: #f4f4f4;
      text-align: center;
    }

    .story h2 {
      font-size: 28px;
      margin-bottom: 10px;
    }

    .story p {
      max-width: 700px;
      margin: 0 auto;
    }

    .donate-section {
      padding: 40px 20px;
      text-align: center;
    }

    .donate-section h2 {
      font-size: 24px;
      margin-bottom: 10px;
    }

    .donate-options button {
      margin: 10px;
      padding: 10px 20px;
      border: none;
      background-color: #ffdb58;
      font-weight: bold;
      border-radius: 5px;
      cursor: pointer;
    }

    .testimonial {
      background-color: #fff;
      padding: 40px 20px;
      text-align: center;
      font-style: italic;
    }

    .impact {
      background-color: #e0f7fa;
      padding: 40px 20px;
      text-align: center;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <section class="hero">
    <div class="hero-text">
      <h1>Be the Generation that stops the Water Crisis.</h1>
      <p>100% of your donation funds clean water projects—and you’ll see your direct impact with every dollar. Watch through real-time updates, photos, and GPS coordinates. Join a transparent movement powered by purpose, not profit.</p>
      <div class="cta-buttons">
        <a href="#" class="cta-blue">Become a Monthly Donor!</a>
        <a href="#" class="cta-yellow">Change a Life Today!</a>
      </div>
    </div>
    <div class="hero-image">
      <img src="https://via.placeholder.com/400x300" alt="Hero placeholder image">
    </div>
  </section>

  <section class="story">
    <h2>Your $10 Goes Far</h2>
    <p>Just $10 can get 11,000 liters of clean water to support a family’s needs for 125 days!</p>
  </section>

  <section class="testimonial">
    <h2>Meet the People You've Helped</h2>
    <p>“Thanks to this project, my children no longer have to walk for hours to get water.” — Amina, Ethiopia</p>
  </section>

  <section class="impact">
    <h2>🌍 You've Helped 100,432 People Get Clean Water</h2>
  </section>

  <section class="donate-section">
    <h2>Choose amount to donate per month:</h2>
    <div class="donate-options">
      <button>$10</button>
      <button>$100</button>
      <button>Other Amount</button>
    </div>
  </section>
</body>
</html>
