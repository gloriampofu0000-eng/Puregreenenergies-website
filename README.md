<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>PureGreenEnergies Pty (Ltd)</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; line-height: 1.6; }
    header { background: #1b5e20; color: white; text-align: center; padding: 2rem 1rem; }
    header h1 { margin: 0; font-size: 2rem; }
    header p { margin-top: 0.5rem; font-size: 1.2rem; }
    section { padding: 2rem; max-width: 900px; margin: auto; }
    h2 { color: #1b5e20; }
    .cta-btn { display: inline-block; background: #388e3c; color: white; padding: 0.8rem 1.2rem; margin-top: 1rem; text-decoration: none; border-radius: 5px; }
    .cta-btn:hover { background: #2e7d32; }
    form { display: flex; flex-direction: column; }
    form input, form textarea { padding: 0.8rem; margin-bottom: 1rem; border: 1px solid #ccc; border-radius: 5px; }
    form button { background: #388e3c; color: white; padding: 0.8rem; border: none; border-radius: 5px; cursor: pointer; }
    form button:hover { background: #2e7d32; }
    footer { text-align: center; background: #1b5e20; color: white; padding: 1rem; margin-top: 2rem; }
    .product-image { display: block; max-width: 300px; margin: 1rem auto; border: 2px solid #ccc; border-radius: 5px; }
  </style>
</head>
<body>
  <header>
    <h1>PureGreenEnergies Pty (Ltd)</h1>
    <p>Affordable & Sustainable Biodiesel Solutions for Africa</p>
  </header>

  <section>
    <h2>About Us</h2>
    <p>PureGreenEnergies Pty (Ltd) is a Zimbabwean-South African partnership under a group of investment companies. We manufacture and sell biodiesel while collecting used cooking oil from restaurants and businesses. Our mission is to provide affordable, sustainable fuel alternatives for Africa’s energy needs — especially in regions dependent on diesel-powered generators.</p>
  </section>

  <section>
    <h2>Our Products</h2>
    <p>We supply all forms of biodiesel, bulk delivery, fleet fueling, and renewable energy consulting. Our featured innovation is the <strong>Biodiesel Air Flow Stove</strong>, designed for efficiency and eco-friendly cooking.</p>
    <img src="https://via.placeholder.com/300x200.png?text=Biodiesel+Stove" alt="Biodiesel Stove" class="product-image">
  </section>

  <section>
    <h2>Contact Us</h2>
    <p>Email: muziwandiledlamini75@gmail.com</p>
    <p>Phone: +27 67 239 6080</p>
    <p>Locations: Johannesburg & Harare</p>
    <form name="contact" method="POST" data-netlify="true">
      <input type="text" name="name" placeholder="Your Name" required>
      <input type="email" name="email" placeholder="Your Email" required>
      <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 PureGreenEnergies Pty (Ltd). All rights reserved.</p>
  </footer>
</body>
</html>
