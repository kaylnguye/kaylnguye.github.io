<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Kayla Nguyen | Chemical Engineering</title>

<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">

<style>

/* Smooth Scrolling */
html {
  scroll-behavior: smooth;
}

/* Global */
body {
  font-family: 'Helvetica Neue', sans-serif;
  background-color: #f7f5f2;
  color: #4a4a4a;
  margin: 0;
}

/* Navbar */
.navbar {
  background-color: #1f1f1f;
  padding: 15px 0;
}

.navbar-brand {
  color: white !important;
  font-weight: bold;
}

.nav-link {
  color: white !important;
  margin-left: 20px;
  text-decoration: none;
}

/* Hero */
.hero {
  padding: 160px 0 120px 0;
  background: #eae6df;
  text-align: center;
}

.hero h1 {
  font-size: 3rem;
  font-weight: 600;
}

.section {
  padding: 100px 0;
}

.alt-bg {
  background-color: #eae6df;
}

/* Project Cards */
.project-card {
  background: white;
  padding: 30px;
  border-radius: 12px;
  transition: 0.3s ease;
  margin-bottom: 30px;
}

.project-card:hover {
  transform: translateY(-8px);
}

/* Skills */
.skills-list {
  list-style: none;
  padding: 0;
}

.skills-list li {
  display: inline-block;
  background: #8c6f5c;
  color: white;
  padding: 8px 15px;
  margin: 5px;
  border-radius: 20px;
}

/* Buttons */
.custom-btn {
  background-color: #8c6f5c;
  color: white;
  border: none;
  padding: 10px 20px;
  text-decoration: none;
  border-radius: 6px;
}

.custom-btn:hover {
  background-color: #6f5647;
}

/* Research Section Hidden by Default */
#alpha-alumina {
  display: none;
}

/* Footer */
footer {
  background-color: #1f1f1f;
  color: white;
  padding: 40px 0;
  text-align: center;
}

</style>
</head>

<body>

<nav class="navbar navbar-expand-lg fixed-top">
  <div class="container">
    <a class="navbar-brand" href="#">Kayla Nguyen</a>
    <div>
      <a class="nav-link" href="#about">About</a>
      <a class="nav-link" href="#projects">Projects</a>
      <a class="nav-link" href="#skills">Skills</a>
      <a class="nav-link" href="#fun">Fun</a>
      <a class="nav-link" href="#contact">Contact</a>
    </div>
  </div>
</nav>

<!-- HERO -->
<section class="hero">
  <div class="container">
    <h1>Kayla Nguyen</h1>
    <p class="lead">Chemical Engineering Major</p>
    <p>Interested in Petrochemicals & Pharmaceuticals</p>
  </div>
</section>

<!-- ABOUT -->
<section id="about" class="section">
  <div class="container">
    <h2>About Me</h2>
    <p>
      I am a Chemical Engineering student passionate about catalysis,
      crystallization, and industrial process optimization. My academic
      interests span petrochemical systems and pharmaceutical development.
    </p>
  </div>
</section>

<!-- PROJECTS -->
<section id="projects" class="section alt-bg">
  <div class="container">
    <h2>Research & Projects</h2>
    <div class="row">

      <div class="col-md-6">
        <div class="project-card">
          <h4>Tuning Morphology of Alpha-Alumina as a Catalyst Support</h4>
          <p>Engineering catalyst supports to improve EO catalytic performance.</p>
          <button class="custom-btn" onclick="showResearch()">View Research</button>
        </div>
      </div>

      <div class="col-md-6">
        <div class="project-card">
          <h4>Template-Induced Nucleation of Pyrazinamide</h4>
          <p>Studied pharmaceutical crystallization via fatty acid templating strategies.</p>
        </div>
      </div>

    </div>
  </div>
</section>

<!-- ALPHA ALUMINA RESEARCH PAGE (Embedded Section) -->
<section id="alpha-alumina" class="section">
  <div class="container">
    <h2>Alpha-Alumina Catalyst Support Research</h2>

    <p>
      This research focuses on tuning the morphology of alpha-alumina
      to optimize surface area, porosity, and catalyst-support interactions
      for enhanced ethylene oxide production efficiency.
    </p>

    <h4>Research Objectives</h4>
    <ul>
      <li>Control particle morphology</li>
      <li>Enhance pore structure</li>
      <li>Improve catalytic stability</li>
    </ul>

    <button class="custom-btn" onclick="hideResearch()">Back to Main Page</button>
  </div>
</section>

<!-- SKILLS -->
<section id="skills" class="section">
  <div class="container">
    <h2>Technical Skills</h2>
    <ul class="skills-list">
      <li>Microsoft Office</li>
      <li>LaTeX</li>
      <li>Java</li>
      <li>Python</li>
      <li>MATLAB</li>
    </ul>
  </div>
</section>

<!-- FUN FACTS -->
<secti
