<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Abang Foundation</title>
    <style>
        body {
            background-image: url('snow.jpg');
            background-size: cover;
            background-repeat: no-repeat;
            background-attachment: fixed; /* Optional: Makes the background fixed while scrolling */
        }
        nav {
            background-color: rgba(0, 0, 0, 0.7); /* Semi-transparent background */
            padding: 10px;
            position: fixed; /* Keeps the nav panel fixed at the top */
            top: 0;
            width: 100%;
            z-index: 1000; /* Ensures it stays above other elements */
        }
        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
        }
        nav ul li {
            margin: 0 15px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        nav ul li a:hover {
            text-decoration: underline;
        }
        main {
            margin-top: 60px; /* Adds space to prevent content from overlapping with the fixed nav */
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Abang Foundation</h1>
        <img src="snow.jpg" width="250px" height="250px" alt="photo of snow-covered mountains">
        <!-- Audio Element -->
        <audio autoplay loop>
            <source src="don't cry.mp3" type="audio/mpeg">
        </audio>
    </header>
    <!-- Navigation Panel -->
    <nav>
        <ul>
            <li><a href="#about">About Us</a></li>
            <li><a href="#services">Our Services</a></li>
            <li><a href="#advantages">Advantages</a></li>
            <li><a href="#help">How to Help</a></li>
            <li><a href="#contact">Contact</a></li>
            <li><a href="#projects">Our Projects</a></li>
        </ul>
    </nav>
    <main>
        <section id="about">
            <h2>About Us</h2>
            <p>Abang Foundation is dedicated to making a positive impact in our community through various initiatives and programs.</p>
            <a href="more-about-us.html">Learn more about us</a>
        </section>
        <section id="services">
            <h2>Our Services</h2>
            <p>We offer educational support, community outreach, and skill development programs to empower individuals.</p>
        </section>
        <section id="advantages">
            <h2>Advantages</h2>
            <ul>
                <li>Empowering communities through education and skill development.</li>
                <li>Providing resources for underprivileged individuals.</li>
                <li>Creating sustainable programs for long-term impact.</li>
            </ul>
        </section>
        <section id="help">
            <h2>How to Help</h2>
            <p>You can support Abang Foundation by:</p>
            <ul>
                <li>Donating funds to support our programs.</li>
                <li>Volunteering your time and skills.</li>
                <li>Spreading awareness about our mission and initiatives.</li>
            </ul>
        </section>
        <section id="contact">
            <h2>Contact</h2>
            <p>Contact us: info@abangfoundation.org | Phone: +123-456-7890</p>
        </section>
        <section id="projects">
            <h2>Our Community Projects</h2>
            <ul>
                <li><strong>Project 1:</strong> Building a community library to promote literacy and education.</li>
                <li><strong>Project 2:</strong> Organizing free health camps for underprivileged families.</li>
                <li><strong>Project 3:</strong> Providing scholarships to deserving students for higher education.</li>
                <li><strong>Project 4:</strong> Conducting skill development workshops for unemployed youth.</li>
                <li><strong>Project 5:</strong> Distributing food and essential supplies during natural disasters.</li>
                <li><strong>Project 6:</strong> Planting trees to combat deforestation and promote environmental sustainability.</li>
                <li><strong>Project 7:</strong> Setting up clean water facilities in rural areas.</li>
            </ul>
        </section>
    </main>
    <footer>
        <p>&copy; 2025 Abang Foundation. All rights reserved.</p>
    </footer>
</body>
</html>
