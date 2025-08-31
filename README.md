<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio - GitHub Pages</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
</head>
<body>
    <nav class="navbar">
        <div class="nav-container">
            <div class="nav-logo">My Portfolio</div>
            <ul class="nav-menu">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </div>
    </nav>

    <section id="home" class="hero">
        <div class="hero-content">
            <h1>Hello, I'm <span class="highlight">Your Name</span></h1>
            <p>Welcome to my personal portfolio website built with GitHub Pages</p>
            <button class="cta-button" onclick="scrollToSection('projects')">View My Work</button>
        </div>
    </section>

    <section id="about" class="about">
        <div class="container">
            <h2>About Me</h2>
            <div class="about-content">
                <p>I'm a passionate developer who loves creating amazing web experiences. This website is hosted for free on GitHub Pages!</p>
                <div class="skills">
                    <h3>My Skills</h3>
                    <div class="skill-tags">
                        <span class="skill-tag">HTML</span>
                        <span class="skill-tag">CSS</span>
                        <span class="skill-tag">JavaScript</span>
                        <span class="skill-tag">GitHub</span>
                        <span class="skill-tag">Web Design</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="projects" class="projects">
        <div class="container">
            <h2>My Projects</h2>
            <div class="project-grid">
                <div class="project-card">
                    <h3>Project 1</h3>
                    <p>A brief description of your first project and what it does.</p>
                    <a href="#" class="project-link">View Project</a>
                </div>
                <div class="project-card">
                    <h3>Project 2</h3>
                    <p>A brief description of your second project and its features.</p>
                    <a href="#" class="project-link">View Project</a>
                </div>
                <div class="project-card">
                    <h3>Project 3</h3>
                    <p>A brief description of your third project and technologies used.</p>
                    <a href="#" class="project-link">View Project</a>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="contact">
        <div class="container">
            <h2>Contact Me</h2>
            <div class="contact-content">
                <p>Feel free to reach out for collaborations or just to say hello!</p>
                <div class="contact-links">
                    <a href="mailto:your.email@example.com" class="contact-link">Email</a>
                    <a href="https://github.com/yourusername" class="contact-link">GitHub</a>
                    <a href="https://linkedin.com/in/yourprofile" class="contact-link">LinkedIn</a>
                </div>
            </div>
        </div>
    </section>

    <footer class="footer">
        <p>&copy; 2024 My Portfolio. Built with ❤️ using GitHub Pages.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
