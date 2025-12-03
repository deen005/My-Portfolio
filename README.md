<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Deena J - Portfolio</title>
  <link rel="stylesheet" href="style.css">

  <style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  background: #0d1b2a;
  color:gold;
  font-size: 20px;
  line-height: 1.6;
}

.resume-btn {
  display: inline-block;
  margin-top: 20px;
  padding: 12px 24px;
  background: linear-gradient(45deg, navy, violet);
  color: white;
  font-weight: bold;
  border-radius: 8px;
  text-decoration: none;
  box-shadow: 0 4px 10px rgba(0,0,0,0.3);
  transition: transform 0.2s, box-shadow 0.2s;
}

.resume-btn:hover {
  transform: scale(1.05);
  box-shadow: 0 6px 15px rgba(11, 11, 11, 0.4);
  background: linear-gradient(45deg,lightblue, lightblue);
  color:blue;
}


a {
  text-decoration: none;
  color: inherit;
}

.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 15px 50px;
  background: #0d1b2a;
}

.logo {
  font-size: 22px;
  font-weight: bold;
}

.navbar nav a {
  margin: 0 15px;
  font-size: 16px;
  color: #ddd;
}

.navbar nav a:hover {
  color:chartreuse;
}

.hero-box {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 80px 10%;
}

.hero-left {
  flex: 1;
  display: flex;
  justify-content: center;
  align-items: center;
}

.profile-img {
  width: 280px;
  height: auto;
  border-radius: 12px;
  border: 6px solid #fff;
  box-shadow: 0 5px 20px rgba(0,0,0,0.3);
}

.hero-right {
  flex: 1;
  padding-left: 50px;
}

.role {
  color: #f9a826;
  font-size: 14px;
  margin-bottom: 10px;
}

.name {
  font-size: 42px;
  font-weight: bold;
  margin: 0;
}

.name span {
  color: #f9a826;
}

.intro {
  font-size: 16px;
  color: #ccc;
  margin: 20px 0;
  max-width: 450px;
}

.btn {
  display: inline-block;
  padding: 10px 20px;
  border: 2px solid #f9a826;
  border-radius: 6px;
  color: #f9a826;
  font-weight: bold;
  transition: 0.3s;
}

.btn:hover {
  background: #f9a826;
  color: #0d1b2a;
}


.about {
  padding: 60px 10%;
  background: #162447;
  text-align: center;
}

.about h2 {
  font-size: 28px;
  margin-bottom: 20px;
  color: #f9a826;
}

.skills {
  padding: 60px 10%;
  background: #0d1b2a;
  text-align: center;
}

.skills h2 {
  font-size: 28px;
  margin-bottom: 30px;
  color: #f9a826;
}

.skill-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
  gap: 20px;
}

.skill {
  background: #1b263b;
  padding: 15px;
  border-radius: 8px;
  font-weight: bold;
  transition: transform 0.3s;
}

.skill:hover {
  transform: scale(1.05);
  background: violet;
  color: #0d1b2a;
}


.projects {
  padding: 60px 10%;
  background: #162447;
  text-align: center;
}

.projects h2 {
  font-size: 28px;
  margin-bottom: 30px;
  color:yellowgreen;
}

.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
  
}

.project-card {
  background: #1b263b;
  padding: 20px;
  border-radius: 10px;
  transition: transform 0.3s;
  border: 2px solid bisque;
}

.project-card:hover {
  transform: translateY(-5px);
  background:purple;
  color:white;
}


.contact {
  padding: 60px 10%;
  background: #0d1b2a;
  text-align: center;
}

.contact h2 {
  font-size: 28px;
  margin-bottom: 20px;
  color: #f9a826;
}

.contact form {
  max-width: 500px;
  margin: 0 auto;
  display: flex;
  flex-direction: column;
}

.contact input,
.contact textarea {
  padding: 12px;
  margin: 10px 0;
  border: none;
  border-radius: 6px;
  outline: none;
}

.contact button {
  padding: 12px;
  border: none;
  border-radius: 6px;
  background: #f9a826;
  color: #0d1b2a;
  font-weight: bold;
  cursor: pointer;
  transition: 0.3s;
}

.contact button:hover {
  background: #ffbe4d;
}


footer {
  text-align: center;
  padding: 20px;
  background: #162447;
  font-size: 14px;
  color: #ccc;
}

    
  </style>
</head>
<body>
  

  <header class="navbar">
    <h1 class="logo">Deena J</h1>
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  
  <section id="home" class="hero-box">
           
    <div class="hero-right">
      <p class="role">— Full Stack Developer</p>
      <h1 class="name">Deena <span>J.</span></h1>
      <p class="intro">
        I am looking for a sweet spot for innovation, somewhere between design, 
        strategy and technology. I love building user-friendly websites 
        and solving problems with code.
      </p>
      <a class="resume-btn" href="./Deena Resume 1.pdf" download="Deena Resume 1.pdf">Download Resume </a>

    </div>
  </section>

  
  <section id="about" class="about">
    <h2>About Me</h2>
    <p>
      I am a passionate developer who loves building interactive web applications. 
      With skills in HTML, CSS, JavaScript, and frameworks like React & Django, 
      I enjoy solving problems and creating user-friendly designs.
    </p>
  </section>

  
  <section id="skills" class="skills">
    <h2>Skills</h2>
    <div class="skill-grid">
      <div class="skill">Python</div>
      <div class="skill">SQL</div> 
      <div class="skill">HTML</div>
      <div class="skill">CSS</div>
      <div class="skill">JavaScript</div>
      <div class="skill">React</div>     
      <div class="skill">Django</div>
    </div>
  </section>

  
  <section id="projects" class="projects">
    <h2>Projects</h2>
    <div class="project-grid">
      <div class="project-card">
        <h3>Library Management System</h3>
        <p>I have made this project by using Python and MySQL</p>
      </div>
      <div class="project-card">
        <h3>Front end </h3>
        <p> None</p>
      </div>
      <div class="project-card">
        <h3> Website</h3>
        <p>Created a responsive portfolio using Html, css and Javascript.</p>
      </div>
    </div>
  </section>

  
  <section id="contact" class="contact">
    <h2>Contact Me</h2>
    <form>
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Your Email" required>
      <textarea placeholder="Your Message"></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  
  <footer>
    <p>© 2025 Deena J | All Rights Reserved</p>
  </footer>
</body>
</html>

