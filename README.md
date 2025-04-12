<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Astrology</title>
</head>
<!-- <link rel="stylesheet" href="{{ url_for('static', filename='css/style.css') }}"> -->

<link rel="stylesheet" href="public/css/style.css"> 
<body>
    <!-- Header -->
    <header>
        <div class="header-container">
            <div class="logo">
                <img src="public image/VEDIC/download (2).jpg" alt="fate logo">
                <h3>FATE <span>LINE</span></h3>
            </div>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="login.html">Horescope</a></li>
                    <li><a href="#service">service</a></li>
                    <li><a href="#contact">contact</a></li>
                    <li></li>
                </ul>
            </nav>
        </div>

    </header>
        <section class="hero" id="home">
            <div class="hero-content">
                <h2>Discover Your Cosmic Blueprint</h2>
                <p>Unlock the secrets of your life with authentic Vedic astrology predictions and remedies based on your birth chart.</p>
            </div>
            <div class="photo">
                <img src="public image/VEDIC/IMG-20250409-WA0014-removebg-preview.png" alt="iitian baba">
            </div>
        </section>

        <section class="features" id="services">
            <div class="container">
                <div class="section-title">
                    <h2>Our Divine Services</h2>
                </div>
                <div class="features-grid">
                    <div class="feature-card">
                        <div class="feature-icon">
                           <a href="#"><img src="public image/VEDIC/birth.png" alt=""></a>
                        </div>
                        <h3>Birth Chart Analysis</h3>
                        <p>Detailed analysis of your Janam Kundali to reveal your life's purpose, strengths, and challenges.</p>
                    </div>
                    <div class="feature-card">
                        <div class="feature-icon">
                            <a href="#"><img src="public image/VEDIC/gamestone.jpg" alt=""></a>
                        </div>
                        <h3>Gemstone Recommendation</h3>
                        <p>Personalized gemstone suggestions to balance planetary energies and enhance your life.</p>
                    </div>
                    <div class="feature-card">
                        <div class="feature-icon">
                            <a href="#"><img src="public image/VEDIC/marriage.jpg" alt=""></a>
                        </div>
                        <h3>Marriage Compatibility</h3>
                        <p>Thorough Kundali matching for marriage to ensure harmonious and prosperous union.</p>
                    </div>
                    <div class="feature-card">
                        <div class="feature-icon">
                          <a href="#"><img src="public image/VEDIC/carrier.jpg" alt=""></a>
                        </div>
                        <h3>Career Guidance</h3>
                        <p>Insights into your professional path based on planetary positions and dashas.</p>
                    </div>
                    <div class="feature-card">
                        <div class="feature-icon">
                           <a href="#"><img src="public image/VEDIC/public image/VEDIC/download (2).jpg" alt=""></a>
                        </div>
                        <h3>Vastu Consultation</h3>
                        <p>Harmonize your living space with cosmic energies for health, wealth and happiness.</p>
                    </div>

                    <div class="feature-card">
                        <div class="feature-icon">
                           <a href="#"><img src="public image/VEDIC/palm.jpg" alt=""></a>
                        </div>
                        <h3> Palm Career Guidance</h3>
                        <p>Palm carrier line shows career path, destiny, ambition, and life direction through palmistry insights.</p>
                    </div>
                    </section>


                    <!-- Compatibility -->
                   
                    <h1>Daily Horoscope</h1>
                    <div class="container1">
                        <div class="zodiac-sign" data-sign="aries">
                            <img src="public image/VEDIC/ARIES.webp" alt="ARIES">
                            
                        </div>
                        <div class="zodiac-sign" data-sign="taurus">
                            <img src="public image/VEDIC/TAURUS-1.webp" alt="">
                          
                        </div>
                        <div class="zodiac-sign" data-sign="gemini">
                            <img src="public image/VEDIC/GEMINI.webp" alt="">
                        </div>
                        <div class="zodiac-sign" data-sign="cancer">
                            <img src="public image/VEDIC/CANCER-1.webp" alt="">
                        </div>
                        <div class="zodiac-sign" data-sign="leo">
                            <img src="public image/VEDIC/LEO-1.webp" alt="">
                        </div>
                        <div class="zodiac-sign" data-sign="virgo">
                            <img src="public image/VEDIC/VIRGO-1.webp" alt="">
                        </div>
                        <div class="zodiac-sign" data-sign="libra">
                            <img src="public image/VEDIC/LIBRA-1.webp" alt="">
                        </div>
                        <div class="zodiac-sign" data-sign="scorpio">
                            <img src="public image/VEDIC/SCORPIO-1.webp" alt="">
                        </div>
                        <div class="zodiac-sign" data-sign="sagittarius">
                            <img src="public image/VEDIC/SAGITTARIUS.webp" alt="">
                        </div>
                        <div class="zodiac-sign" data-sign="capricorn">
                            <img src="public image/VEDIC/CAPRI-1.webp" alt="">
                        </div>
                        <div class="zodiac-sign" data-sign="aquarius">
                            <img src="public image/VEDIC/AQUARI-1.webp" alt="">
                        </div>
                        <div class="zodiac-sign" data-sign="pisces">
                            <img src="public image/VEDIC/PISCES-1.webp" alt="">
                        </div>
                    </div>
                
                    <div id="horoscope-display">
                        <h2 id="sign-name"></h2>
                        <p id="horoscope-text">Click on a zodiac sign to see today's horoscope.</p>
                    </div>

                     <!-- Footer -->
    <footer id="contact">
        <div class="container">
            <div class="footer-content">
                <div class="footer-column">
                    <h3>About Jyotish Darshan</h3>
                    <p>We provide authentic Vedic astrology services based on ancient Indian wisdom combined with modern interpretation techniques.</p>
                    <div class="social-links">
                        <a href="#"><i class="fab fa-facebook-f"></i></a>
                        <a href="#"><i class="fab fa-twitter"></i></a>
                        <a href="#"><i class="fab fa-instagram"></i></a>
                        <a href="#"><i class="fab fa-youtube"></i></a>
                    </div>
                </div>
                <div class="footer-column">
                    <h3>Quick Links</h3>
                    <ul>
                        <li><a href="#home">Home</a></li>
                        <li><a href="#horoscope">Daily Horoscope</a></li>
                        <li><a href="#services">Our Services</a></li>
                        <li><a href="#">Love Compatibility</a></li>
                        <li><a href="#">Birth Chart Calculator</a></li>
                    </ul>
                </div>
                <div class="footer-column">
                    <h3>Services</h3>
                    <ul>
                        <li><a href="#">Kundali Analysis</a></li>
                        <li><a href="#">Manglik Dosha Check</a></li>
                        <li><a href="#">Gemstone Consultation</a></li>
                        <li><a href="#">Numerology Report</a></li>
                        <li><a href="#">Vastu Shastra</a></li>
                    </ul>
                </div>
                <div class="footer-column">
                    <h3>Contact Us</h3>
                    <p><i class="fas fa-map-marker-alt"></i> 123 Astro Lane, Varanasi, UP, India</p>
                    <p><i class="fas fa-phone"></i> +91 9876543210</p>
                    <p><i class="fas fa-envelope"></i> contact@jyotishdarshan.com</p>
                </div>
            </div>
            <div class="copyright">
                <p>&copy; 2023 Jyotish Darshan. All Rights Reserved.</p>
            </div>
        </div>
    </footer>
                
                    
        <script src="server.js"></script>
        
</body>
</html>


