# portfolio
project1htmlcode
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Riddhi Tiwari | Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: 'Poppins', sans-serif; background-color: #fef9f4; color: #222; }
    header { background: #000; color: #fff; padding: 1rem 2rem; display: flex; justify-content: space-between; align-items: center; }
    header nav a { color: #fff; margin-left: 1rem; text-decoration: none; font-weight: 600; }
    .hero { padding: 4rem 2rem; text-align: center; background: #fff8ee; }
    .hero h1 { font-size: 2.5rem; margin-bottom: 1rem; }
    .hero p { font-size: 1.2rem; }
    .section { padding: 3rem 2rem; }
    .projects { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 2rem; }
    .project-card { border: 1px solid #ddd; border-radius: 10px; padding: 1rem; background: #fff; }
    .project-card h3 { margin-bottom: 0.5rem; }
    .project-card a { color: #0077cc; text-decoration: none; font-size: 0.9rem; }
    footer { background: #000; color: #fff; padding: 1rem 2rem; text-align: center; margin-top: 2rem; }
  </style>
</head>
<body>
  <header>
    <h2>Riddhi Tiwari</h2>
    <nav>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Hello, I'm Riddhi 👋</h1>
    <p>A passionate developer & blogger. I build websites and share what I learn.</p>
  </section>

  <section id="about" class="section">
    <h2>About Me</h2>
    <p>I’m a Computer Science graduate from CSJM University (2022) with a strong interest in software development and teaching. Skilled in HTML, CSS, JavaScript, Python, and Git.</p>
  </section>

  <section id="projects" class="section">
    <h2>Projects</h2>
    <div class="projects">
      <div class="project-card">
        <h3>My First Web Project</h3>
        <p>A simple HTML/CSS website showcasing basic layout skills.</p>
        <a href="https://github.com/yourusername/project-name">View Code</a>
        <br>
        <a href="https://yourusername.github.io/project-name">Live Demo</a>
      </div>
      <!-- Add more projects here -->
    </div>
  </section>

  <section id="contact" class="section">
    <h2>Contact</h2>
    <p>Email: riddhi@example.com</p>
    <p>Instagram: <a href="https://instagram.com/yourusername">@yourusername</a></p>
    <p>LinkedIn: <a href="https://linkedin.com/in/yourusername">Riddhi Tiwari</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Riddhi Tiwari. All rights reserved.</p>
  </footer>
</body>
</html>
