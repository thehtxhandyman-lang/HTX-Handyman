<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>The HTX Handyman</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f4f4f4;
      color: #333;
    }

    header {
      background: #111;
      color: white;
      text-align: center;
      padding: 20px;
    }

    header img {
      max-width: 250px;
    }

    .container {
      max-width: 1000px;
      margin: auto;
      padding: 20px;
    }

    h1, h2 {
      text-align: center;
    }

    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 15px;
      margin-top: 20px;
    }

    .service-box {
      background: white;
      padding: 15px;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }

    .qr-section {
      text-align: center;
      margin-top: 40px;
      background: white;
      padding: 20px;
      border-radius: 8px;
    }

    .qr-section img {
      width: 200px;
      margin-top: 10px;
    }

    footer {
      text-align: center;
      padding: 15px;
      background: #111;
      color: white;
      margin-top: 30px;
    }

    .btn {
      display: inline-block;
      margin-top: 10px;
      padding: 12px 20px;
      background: #c0392b;
      color: white;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
    }

  </style>
</head>
<body>

<header>
  <!-- Replace logo path if needed -->
  <img src="logo.png" alt="HTX Handyman Logo">
  <h1>The HTX Handyman</h1>
  <p>Reliable. Skilled. Professional.</p>
</header>

<div class="container">

  <h2>Our Services</h2>

  <div class="services">
    <div class="service-box">Drywall Repair</div>
    <div class="service-box">Minor Plumbing</div>
    <div class="service-box">Painting</div>
    <div class="service-box">Appliance Repair & Installation</div>
    <div class="service-box">Furniture Assembly</div>
    <div class="service-box">Fence Installation & Repair</div>
    <div class="service-box">Doorbell Installation</div>
    <div class="service-box">Camera Installation</div>
    <div class="service-box">Door Installation & Repair</div>
    <div class="service-box">Light Fixture Replacement</div>
    <div class="service-box">Switch & Outlet Replacement</div>
    <div class="service-box">Washer & Dryer Installation</div>
    <div class="service-box">Water Softener Repair & Installation</div>
  </div>

  <div class="qr-section">
    <h2>Scan here to chat with a professional today!</h2>

    <!-- QR Code that opens SMS -->
    <img src="https://chart.googleapis.com/chart?chs=250x250&cht=qr&chl=sms:3469414179" alt="QR Code">

    <br>

    <a class="btn" href="sms:3469414179">Text Now</a>
  </div>

</div>

<footer>
  <p>© 2026 The HTX Handyman | Houston, TX</p>
</footer>

</body>
</html>
