<style>
  /* 1. GLOBAL STYLES & CURSOR */
  html {
    scroll-behavior: smooth;
  }

  body {
    background-color: #0e1a2b;
    color: white;
    font-family: sans-serif;
    margin: 0;
    padding-top: 60px; 
  }

  /* 2. STICKY NAVIGATION */
  .navbar {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    background-color: #112244;
    padding: 15px 0;
    text-align: right;
    z-index: 1000;
    border-bottom: 1px solid #ffffff33;
  }

  .navbar a {
    color: white;
    text-decoration: none;
    margin-right: 30px;
    font-weight: bold;
    font-size: 1.1rem;
    transition: color 0.3s;
  }

  .navbar a:hover {
    color: #00d4ff;
  }

  /* 3. LAYOUT UTILITIES */
  .section-container {
    padding: 40px 20px;
    max-width: 1200px;
    margin: auto;
  }

  .flex-row {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    align-items: center; /* Vertical alignment */
    margin-bottom: 30px;
  }

  .flex-item {
    flex: 1;
    min-width: 300px;
  }

  /* Center alignment for the intro text */
  .intro-text {
    text-align: center;
    list-style-position: inside;
    padding: 0;
  }

  .intro-text li {
    margin-bottom: 10px;
  }

  /* Image Albums (Horizontal Scroll) */
  .album-scroll {
    overflow-x: auto;
    white-space: nowrap;
    padding: 15px;
    border: 1px solid #ffffff33;
    border-radius: 8px;
    background: #0a121e;
  }

  .album-scroll img, .album-scroll video {
    height: 350px;
    margin-right: 15px;
    border-radius: 4px;
    display: inline-block;
  }

  /* Unity Certification blending */
  .cert-img {
    width: 200px;
    mix-blend-mode: lighten; /* Helps blend white backgrounds into dark themes */
  }

  /* Skills List Styling */
  .skills-group {
    margin-bottom: 25px;
  }
  
  .skills-group h4 {
    color: #00d4ff;
    border-bottom: 1px solid #ffffff33;
    padding-bottom: 5px;
    margin-bottom: 10px;
  }
</style>

<div class="navbar">
  <a href="#home">Home</a>
  <a href="#projects">Projects</a>
  <a href="#experience">Experience</a>
  <a href="#contact">Contact</a>
</div>

---

<div id="home" class="section-container">
  <h1><center>Kevin Shu Too</center></h1>
  
  <div class="flex-row">
    <div class="flex-item">
      <h2 style="text-align: center;">Who Am I?</h2>
      <ul class="intro-text">
        <li>Creative and adaptable Game Developer with experience in C#, C++, Unity, and Unreal Engine 5.</li>
        <li>Experienced in programming, databases, UI, Scriptable Objects, and animation.</li>
        <li>Seeking to further develop technical and problem-solving skills.</li>
        <li>Passionate about creating immersive and memorable games.</li>
        <li>Deeply passionate about Transformers, Pokemon, Ben 10, and Arknights.</li>
      </ul>
    </div>
    <div class="flex-item" style="text-align: center;">
      <img src="Doc/Resume.png" style="max-width: 100%; border: 1px solid #ffffff33; box-shadow: 0px 4px 15px rgba(0,0,0,0.5);" alt="Resume">
    </div>
  </div>

  <h2>Certifications</h2>
  <div style="display: flex; gap: 20px; margin-bottom: 40px;">
    <img src="web_imgs/unity-essentials-pathway.png" class="cert-img" alt="Unity Essentials"/>
    <img src="web_imgs/unity-junior-programmer.png" class="cert-img" alt="Unity Junior Programmer"/>
  </div>

  <h2>Showcase Gallery</h2>
  <div class="album-scroll">
    <img src="Unity/Semester Saga/Semester_Saga.png" alt="Saga">
    <img src="Unity/Curation Curiosity/CurationCuriosity.png" alt="Curiosity">
    <img src="Unity/What Lurks In The Dark/Logo.jpg" alt="Horror">
    <img src="Unity/Astro Shork/astro_shork_icon.jpg" alt="Shork">
  </div>
</div>

<hr style="border: 1px solid #ffffff11;">

<div id="projects" class="section-container">
  <h1 style="text-align: center;">Academic Projects</h1>

  <h3>Semester Saga by More Boullets Studios (2023 - 2024)</h3>
  <p><b>Role:</b> Engineer | <b>Tech:</b> Unity, C# | <b>Genre:</b> School Sim RPG</p>
  <ul>
    <li>Created minigames, animations, and scripts for time/event systems.</li>
    <li><a href="https://drive.google.com/drive/folders/1okrHnOI2sQgRrplz9Dnf2-Sy_4tCZldm?usp=drive_link" target="_blank">View Build & Source</a></li>
  </ul>
  <div class="album-scroll">
    <img src="Unity/Semester Saga/Semester_Saga.png" alt="Logo">
    <video src="Unity/Semester Saga/Semester Saga Short Gameplay Video.mp4" controls></video>
    <video src="Unity/Semester Saga/Animation Clip.mp4" controls></video>
  </div>

  <h3>What Lurks In The Dark (2025)</h3>
  <p><b>Role:</b> Engineer | <b>Tech:</b> Unity, C# | <b>Genre:</b> Horror 2D Platformer</p>
  <ul>
    <li>Coded enemy behaviors, scene design, and flashlight mechanics.</li>
    <li><a href="https://github.com/Kenneth2Shu/IEPRFDV-What-Lurks-In-The-Dark" target="_blank">GitHub Repo</a> | <a href="https://hollowscapemedia.itch.io/what-lurks-in-the-dark" target="_blank">Itch.io</a></li>
  </ul>
  <div class="album-scroll">
    <img src="Unity/What Lurks In The Dark/Banner.jpg" alt="Banner">
    <video src="Unity/Semester Saga/Animation Clip.mp4" controls></video>
  </div>

  <h3>Astro Shork (2025)</h3>
  <p><b>Role:</b> Engineer | <b>Tech:</b> Unity, C# | <b>Genre:</b> Arcade</p>
  <ul>
    <li>Enemy and bullet scripting for a Vampire Survivors-like arcade game.</li>
    <li><a href="https://finalspeedz.itch.io/astro-shork" target="_blank">Play on Itch.io</a></li>
  </ul>
  <div class="album-scroll">
    <img src="Unity/Astro Shork/banner.jpg" alt="Banner">
    <video src="Unity/Semester Saga/Animation Clip.mp4" controls></video>
  </div>

  <h3>Kalu-Cookan (2025-2026)</h3>
  <p><b>Role:</b> Engineer | <b>Tech:</b> Unity, C# | <b>Genre:</b> Educational Cooking</p>
  <ul>
    <li>Researched nutrition and created recipe systems, UI, and level design.</li>
  </ul>
  <div class="album-scroll">
    <img src="Unity/Kalu-Cookan/Game Logo.png" alt="Logo">
    <img src="Unity/Kalu-Cookan/Screenshot1.png" alt="S1">
  </div>

  <h3>Curation Curiosity by Touch Grass Studios (2025)</h3>
  <p><b>Role:</b> Engineer | <b>Tech:</b> Unity, C# | <b>Genre:</b> Educational (MATATAG Curriculum)</p>
  <ul>
    <li>Focused on animal classification; handled bug fixing and particle systems.</li>
    <li><a href="https://github.com/loldope19/Curation-Curiosity" target="_blank">GitHub Repo</a> | <a href="https://loldope19.itch.io/curation-curiosity" target="_blank">Itch.io</a></li>
  </ul>
</div>

<hr style="border: 1px solid #ffffff11;">

<div id="experience" class="section-container">
  <h1 style="text-align: center;">Experience & Skills</h1>

  <h3>Professional Experience</h3>
  <p><b>DLSU GAME Lab (2025)</b> - Intern and Lead Engineer</p>
  <ul>
    <li>Programmed desktop/mobile research apps and led user testing.</li>
    <li><a href="https://www.facebook.com/DLSUGAMELab" target="_blank">Visit Page</a></li>
  </ul>

  <h3>Technical Expertise</h3>
  <div class="skills-group">
    <h4>Coding Languages</h4>
    <ul>
      <li>C#, C++, C, Python, HTML</li>
      <li>Mandarin (Basic Proficiency)</li>
    </ul>
  </div>

  <div class="skills-group">
    <h4>Game Engines</h4>
    <ul>
      <li>Unity</li>
      <li>Unreal Engine 5</li>
      <li>Godot</li>
    </ul>
  </div>

  <div class="skills-group">
    <h4>Other Softwares</h4>
    <ul>
      <li>Visual Studio / VS Code</li>
      <li>Github / AutoCAD</li>
      <li>GIMP / Photoshop / 3ds Max</li>
    </ul>
  </div>

  <h3>Other Information</h3>
  <div class="skills-group">
    <h4>Education</h4>
    <ul>
      <li><b>De La Salle University</b> - BS Interactive Entertainment Technologies (Major in Game Development), 2019 - 2026</li>
    </ul>
  </div>

  <div class="skills-group">
    <h4>Soft Skills</h4>
    <ul>
      <li>Project Management, Adaptability, Creative Thinking, Quality Testing</li>
    </ul>
  </div>

  <div class="skills-group">
    <h4>Design Skills</h4>
    <ul>
      <li>Creative writing, Narrative Design, Level Design, UI/UX</li>
    </ul>
  </div>
</div>

<hr style="border: 1px solid #ffffff11;">

<div id="contact" class="section-container" style="text-align: center; padding-bottom: 100px;">
  <h1>Let's Connect</h1>
  <p>Feel free to reach out for collaborations or inquiries!</p>
  <p>📧 <b>Email:</b> <a href="mailto:kevinshuthree@gmail.com" style="color: #00d4ff;">kevinshuthree@gmail.com</a></p>
  <p>🔗 <b>LinkedIn:</b> <a href="https://www.linkedin.com/in/kevin-shu-too-b776b233b/" target="_blank" style="color: #00d4ff;">Profile Link</a></p>
</div>