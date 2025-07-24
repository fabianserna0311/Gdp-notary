# Gdp-notary
Notary
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>GDP Notary</title>
  <style>
    * { box-sizing: border-box; }
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; color: #333; background: #f9f9f9; }
    header, footer { background: #004080; color: white; padding: 1em 2em; text-align: center; }
    nav a { margin: 0 0.5em; color: white; text-decoration: none; font-weight: bold; display: inline-block; }
    nav { margin-top: 0.5em; }
    main { padding: 2em 1em; }
    section { margin-bottom: 3em; }
    h1, h2 { color: #004080; }
    .container { max-width: 800px; margin: auto; }
    .services, .contact-form, .booking-form { max-width: 600px; margin: auto; }
    label { display: block; margin-top: 1em; }
    input, textarea { width: 100%; padding: 0.5em; margin-top: 0.25em; border: 1px solid #ccc; border-radius: 4px; }
    button { margin-top: 1em; padding: 0.75em 1.5em; background: #004080; color: white; border: none; cursor: pointer; border-radius: 4px; }
    button:hover { background: #003366; }
    img.logo { max-height: 60px; display: block; margin: 0 auto 10px; }
    @media (max-width: 600px) {
      nav a { display: block; margin: 0.5em 0; }
      main { padding: 1em; }
    }
  </style>
</head>
<body>
  <header>
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e0/Simple_icon_for_a_seal_or_stamp.svg/512px-Simple_icon_for_a_seal_or_stamp.svg.png" alt="GDP Notary Logo" class="logo">
    <h1>GDP Notary</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main class="container">
    <section id="home">
      <h2>Reliable, Mobile, and Professional Notary Services</h2>
      <p>We offer certified notary services with the utmost professionalism and flexibility. Whether you need mobile notary, loan signing, or document authentication — we've got you covered.</p>
    </section>

    <section id="about">
      <h2>About Us</h2>
      <p>GDP Notary is committed to delivering reliable and timely notarizations across your area. With a focus on customer satisfaction, we ensure each client receives secure and efficient service.</p>
    </section>

    <section id="services" class="services">
      <h2>Our Services</h2>
      <ul>
        <li>Mobile Notary Public</li>
        <li>Loan Signing Agent</li>
        <li>Real Estate Document Notarization</li>
        <li>Power of Attorney and Affidavit Notarization</li>
        <li>Witness Services</li>
      </ul>
    </section>

    <section id="contact" class="contact-form">
      <h2>Contact Us</h2>
      <form>
        <label for="name">Full Name</label>
        <input type="text" id="name" name="name" required />

        <label for="email">Email</label>
        <input type="email" id="email" name="email" required />

        <label for="message">Message</label>
        <textarea id="message" name="message" rows="5"></textarea>

        <button type="submit">Send Message</button>
      </form>
    </section>

    <section class="booking-form">
      <h2>Book an Appointment</h2>
      <form>
        <label for="client-name">Name</label>
        <input type="text" id="client-name" name="client-name" required />

        <label for="client-email">Email</label>
        <input type="email" id="client-email" name="client-email" required />

        <label for="date">Preferred Date</label>
        <input type="date" id="date" name="date" required />

        <label for="time">Preferred Time</label>
        <input type="time" id="time" name="time" required />

        <label for="service">Service Needed</label>
        <input type="text" id="service" name="service" required />

        <button type="submit">Book Now</button>
      </form>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 GDP Notary. All rights reserved.</p>
  </footer>
</body>
</html>
