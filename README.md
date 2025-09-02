<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Nail It Down: ToolDash</title>
  <style>
    /* Basic Reset */
    body, h1, h2, h3, p, a, form {
      margin: 0;
      padding: 0;
      font-family: 'Arial', sans-serif;
    }
    body {
      background-color: #f4f4f9;
      color: #333;
    }

    /* Header */
    header {
      background-color: #007bff;
      padding: 20px;
      text-align: center;
      color: white;
    }

    header h1 {
      margin: 0;
      font-size: 36px;
    }

    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #fff;
      font-size: 16px;
    }

    nav a:hover {
      text-decoration: underline;
    }

    /* Hero Section */
    .hero {
      background-color: #007bff;
      color: white;
      text-align: center;
      padding: 80px 20px;
    }

    .hero h2 {
      font-size: 48px;
      margin: 0;
    }

    .hero p {
      font-size: 20px;
      margin-top: 20px;
    }

    .cta-button {
      background-color: #ff5722;
      color: white;
      padding: 15px 25px;
      border: none;
      border-radius: 4px;
      cursor: pointer;
      font-size: 18px;
      text-decoration: none;
    }

    .cta-button:hover {
      background-color: #e64a19;
    }

    /* About Section */
    .about {
      padding: 60px 20px;
      text-align: center;
    }

    .about h2 {
      font-size: 32px;
      color: #333;
    }

    .about p {
      font-size: 18px;
      color: #555;
      max-width: 800px;
      margin: 20px auto;
    }

    /* Services Section */
    .services {
      background-color: #f9f9f9;
      padding: 60px 20px;
      text-align: center;
    }

    .services h2 {
      font-size: 32px;
      color: #333;
    }

    .service-card {
      background-color: white;
      border: 1px solid #ddd;
      padding: 30px;
      margin: 20px;
      border-radius: 8px;
      display: inline-block;
      width: 250px;
      text-align: center;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    }

    .service-card h3 {
      font-size: 24px;
      color: #333;
    }

    .service-card p {
      color: #555;
      font-size: 16px;
    }

    /* Contact Section */
    .contact {
      padding: 60px 20px;
      text-align: center;
    }

    .contact h2 {
      font-size: 32px;
      color: #333;
    }

    .contact form {
      max-width: 600px;
      margin: 0 auto;
    }

    .contact input, .contact textarea {
      width: 100%;
      padding: 15px;
      margin: 10px 0;
      border: 1px solid #ddd;
      border-radius: 4px;
      font-size: 16px;
    }

    .contact button {
      background-color: #007bff;
      color: white;
      padding: 15px 20px;
      border: none;
      border-radius: 4px;
      cursor: pointer;
      font-size: 16px;
    }

    .contact button:hover {
      background-color: #0056b3;
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <h1>Nail It Down: ToolDash</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- Hero Section -->
  <section class="hero" id="home">
    <h2>Transform Your Workflow with ToolDash</h2>
    <p>Get the tools you need, when you need them. Nail your projects with ease.</p>
    <a href="#services" class="cta-button">Learn More</a>
  </section>

  <!-- About Section -->
  <section class="about" id="about">
    <h2>About ToolDash</h2>
    <p>At ToolDash, we provide a wide range of tools to help you complete your projects faster and more efficiently. Whether you're working on a small home improvement project or a major construction job, we've got the right tool for you.</p>
  </section>

  <!-- Services Section -->
  <section class="services" id="services">
    <h2>Our Services</h2>
    <div class="service-card">
      <h3>Tool Rentals</h3>
      <p>Rent high-quality tools for any project, large or small.</p>
    </div>
    <div class="service-card">
      <h3>Tool Delivery</h3>
      <p>Get your tools delivered directly to your door with same-day service.</p>
    </div>
    <div class="service-card">
      <h3>Maintenance & Repair</h3>
      <p>Need a tool fixed? We offer repair services to keep you on track.</p>
    </div>
  </section>

  <!-- Contact Section -->
  <section class="contact" id="contact">
    <h2>Contact Us</h2>
    <form action="#">
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Your Email" required>
      <textarea placeholder="Your Message" rows="4" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

</body>
</html>
