<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f5f5f5;
      color: #333;
    }
    header {
      background: #1e293b;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    nav {
      margin-top: 10px;
    }
    nav a {
      color: #fff;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 50px 20px;
      max-width: 900px;
      margin: auto;
    }
    .skills, .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .card {
      background: #fff;
      border-radius: 10px;
      padding: 20px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    }
    .card h3 {
      margin-top: 0;
    }
    footer {
      background: #1e293b;
      color: #fff;
      text-align: center;
      padding: 20px;
      margin-top: 30px;
    }
    button {
      background: #1e40af;
      color: white;
      border: none;
      padding: 10px 20px;
      border-radius: 5px;
      cursor: pointer;
      margin-top: 10px;
    }
    button:hover {
      background: #2563eb;
    }
  </style>
</head>
<body>

  <header>
    <h1>👨‍💻 VISHWANATH</h1>
    <p>APP Developer | Programmer | Learner</p>
    <nav>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>Hello! I am a B.Tech CSE student passionate about coding, App development, and problem-solving. I love building projects and learning new technologies.</p>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <div class="skills">
      <div class="card"><h3>Programming</h3><p> Dart, Kotlin, Python</p></div>
      <div class="card"><h3>Web</h3><p>HTML, CSS, JavaScript, </p></div>
      <div class="card"><h3>Frameworks</h3><p>Flutter, React.js, Node.js</p></div>
    </div>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="projects">
      <div class="card">
        <h3>Wheather App</h3>
        <p>Flutter Weather Application with API </p>
        <button onclick="alert('Link to GitHub Repo')">View Project</button>
      </div>
      <div class="card">
        <h3>ToDo App</h3>
        <p>Flutter Todo List App With Firebase & Riverpod Architecture.</p>
        <button onclick="alert('Link to Live Demo')">View Project</button>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <p>Email: <a href="mailto:your.email@example.com">v8408382@gmail.com</a></p>
   
  </section>

  <footer>
    <p>©  Vishu 2025 | All Rights Reserved</p>
  </footer>

</body>
</html>

