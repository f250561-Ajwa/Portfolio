# Portfolio
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ajwa Shahid - Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet" />
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: #ffe6f2;
      color: #2b1f2b;
    }
    header {
      text-align: center;
      padding: 25px;
      background: #ff99cc;
      color: white;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    }
    header h1 {
      margin: 0;
      font-size: 34px;
    }
    header p {
      margin: 5px 0 0;
      font-weight: 300;
      letter-spacing: 1px;
    }
    .container {
      max-width: 900px;
      margin: 40px auto;
      background: white;
      border-radius: 15px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.1);
      padding: 30px;
    }
    .hero-text {
      text-align: center;
    }
    .hero-text h2 {
      color: #ff4fa0;
      margin-top: 0;
    }
    .hero-text p {
      font-size: 15px;
      line-height: 1.7;
      color: #444;
    }
    .section {
      margin-top: 40px;
    }
    h3 {
      color: #ff4fa0;
      border-bottom: 2px solid #ffcce0;
      padding-bottom: 5px;
    }
    .skills, .education, .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 15px;
    }
    .card {
      background: #fff0f7;
      border-radius: 12px;
      padding: 15px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.05);
      transition: transform 0.3s;
    }
    .card:hover {
      transform: translateY(-5px);
    }
    footer {
      text-align: center;
      margin-top: 40px;
      font-size: 14px;
      color: #666;
    }
    a {
      color: #ff4fa0;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    .skills-img, .bottom-image {
      width: 100%;
      border-radius: 15px;
      box-shadow: 0 6px 15px rgba(0,0,0,0.1);
      margin-top: 25px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Ajwa Shahid</h1>
    <p>BS Computer Science — FAST University</p>
  </header>

  <div class="container">
    <section class="hero-text">
      <h2>Welcome to My Portfolio 💻</h2>
      <p>Hi! I’m <b>Ajwa Shahid</b>, a first-semester BSCS student at <b>FAST University</b>.  
      I love exploring how technology and creativity come together to solve real-world problems.  
      I studied at <b>DPS Kasur</b> and <b>KIPS College (Pre-Medical with Additional Maths)</b>.  
      My focus now is on building my skills in programming, design, and web technologies.</p>
    </section>

    <section class="section education">
      <h3>Education</h3>
      <div class="card">🏫 <strong>School:</strong> DPS Kasur</div>
      <div class="card">🎓 <strong>College:</strong> KIPS College Kasur (FSc Pre-Medical + Additional Maths)</div>
      <div class="card">💻 <strong>University:</strong> FAST University (BSCS - 1st Semester)</div>
    </section>

    <section class="section skills">
      <h3>Skills</h3>
      <div class="card">🌸 HTML — Responsive and semantic structure</div>
      <div class="card">💫 CSS — Layouts, colors & animations</div>
      <div class="card">🪄 MS Word — Reports & formatting</div>
      <div class="card">📊 MS Excel — Data organization & formulas</div>
      <div class="card">🎨 Canva — Creative posters & presentation designs</div>
      <div class="card">📧 Gmail — Professional email communication</div>
      <div class="card">💻 C++ Programming — Learning object-oriented programming & problem solving</div>
      <div class="card">🌐 Web Development — Responsive design & user experience</div>
      <div class="card">🧠 Logical Thinking — Debugging & code optimization</div>

      <!-- Skill related image (Unsplash - no error) -->
      <img class="skills-img" src="https://images.unsplash.com/photo-1555066931-4365d14bab8c?auto=format&fit=crop&w=900&q=60" alt="Coding Skills Image">
    </section>

    <section class="section projects">
      <h3>Projects</h3>
      <div class="card">
        <p><strong>💻 Portfolio Website:</strong> My first responsive HTML/CSS project that represents my academic journey and creativity.</p>
      </div>
      <div class="card">
        <p><strong>⚙️ C++ Mini Projects:</strong> Console programs like calculator, student grading system, and pattern generator.</p>
      </div>
      <div class="card">
        <p><strong>🎨 Canva Designs:</strong> Posters and graphics created for university societies and events.</p>
      </div>
    </section>

    <section class="section contact">
      <h3>Contact</h3>
      <p>Email: <a href="mailto:ajwashahid150@gmail.com">ajwashahid150@gmail.com</a></p>
      
      <p>LinkedIn: <a href="#">linkedin.com/in/ajwashahid</a></p>
    </section>

    <!-- Decorative image at the bottom (Unsplash) -->
    <img class="bottom-image" src="https://images.unsplash.com/photo-1507842217343-583bb7270b66?auto=format&fit=crop&w=900&q=60" alt="Pink Abstract Background">
  </div>

  <footer>
    © 2025 Ajwa Shahid at FAST University
  </footer>
</body>
</html>
 `
