# liz4662.github.io
<!DOCTYPE>
<html lang="en">
  <head>
    <link rel="stylesheet" href="styles.css">
   <meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Personal Profile</title>
  </head>

  <body>

  <nav id="navbar" class="nav">
    <ul class="nav-list">
      <li>
        <a href="#welcome-section">About</a>
      </li>
      <li>
        <a href="#projects">Work</a>
      </li>
      <li>
        <a href="#contact">Contact</a>
      </li>
    </ul>
  </nav>


  <section id="welcome-section" class="welcome-section">
    <h1>WELCOME!</h1>
    <p>My name is Lizette.</p>
  </section>


  <section id="projects" class="projects-section">
    <h2 class="projects-section-header">These are some of my projects</h2>

    <div class="projects-grid">
      <a href="https://codepen.io/freeCodeCamp/full/zNqgVx" target="_blank" class="project project-tile">
        <img class="project-image" src="https://cdn.freecodecamp.org/testable-projects-fcc/images/tribute.jpg" alt="project">
        <p class="project-title">
          <span class="code">&lt;</span>
          Tribute Page
          <span class="code">/&gt;</span>
        </p>
      </a>
      <a href="https://codepen.io/freeCodeCamp/full/qRZeGZ" target="_blank" class="project project-tile">
        <img class="project-image" src="https://cdn.freecodecamp.org/testable-projects-fcc/images/random-quote-machine.png" alt="project">
        <p class="project-title">
          <span class="code">&lt;</span>
          Random Quote Machine
          <span class="code">/&gt;</span>
        </p>
      </a>
      <a href="https://codepen.io/freeCodeCamp/full/wgGVVX" target="_blank" class="project project-tile">
        <img class="project-image" src="https://cdn.freecodecamp.org/testable-projects-fcc/images/calc.png" alt="project">
        <p class="project-title">
          <span class="code">&lt;</span>
          JavaScript Calculator
          <span class="code">/&gt;</span>
        </p>
      </a>
      <a href="https://codepen.io/freeCodeCamp/full/mVEJag" target="_blank" class="project project-tile">
        <img class="project-image" src="https://cdn.freecodecamp.org/testable-projects-fcc/images/map.jpg" alt="project">
        <p class="project-title">
          <span class="code">&lt;</span>
          Map Data Across the Globe
          <span class="code">/&gt;</span>
        </p>
      </a>
      <a href="https://codepen.io/freeCodeCamp/full/wGqEga" target="_blank" class="project project-tile">
      <a href="https://codepen.io/freeCodeCamp/full/KzXQgy" target="_blank" class="project project-tile">
        <img class="project-image" src="https://cdn.freecodecamp.org/testable-projects-fcc/images/tic-tac-toe.png" alt="project">
        <p class="project-title">
          <span class="code">&lt;</span>
          Tic Tac Toe Game
          <span class="code">/&gt;</span>
        </p>
      </a>
    </div>

    <a href="https://codepen.io/FreeCodeCamp/" class="btn btn-show-all" target="_blank">Show all<i class="fas fa-chevron-right"></i></a>
  </section>

  <!-- END PROJECTS SECTION -->

  <!-- START CONTACT SECTION -->

  <section id="contact" class="contact-section">
    <div class="contact-section-header">
      <h2>Let's work together...</h2>
      <p>How do you take your coffee?</p>
    </div>
    <div class="contact-links">
      <a href="https://facebook.com/freecodecamp" target="_blank" class="btn contact-details"><i class="fab fa-facebook-square"></i> Facebook</a>
      <a id="profile-link" href="https://github.com/freecodecamp" target="_blank" class="btn contact-details"><i class="fab fa-github"></i> GitHub</a>
      <a href="https://twitter.com/freecodecamp" target="_blank" class="btn contact-details"><i class="fab fa-twitter"></i> Twitter</a>
      <a href="mailto:example@example.com" class="btn contact-details"><i class="fas fa-at"></i> Send a mail</a>
      <a href="tel:6506904544" class="btn contact-details"><i class="fas fa-mobile-alt"></i> Call me</a>
    </div>
  </section>

  <!-- END CONTACT SECTION -->

  <!-- START FOOTER SECTION -->
  <footer>
    <p>
      **This is just a fake portfolio. All the projects and contact details
      given are not real.
    </p>
    <p>
      © Created for
      <a href="https://www.freecodecamp.com/" target="_blank">freeCodeCamp <i class="fab fa-free-code-camp"></i></a>
    </p>
  </footer>
  </body>
  <style>
   @media (hover: hover) {
  a:hover {
    color: white;
    background: black;
  }
}

nav{
position:fixed;
  top:0;
}

.welcome-section {
    display: flex;
    color: black;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    width: 100%;
    height: 100vh;
    background-color: #E1C2A7
    
}

*{
    box-sizing: inherit;
    margin: 0;
}
html {
    font-size: 58%;
    scroll-behavior: smooth;
}
body {
    font-family: 'Poppins', sans-serif;
    font-weight: 400;
    line-height: 1.4;
    color: white;
    display: block;
}
.nav {
    display: flex;
    justify-content: flex-end;
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    background: #6B4B2F;
    box-shadow: 0 2px 0 rgba(0, 0, 0, 0.4);

}

ul {
    list-style: none;
    margin-block-start: 1em;
    margin-block-end: 1em;
    margin-inline-start: 0px;
    margin-inline-end: 0px;
    padding-inline-start: 40px;
}

li {
    text-align: center;
    display:inline-block;
}
nav-list {
    display: flex;
    margin-right: 2rem;
}
.nav-list a {
    display: block;
    font-size: 2.2rem;
    padding: 2rem;
}
a {
    text-decoration: none;
    color: var(--main-white);
}

    
h1 {
    font-size: 6rem;
}
h1, h2 {
    font-family: 'Raleway', sans-serif;
    font-weight: 700;
    text-align: center;
}
.welcome-section > p {
    font-size: 3rem;
    font-weight: 200;
    font-style: italic;
    color: var(--main-red);
}
.projects-section {
    text-align: center;
    padding: 10rem 2rem;
    background: var(--main-blue);
}
footer {
  font-weight: 300;
  display: flex;
  justify-content: space-evenly;
  padding: 2rem;
  background: var(--main-gray);
  border-top: 4px solid var(--main-red);
}

footer > p {
  margin: 2rem;
}

footer i {
  vertical-align: middle;
}

@media (max-width: 28.75em) {
  footer {
    flex-direction: column;
    text-align: center;
  }
    </style>

</html>
