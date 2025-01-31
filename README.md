<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Amit Kumar - Fitness Coach</title>
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
  <style>
    /* General Styles */
    body {
      font-family: 'Poppins', sans-serif;
      margin: 0;
      padding: 0;
      background: linear-gradient(135deg, #1a1a2e, #16213e);
      color: #fff;
      overflow-x: hidden;
    }

    h1, h2, h3 {
      font-weight: 600;
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    /* Floating WhatsApp Icon */
    .whatsapp-float {
      position: fixed;
      bottom: 20px;
      right: 20px; /* Moved to the right */
      background: #25d366; /* Green color */
      color: #fff;
      width: 50px;
      height: 50px;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 24px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
      animation: float 3s ease-in-out infinite, glow 2s infinite alternate;
      z-index: 1000;
    }

    @keyframes float {
      0% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
      100% { transform: translateY(0); }
    }

    @keyframes glow {
      0% { box-shadow: 0 0 10px #25d366; }
      100% { box-shadow: 0 0 20px #25d366; }
    }

    /* Welcome Pop-up */
    .welcome-popup {
      position: fixed;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      background: #ffffff; /* White background */
      color: #333; /* Dark grey text */
      padding: 40px;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
      text-align: center;
      z-index: 1001;
      animation: fadeIn 1s ease-in-out;
      width: 80%; /* Broad pop-up */
      max-width: 600px; /* Maximum width */
    }

    .welcome-popup h2 {
      font-size: 2rem;
      margin-bottom: 20px;
    }

    .welcome-popup p {
      font-size: 1.2rem;
      margin-bottom: 30px;
    }

    .welcome-popup button {
      background: #ff6f61; /* Coral color */
      color: #fff;
      border: none;
      padding: 10px 20px;
      border-radius: 5px;
      cursor: pointer;
      font-size: 1rem;
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    /* Announcement Section */
    .announcement {
      text-align: center;
      padding: 20px;
      background: #ff6f61; /* Coral color */
      color: #fff;
      margin: 20px 0;
    }

    .announcement h2 {
      font-size: 1.5rem;
      margin-bottom: 10px;
    }

    .announcement p {
      font-size: 1rem;
    }

    /* Background Content */
    .content {
      transition: transform 0.5s ease;
    }

    .content.slide-up {
      transform: translateY(-100vh); /* Slide up and disappear */
    }

    .content.slide-down {
      transform: translateY(0); /* Slide back down */
    }

    /* Header Section */
    .header {
      text-align: center;
      padding: 100px 20px;
      background: linear-gradient(135deg, #1a1a2e, #16213e);
      position: relative;
      overflow: hidden;
    }

    .header h1 {
      font-size: 2.5rem;
      margin-bottom: 20px;
      animation: fadeIn 2s ease-in-out;
    }

    .header p {
      font-size: 1.2rem;
      margin-bottom: 30px;
      animation: fadeIn 3s ease-in-out;
    }

    /* Benefits Section */
    .benefits {
      padding: 80px 20px;
      text-align: center;
      background: #16213e;
    }

    .benefits h2 {
      font-size: 2rem;
      margin-bottom: 40px;
    }

    .benefits .icon {
      font-size: 3rem;
      margin-bottom: 20px;
      animation: float 3s ease-in-out infinite;
    }

    /* Testimonials Section */
    .testimonials {
      padding: 80px 20px;
      text-align: center;
      background: #1a1a2e;
      overflow: hidden;
    }

    .testimonials h2 {
      font-size: 2rem;
      margin-bottom: 40px;
    }

    .testimonial-container {
      display: flex;
      overflow-x: auto;
      scroll-behavior: smooth;
      padding-bottom: 20px;
    }

    .testimonial-card {
      background: #16213e;
      padding: 20px;
      border-radius: 10px;
      margin: 0 15px;
      min-width: 280px; /* Moderate size */
      max-width: 300px; /* Maximum width */
      text-align: left;
      animation: fadeIn 2s ease-in-out;
    }

    .testimonial-card p {
      font-size: 1rem;
      margin-bottom: 10px;
    }

    .testimonial-card span {
      font-size: 0.9rem;
      color: #ff6f61;
    }

    /* Payment Section */
    .payment {
      padding: 80px 20px;
      text-align: center;
      background: #16213e;
    }

    .payment h2 {
      font-size: 2rem;
      margin-bottom: 20px;
    }

    .payment-box {
      background: #1a1a2e;
      padding: 20px;
      border-radius: 10px;
      max-width: 300px;
      margin: 0 auto;
    }

    .payment-box p {
      font-size: 1rem;
      margin-bottom: 20px;
    }

    .payment-box button {
      background: #ff6f61; /* Coral color */
      color: #fff;
      border: none;
      padding: 10px 20px;
      border-radius: 5px;
      cursor: pointer;
    }

    /* Footer Section */
    .footer {
      padding: 20px;
      text-align: center;
      background: #1a1a2e;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

  <!-- Floating WhatsApp Icon -->
  <a href="https://wa.me/918210145599" class="whatsapp-float">
    <i class="fab fa-whatsapp"></i>
  </a>

  <!-- Welcome Pop-up -->
  <div id="welcomePopup" class="welcome-popup">
    <h2>Welcome to Amit Kumar's Fitness Coaching!</h2>
    <p>We’re thrilled to have you here. Let’s embark on a journey to transform your health and achieve your fitness goals together. You’re in great hands!</p>
    <button onclick="closePopup()">Thanks</button>
  </div>

  <!-- Announcement Section -->
  <div class="announcement">
    <h2>Special Offer!</h2>
    <p>Get 2 free Zoom live classes when you sign up today. Don’t miss this opportunity to transform your health!</p>
  </div>

  <!-- Background Content -->
  <div id="content" class="content slide-up">
    <!-- Header Section -->
    <div class="header">
      <h1>Transform Your Health with Amit Kumar</h1>
      <p>Lose weight, manage diseases like Thyroid, PCOD, PCOS, Hypertension, and Diabetes, and achieve your fitness goals with personalized coaching.</p>
    </div>

    <!-- Benefits Section -->
    <div class="benefits">
      <h2>Why Choose My Coaching?</h2>
      <div class="icon">💪</div>
      <p>Personalized fitness plans tailored to your needs.</p>
      <div class="icon">🏥</div>
      <p>Expert guidance for weight loss and disease management.</p>
      <div class="icon">📈</div>
      <p>Proven results with regular sessions and disciplined routines.</p>
    </div>
<!-- Add this new section below the Benefits section -->
<div class="results">
  <h2>Client Transformations</h2>
  <div class="results-container">
    <!-- Before & After Photos -->
    <div class="result-slide">
      <img src="https://raw.githubusercontent.com/Technile/Fitness/main/IMG-20250130-WA0024.jpg" alt="Transformation 1">
    </div>
    <div class="result-slide">
      <img src="https://raw.githubusercontent.com/Technile/Fitness/main/IMG-20250130-WA0025.jpg" alt="Transformation 2">
    </div>
    <div class="result-slide">
      <img src="https://raw.githubusercontent.com/Technile/Fitness/main/IMG-20250130-WA0026.jpg" alt="Transformation 3">
    </div>
    <div class="result-slide">
      <img src="https://raw.githubusercontent.com/Technile/Fitness/main/IMG-20250130-WA0027.jpg" alt="Transformation 4">
    </div>
    <div class="result-slide">
      <img src="https://raw.githubusercontent.com/Technile/Fitness/main/IMG-20250130-WA0010.jpg" alt="Transformation 5">
    </div>
    <div class="result-slide">
      <img src="https://raw.githubusercontent.com/Technile/Fitness/main/IMG-20250130-WA0009.jpg" alt="Transformation 6">
    </div>
    <div class="result-slide">
      <img src="https://raw.githubusercontent.com/Technile/Fitness/main/IMG-20250130-WA0008.jpg" alt="Transformation 7">
    </div>
    <div class="result-slide">
      <img src="https://raw.githubusercontent.com/Technile/Fitness/main/IMG-20250130-WA0004.jpg" alt="Transformation 8">
    </div>
    <div class="result-slide">
      <img src="https://raw.githubusercontent.com/Technile/Fitness/main/IMG-20250130-WA0007.jpg" alt="Transformation 9">
    </div>
  </div>
</div>

<!-- Add this CSS to your style section -->
<style>
  .results {
    padding: 80px 20px;
    text-align: center;
    background: #1a1a2e;
  }

  .results h2 {
    font-size: 2rem;
    margin-bottom: 40px;
  }

  .results-container {
    display: flex;
    overflow-x: auto;
    scroll-behavior: smooth;
    gap: 20px;
    padding: 20px 0;
  }

  .result-slide {
    min-width: 80vw;
    height: 60vh;
    flex-shrink: 0;
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
  }

  .result-slide img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform 0.3s ease;
  }

  .result-slide:hover img {
    transform: scale(1.05);
  }

  /* For desktop screens */
  @media (min-width: 768px) {
    .result-slide {
      min-width: 600px;
      height: 70vh;
    }
  }
</style>
    <!-- Testimonials Section -->
    <div class="testimonials">
      <h2>What My Clients Say</h2>
      <div class="testimonial-container" id="testimonialContainer">
        <div class="testimonial-card">
          <p>"Thanks to Amit, I lost 10 kg in 3 months and managed my thyroid levels effectively. Highly recommended!"</p>
          <span>– Priya S.</span>
        </div>
        <div class="testimonial-card">
          <p>"His sessions are life-changing! My PCOD symptoms have improved significantly."</p>
          <span>– Riya M.</span>
        </div>
        <div class="testimonial-card">
          <p>"Amit’s guidance helped me control my blood sugar levels and lose weight. Thank you!"</p>
          <span>– Rajesh K.</span>
        </div>
        <!-- Add more testimonials here -->
        <div class="testimonial-card">
          <p>"I feel more energetic and confident after joining Amit's sessions. Highly recommended!"</p>
          <span>– Anjali R.</span>
        </div>
        <div class="testimonial-card">
          <p>"Amit's personalized plans helped me achieve my fitness goals faster than I expected."</p>
          <span>– Vikram S.</span>
        </div>
        <div class="testimonial-card">
          <p>"The best decision I made for my health was joining Amit's coaching program."</p>
          <span>– Neha P.</span>
        </div>
        <!-- Add 20 more testimonials similarly -->
      </div>
    </div>

    <!-- Payment Section -->
    <div class="payment">
      <h2>Start Your Journey Today</h2>
      <div class="payment-box">
        <p>Make a payment via UPI to get started:</p>
        <button onclick="copyUPI()">Copy UPI ID: amit4967@okicici</button>
      </div>
    </div>

    <!-- Footer Section -->
    <div class="footer">
      <p>© 2023 Amit Kumar. All rights reserved.</p>
      <p>Disclaimer: Results may vary based on individual effort and consistency.</p>
      <p>Contact only via WhatsApp: +91 8210145599.</p>
    </div>
  </div>

  <script>
    // Welcome Pop-up Script
    function closePopup() {
      document.getElementById('welcomePopup').style.display = 'none';
      document.getElementById('content').classList.remove('slide-up');
      document.getElementById('content').classList.add('slide-down');
    }

    // Show pop-up on page load
    window.onload = function() {
      document.getElementById('welcomePopup').style.display = 'block';
      document.getElementById('content').classList.add('slide-up');
    };

    // Copy UPI ID
    function copyUPI() {
      const upiId = 'amit4967@okicici';
      navigator.clipboard.writeText(upiId).then(() => {
        alert('UPI ID copied to clipboard: ' + upiId);
      });
    }

    // Automatic Scrolling for Testimonials
    const testimonialContainer = document.getElementById('testimonialContainer');
    let scrollAmount = 0;

    setInterval(() => {
      scrollAmount += 300; // Adjust scroll speed
      if (scrollAmount >= testimonialContainer.scrollWidth) {
        scrollAmount = 0; // Reset scroll to start
      }
      testimonialContainer.scrollTo({
        left: scrollAmount,
        behavior: 'smooth'
      });
    }, 5000); // Adjust scroll interval (5 seconds)
  </script>

</body>
</html>
