# Codealpha
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Madhumitha | Portfolio</title>

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial,sans-serif;
}

html{
    scroll-behavior:smooth;
}

body{
    background:#f5f5f5;
    color:#333;
}

/* Navigation */

nav{
    position:fixed;
    top:0;
    width:100%;
    background:#222;
    padding:15px 0;
    z-index:1000;
}

nav ul{
    display:flex;
    justify-content:center;
    list-style:none;
}

nav ul li{
    margin:0 20px;
}

nav ul li a{
    text-decoration:none;
    color:white;
    font-weight:bold;
    transition:0.3s;
}

nav ul li a:hover{
    color:orange;
}

/* Hero Section */

.hero{
    height:100vh;
    display:flex;
    flex-direction:column;
    justify-content:center;
    align-items:center;
    text-align:center;
    background:linear-gradient(135deg,#4facfe,#00f2fe);
    color:white;
}

.hero h1{
    font-size:3rem;
    animation:fadeIn 2s;
}

.hero p{
    margin-top:15px;
    font-size:1.2rem;
}

.btn{
    display:inline-block;
    margin-top:20px;
    padding:12px 25px;
    background:white;
    color:#333;
    text-decoration:none;
    border-radius:5px;
    transition:0.3s;
}

.btn:hover{
    transform:scale(1.05);
}

/* Sections */

section{
    padding:80px 10%;
}

section h2{
    text-align:center;
    margin-bottom:30px;
    color:#222;
}

/* About */

.about{
    text-align:center;
    line-height:1.8;
}

/* Skills */

.skills-container{
    display:flex;
    flex-wrap:wrap;
    justify-content:center;
    gap:15px;
}

.skill{
    background:#222;
    color:white;
    padding:12px 20px;
    border-radius:30px;
    transition:0.3s;
}

.skill:hover{
    background:orange;
    transform:translateY(-5px);
}

/* Projects */

.projects{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.project-card{
    background:white;
    padding:20px;
    border-radius:10px;
    box-shadow:0 4px 10px rgba(0,0,0,0.1);
    transition:0.3s;
}

.project-card:hover{
    transform:translateY(-8px);
}

.project-card h3{
    margin-bottom:10px;
}

/* Resume */

.resume{
    text-align:center;
}

/* Contact */

.contact{
    text-align:center;
    line-height:2;
}

/* Footer */

footer{
    background:#222;
    color:white;
    text-align:center;
    padding:15px;
}

/* Animation */

@keyframes fadeIn{
    from{
        opacity:0;
        transform:translateY(30px);
    }
    to{
        opacity:1;
        transform:translateY(0);
    }
}

/* Responsive */

@media(max-width:768px){

    .hero h1{
        font-size:2.2rem;
    }

    nav ul{
        flex-wrap:wrap;
    }
}

</style>
</head>
<body>

<!-- Navigation -->

<nav>
    <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#resume">Resume</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
</nav>

<!-- Hero Section -->

<div class="hero">

    <h1>Hello, I'm Madhumitha</h1>

    <p>Web Developer | Student | Tech Enthusiast</p>

    <a href="#about" class="btn">Explore Portfolio</a>

</div>

<!-- About -->

<section id="about">

    <h2>About Me</h2>

    <div class="about">

        <p>
            I am Madhumitha, a passionate student interested in
            Web Development, Programming and Technology.
            I enjoy creating responsive websites and learning
            new technologies to improve my skills.
        </p>

    </div>

</section>

<!-- Skills -->

<section id="skills">

    <h2>Skills</h2>

    <div class="skills-container">

        <div class="skill">HTML</div>
        <div class="skill">CSS</div>
        <div class="skill">JavaScript</div>
        <div class="skill">Bootstrap</div>
        <div class="skill">Python</div>
        <div class="skill">Git & GitHub</div>

    </div>

</section>

<!-- Projects -->

<section id="projects">

    <h2>Projects</h2>

    <div class="projects">

        <div class="project-card">
            <h3>Image Gallery</h3>
            <p>
                Responsive image gallery with lightbox,
                filters and navigation.
            </p>
        </div>

        <div class="project-card">
            <h3>Calculator</h3>
            <p>
                Interactive calculator built using
                HTML, CSS and JavaScript.
            </p>
        </div>

        <div class="project-card">
            <h3>Portfolio Website</h3>
            <p>
                Personal portfolio showcasing skills,
                projects and contact details.
            </p>
        </div>

    </div>

</section>

<!-- Resume -->

<section id="resume">

    <h2>Resume</h2>

    <div class="resume">

        <p>Click below to download my resume.</p>

        <br>

        <a href="resume.pdf" class="btn" download>
            Download Resume
        </a>

    </div>

</section>

<!-- Contact -->

<section id="contact">

    <h2>Contact Me</h2>

    <div class="contact">

        <p>Email: madhumitha@example.com</p>

        <p>Phone: +91 XXXXX XXXXX</p>

        <p>LinkedIn: linkedin.com/in/yourprofile</p>

        <p>GitHub: github.com/yourusername</p>

    </div>

</section>

<!-- Footer -->

<footer>

    <p>&copy; 2026 Madhumitha. All Rights Reserved.</p>

</footer>

</body>
</html>
