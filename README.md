<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Graphic Designer Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            font-family: 'Roboto', sans-serif;
            background-color: #1e1e1e;
            color: #f4f4f4;
        }
        header {
            background-color: #121212;
            color: #f4f4f4;
            padding: 1rem 2rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
        }
        header h1 {
            margin: 0;
            font-size: 1.8rem;
        }
        nav a {
            color: #f4f4f4;
            text-decoration: none;
            margin: 0 1rem;
            font-weight: 700;
        }
        nav a:hover {
            color: #ff5722;
        }
        .hero {
            text-align: center;
            padding: 6rem 2rem;
            background: linear-gradient(to bottom, rgba(18, 18, 18, 0.8), rgba(18, 18, 18, 0.8)), url('hero-image.jpg') no-repeat center center/cover;
            color: #fff;
        }
        .hero h2 {
            font-size: 3.5rem;
            margin-bottom: 1rem;
            line-height: 1.2;
        }
        .hero p {
            font-size: 1.5rem;
            margin: 1rem 0;
        }
        .hero button {
            padding: 0.8rem 2rem;
            background-color: #ff5722;
            color: white;
            border: none;
            border-radius: 4px;
            font-size: 1rem;
            cursor: pointer;
        }
        .hero button:hover {
            background-color: #e64a19;
        }
        section {
            padding: 4rem 2rem;
            max-width: 1200px;
            margin: 0 auto;
        }
        .portfolio {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 1.5rem;
        }
        .portfolio img {
            width: 100%;
            border-radius: 8px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .portfolio img:hover {
            transform: scale(1.05);
            box-shadow: 0 8px 15px rgba(0, 0, 0, 0.3);
        }
        .about {
            text-align: center;
            line-height: 1.8;
        }
        .contact-form {
            max-width: 600px;
            margin: 0 auto;
            background: #121212;
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 8px 15px rgba(0, 0, 0, 0.2);
        }
        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 1rem;
            margin: 0.5rem 0;
            border: none;
            border-radius: 4px;
            background: #1e1e1e;
            color: #f4f4f4;
        }
        .contact-form button {
            padding: 0.8rem 2rem;
            background-color: #ff5722;
            color: white;
            border: none;
            border-radius: 4px;
            font-size: 1rem;
            cursor: pointer;
            transition: background 0.3s ease;
        }
        .contact-form button:hover {
            background-color: #e64a19;
        }
        footer {
            text-align: center;
            padding: 1.5rem;
            background-color: #121212;
            color: #f4f4f4;
            font-size: 0.9rem;
        }
        footer a {
            color: #ff5722;
            text-decoration: none;
        }
        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>Creative Vision</h1>
        <nav>
            <a href="#portfolio">Portfolio</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <div class="hero">
        <h2>Innovative Graphic Design for the Modern Era</h2>
        <p>Crafting timeless designs to make your brand stand out.</p>
        <button>Explore My Work</button>
    </div>

    <section id="portfolio">
        <h2>Portfolio</h2>
        <div class="portfolio">
            <img src="design1.jpg" alt="Design 1">
            <img src="design2.jpg" alt="Design 2">
            <img src="design3.jpg" alt="Design 3">
            <img src="design4.jpg" alt="Design 4">
        </div>
    </section>

    <section id="about">
        <h2>About Me</h2>
        <div class="about">
            <p>Hello! I'm a graphic designer specializing in modern, impactful designs. My mission is to bring your ideas to life with creativity and precision. Whether it's branding, illustrations, or digital media, I strive to deliver exceptional results tailored to your vision.</p>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <form class="contact-form">
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" rows="5" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Creative Vision. Designed with passion. <a href="#">Privacy Policy</a></p>
    </footer>
</body>
</html>
