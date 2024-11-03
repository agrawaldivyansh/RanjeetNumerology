# RanjeetNumerology
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Numerology Services by Ranjeet Agrawal</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/js/all.min.js"></script>
    <style>
        :root {
            --primary-color: #7E57C2;
            --secondary-color: #B39DDB;
            --text-color: #333;
            --light-bg: #F5F5F5;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            line-height: 1.6;
            color: var(--text-color);
        }

        .header {
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
            color: white;
            padding: 2rem 0;
            text-align: center;
        }

        .nav {
            background: white;
            padding: 1rem;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        .nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 2rem;
        }

        .nav a {
            text-decoration: none;
            color: var(--text-color);
            font-weight: 500;
            transition: color 0.3s;
        }

        .nav a:hover {
            color: var(--primary-color);
        }

        .hero {
            background: var(--light-bg);
            padding: 4rem 2rem;
            text-align: center;
        }

        .services {
            padding: 4rem 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }

        .service-card {
            background: white;
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            text-align: center;
            transition: transform 0.3s;
        }

        .service-card:hover {
            transform: translateY(-5px);
        }

        .testimonials {
            background: var(--light-bg);
            padding: 4rem 2rem;
            text-align: center;
        }

        .testimonial-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
            max-width: 1200px;
            margin: 2rem auto 0;
        }

        .testimonial-card {
            background: white;
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }

        .contact {
            padding: 4rem 2rem;
            text-align: center;
            max-width: 600px;
            margin: 0 auto;
        }

        .contact-form {
            display: grid;
            gap: 1rem;
            margin-top: 2rem;
        }

        input, textarea {
            padding: 0.8rem;
            border: 1px solid #ddd;
            border-radius: 4px;
        }

        button {
            background: var(--primary-color);
            color: white;
            padding: 1rem 2rem;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        button:hover {
            background: var(--secondary-color);
        }

        .footer {
            background: var(--primary-color);
            color: white;
            text-align: center;
            padding: 2rem;
            margin-top: 4rem;
        }

        .social-links {
            margin-top: 1rem;
        }

        .social-links a {
            color: white;
            margin: 0 1rem;
            font-size: 1.5rem;
        }

        @media (max-width: 768px) {
            .nav ul {
                flex-direction: column;
                text-align: center;
                gap: 1rem;
            }
        }
    </style>
</head>
<body>
    <header class="header">
        <h1>Ranjeet Agrawal</h1>
        <p>Expert Numerologist & Life Guide</p>
    </header>

    <nav class="nav">
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#testimonials">Testimonials</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <section class="hero" id="home">
        <h2>Discover Your Life's Path Through Numbers</h2>
        <p>With over 20 years of experience in numerology, I help individuals unlock their true potential and find their purpose.</p>
    </section>

    <section class="services" id="services">
        <h2>My Services</h2>
        <div class="services-grid">
            <div class="service-card">
                <i class="fas fa-star fa-2x" style="color: var(--primary-color);"></i>
                <h3>Personal Numerology Reading</h3>
                <p>Discover your life path number and understand your destiny through detailed analysis.</p>
            </div>
            <div class="service-card">
                <i class="fas fa-heart fa-2x" style="color: var(--primary-color);"></i>
                <h3>Relationship Compatibility</h3>
                <p>Learn about your compatibility with partners through numerical analysis.</p>
            </div>
            <div class="service-card">
                <i class="fas fa-briefcase fa-2x" style="color: var(--primary-color);"></i>
                <h3>Career Guidance</h3>
                <p>Get insights into your professional life and make informed career decisions.</p>
            </div>
        </div>
    </section>

    <section class="testimonials" id="testimonials">
        <h2>Client Testimonials</h2>
        <div class="testimonial-grid">
            <div class="testimonial-card">
                <p>"Mr. Agrawal's numerology reading was incredibly accurate and helped me make important life decisions."</p>
                <strong>- Priya Shah</strong>
            </div>
            <div class="testimonial-card">
                <p>"The career guidance I received was invaluable. It helped me choose the right path for my future."</p>
                <strong>- Rahul Mehta</strong>
            </div>
        </div>
    </section>

    <section class="contact" id="contact">
        <h2>Book a Consultation</h2>
        <form class="contact-form">
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <input type="tel" placeholder="Phone Number" required>
            <textarea rows="4" placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer class="footer">
        <p>Connect with Ranjeet Agrawal</p>
        <div class="social-links">
            <a href="#"><i class="fab fa-facebook"></i></a>
            <a href="#"><i class="fab fa-instagram"></i></a>
            <a href="#"><i class="fab fa-whatsapp"></i></a>
        </div>
        <p>&copy; 2024 Ranjeet Agrawal Numerology Services. All rights reserved.</p>
    </footer>
</body>
</html>
