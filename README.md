
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Kartheek | ECE Portfolio</title>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  scroll-behavior: smooth;
}

body {
  font-family: Arial, sans-serif;
  background: #0b1120;
  color: #e5e7eb;
  line-height: 1.7;
}

header {
  background: #111c32;
  padding: 18px 8%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
}

header h2 {
  color: #60a5fa;
}

nav a {
  color: white;
  text-decoration: none;
  margin: 8px;
  font-size: 14px;
}

nav a:hover {
  color: #60a5fa;
}

section {
  padding: 65px 10%;
  scroll-margin-top: 20px;
}

.hero {
  min-height: 75vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.hero h1 {
  font-size: 42px;
  color: white;
  margin: 12px 0;
}

.hero h1 span {
  color: #60a5fa;
}

.hero p {
  max-width: 650px;
  color: #bdc8da;
}

.tag {
  color: #60a5fa;
  font-weight: bold;
}

.btn {
  display: inline-block;
  background: #2563eb;
  color: white;
  padding: 11px 22px;
  border-radius: 7px;
  text-decoration: none;
  margin-top: 22px;
}

h2.title {
  font-size: 28px;
  color: #60a5fa;
  margin-bottom: 22px;
}

.card {
  background: #14213a;
  padding: 22px;
  border-radius: 12px;
  margin: 15px 0;
  border: 1px solid #293957;
}

.card h3 {
  color: #93c5fd;
  margin-bottom: 8px;
}

.skills {
  display: flex;
  gap: 12px;
  flex-wrap: wrap;
}

.skills span {
  background: #1e3a5f;
  padding: 9px 16px;
  border-radius: 20px;
  color: #bfdbfe;
}

ul {
  padding-left: 22px;
}

footer {
  text-align: center;
  padding: 25px;
  background: #111c32;
  color: #9ca3af;
}

a {
  color: #93c5fd;
}

@media(max-width:600px) {
  header {
    gap: 12px;
  }

  nav a {
    margin: 5px;
    font-size: 12px;
  }

  .hero h1 {
    font-size: 32px;
  }

  section {
    padding: 50px 7%;
  }
}
</style>
</head>

<body>

<header>
<h2>Kartheek.</h2>
<nav>
<a href="#home">Home</a>
<a href="#about">About</a>
<a href="#education">Education</a>
<a href="#skills">Skills</a>
<a href="#projects">Projects</a>
<a href="#contact">Contact</a>
</nav>
</header>

<!-- HOME -->

<section class="hero" id="home">
<p class="tag">HELLO, WELCOME TO MY PORTFOLIO</p>

<h1>Hi, I'm <span>Kartheek</span></h1>

<h2>Final-Year Electronics and Communication Engineering Student</h2>

<p>
Interested in VLSI Design, Digital Electronics, Verilog HDL
and Hardware Verification. Passionate about learning new
technologies and developing innovative solutions.
</p>

<a class="btn" href="#projects">Explore My Projects</a>
</section>

<!-- ABOUT ME -->

<section id="about">
<h2 class="title">About Me</h2>

<div class="card">
<p>
I am a final-year B.Tech student pursuing Electronics and
Communication Engineering (ECE), graduating in 2027.
I have a strong interest in VLSI Design, Digital Electronics,
and Hardware Verification.
</p>

<p>
I am familiar with MATLAB and Verilog HDL, with academic
project experience in digital design and verification.
I am passionate about learning new technologies, improving
my technical skills, and exploring opportunities in the
VLSI and semiconductor industry.
</p>
</div>
</section>

<!-- EDUCATION -->

<section id="education">
<h2 class="title">Education</h2>

<div class="card">
<h3>B.Tech - Electronics and Communication Engineering</h3>
<p>Final Year Student</p>
<p>Expected Graduation: 2027</p>
</div>
</section>

<!-- SKILLS -->

<section id="skills">
<h2 class="title">Technical Skills</h2>

<div class="skills">
<span>Verilog HDL</span>
<span>MATLAB</span>
<span>Digital Electronics</span>
<span>VLSI Fundamentals</span>
<span>Embedded Systems</span>
<span>SystemVerilog</span>
<span>Basic UVM</span>
<span>Communication Skills</span>
</div>
</section>

<!-- PROJECTS -->

<section id="projects">
<h2 class="title">Academic Projects</h2>

<div class="card">
<h3>PWM Controller Design and Verification</h3>
<p>
Academic project focused on designing a PWM controller
and developing an end-to-end UVM testbench to verify
duty-cycle variation and frequency control.
</p>
<p><b>Technologies:</b> Verilog, SystemVerilog, UVM</p>
</div>

<div class="card">
<h3>Automated Fabric Defect Detection Using Image Processing</h3>
<p>
Academic project focused on identifying fabric defects
using image processing techniques.
</p>
<p><b>Technology:</b> MATLAB, Image Processing</p>
</div>

<div class="card">
<h3>Smart Watch Monitoring for Differently-Abled People</h3>
<p>
First-year academic project focused on developing a
smart monitoring concept to support differently-abled people.
</p>
</div>
</section>

<!-- CONTACT -->

<section id="contact">
<h2 class="title">Contact Me</h2>

<div class="card">
<p>
I am open to internship opportunities and career
opportunities in the VLSI and Electronics domain.
</p>

<p>
Email:
<a href="mailto:YOUR_EMAIL@gmail.com">
YOUR_EMAIL@gmail.com
</a>
</p>

<p>
GitHub:
<a href="https://github.com/Kartheek2006" target="_blank">
github.com/Kartheek2006
</a>
</p>

<p>
LinkedIn: Add your LinkedIn profile link here
</p>
</div>
</section>

<footer>
<p>© 2026 Kartheek | Personal Portfolio</p>
<p>Designed with HTML and CSS</p>
</footer>

</body>
</html>
# Kartheek2006.github.io
My Personal Portfolio Website
