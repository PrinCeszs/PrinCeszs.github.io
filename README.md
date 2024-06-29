<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Travel Agency Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Welcome to [Your Travel Agency Name]</h1>
            <p>We specialize in creating memorable travel experiences.</p>
            <a href="#services" class="btn">Our Services</a>
            <a href="#contact" class="btn">Contact Us</a>
        </div>
    </header>

    <section id="services">
        <div class="container">
            <h2>Our Services</h2>
            <p>Explore our diverse range of travel services.</p>
            <div class="services-grid">
                <div class="service">
                    <h3>Beach Getaways</h3>
                    <img src="images/beach.jpg" alt="Beach Getaways">
                </div>
                <div class="service">
                    <h3>Adventure Treks</h3>
                    <img src="images/trek.jpg" alt="Adventure Treks">
                </div>
                <div class="service">
                    <h3>Cultural Tours</h3>
                    <img src="images/culture.jpg" alt="Cultural Tours">
                </div>
            </div>
        </div>
    </section>

    <section id="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <p>Get in touch for personalized assistance.</p>
            <form action="submit.php" method="POST">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" placeholder="Your Message" rows="4" required></textarea>
                <button type="submit" class="btn">Send Message</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2024 [Your Travel Agency Name]. All rights reserved.</p>
        </div>
    </footer>

    <script src="scripts/main.js"></script>
</body>
</html>
