# portfolio-
sayali vikas ghadshi

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sayali Vikas Ghadshi | Portfolio</title>

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, Helvetica, sans-serif;
}
body{
    background:#f4f6f8;
    color:#333;
}
header{
    background:#0f172a;
    color:#fff;
    padding:60px 20px;
    text-align:center;
}
header h1{
    font-size:40px;
}
header p{
    margin-top:10px;
    font-size:18px;
    color:#cbd5f5;
}
nav{
    background:#020617;
    padding:12px;
    text-align:center;
    position:sticky;
    top:0;
}
nav a{
    color:#fff;
    margin:0 15px;
    text-decoration:none;
    font-weight:bold;
}
nav a:hover{
    color:#38bdf8;
}
section{
    padding:60px 20px;
    max-width:1100px;
    margin:auto;
}
h2{
    text-align:center;
    margin-bottom:40px;
    color:#0f172a;
    font-size:32px;
}
.about{
    text-align:center;
    font-size:18px;
    line-height:1.6;
}
.skills{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}
.card{
    background:#fff;
    padding:25px;
    border-radius:10px;
    box-shadow:0 5px 15px rgba(0,0,0,0.1);
}
.card h3{
    margin-bottom:15px;
    color:#020617;
}
.card ul{
    margin-left:20px;
}
.projects{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
    gap:25px;
}
.project{
    background:#fff;
    padding:25px;
    border-radius:10px;
    box-shadow:0 5px 15px rgba(0,0,0,0.1);
}
.project h3{
    margin-bottom:10px;
}
.contact{
    text-align:center;
}
.contact p{
    font-size:18px;
    margin:10px 0;
}
.social a{
    margin:0 10px;
    font-size:22px;
    color:#0f172a;
}
.social a:hover{
    color:#38bdf8;
}
footer{
    background:#020617;
    color:#fff;
    text-align:center;
    padding:20px;
    margin-top:40px;
}
button{
    background:#0ea5e9;
    border:none;
    color:#fff;
    padding:12px 25px;
    border-radius:25px;
    font-size:16px;
    cursor:pointer;
}
button:hover{
    background:#0284c7;
}
</style>
</head>

<body>

<header>
    <h1>Sayali Vikas Ghadshi</h1>
    <p>Full Stack Web Developer | AI Enthusiast | Digital Marketing Specialist</p>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
</nav>

<section id="about">
    <h2>About Me</h2>
    <p class="about">
        I am a Full Stack Web Developer and AI enthusiast with experience in building
        responsive, client-ready websites and web applications. I work with modern
        technologies like React, Angular, Node.js, PHP, SQL, and AI tools to create
        scalable digital solutions. I also have strong experience in digital marketing
        and entrepreneurship.
    </p>
</section>

<section id="skills">
    <h2>Skills</h2>
    <div class="skills">

        <div class="card">
            <h3>Frontend</h3>
            <ul>
                <li>HTML5, CSS3, JavaScript</li>
                <li>React.js</li>
                <li>Angular</li>
                <li>Responsive Design</li>
            </ul>
        </div>

        <div class="card">
            <h3>Backend</h3>
            <ul>
                <li>Node.js</li>
                <li>PHP</li>
                <li>REST APIs</li>
            </ul>
        </div>

        <div class="card">
            <h3>Database</h3>
            <ul>
                <li>SQL / MySQL</li>
            </ul>
        </div>

        <div class="card">
            <h3>AI & Automation</h3>
            <ul>
                <li>AI Tools (ChatGPT, AI APIs)</li>
                <li>Prompt Engineering</li>
                <li>AI Content Generation</li>
            </ul>
        </div>

        <div class="card">
            <h3>Digital Marketing</h3>
            <ul>
                <li>Social Media Marketing</li>
                <li>SEO Basics</li>
                <li>Email & WhatsApp Automation</li>
            </ul>
        </div>

    </div>
</section>

<section id="projects">
    <h2>Projects</h2>

    <div class="projects">

        <div class="project">
            <h3>EcoBliss Botanicals / SnowySilk</h3>
            <p>
                Eco-friendly skincare brand website with product pages,
                contact forms, branding, and AI-assisted content creation.
            </p>
        </div>

        <div class="project">
            <h3>Client Website Templates</h3>
            <p>
                Reusable website templates for law firms, marketing agencies,
                and beauty brands using HTML, CSS, and JavaScript.
            </p>
        </div>

        <div class="project">
            <h3>Full Stack & AI Projects</h3>
            <p>
                CRUD applications using Node.js & SQL, frontend with React
                and Angular, and AI tools for automation and optimization.
            </p>
        </div>

    </div>
</section>

<section id="contact">
    <h2>Contact Me</h2>
    <div class="contact">
        <p>📍 India</p>
        <p>📞 7977193279</p>
        <p>📧 ghadshisayali2@gmail.com</p>
        <br>
        <button onclick="alert('Thank you for visiting my portfolio!')">
            Hire Me
        </button>

        <div class="social" style="margin-top:20px;">
            <a href="#"><i class="fab fa-linkedin"></i></a>
            <a href="#"><i class="fab fa-github"></i></a>
            <a href="#"><i class="fab fa-instagram"></i></a>
        </div>
    </div>
</section>

<footer>
    © 2025 Sayali Vikas Ghadshi | Portfolio
</footer>

</body>
</html>
