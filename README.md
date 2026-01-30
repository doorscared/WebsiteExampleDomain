<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Website Hosting</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background: #e9f6ff;
    }

    /* NAVBAR */
    .navbar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 60px;
      background: white;
    }

    .logo {
      font-size: 22px;
      font-weight: bold;
      color: #3575d3;
    }

    .navbar nav a {
      margin-left: 20px;
      text-decoration: none;
      color: #333;
      font-size: 14px;
    }

    /* HERO SECTION */
    .hero {
      display: flex;
      justify-content: space-between;
      align-items: flex-start; /* FIX */
      gap: 40px;
      padding: 80px 60px;
    }

    .hero-text {
      max-width: 500px;
    }

    .hero-text h1 {
      font-size: 52px;
      margin-bottom: 20px;
      color: #1b1b1b;
    }

    .hero-text p {
      font-size: 16px;
      color: #444;
      margin-bottom: 30px;
      line-height: 1.5;
    }

    .cta-button {
      text-decoration: none;
    }

    .cta-button button {
      padding: 14px 28px;
      background: #3575d3;
      color: white;
      border: none;
      font-size: 16px;
      cursor: pointer;
      border-radius: 4px;
    }

    .cta-button button:hover {
      background: #285fb4;
    }

    .hero-image img {
      max-width: 450px;
      border-radius: 6px;
    }

    /* RESPONSIVE */
    @media (max-width: 900px) {
      .hero {
        flex-direction: column;
        text-align: center;
      }

      .hero-image img {
        max-width: 100%;
        margin-top: 30px;
      }
    }
  </style>
</head>

<body>

  <header class="navbar">
    <div class="logo">Space Pops</div>
    <nav>
      <a href="https://www.youtube.com/watch?v=xvFZjo5PgG0">Products</a>
      <a href="https://www.youtube.com/watch?v=xvFZjo5PgG0">Contacts</a>
      <a href="https://www.youtube.com/watch?v=xvFZjo5PgG0">Domains</a>
      <a href="https://www.youtube.com/watch?v=xvFZjo5PgG0">Email</a>
    </nav>
  </header>

  <section class="hero">
    <div class="hero-text">
      <h1>Check out our products!</h1>
      <p>
        After you order your first treat, Mind sharing some feedbacks to our
      products.
      </p>

      <a href="https://www.youtube.com/watch?v=xvFZjo5PgG0" class="cta-button">
        <button>Get Started</button>
      </a>
      
    
    <div class="hero-image">
      <img src="XXXXXXXXXX" alt="">
    </div>
  </section>

</body>
</html>
