---
layout: default
---

<section id="hero" class="hero">
    <div class="container">
        <h1>Hi, I'm {{ site.title | split: '-' | first }}</h1>
        <p>Software Developer passionate about creating elegant solutions to complex problems</p>
    </div>
</section>

<section id="about">
    <div class="container">
        <h2>About Me</h2>
        <p>I'm a software developer with expertise in modern web technologies and a passion for building scalable applications. I enjoy working on challenging projects and continuously learning new technologies.</p>
    </div>
</section>

<section id="skills">
    <div class="container">
        <h2>Skills & Technologies</h2>
        <div class="skills-grid">
            <div class="skill">
                <i class="fab fa-js"></i>
                <h3>JavaScript/TypeScript</h3>
                <p>Modern ES6+, React, Node.js</p>
            </div>
            <div class="skill">
                <i class="fab fa-python"></i>
                <h3>Python</h3>
                <p>Django, FastAPI, Data Analysis</p>
            </div>
            <div class="skill">
                <i class="fas fa-database"></i>
                <h3>Databases</h3>
                <p>SQL Server, Oracle, MySQL</p>
            </div>
            <div class="skill">
                <i class="fab fa-aws"></i>
                <h3>Cloud & DevOps</h3>
                <p>Azure, AWS, Docker, CI/CD</p>
            </div>
        </div>
    </div>
</section>

<section id="projects">
    <div class="container">
        <h2>Featured Projects</h2>
        <div class="project-grid">
            <div class="project-card">
                <div class="project-content">
                    <h3>Project Name 1</h3>
                    <p>A brief description of your project and what technologies you used.</p>
                    <a href="#" class="project-link">View Project</a>
                </div>
            </div>
            <div class="project-card">
                <div class="project-content">
                    <h3>Project Name 2</h3>
                    <p>A brief description of your project and what technologies you used.</p>
                    <a href="#" class="project-link">View Project</a>
                </div>
            </div>
            <div class="project-card">
                <div class="project-content">
                    <h3>Project Name 3</h3>
                    <p>A brief description of your project and what technologies you used.</p>
                    <a href="#" class="project-link">View Project</a>
                </div>
            </div>
        </div>
    </div>
</section>

<section id="contact">
    <div class="container">
        <h2>Get in Touch</h2>
        <p>I'm always interested in hearing about new projects and opportunities. Feel free to connect with me on social media or send me an email.</p>
        <div class="social-links">
            {% if site.github_username %}
            <a href="https://github.com/{{ site.github_username }}" target="_blank"><i class="fab fa-github"></i></a>
            {% endif %}
            {% if site.linkedin_username %}
            <a href="https://linkedin.com/in/{{ site.linkedin_username }}" target="_blank"><i class="fab fa-linkedin"></i></a>
            {% endif %}
            {% if site.twitter_username %}
            <a href="https://twitter.com/{{ site.twitter_username }}" target="_blank"><i class="fab fa-twitter"></i></a>
            {% endif %}
        </div>
    </div>
</section>