<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Amit Kumar - Fitness Coach</title>
  <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap">
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

    /* Header Section */
    .header {
      text-align: center;
      padding: 100px 20px;
      background: linear-gradient(135deg, #1a1a2e, #16213e);
      position: relative;
      overflow: hidden;
    }

    .header h1 {
      font-size: 3rem;
      margin-bottom: 20px;
      animation: fadeIn 2s ease-in-out;
    }

    .header p {
      font-size: 1.2rem;
      margin-bottom: 30px;
      animation: fadeIn 3s ease-in-out;
    }

    .whatsapp-button {
      display: inline-block;
      background: #25d366;
      color: #fff;
      padding: 15px 30px;
      border-radius: 50px;
      font-size: 1.2rem;
      animation: pulse 2s infinite;
    }

    .whatsapp-button:hover {
      background: #128c7e;
    }

    /* Animations */
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.1); }
      100% { transform: scale(1); }
    }

    /* Benefits Section */
    .benefits {
      padding: 80px 20px;
      text-align: center;
      background: #16213e;
    }

    .benefits h2 {
      font-size: 2.5rem;
      margin-bottom: 40px;
    }

    .benefits .icon {
      font-size: 3rem;
      margin-bottom: 20px;
      animation: float 3s ease-in-out infinite;
    }

    @keyframes float {
      0% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
      100% { transform: translateY(0); }
    }

    /* About Section */
    .about {
      padding: 80px 20px;
      text-align: center;
      background: #1a1a2e;
    }

    .about img {
      width: 150px;
      border-radius: 50%;
      border: 5px solid #25d366;
      margin-bottom: 20px;
    }

    /* Testimonials Section */
    .testimonials {
      padding: 80px 20px;
      text-align: center;
      background: #16213e;
    }

    .testimonials h2 {
      font-size: 2.5rem;
      margin-bottom: 40px;
    }

    .testimonial-card {
      background: #1a1a2e;
      padding: 20px;
      border-radius: 10px;
      margin: 20px;
      display: inline-block;
      width: 300px;
      animation: fadeIn 2s ease-in-out;
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

  <!-- Header Section -->
  <div class="header">
    <h1>Transform Your Health with Amit Kumar</h1>
    <p>Lose weight, manage diseases like Thyroid, PCOD, PCOS, Hypertension, and Diabetes, and achieve your fitness goals with personalized coaching.</p>
    <a href="https://wa.me/918210145599" class="whatsapp-button">Chat with Me on WhatsApp</a>
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

  <!-- About Section -->
  <div class="about">
    <h2>About Me</h2>
    <img src="https://via.placeholder.com/150" alt="Amit Kumar">
    <p>Hi, I’m Amit Kumar, a certified fitness coach with years of experience helping people achieve their health and fitness goals. Whether you’re looking to lose weight, manage a chronic condition, or simply lead a healthier lifestyle, I’m here to guide you every step of the way.</p>
  </div>

  <!-- Testimonials Section -->
  <div class="testimonials">
    <h2>What My Clients Say</h2>
    <div class="testimonial-card">
      <p>"Thanks to Amit, I lost 10 kg in 3 months and managed my thyroid levels effectively. Highly recommended!" – Priya S.</p>
    </div>
    <div class="testimonial-card">
      <p>"His sessions are life-changing! My PCOD symptoms have improved significantly." – Riya M.</p>
    </div>
    <div class="testimonial-card">
      <p>"Amit’s guidance helped me control my blood sugar levels and lose weight. Thank you!" – Rajesh K.</p>
    </div>
  </div>

  <!-- Footer Section -->
  <div class="footer">
    <p>© 2023 Amit Kumar. All rights reserved.</p>
    <p>Disclaimer: Results may vary based on individual effort and consistency.</p>
    <p>Contact only via WhatsApp: +91 8210145599.</p>
  </div>

</body>
</html>
