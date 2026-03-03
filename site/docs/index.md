<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Chu Ngoc Truong | Student Portfolio</title>

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;800&family=Orbitron:wght@500;700&display=swap" rel="stylesheet">

  <style>
    :root {
      --primary: #6C63FF;
      --secondary: #FF6584;
      --accent: #00E5A8;
      --dark: #1e1e2f;
      --light: #ffffff;
      --gradient: linear-gradient(135deg, #6C63FF, #00E5A8);
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background: var(--dark);
      color: var(--light);
      line-height: 1.6;
    }

    header {
      background: var(--gradient);
      padding: 3rem 1rem;
      text-align: center;
    }

    header h1 {
      font-family: 'Orbitron', sans-serif;
      font-size: 3rem;
      font-weight: 700;
    }

    header p {
      margin-top: 1rem;
      font-size: 1.2rem;
      font-weight: 300;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 2rem;
      background: #2a2a40;
      padding: 1rem;
      flex-wrap: wrap;
    }

    nav a {
      color: var(--light);
      text-decoration: none;
      font-weight: 600;
      transition: 0.3s;
    }

    nav a:hover {
      color: var(--accent);
    }

    section {
      padding: 4rem 10%;
    }

    .about, .projects, .contact {
      margin-bottom: 4rem;
    }

    h2 {
      font-size: 2rem;
      margin-bottom: 1.5rem;
      color: var(--accent);
    }

    .card-container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
    }

    .card {
      background: #2a2a40;
      padding: 2rem;
      border-radius: 15px;
      transition: 0.4s;
      box-shadow: 0 10px 25px rgba(0,0,0,0.3);
    }

    .card:hover {
      transform: translateY(-10px);
      background: linear-gradient(135deg, #6C63FF, #FF6584);
    }

    .card h3 {
      margin-bottom: 1rem;
    }

    .contact form {
      display: flex;
      flex-direction: column;
      gap: 1rem;
      max-width: 500px;
    }

    input, textarea {
      padding: 0.8rem;
      border-radius: 8px;
      border: none;
      font-family: inherit;
    }

    button {
      padding: 0.8rem;
      border-radius: 8px;
      border: none;
      background: var(--secondary);
      color: white;
      font-weight: 600;
      cursor: pointer;
      transition: 0.3s;
    }

    button:hover {
      background: var(--accent);
      color: black;
    }

    footer {
      text-align: center;
      padding: 2rem;
      background: #2a2a40;
      margin-top: 2rem;
      font-size: 0.9rem;
    }

    @media (max-width: 768px) {
      header h1 {
        font-size: 2rem;
      }

      section {
        padding: 3rem 5%;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Chu Ngoc Truong</h1>
    <p>Computer Science Student | Web Developer | Tech Enthusiast</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about" class="about">
    <h2>About Me</h2>
    <p>
      Hello! I'm Chu Ngoc Truong, a passionate student who loves building creative and functional web applications.
      I enjoy learning new technologies, solving problems, and designing beautiful user experiences.
    </p>
  </section>

  <section id="projects" class="projects">
    <h2>My Projects</h2>
    <div class="card-container">
      <div class="card">
        <h3>Project One</h3>
        <p>A responsive website built with HTML, CSS, and JavaScript.</p>
      </div>
      <div class="card">
        <h3>Project Two</h3>
        <p>A data visualization dashboard using modern web technologies.</p>
      </div>
      <div class="card">
        <h3>Project Three</h3>
        <p>A backend API project with database integration.</p>
      </div>
    </div>
  </section>

  <section id="contact" class="contact">
    <h2>Contact Me</h2>
    <form>
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea rows="5" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    © 2026 Chu Ngoc Truong | Designed with passion and creativity ✨
  </footer>

</body>
</html>