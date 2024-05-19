<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
  <title>Tingle Dating - Find Your Perfect Match</title>
  <style>
    /* Global Styles */
    body {
      font-family: 'Arial', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f9f9f9;
      color: #333;
    }

    /* Header Styles */
    header {
      background-image: url('https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEi2KCHfHSAepQsOmHfTRJhbtiZ-MpFDsIaQQlRX0ZIylxD6gto5u3WfiBfwFNCQpWkYEavQSMhxD_lOawx2zCFSbTSibVDBx1hzvVD-74XQmWQdq2cVzXETLGPADcKqQ6-cQC_mC2FDTlBDdnLUT0aTmp5uvD3EwXW1l3mwVwp1enVgfOnqdjz1B5yF99LQ/s1920/Tinglen.png');
      background-size: cover;
      background-position: center;
      color: #453F78;
      padding: 150px 20px;
      text-align: center;
      animation: slideUp 1s ease-in-out;
    }

    header h1 {
      font-size: 48px;
      margin-bottom: -80px;
      text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
    }

    header p {
      font-size: 24px;
      margin-bottom: -40px;
    }

    /* Feature Section Styles */
    .feature {
      padding: 60px 10px;
      text-align: center;
      background-color: #fff;
      margin: 40px;
      border-radius: 15px;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.5);
      animation: slideUp 1s ease-in-out;
    }

    .feature h2 {
      font-size: 36px;
      margin-bottom: 20px;
      color: #333;
    }

    .feature p {
      font-size: 18px;
      margin-bottom: 40px;
      color: #666;
    }

    .feature img {
      max-width: 100%;
      height: auto;
      margin-bottom: 20px;
      border-radius: 10px;
    }

    /* About Section Styles */
    .about-container {
      display: flex;
      justify-content: center;
      align-items: center;
      margin: 80px 0;
    }

    .about {
      background-color: #fff;
      padding: 40px;
      border-radius: 15px;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.5);
      width: 60%;
      animation: fadeIn 1s ease-in-out;
    }

    .about h2 {
      font-size: 36px;
      margin-bottom: 20px;
      color: #333;
    }

    .about p {
      font-size: 18px;
      margin-bottom: 40px;
      color: #666;
    }
       .signup-container {
      max-width: 600px;
      margin: 20px;
      padding: 40px;
      background-color: #FFC55A;
      border-radius: 10px;
      text-align: center;
      position: relative;
      overflow: hidden;
    }

    .signup-section {
      margin-bottom: 40px;
    }

    .signup-title {
      font-size: 24px;
      color: #333;
      margin-bottom: 10px;
    }

    .signup-description {
      font-size: 18px;
      color: #666;
      margin-bottom: 30px;
    }

    .signup-button {
      display: inline-block;
      padding: 15px 30px;
      background-color: #007bff;
      color: white;
      text-decoration: none;
      border-radius: 30px;
      font-size: 18px;
      font-weight: bold;
      text-transform: uppercase;
      border: none;
      transition: all 0.3s ease;
      cursor: pointer;
    }

    .signup-button:hover {
      background-color: #0056b3;
    }

    .signup-features {
      text-align: left;
      margin-top: 30px;
    }

    .signup-features h3 {
      font-size: 20px;
      color: #333;
      margin-bottom: 10px;
      position: relative;
      display: inline-block;
      padding-bottom: 5px;
    }

    .signup-features h3::before,
    .signup-features h3::after {
      content: "";
      position: absolute;
      bottom: 0;
      width: 50%;
      height: 1px;
      background-color: #007bff;
    }

    .signup-features h3::before {
      left: 0;
    }

    .signup-features h3::after {
      right: 0;
    }

    .signup-features ul {
      list-style-type: none;
      padding: 0;
      margin: 0;
    }

    .signup-features li {
      font-size: 16px;
      color: #666;
      margin-bottom: 10px;
    }

    /* Testimonial Section Styles */
    .testimonial-container {
      display: flex;
      justify-content: center;
      align-items: center;
      margin: 80px -120px;
    }

    .testimonial {
      background-color: #f9f9f9;
      padding: 40px;
      border-radius: 20px;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.5);
      width: 40%;
      animation: slideUp 1s ease-in-out;
    }

    .testimonial h2 {
      font-size: 36px;
      margin-bottom: 20px;
      color: #333;
    }

    .testimonial p {
      font-size: 18px;
      margin-bottom: 40px;
      color: #666;
    }

    .testimonial blockquote {
      font-style: italic;
      margin-bottom: 20px;
    }

    .testimonial cite {
      font-weight: bold;
    }

    
    /* Animations */
    @keyframes slideUp {
      0% {
        transform: translateY(50px);
        opacity: 0;
      }
      100% {
        transform: translateY(0);
        opacity: 1;
      }
    }

    @keyframes fadeIn {
      0% {
        opacity: 0;
      }
      100% {
        opacity: 1;
      }
    }
    footer {
      background-color: #252B48;
      color: #fff;
      padding: 20px;
      text-align: center;
      position: fixed;
      left: 0;
      bottom: 0;
      width: 90%;
      margin: 0 auto;
      border: 1px solid #ccc;
      border-radius: 20px 20px 0 0;
    }

    nav ul {
      list-style-type: none;
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: space-between;
    }

    nav li {
      margin: 0 5px;
      transition: transform 0.3s ease;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      font-size: 24px;
      display: block;
    }

    nav a:hover {
      color: #FEC260;
    }

    nav li:hover {
      transform: translateY(-5px);
    }
  </style>
</head>
<body>
  <header>
   <h1> search your partner now!!</h1>
  </header>

  <section class="feature">
    <img src="feature1-image.jpg" alt="Feature 1">
    <h2>Personalized Matches</h2>
    <p>Our advanced algorithm matches you with compatible partners based on your preferences and interests.</p>
  </section>

  <section class="feature">
    <img src="feature2-image.jpg" alt="Feature 2">
    <h2>Secure and Private</h2>
    <p>Your privacy is our top priority. We use advanced security measures to protect your personal information.</p>
  </section>

  <div class="about-container">
    <section class="about">
      <h2>About Tingle Dating</h2>
      <p>Tingle Dating is a premier online dating platform that connects singles looking for meaningful relationships. Our mission is to help you find your perfect match in a safe and welcoming environment.</p>
    </section>
  </div>
<div class="signup-container">
  <section class="signup-section">
    <h2 class="signup-title">Join Our Community</h2>
    <p class="signup-description">Sign up now to get access to exclusive features.</p>
    <a href="#" class="signup-button">Sign Up</a>
  </section>

  <div class="signup-features">
    <h3>Why Sign Up?</h3>
    <ul>
      <li>Access to premium content</li>
      <li>Exclusive discounts and offers</li>
      <li>Personalized recommendations</li>
      <li>Early access to new features</li>
      <li>Community forums and discussions</li>
    </ul>
  </div>
</div>
  <div class="testimonial-container">
    <section class="testimonial">
      <h2>What Our Members Say</h2>
      <blockquote>
        "I never thought I'd find love online, but Tingle Dating proved me wrong. I met my soulmate and we're happily married now. Thank you, Tingle!"
        <cite>- John and Jane Doe</cite>
      </blockquote>
      <blockquote>
        "Tingle Dating is the best dating site I've ever used. The matches are spot-on, and the community is so welcoming. Highly recommended!"
        <cite>- Sarah Johnson</cite>
      </blockquote>
    </section>
  </div>
  <footer>   <nav>
      <ul>
        <li><a href="#"><i class="fas fa-home"></i></a></li>
        <li><a href="#"><i class="fas fa-info-circle"></i></a></li>
        <li><a href="#"><i class="fas fa-cogs"></i></a></li>
        <li><a href="#"><i class="fas fa-envelope"></i></a></li>
      </ul>
    </nav>
 </footer>
</body>
</html>
