# True-trails-care-
NDIS PROVIDER, Ndis services
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>True Trails Care - Trusted NDIS Provider Queensland</title>
  <style>
    /* Reset & base */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      line-height: 1.6;
      color: #333;
      background: #f8fafc;
    }
    a {
      text-decoration: none;
      color: #005ea2;
    }
    a:hover {
      color: #023e7d;
    }

    /* Header */
    header {
      background: #005ea2;
      color: white;
      padding: 20px 0;
      text-align: center;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    header h1 {
      font-size: 2.4rem;
      margin-bottom: 5px;
      letter-spacing: 2px;
    }
    header p {
      font-size: 1.1rem;
      font-weight: 300;
    }

    /* Navigation */
    nav {
      background: #004080;
      display: flex;
      justify-content: center;
      padding: 10px 0;
      box-shadow: inset 0 -1px 0 rgba(255,255,255,0.1);
    }
    nav a {
      color: white;
      margin: 0 20px;
      font-weight: 600;
      font-size: 1rem;
      padding: 8px 0;
      border-bottom: 3px solid transparent;
      transition: border-color 0.3s ease;
    }
    nav a:hover,
    nav a.active {
      border-bottom: 3px solid #ffba08;
    }

    /* Hero Section */
    .hero {
      background: url('https://images.unsplash.com/photo-1600880291844-937e0d9fdbb5?auto=format&fit=crop&w=1350&q=80') center/cover no-repeat;
      height: 350px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-align: center;
      padding: 0 20px;
      box-shadow: inset 0 0 0 1000px rgba(0,94,162,0.6);
    }
    .hero h2 {
      font-size: 2.8rem;
      max-width: 600px;
      margin-bottom: 15px;
      letter-spacing: 1px;
    }
    .hero p {
      font-size: 1.2rem;
      max-width: 500px;
      margin: auto;
      line-height: 1.4;
    }
    .hero .btn-primary {
      background: #ffba08;
      color: #004080;
      padding: 12px 30px;
      font-weight: 700;
      border-radius: 5px;
      margin-top: 25px;
      display: inline-block;
      transition: background 0.3s ease;
    }
    .hero .btn-primary:hover {
      background: #e6a300;
    }

    /* Main Content */
    main {
      max-width: 1100px;
      margin: 40px auto;
      padding: 0 20px;
    }

    /* About Section */
    #about {
      text-align: center;
      margin-bottom: 50px;
    }
    #about h3 {
      font-size: 2rem;
      color: #005ea2;
      margin-bottom: 15px;
    }
    #about p {
      max-width: 700px;
      margin: auto;
      font-size: 1.1rem;
      color: #555;
      line-height: 1.6;
    }

    /* Services Section */
    #services {
      margin-bottom: 50px;
    }
    #services h3 {
      font-size: 2rem;
      color: #005ea2;
      text-align: center;
      margin-bottom: 30px;
    }
    .services-list {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }
    .service-item {
      background: white;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      border-radius: 8px;
      padding: 20px;
      flex: 1 1 250px;
      max-width: 280px;
      text-align: center;
      transition: transform 0.3s ease;
    }
    .service-item:hover {
      transform: translateY(-8px);
    }
    .service-item h4 {
      color: #ffba08;
      margin-bottom: 15px;
      font-weight: 700;
    }
    .service-item p {
      color: #555;
      font-size: 1rem;
      line-height: 1.4;
    }

    /* Why Choose Us Section */
    #why-choose {
      background: #e0f0ff;
      padding: 40px 20px;
      border-radius: 8px;
      margin-bottom: 50px;
      max-width: 900px;
      margin-left: auto;
      margin-right: auto;
      text-align: center;
    }
    #why-choose h3 {
      color: #005ea2;
      margin-bottom: 25px;
      font-size: 2rem;
    }
    #why-choose ul {
      list-style: none;
      padding-left: 0;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }
    #why-choose li {
      background: white;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      padding: 20px;
      border-radius: 8px;
      flex: 1 1 250px;
      max-width: 280px;
      font-weight: 600;
      color: #004080;
    }

    /* Contact Section */
    #contact {
      max-width: 600px;
      margin: 0 auto 60px auto;
      padding: 20px;
      background: white;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      border-radius: 8px;
    }
    #contact h3 {
      text-align: center;
      margin-bottom: 25px;
      color: #005ea2;
      font-size: 2rem;
    }
    #contact form {
      display: flex;
      flex-direction: column;
      gap: 15px;
    }
    #contact input, #contact textarea {
      padding: 12px;
      font-size: 1rem;
      border: 1px solid #ccc;
      border-radius: 5px;
      resize: vertical;
      transition: border-color 0.3s ease;
    }
    #contact input:focus, #contact textarea:focus {
      border-color: #005ea2;
      outline: none;
    }
    #contact button {
      background: #005ea2;
      color: white;
      border: none;
      padding: 14px;
      font-size: 1.1rem;
      border-radius: 5px;
      cursor: pointer;
      font-weight: 700;
      transition: background 0.3s ease;
    }
    #contact button:hover {
      background: #003b66;
    }

    /* Footer */
    footer {
      background: #004080;
      color: white;
      text-align: center;
      padding: 20px 10px;
      font-size: 0.9rem;
      letter-spacing: 0.5px;
    }

    /* Responsive */
    @media (max-width: 768px) {
      .services-list, #why-choose ul {
        flex-direction: column;
        align-items: center;
      }
      nav {
        flex-direction: column;
        gap: 10px;
      }
      nav a {
        margin: 0;
      }
      .hero h2 {
        font-size: 2rem;
      }
    }
  </style>
</head>
<body>

<header>
  <h1>True Trails Care</h1>
  <p>Empowering Lives through NDIS Support in Queensland</p>
</header>

<nav>
  <a href="#about" class="active">About</a>
  <a href="#services">Services</a>
  <a href="#why-choose">Why Choose Us</a>
  <a href="#contact">Contact</a>
</nav>

<section class="hero" role="img" aria-label="Caring hands supporting a person" style="background: url('https://images.unsplash.com/photo-1600880291844-937e0d9fdbb5?auto=format&fit=crop&w=1350&q=80') center/cover no-repeat; height: 350px; display: flex; align-items: center; justify-content: center; color: white; text-align: center; padding: 0 20px; box-shadow: inset 0 0 0 1000px rgba(0,94,162,0.6);">
  <div>
    <h2>Your Trusted Partner for Quality NDIS Support</h2>
    <p>Compassionate, client-focused care tailored to your needs.</p>
    <a href="#contact" class="btn-primary" style="color:#004080; background:#ffba08; padding:12px 24px; border-radius:5px; font-weight:700;">Get in Touch</a>
  </div>
</section>

<main>
  <section id="about" aria-labelledby="about-heading">
    <h3 id="about-heading">About True Trails Care</h3>
    <p>Based in Queensland, True Trails Care is dedicated to delivering person-centered NDIS services that promote independence, dignity, and community inclusion. Our experienced team understands your unique needs and works closely with you to build a meaningful support plan.</p>
  </section>

  <section id="services" aria-labelledby="services-heading">
    <h3 id="services-heading">Our NDIS Services</h3>
    <div class="services-list">
      <article class="service-item" role="region" aria-label="Daily Personal Activities service">
        <h4>Daily Personal Activities</h4>
        <p>Assisting with daily routines such as personal care, hygiene, and mobility to help you live comfortably and confidently.</p>
      </article>
      <article class="service-item" role="region" aria-label="Community Participation service">
        <h4>Community Participation</h4>
        <p>Support to engage in community, social, and recreational activities, fostering connection and wellbeing.</p>
      </article>
      <article class="service-item" role="region" aria-label="Household Tasks service">
        <h4>Household Tasks</h4>
        <p>Help with cooking, cleaning, and maintaining a safe and healthy home environment.</p>
      </article>
      <article class="service-item" role="region" aria-label="Transport Assistance service">
        <h4>Transport Assistance</h4>
        <p>Providing reliable transportation support to appointments, social events, and other activities.</p>
      </article>
      <article class="service-item" role="region" aria-label="Support Coordination service">
        <h4>Support Coordination</h4>
        <p>Helping you navigate your NDIS plan and connect with appropriate service providers.</p>
      </article>
    </div>
  </section>

  <section id="why-choose" aria-labelledby="why-choose-heading">
    <h3 id="why-choose-heading">Why Choose True Trails Care?</h3>
    <ul>
      <li>Experienced, compassionate support staff</li>
      <li>Client-centered approach tailored to your needs</li>
      <li>Fully registered NDIS provider with proven track record</li>
      <li>Flexible scheduling and transparent communication</li>
      <li>Committed to empowering independence and wellbeing</li>
    </ul>
  </section>

  <section id="contact" aria-labelledby="contact-heading">
    <h3 id="contact-heading">Get In Touch</h3>
    <form action="mailto:contact@truetrailscare.com.au" method="post" enctype="text/plain" aria-label="Contact form">
      <label for="name">Name</label>
      <input type="text" id="name" name="Name" required placeholder="Your full name" />

      <label for="email">Email</label>
      <input type="email" id="email" name="Email" required placeholder="Your email address" />

      <label for="message">Message</label>
      <textarea id="message" name="Message" rows="5" required placeholder="How can we help you?"></textarea>

      <button type="submit">Send Message</button>
    </form>
  </section>
</main>

<footer>
  <p>© 2025 True Trails Care | NDIS Registered Provider | Queensland, Australia</p>
  <p>Contact: <a href="mailto:contact@truetrailscare.com.au">contact@truetrailscare.com.au</a> | Phone: 0415 925 965</p>
</footer>

</body>
</html>
