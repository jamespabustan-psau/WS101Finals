<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title> Joana Dental Clinic </title>
  <link rel="stylesheet" href="website.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
</head>
<body>

  <nav class="navbar">
    <img src="JoanaLogo.jpg" alt="Joana Dental Clinic Logo" class="clinic-logo">
    <h1>Joana's Dental Clinic</h1>

    <div class="hamburger" onclick="toggleMenu()">&#9776;</div>
    <ul class="nav-links" id="navLinks">
      <li><a href="#home"> Home </a></li>
      <li><a href="#about"> About Us </a></li>
      <li><a href="#services"> Services </a></li>
      <li><a href="#faqs"> FAQs </a></li>
      <li><a href="#contact"> Contact Us </a></li>
    </ul>
  </nav>

  <header id="home">
    <div class="header-content">
      <h2 class="slogan-heading"> Smile Brighter, Live Better </h2>
      <h1> A WONDERFUL SMILE </h1>
      <a href="#appointment" class="btn"> Book Appointment </a>
    </div>
  </header>

  <section id="about" class="about-section">
    <div class="about-text">
      <h2 class="about-us-heading">About Us</h2>
      <p>
        Joana Lyn Salunga, widely known as Dr. Joana Lyn, is the proud owner of Joana's Dental Clinic. She is a successful and driven individual who has established two branches of her clinic. Dr. Joana began her career and business journey in 2023, the year she opened her first clinic in Balibago, Angeles, Pampanga. Later, she expanded her practice by opening a second branch in Santa Cruz, Magalang, Pampanga.
        <br><br>
        She studied dentistry at Centro Escolar University and pursued private studies to become a licensed dentist. Dr. Joana prefers to work independently, which inspired her to choose a career where she could be her own boss.
      </p>
    </div>

    <div class="about-image-container">
      <div class="image-wrapper">
        <a href="https://www.facebook.com/DrJoanaLyn" target="_blank">
          <img src="Joana.jpg" alt="Dr. Joana Lyn" class="about-image">
        </a>
        <span class="doctor-name">Dr. Joana Lyn</span>
      </div>
    </div>
  </section>

  <section class="clinic-overview">
    <h2>Our Clinic Facilities</h2>
    <div class="facility-gallery">
      <div class="facility-item">
        <img src="Dentalchair.jpg" alt="Dental Chair">
        <h3>Dental Chair</h3>
        <p>This is where dental procedures are performed comfortably.</p>
      </div>

      <div class="facility-item">
        <img src="Reception.jpg" alt="Reception Area">
        <h3>Reception Area</h3>
        <p>Here is where patients check in and settle payments after their appointment.</p>
      </div>

      <div class="facility-item">
        <img src="Certificates.jpg" alt="Certificates">
        <h3>Certificates & Credentials</h3>
        <p>We proudly display our dentist's professional achievements and licenses.</p>
      </div>
    </div>
  </section>

  <section id="clinic-location" class="about-section">
    <div class="about-text">
      <h2 class="clinic-location-heading">Clinic Location</h2>

      <div class="branch-container">
        <div class="branch">
          <img src="balibago.jpg" alt="Balibago Branch Map" class="branch-image">
          <p>
            One of our branches is located in 
            <a href="https://maps.app.goo.gl/iRmh1uyqA99PKr2z6" target="_blank"><strong>Balibago, Angeles, Pampanga</strong></a>.
          </p>
        </div>

        <div class="branch">
          <img src="Magalang.jpg" alt="Magalang Branch Map" class="branch-image">
          <p>
            The other branch is located in 
            <a href="https://maps.app.goo.gl/fiC7RPxtE6rMzrjK7" target="_blank"><strong>Magalang, Pampanga</strong></a>, on the 2nd floor near Chowking.
          </p>
        </div>
      </div>
    </div>
  </section>

  <section id="services" class="about-us-services">
    <h2>Services</h2>
    <div class="services-container">
      <div class="service-card">
        <img src="Teeth Cleaning.jpg" alt="Teeth Cleaning">
        <h3 class="dental-services">Teeth Cleaning</h3>
        <p>Professional teeth cleaning to maintain oral health and prevent gum disease.</p>
      </div>

      <div class="service-card">
        <img src="Filling.jpg" alt="Dental Filling">
        <h3 class="dental-services">Filling (Pasta)</h3>
        <p>High-quality dental fillings to restore decayed or damaged teeth.</p>
      </div>

      <div class="service-card">
        <img src="Veneers.jpg" alt="Dental Veneers">
        <h3 class="dental-services">Veneers</h3>
        <p>Custom-made veneers to enhance the appearance of your smile.</p>
      </div>

      <div class="service-card">
        <img src="Braces.jpg" alt="Dental Braces">
        <h3 class="dental-services">Braces</h3>
        <p>Orthodontic solutions to align your teeth for a healthier bite and better aesthetics.</p>
      </div>

      <div class="service-card">
        <img src="Teeth Whitening.jpg" alt="Teeth Whitening">
        <h3 class="dental-services">Teeth Whitening</h3>
        <p>Safe and effective treatments for a brighter, whiter smile.</p>
      </div>
    </div>
  </section>

  <section id="faqs" class="about-faqs">
    <h2 class="faq-title">Frequently Asked Questions</h2>
    <div class="faq-grid">
      <div class="faq-item">
        <div class="faq-question">What services do you offer?</div>
        <div class="faq-answer">We offer Teeth Cleaning, Filling (Pasta), Veneers, Braces, and Teeth Whitening.</div>
      </div>

      <div class="faq-item">
        <div class="faq-question">Do I need to make an appointment before visiting?</div>
        <div class="faq-answer">No, we accept walk-ins.</div>
      </div>

      <div class="faq-item">
        <div class="faq-question">Do you accept walk-ins?</div>
        <div class="faq-answer">Yes, we accept walk-ins depending on dentist availability, but appointments are prioritized.</div>
      </div>

      <div class="faq-item">
        <div class="faq-question">What are your clinic hours?</div>
        <div class="faq-answer">Our clinic is open from 9:00 AM to 5:30 PM on Tuesday, Thursday, and Friday.</div>
      </div>

      <div class="faq-item">
        <div class="faq-question">Where is your clinic located?</div>
        <div class="faq-answer">We have two branches: one in Balibago, Angeles, and another in Santa Cruz, Magalang.</div>
      </div>

      <div class="faq-item">
        <div class="faq-question">What modes of payment does your clinic accept?</div>
        <div class="faq-answer">Our clinic accepts Cash, Bank Transfer, and mobile payments via GCash.</div>
      </div>
    </div>
  </section>

  <footer id="contact">
    <div class="footer-content">
      <h2>Contact Us</h2>
      <p><i class="fas fa-map-marker-alt"></i> <strong>1st Branch:</strong> 1911 McArthur Highway, Balibago, Angeles City, Pampanga<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Almalel Bldg, 2nd Floor, Unit 5</p>
      <p><i class="fas fa-map-marker-alt"></i> <strong>2nd Branch:</strong> Marvea Subd, Sta. Cruz, Magalang, Pampanga, 2009</p>
      <p><i class="fas fa-map"></i> <strong>Service Areas:</strong> Dau · Cutud · Angeles City · Mabalacat · Magalang · San Fernando</p>
      <p><i class="fas fa-phone"></i> <strong>Mobile:</strong> <a href="tel:+639914221860">0991 422 1860</a></p>
      <p><i class="fas fa-envelope"></i> <strong>Email:</strong> <a href="mailto:prosmilebydrjoana@gmail.com">prosmilebydrjoana@gmail.com</a></p>
      <p><i class="fab fa-instagram"></i> <strong>Instagram:</strong> <a href="https://www.instagram.com/docjoanadental_clinic" target="_blank">@docjoanadental_clinic</a></p>
    </div>

    <div class="footer-bottom">
      <p>&copy; 2025 Joana's Dental Clinic. All rights reserved.</p>
    </div>
  </footer>

  <script>
    function toggleMenu() {
      const navLinks = document.getElementById("navLinks");
      navLinks.classList.toggle("active");
    }
  </script>

</body>
</html>


