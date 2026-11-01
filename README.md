# Peptalpop-website
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <link rel="stylesheet" href="style.css">
    <script src="script.js" defer></script>
</head>
<body>

    <!-- Navigation bar -->
    <header>
        <nav class="navbar">
            <a href="home.html" class="logo">MyWebsite</a>

            <ul class="nav-links">
<li><a href="one.html">Index</a></li>

                <li><a href="home.html">Home</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="services.html">Services</a></li>
<li><a href="testing1/gallery/tww.html">Gallery</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Home section -->
    <section id="home" class="hero">
        <h1>Welcome to Our Website</h1>
        <p>We would love to hear from you. Send us a message!</p>
        <a href="contact.html" class="hero-button">Contact Us</a>
    </section>

    <!-- About section -->
    <section id="about" class="about">
        <h2>About Us</h2>
        <p>
            We provide quality services and value our customers.
            Complete the contact form below and our team will
            get back to you.
        </p>
    </section>

    <!-- Contact Form -->
    <section id="contact" class="contact-section">
    div class="form-container"
    form id="contactForm"
        required

        <label for="email">Email Address *</label>
        <input
            type="email"
            id="email"
            name="email"
            placeholder="example@email.com"
            maxlength="254"
            autocomplete="email"
            required>

        <label for="phone">Phone Number *</label>
        <input
            type="tel"
            id="phone"
            name="phone"
            placeholder="+27 82 123 4567"
            pattern="[+]{0,1}[0-9 ()-]{9,20}"
            minlength="9"
            maxlength="20"
            autocomplete="tel"
            required>

        <label for="subject">Subject *</label>
        <select id="subject" name="subject" required>
            <option value="">Select a subject</option>
            <option value="General Enquiry">General Enquiry</option>
            <option value="Support">Support</option>
            <option value="Feedback">Feedback</option>
            <option value="Other">Other</option>
        </select>

        <label for="message">Message *</label>
        <textarea
            id="message"
            name="message"
            rows="5"
            minlength="10"
            maxlength="2000"
            placeholder="Write your message here..."
            required></textarea>
                    <textarea
            id="message"
            name="message"
            rows="5"
            minlength="10"
            maxlength="2000"
            placeholder="Write your message here..."
            required></textarea>

        <button type="submit" id="submitBtn">
            Send Message
        </button>

        <p id="formStatus" role="status" aria-live="polite"></p>
    </form>
    </div>
</section>

<!-- Map section -->
<section id="location" class="location-section">
    <h2>Find Our Location</h2>
    <p>Visit us in Johannesburg, South Africa.</p>

    <iframe
        title="Map showing Johannesburg, South Africa"
        src="https://maps.google.com/maps?q=Johannesburg%2C%20South%20Africa&output=embed"
        width="100%"
        height="350"
        style="border:0"
        loading="lazy"
        referrerpolicy="no-referrer-when-downgrade"
        allowfullscreen>
    </iframe>
</section>

<!-- Footer -->
<footer>
    <p>&copy; 2026 MyWebsite. All rights reserved.</p>
</footer>

</body>
</html>
