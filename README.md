# MDAP-EX_01-Portfolio
## Date:

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
###index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jenil Pio - Portfolio (No JavaScript)</title>
    <link rel="stylesheet" href="styles.css">

    <!--
        HUMAN-READABLE NOTES:
        - Smooth scrolling for nav links was previously handled by JavaScript (removed).
        - Contact form previously submitted via JS and showed a modal "Thank you" message — now it uses plain HTML form behaviour.
        - Navbar background previously changed on scroll — now it stays fixed with one style.
        - All animations and hover effects are preserved with CSS.
        - For modal behaviour, smooth scroll, and dynamic navbar, reintroduce equivalent JS.
    -->
</head>
<body>
    <!-- Navigation Bar -->
    <nav class="navbar">
        <div class="nav-container">
            <div class="logo">Portfolio</div>
            <ul class="nav-links">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="container">
            <h1>Jenil Pio</h1>
            <p>Full Stack Developer & UI/UX Designer</p>
            <a href="#projects" class="cta-button">View My Work</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
        <div class="container">
            <div class="about-content">
                <div class="profile-image">
                    👨‍💻
                </div>
                <div class="about-text">
                    <h2>About Me</h2>
                    <p>I'm a passionate full-stack developer with 3+ years of experience creating beautiful, functional web applications. I love turning complex problems into simple, elegant solutions.</p>
                    <p>When I'm not coding, you can find me exploring new technologies, contributing to open-source projects, or enjoying a good cup of coffee while reading about the latest web development trends.</p>
                    <div class="skills">
                        <span class="skill-tag">JavaScript</span>
                        <span class="skill-tag">React</span>
                        <span class="skill-tag">Node.js</span>
                        <span class="skill-tag">Python</span>
                        <span class="skill-tag">CSS</span>
                        <span class="skill-tag">HTML</span>
                        <span class="skill-tag">MongoDB</span>
                        <span class="skill-tag">Git</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="projects">
        <div class="container">
            <h2 class="section-title">My Projects</h2>
            <div class="projects-grid">
                <div class="project-card">
                    <div class="project-image">🌐</div>
                    <div class="project-content">
                        <h3>E-Commerce Website</h3>
                        <p>A full-stack e-commerce platform built with React and Node.js, featuring user authentication, payment integration, and admin dashboard.</p>
                        <a href="#" class="project-link">View Project →</a>
                    </div>
                </div>
                <div class="project-card">
                    <div class="project-image">📱</div>
                    <div class="project-content">
                        <h3>Task Management App</h3>
                        <p>A responsive task management application with drag-and-drop functionality, real-time updates, and team collaboration features.</p>
                        <a href="#" class="project-link">View Project →</a>
                    </div>
                </div>
                <div class="project-card">
                    <div class="project-image">🎨</div>
                    <div class="project-content">
                        <h3>Portfolio Website</h3>
                        <p>A modern, responsive portfolio website showcasing creative design and smooth animations, built with HTML, CSS, and JavaScript.</p>
                        <a href="#" class="project-link">View Project →</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <div class="container">
            <h2 class="section-title">Get In Touch</h2>
            <div class="contact-content">
                <div class="contact-info">
                    <h3>Contact Information</h3>
                    <div class="contact-item">
                        <span>📧</span>
                        <span>jenil.pio@email.com</span>
                    </div>
                    <div class="contact-item">
                        <span>📱</span>
                        <span>+1 (555) 123-4567</span>
                    </div>
                    <div class="contact-item">
                        <span>📍</span>
                        <span>New York, NY</span>
                    </div>
                    <div class="contact-item">
                        <span>💼</span>
                        <span>linkedin.com/in/jenilpio</span>
                    </div>
                </div>
                <!--
                    Originally the form submission was intercepted by JS to show a modal confirmation.
                    Now it will submit to the action URL (set it to your email backend or form handler).
                -->
                <form class="contact-form" action="#" method="post">
                    <div class="form-group">
                        <label for="name">Name</label>
                        <input type="text" id="name" name="name" required>
                    </div>
                    <div class="form-group">
                        <label for="email">Email</label>
                        <input type="email" id="email" name="email" required>
                    </div>
                    <div class="form-group">
                        <label for="message">Message</label>
                        <textarea id="message" name="message" rows="5" required></textarea>
                    </div>
                    <button type="submit" class="submit-btn">Send Message</button>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <p>&copy; 2024 Jenil Pio. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
```
###style.css
```
/* styles.css - extracted from inline styles in original HTML */

/* Global Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.6;
    color: #333;
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    min-height: 100vh;
}

/* Navigation Bar */
.navbar {
    position: fixed;
    top: 0;
    width: 100%;
    background: rgba(255, 255, 255, 0.95);
    backdrop-filter: blur(10px);
    padding: 1rem 0;
    z-index: 1000;
    box-shadow: 0 2px 20px rgba(0, 0, 0, 0.1);
}

.nav-container {
    max-width: 1200px;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0 2rem;
}

.logo {
    font-size: 1.5rem;
    font-weight: bold;
    color: #667eea;
}

.nav-links {
    display: flex;
    list-style: none;
    gap: 2rem;
}

.nav-links a {
    text-decoration: none;
    color: #333;
    font-weight: 500;
    transition: color 0.3s ease;
    position: relative;
}

.nav-links a:hover {
    color: #667eea;
}

.nav-links a::after {
    content: '';
    position: absolute;
    width: 0;
    height: 2px;
    bottom: -5px;
    left: 0;
    background-color: #667eea;
    transition: width 0.3s ease;
}

.nav-links a:hover::after {
    width: 100%;
}

/* Main Container */
.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 2rem;
}

/* Sections */
section {
    padding: 5rem 0;
    margin-top: 80px;
}

section:first-of-type {
    margin-top: 0;
}

/* Hero Section */
.hero {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
    text-align: center;
    padding: 8rem 0;
    margin-top: 0;
}

.hero h1 {
    font-size: 3.5rem;
    margin-bottom: 1rem;
    animation: fadeInUp 1s ease;
}

.hero p {
    font-size: 1.2rem;
    margin-bottom: 2rem;
    animation: fadeInUp 1s ease 0.2s both;
}

.cta-button {
    display: inline-block;
    background: white;
    color: #667eea;
    padding: 1rem 2rem;
    text-decoration: none;
    border-radius: 50px;
    font-weight: bold;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    animation: fadeInUp 1s ease 0.4s both;
}

.cta-button:hover {
    transform: translateY(-3px);
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
}

/* About Section */
.about {
    background: white;
    padding: 5rem 0;
}

.about-content {
    display: grid;
    grid-template-columns: 1fr 2fr;
    gap: 3rem;
    align-items: center;
}

.profile-image {
    width: 300px;
    height: 300px;
    border-radius: 50%;
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 4rem;
    color: white;
    margin: 0 auto;
    box-shadow: 0 20px 40px rgba(0, 0, 0, 0.1);
}

.about-text h2 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
    color: #333;
}

.about-text p {
    font-size: 1.1rem;
    margin-bottom: 1.5rem;
    color: #666;
}

.skills {
    display: flex;
    flex-wrap: wrap;
    gap: 1rem;
    margin-top: 2rem;
}

.skill-tag {
    background: #667eea;
    color: white;
    padding: 0.5rem 1rem;
    border-radius: 25px;
    font-size: 0.9rem;
    transition: transform 0.3s ease;
}

.skill-tag:hover {
    transform: scale(1.05);
}

/* Projects Section */
.projects {
    background: #f8f9fa;
    padding: 5rem 0;
}

.section-title {
    text-align: center;
    font-size: 2.5rem;
    margin-bottom: 3rem;
    color: #333;
}

.projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 2rem;
}

.project-card {
    background: white;
    border-radius: 15px;
    overflow: hidden;
    box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.project-card:hover {
    transform: translateY(-10px);
    box-shadow: 0 20px 40px rgba(0, 0, 0, 0.15);
}

.project-image {
    height: 200px;
    background: linear-gradient(45deg, #667eea, #764ba2);
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 3rem;
    color: white;
}

.project-content {
    padding: 1.5rem;
}

.project-content h3 {
    font-size: 1.3rem;
    margin-bottom: 1rem;
    color: #333;
}

.project-content p {
    color: #666;
    margin-bottom: 1rem;
}

.project-link {
    color: #667eea;
    text-decoration: none;
    font-weight: bold;
    transition: color 0.3s ease;
}

.project-link:hover {
    color: #764ba2;
}

/* Contact Section */
.contact {
    background: white;
    padding: 5rem 0;
}

.contact-content {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 3rem;
}

.contact-info h3 {
    font-size: 1.5rem;
    margin-bottom: 1rem;
    color: #333;
}

.contact-item {
    display: flex;
    align-items: center;
    margin-bottom: 1rem;
    font-size: 1.1rem;
    color: #666;
}

.contact-item span {
    margin-right: 1rem;
    font-size: 1.2rem;
}

.contact-form {
    background: #f8f9fa;
    padding: 2rem;
    border-radius: 15px;
}

.form-group {
    margin-bottom: 1.5rem;
}

.form-group label {
    display: block;
    margin-bottom: 0.5rem;
    color: #333;
    font-weight: 500;
}

.form-group input,
.form-group textarea {
    width: 100%;
    padding: 1rem;
    border: 2px solid #e9ecef;
    border-radius: 10px;
    font-size: 1rem;
    transition: border-color 0.3s ease;
}

.form-group input:focus,
.form-group textarea:focus {
    outline: none;
    border-color: #667eea;
}

.submit-btn {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
    padding: 1rem 2rem;
    border: none;
    border-radius: 50px;
    font-size: 1rem;
    font-weight: bold;
    cursor: pointer;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.submit-btn:hover {
    transform: translateY(-2px);
    box-shadow: 0 10px 30px rgba(102, 126, 234, 0.3);
}

/* Footer */
.footer {
    background: #333;
    color: white;
    text-align: center;
    padding: 2rem 0;
}

/* Animations */
@keyframes fadeInUp {
    from {
        opacity: 0;
        transform: translateY(30px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

/* Responsive Design */
@media (max-width: 768px) {
    .nav-links {
        display: none;
    }

    .hero h1 {
        font-size: 2.5rem;
    }

    .about-content {
        grid-template-columns: 1fr;
        text-align: center;
    }

    .contact-content {
        grid-template-columns: 1fr;
    }

    .profile-image {
        width: 200px;
        height: 200px;
        font-size: 3rem;
    }
}
```


## OUTPUT
<img width="1919" height="1078" alt="Screenshot 2025-08-12 101744" src="https://github.com/user-attachments/assets/ba04a2d8-b3a5-4bac-a806-47d43a720a45" />
<img width="1919" height="1079" alt="Screenshot 2025-08-12 101802" src="https://github.com/user-attachments/assets/68ec595d-5ad6-40c0-b259-a5edf9caedd3" />
<img width="1919" height="1079" alt="Screenshot 2025-08-12 101819" src="https://github.com/user-attachments/assets/7ef8b2ad-b89b-4302-847a-d0790d3b6fda" />
<img width="1919" height="1074" alt="Screenshot 2025-08-12 101834" src="https://github.com/user-attachments/assets/7ba57524-b09b-4c52-bc73-656bdb8cc469" />




## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
