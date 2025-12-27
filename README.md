<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SRIRAM | Portfolio</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background-color: #e7e6eceb;
      color: #333;
      line-height: 1.6;
    }

    header {
      background: #0a2540;
      color: white;
      padding: 60px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 2.5rem;
    }

    header p {
      margin: 10px 0;
      font-size: 1.2rem;
    }

    nav {
      margin-top: 15px;
    }

    nav a {
      color: white;
      margin: 0 10px;
      text-decoration: none;
      font-weight: bold;
    }

    section {
      padding: 50px 20px;
      max-width: 1000px;
      margin: auto;
    }

    h2 {
      margin-bottom: 20px;
      color: #0a2540;
      text-align: center;
    }

    .about, .education, .contact {
      text-align: center;
    }

    .skills, .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
    }

    .card {
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      text-align: center;
    }

    .card h3 {
      margin-bottom: 10px;
      color: #0a2540;
    }

    .card a {
      display: inline-block;
      margin-top: 10px;
      color: #0a2540;
      text-decoration: none;
      font-weight: bold;
    }

    footer {
      background: #0a2540;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 2rem;
      }

      header p {
        font-size: 1rem;
      }
    }
  </style>
</head>

<body>

    }
  <header>
    <h1>SRIRAM</h1>
    <p>Computer Science Student | Web Developer</p>
    <nav>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>


  <section id="about" class="about">
    <h2>About Me</h2>
    <p>
      I am a college student at Bannari Amman Institute of Technology with a strong interest
      in web development and software engineering. I enjoy building responsive and user-friendly
      web applications.
    </p>
  </section>

  
  <section class="education">
    <h2>Education</h2>
    <p>
      <strong>B.E – Computer Science Engineering</strong><br>
      Bannari Amman Institute of Technology<br>
      2024 – 2028
    </p>
  </section>

  
  <section id="skills">
    <h2>Skills</h2>
    <div class="skills">
      <div class="card">HTML</div>
      <div class="card">CSS</div>
      <div class="card">JavaScript</div>
      <div class="card">React</div>
      <div class="card">Node.js</div>
      <div class="card">Java</div>
    </div>
  </section>

  
  <section id="projects">
    <h2>Projects</h2>
    <div class="projects">
      <div class="card">
        <h3>ReWear</h3>
        <p>Community clothing exchange platform for sustainable fashion.</p>
        <p><strong>Tech:</strong> React, Node.js</p>
        <a href="#">View Project</a>
      </div>

      <div class="card">
        <h3>Smart Darshan Booking</h3>
        <p>Online booking system with slot management and payments.</p>
        <p><strong>Tech:</strong> React, Express</p>
        <a href="#">View Project</a>
      </div>

      <div class="card">
        <h3>Farm Smart</h3>
        <p>Smart agriculture solution for farmers.</p>
        <p><strong>Tech:</strong> Web Technologies</p>
        <a href="#">View Project</a>
      </div>
    </div>
  </section>

  
  <section id="contact" class="contact">
    <h2>Contact</h2>
    <p>Email: sriramr.cs24@bitsathy.ac.in</p>
    <p>GitHub: https://github.com/SRIRAMtech143</p>
    <p>LinkedIn: www.linkedin.com/in/sri-ram-r-b14633361</p>
  </section>

  <footer>
    <p>© 2025 SRIRAM | Built with HTML & CSS</p>
  </footer>

</body>
</html>
