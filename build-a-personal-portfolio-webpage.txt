** start of index.html **

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>WaldoXP Portfolio</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>

  <nav id="navbar">
    <ul>
      <li><a href="#welcome-section">Welcome</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a id="profile-link" href="https://github.com/YOUR_USERNAME" target="_blank">My GitHub</a></li>
    </ul>
  </nav>

  <section id="welcome-section">
    <h1>Welcome to WaldoXP's Portfolio</h1>
  </section>

  <section id="projects">
    <h2>My Projects</h2>
    <div class="project-tile">
      <a href="https://your-project-link.example.com" target="_blank">
        <h3>Project Title</h3>
        <p>Short project description goes here.</p>
      </a>
    </div>
  </section>

</body>
</html>

** end of index.html **

** start of styles.css **

/* Base Styles */
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
}

/* Navbar */
#navbar {
  position: fixed;
  top: 0;
  width: 100%;
  background-color: #333;
  padding: 1rem;
  z-index: 10;
}

#navbar ul {
  list-style: none;
  display: flex;
  justify-content: center;
  gap: 2rem;
}

#navbar a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

#navbar a:hover {
  text-decoration: underline;
}

/* Welcome Section */
#welcome-section {
  height: 100vh;
  background: linear-gradient(to bottom, #4facfe, #00f2fe);
  color: white;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  padding: 2rem;
}

/* Projects Section */
#projects {
  padding: 4rem 2rem;
  background-color: #f4f4f4;
}

.project-tile {
  background-color: white;
  border: 1px solid #ddd;
  padding: 1rem;
  margin: 1rem 0;
  border-radius: 8px;
  transition: transform 0.3s;
}

.project-tile:hover {
  transform: scale(1.03);
}

.project-tile a {
  text-decoration: none;
  color: #333;
}

/* Responsive Design */
@media (max-width: 768px) {
  #navbar ul {
    flex-direction: column;
    gap: 1rem;
  }

  #projects {
    padding: 2rem 1rem;
  }
}

** end of styles.css **

