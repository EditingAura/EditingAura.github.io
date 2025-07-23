<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Editing Aura - Video Editing Services</title>
    <link rel="stylesheet" href="styles.css"> <!-- Link to external CSS file -->
</head>
<body>
    <header>
        <div class="container">
            <h1>Editing Aura</h1>
            <p>Transform Your Podcasts into Engaging Social Media Content</p>
        </div>
    </header>
    <nav>
        <div class="container">
            <a href="#home">Home</a>
            <a href="#services">Services</a>
            <a href="#portfolio">Portfolio</a>
            <a href="#testimonials">Testimonials</a>
            <a href="#about">About Us</a>
            <a href="#contact">Contact</a>
        </div>
    </nav>
    <section id="home">
        <div class="container">
            <h2>Welcome to Editing Aura</h2>
            <p>Specializing in podcast editing, short-form content repurposing, and cinematic YouTube edits.</p>
            <a href="#contact" class="cta-button">Get Started</a>
        </div>
    </section>
    <section id="services">
        <div class="container">
            <h2>Our Services</h2>
            <ul>
                <li>Podcast Edits</li>
                <li>YouTube Videos</li>
                <li>Reels/Shorts</li>
                <li>Captions/Subtitles</li>
                <li>Custom Video Solutions</li>
            </ul>
        </div>
    </section>
    <section id="portfolio">
        <div class="container">
            <h2>Portfolio</h2>
            <div class="portfolio-item">
                <h3>Podcast Edit</h3>
                <iframe width="560" height="315" src="https://www.youtube.com/embed/dQw4w9WgXcQ" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
            </div>
            <div class="portfolio-item">
                <h3>YouTube Edit</h3>
                <iframe width="560" height="315" src="https://www.youtube.com/embed/dQw4w9WgXcQ" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
            </div>
        </div>
    </section>
    <section id="testimonials">
        <div class="container">
            <h2>Client Testimonials</h2>
            <div class="testimonial">
                <p>"Editing Aura took my podcast to the next level with their professional edits and quick turnaround times."</p>
                <p>— John Doe, Podcast Host</p>
            </div>
            <div class="testimonial">
                <p>"Their YouTube edits are cinematic and engaging. Highly recommend!"</p>
                <p>— Jane Smith, YouTuber</p>
            </div>
        </div>
    </section>
    <section id="about">
        <div class="container">
            <h2>About Us</h2>
            <p>Editing Aura is a professional video editing agency specializing in podcast editing, short-form content repurposing, and cinematic YouTube edits. Our goal is to help you reach a wider audience and maximize the impact of your content.</p>
        </div>
    </section>
    <section id="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <form class="contact-form" action="https://formspree.io/f/YOUR_FORMSPREE_ID" method="POST">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <input type="url" name="link" placeholder="Link to your raw file (Drive, Dropbox, etc.)">
                <textarea name="message" placeholder="Describe what you need" required></textarea>
                <button type="submit">Send</button>
            </form>
        </div>
    </section>
    <footer>
        <div class="container">
            <p>&copy; 2025 Editing Aura. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
/* styles.css */

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #ffffff;
    color: #333333;
}

.container {
    width: 80%;
    margin: auto;
    overflow: hidden;
}

header {
    background-color: #003366;
    color: #ffffff;
    padding: 1em 0;
    text-align: center;
}

header h1 {
    font-size: 2.5em;
}

header p {
    font-size: 1.2em;
}

nav {
    display: flex;
    justify-content: center;
    background-color: #003366;
}

nav a {
    color: #ffffff;
    padding: 1em;
    text-decoration: none;
    font-size: 1.2em;
}

nav a:hover {
    background-color: #002244;
}

section {
    padding: 2em;
    text-align: center;
}

section h2 {
    font-size: 2em;
}

.portfolio-item {
    margin: 1em 0;
}

.portfolio-item iframe {
    max-width: 100%;
    height: auto;
}

.contact-form {
    display: flex;
    flex-direction: column;
    align-items: center;
}

.contact-form input, .contact-form textarea {
    width: 100%;
    padding: 0.5em;
    margin: 0.5em 0;
    border: 1px solid #cccccc;
    border-radius: 4px;
    background-color: #ffffff;
    color: #333333;
}

.contact-form button {
    padding: 0.5em 1em;
    background-color: #003366;
    color: #ffffff;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

.contact-form button:hover {
    background-color: #002244;
}

footer {
    background-color: #003366;
    color: #ffffff;
    text-align: center;
    padding: 1em 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}
