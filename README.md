<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rubini Raju - Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav class="navbar">
            <div class="container">
                <div class="logo">Rubini Raju</div>
                <ul class="nav-links">
                    <li><a href="#about">About</a></li>
                    <li><a href="#projects">Projects</a></li>
                    <li><a href="#skills">Skills</a></li>
                    <li><a href="#contact">Contact</a></li>
                    <li><a href="#resume">Resume</a></li>
                </ul>
            </div>
        </nav>
    </header>

    <main>
        <!-- Hero Section -->
        <section id="hero" class="hero">
            <div class="container">
                <h1>Welcome to My Portfolio</h1>
                <p>Full Stack Developer | Designer | Innovator</p>
                <a href="#projects" class="btn">View My Work</a>
            </div>
        </section>

        <!-- About Section -->
        <section id="about" class="about">
            <div class="container">
                <h2>About Me</h2>
                <p>I am a passionate developer with expertise in creating modern, responsive web applications. I love solving problems and learning new technologies.</p>
            </div>
        </section>

        <!-- Projects Section -->
        <section id="projects" class="projects">
            <div class="container">
                <h2>Projects</h2>
                <div class="projects-grid">
                    <div class="project-card">
                        <h3>Project 1</h3>
                        <p>Description of your project</p>
                        <a href="#" class="project-link">View Project</a>
                    </div>
                    <div class="project-card">
                        <h3>Project 2</h3>
                        <p>Description of your project</p>
                        <a href="#" class="project-link">View Project</a>
                    </div>
                    <div class="project-card">
                        <h3>Project 3</h3>
                        <p>Description of your project</p>
                        <a href="#" class="project-link">View Project</a>
                    </div>
                </div>
            </div>
        </section>

        <!-- Skills Section -->
        <section id="skills" class="skills">
            <div class="container">
                <h2>Skills</h2>
                <div class="skills-grid">
                    <div class="skill-item">
                        <h3>Frontend</h3>
                        <p>HTML, CSS, JavaScript, React</p>
                    </div>
                    <div class="skill-item">
                        <h3>Backend</h3>
                        <p>Node.js, Python, SQL</p>
                    </div>
                    <div class="skill-item">
                        <h3>Tools</h3>
                        <p>Git, GitHub, VS Code</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="contact">
            <div class="container">
                <h2>Get In Touch</h2>
                <form class="contact-form">
                    <input type="text" placeholder="Your Name" required>
                    <input type="email" placeholder="Your Email" required>
                    <textarea placeholder="Your Message" rows="5" required></textarea>
                    <button type="submit" class="btn">Send Message</button>
                </form>
            </div>
        </section>

        <!-- Resume Section -->
        <section id="resume" class="resume">
            <div class="container">
                <h2>Resume</h2>
                <p>Download my resume or view my professional experience below.</p>
                <a href="#" class="btn">Download Resume</a>
            </div>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2026 Rubini Raju. All rights reserved.</p>
            <div class="social-links">
                <a href="#">LinkedIn</a>
                <a href="#">GitHub</a>
                <a href="#">Twitter</a>
            </div>
        </div>
    </footer>

    <script src="scripts.js"></script>
</body>
</html>
