# index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        /* Basic Page Styling */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #f8f9fa;
            color: #333;
        }

        /* Header and Navigation */
        header {
            background-color: #222;
            color: white;
            text-align: center;
            padding: 15px 0;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }

        nav a:hover {
            color: #00bcd4;
        }

        /* Main Content Sections */
        section {
            padding: 40px 20px;
            text-align: center;
        }

        #portfolio img {
            width: 200px;
            height: 150px;
            margin: 10px;
            border-radius: 8px;
        }

        /* Footer */
        footer {
            background-color: #222;
            color: white;
            text-align: center;
            padding: 20px 0;
        }

        .social-links a {
            color: white;
            text-decoration: none;
            margin: 0 10px;
        }

        .social-links a:hover {
            color: #00bcd4;
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>My Portfolio</h1>
        <nav>
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#portfolio">Portfolio</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <!-- Home Section -->
    <section id="home">
        <h2>Welcome to My Website</h2>
        <p>Hello! I’m glad you’re here. This website showcases my work and interests.</p>
    </section>

    <!-- About Section -->
    <section id="about">
        <h2>About Me</h2>
        <p>Hi, I'm Beeram Haripriya. I’m a creative web enthusiast who loves building user-friendly and visually appealing websites.</p>
    </section>

    <!-- Portfolio Section -->
    <section id="portfolio">
        <h2>My Projects</h2>
        <div>
            <img src="https://via.placeholder.com/200x150" alt="Project 1">
            <img src="https://via.placeholder.com/200x150" alt="Project 2">
            <img src="https://via.placeholder.com/200x150" alt="Project 3">
        </div>
        <p>These are sample projects that represent my work style and creativity.</p>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2025 My Portfolio. All rights reserved.</p>
        <div class="social-links">
            <a href="#">LinkedIn</a> |
            <a href="#">GitHub</a> |
            <a href="#">Twitter</a>
        </div>
    </footer>

</body>
</html>
