<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My Portfolio</title>

<!-- Bootstrap CSS -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

<style>
html{
    scroll-behavior:smooth;
}

body{
    font-family: Arial, sans-serif;
}

.hero{
    height:100vh;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
    background:linear-gradient(135deg,#0d6efd,#6610f2);
    color:white;
}

section{
    padding:80px 0;
}

.card{
    transition:0.3s;
}

.card:hover{
    transform:translateY(-5px);
}

footer{
    background:#212529;
    color:white;
    padding:20px;
    text-align:center;
}
</style>
</head>

<body>

<!-- Navbar -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark fixed-top">
<div class="container">
<a class="navbar-brand" href="#">Portfolio</a>

<button class="navbar-toggler" type="button"
data-bs-toggle="collapse"
data-bs-target="#navbarNav">
<span class="navbar-toggler-icon"></span>
</button>

<div class="collapse navbar-collapse" id="navbarNav">
<ul class="navbar-nav ms-auto">
<li class="nav-item">
<a class="nav-link" href="#home">Home</a>
</li>

<li class="nav-item">
<a class="nav-link" href="#skills">Skills</a>
</li>

<li class="nav-item">
<a class="nav-link" href="#projects">Projects</a>
</li>

<li class="nav-item">
<a class="nav-link" href="#contact">Contact</a>
</li>
</ul>
</div>
</div>
</nav>

<!-- Home -->
<section id="home" class="hero">
<div class="container">
<h1>Hello, I'm Ayush Singh</h1>
<p class="lead">Web Developer | Python Developer | Student</p>
<a href="#projects" class="btn btn-light btn-lg">
View Projects
</a>
</div>
</section>

<!-- Skills -->
<section id="skills">
<div class="container">
<h2 class="text-center mb-5">Skills</h2>

<div class="row text-center">
<div class="col-md-3 mb-3">
<div class="card p-3">
<h5>HTML</h5>
</div>
</div>

<div class="col-md-3 mb-3">
<div class="card p-3">
<h5>CSS</h5>
</div>
</div>

<div class="col-md-3 mb-3">
<div class="card p-3">
<h5>Bootstrap</h5>
</div>
</div>

<div class="col-md-3 mb-3">
<div class="card p-3">
<h5>Python</h5>
</div>
</div>
</div>
</div>
</section>

<!-- Projects -->
<section id="projects" class="bg-light">
<div class="container">
<h2 class="text-center mb-5">Projects</h2>

<div class="row">

<div class="col-md-4 mb-4">
<div class="card">
<div class="card-body">
<h5 class="card-title">Portfolio Website</h5>
<p>Responsive personal portfolio website.</p>
</div>
</div>
</div>

<div class="col-md-4 mb-4">
<div class="card">
<div class="card-body">
<h5 class="card-title">Student Management System</h5>
<p>Python-based student management project.</p>
</div>
</div>
</div>

<div class="col-md-4 mb-4">
<div class="card">
<div class="card-body">
<h5 class="card-title">Calculator App</h5>
<p>Simple calculator using HTML, CSS & JS.</p>
</div>
</div>
</div>

</div>
</div>
</section>

<!-- Contact -->
<section id="contact">
<div class="container">
<h2 class="text-center mb-5">Contact Me</h2>

<div class="row justify-content-center">
<div class="col-md-6">

<form>
<input type="text" class="form-control mb-3"
placeholder="Your Name">

<input type="email" class="form-control mb-3"
placeholder="Your Email">

<textarea class="form-control mb-3"
rows="5"
placeholder="Your Message"></textarea>

<button class="btn btn-primary w-100">
Send Message
</button>

</form>

</div>
</div>
</div>
</section>

<!-- Footer -->
<footer>
<p>© 2026 Ayush Singh | All Rights Reserved</p>
</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html># portfolio--website
GitHub Repository Description:  🌐 Responsive Portfolio Website  A modern and fully responsive personal portfolio website built using HTML, CSS, and Bootstrap. The website includes Home, Skills, Projects, and Contact sections with smooth scrolling navigation and a mobile-friendly design.  Features  ✅ Responsive Design for all devices ✅
