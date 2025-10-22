# Muhammad-Usman-Nadeem
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Muhammad Usman Nadeem — Portfolio</title>
  <meta name="description" content="Portfolio of Muhammad Usman Nadeem — BSc Data Science & AI student. Projects: Battleship (Java), Operation Scheduler, Responsive Website.">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#f7f9fb; --card:#ffffff; --muted:#666d76; --accent:#0b67ff; --dark:#0b1320;
      --radius:12px; --container:1100px;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0; font-family:Inter,system-ui,-apple-system,"Segoe UI",Roboto,"Helvetica Neue",Arial;
      background:linear-gradient(180deg,var(--bg),#eef3f9); color:var(--dark); -webkit-font-smoothing:antialiased;
      line-height:1.5; padding:28px;
    }
    .wrap{max-width:var(--container); margin:0 auto;}
    header{
      display:flex; gap:16px; align-items:center; justify-content:space-between; margin-bottom:22px;
    }
    .brand{display:flex; gap:14px; align-items:center}
    .avatar{
      width:72px; height:72px; border-radius:8px; background:linear-gradient(135deg,var(--accent),#2bb3ff); color:white;
      display:flex; align-items:center; justify-content:center; font-weight:700; font-size:20px;
      box-shadow:0 6px 18px rgba(11,103,255,0.12);
    }
    h1{font-size:20px;margin:0}
    .lead{color:var(--muted); margin-top:4px; font-size:14px}
    nav a{color:var(--muted); text-decoration:none; margin-left:18px; font-weight:600; font-size:14px}
    .grid{
      display:grid; grid-template-columns: 1fr 360px; gap:20px;
    }
    main{min-height:360px}
    .card{background:var(--card); border-radius:var(--radius); padding:18px; box-shadow:0 6px 18px rgba(16,24,40,0.04)}
    .section-title{display:flex; justify-content:space-between; align-items:center; margin-bottom:12px}
    .section-title h2{margin:0; font-size:16px}
    .muted{color:var(--muted); font-size:14px}
    .btn{
      display:inline-block; text-decoration:none; padding:8px 12px; border-radius:8px; background:var(--accent); color:white;
      font-weight:700; font-size:13px;
    }

    /* Projects list */
    .project{border-left:3px solid rgba(11,103,255,0.12); padding:12px; margin-bottom:12px; border-radius:8px}
    .project h3{margin:0 0 6px 0; font-size:15px}
    .tags{font-size:13px; color:var(--muted)}
    .skills-grid{display:flex; flex-wrap:wrap; gap:8px; margin-top:8px}
    .skill-pill{background:#f2f6ff; padding:6px 10px; border-radius:999px; font-weight:600; font-size:13px; color:var(--accent)}

    /* Sidebar */
    aside .small{font-size:13px; color:var(--muted); margin-bottom:8px}
    .contact-list{list-style:none; padding:0; margin:0}
    .contact-list li{margin-bottom:8px; font-size:14px}
    footer{margin-top:18px; text-align:center; color:var(--muted); font-size:13px}

    /* Responsive */
    @media (max-width:920px){
      .grid{grid-template-columns:1fr; }
      aside{order:2}
    }

    /* accessibility focus */
    a:focus{outline:3px solid rgba(11,103,255,0.12); outline-offset:3px}
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <div class="brand">
        <div class="avatar" aria-hidden="true">UN</div>
        <div>
          <h1>Muhammad Usman Nadeem</h1>
          <div class="lead">First-year BSc Data Science & Artificial Intelligence — University of Dundee</div>
        </div>
      </div>
      <nav aria-label="Main navigation">
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
      </nav>
    </header>

    <div class="grid">
      <!-- Main column -->
      <main>
        <!-- About / Profile -->
        <section id="about" class="card" aria-labelledby="about-title">
          <div class="section-title">
            <h2 id="about-title">About Me</h2>
            <a class="btn" href="Muhammad_Usman_Nadeem_CV.pdf" download>Download CV (PDF)</a>
          </div>
          <p class="muted">
            I’m a motivated and detail-oriented first-year BSc Data Science & Artificial Intelligence student at the University of Dundee.
            I have hands-on experience in Java programming, data structures & algorithms, Linux/Unix fundamentals and front-end web development.
            Currently working as a Web Development Intern at DotsBit Software Company where I build responsive interfaces and collaborate on real projects.
          </p>

          <div style="margin-top:14px;">
            <strong>Career Goal</strong>
            <p class="muted">To secure a Data Science / Web Development internship where I can apply programming and analytical skills to deliver real-world solutions and learn from experienced engineers.</p>
          </div>
        </section>

        <!-- Education -->
        <section id="education" class="card" style="margin-top:16px" aria-labelledby="edu-title">
          <div class="section-title">
            <h2 id="edu-title">Education</h2>
            <div class="muted">April 2025 – June 2028</div>
          </div>
          <div>
            <strong>BSc (Hons) Data Science & AI</strong> — University of Dundee<br>
            <span class="muted">Modules (first year): Java Programming, Data Structures & Algorithms, Unix & Networking, Mathematics for Computing, Web Development</span>
          </div>

          <hr style="margin:12px 0; border:none; border-top:1px solid #eef3f9">

          <div>
            <strong>Higher Secondary School Certificate (Pre-Engineering)</strong><br>
            DPS College for Boys, Okara — <span class="muted">Oct 2021 – Sep 2023</span>
          </div>

          <div style="margin-top:8px">
            <strong>Secondary School Certificate</strong><br>
            District Public School For Boys, Okara — <span class="muted">Sep 2019 – Oct 2021</span>
          </div>
        </section>

        <!-- Projects -->
        <section id="projects" class="card" style="margin-top:16px" aria-labelledby="proj-title">
          <div class="section-title">
            <h2 id="proj-title">Selected Projects</h2>
            <div class="muted">At least 3 projects — include descriptions, tech & your role</div>
          </div>

          <article class="project" aria-labelledby="p1">
            <h3 id="p1">Battleship Game (Java)</h3>
            <div class="tags muted">Java • OOP • Data Structures & Algorithms</div>
            <p class="muted" style="margin-top:8px">
              Implemented a Battleship game simulation using object-oriented design. Built grid management, ship placement algorithms,
              and turn-based logic. Focus on algorithmic efficiency and clean code structure.
            </p>
            <p style="margin:6px 0"><strong>Role:</strong> Lead developer (academic project)</p>
            <p><a href="#project1" aria-label="Project 1 placeholder link">View code / repo</a> (add GitHub link)</p>
          </article>

          <article class="project" aria-labelledby="p2">
            <h3 id="p2">Operation Scheduler App</h3>
            <div class="tags muted">Java • Algorithms • Process Scheduling</div>
            <p class="muted" style="margin-top:8px">
              Developed a scheduling application as part of Data Structures & Algorithms coursework. Implemented scheduling logic
              and data structures to manage tasks and optimize order of operations.
            </p>
            <p style="margin:6px 0"><strong>Role:</strong> Developer</p>
            <p><a href="#project2">View code / repo</a></p>
          </article>

          <article class="project" aria-labelledby="p3">
            <h3 id="p3">Website Development Project</h3>
            <div class="tags muted">HTML • CSS • JavaScript • Bootstrap</div>
            <p class="muted" style="margin-top:8px">
              Built a responsive, accessible website as part of the Web Development module. Implemented responsive layout,
              form validation, and interactive elements aligned with UX best practices.
            </p>
            <p style="margin:6px 0"><strong>Role:</strong> Front-end developer</p>
            <p><a href="#project3">Live demo / repo</a></p>
          </article>

        </section>

        <!-- Experience -->
        <section id="experience" class="card" style="margin-top:16px" aria-labelledby="exp-title">
          <div class="section-title">
            <h2 id="exp-title">Work Experience</h2>
            <div class="muted">Jan 2024 – Present</div>
          </div>

          <div>
            <strong>Web Development Intern</strong><br>
            DotsBit Software Company, Okara
            <ul class="muted" style="margin-top:8px">
              <li>Assisted in development and maintenance of responsive web applications using HTML, CSS and JavaScript.</li>
              <li>Implemented features such as form validation and interactive UI elements.</li>
              <li>Worked with Visual Studio Code, Git and Bootstrap for version control and responsive design.</li>
            </ul>
          </div>
        </section>

        <!-- Skills -->
        <section id="skills" class="card" style="margin-top:16px" aria-labelledby="skills-title">
          <div class="section-title">
            <h2 id="skills-title">Technical & Transferable Skills</h2>
          </div>

          <div class="skills-grid" aria-hidden="true" style="margin-bottom:12px">
            <div class="skill-pill">Java</div>
            <div class="skill-pill">Data Structures & Algorithms</div>
            <div class="skill-pill">HTML</div>
            <div class="skill-pill">CSS</div>
            <div class="skill-pill">JavaScript</div>
            <div class="skill-pill">Linux / Unix</div>
            <div class="skill-pill">Git</div>
            <div class="skill-pill">Bootstrap</div>
          </div>

          <div>
            <strong>Transferable Skills</strong>
            <p class="muted">Analytical & problem-solving, teamwork, communication, time management, adaptability, attention to detail.</p>
          </div>
        </section>

        <!-- Certifications -->
        <section id="certs" class="card" style="margin-top:16px" aria-labelledby="cert-title">
          <div class="section-title">
            <h2 id="cert-title">Certifications</h2>
            <div class="muted">2025</div>
          </div>
          <div>
            <strong>Earn $1000+ Monthly on Etsy with Digital Products</strong><br>
            Certificate ID: d9iejltrne
          </div>
        </section>
      </main>

      <!-- Sidebar -->
      <aside>
        <div class="card">
          <div class="section-title" style="margin-bottom:8px">
            <h2>Contact</h2>
          </div>
          <ul class="contact-list">
            <li><strong>Location:</strong> Dundee, Scotland, UK</li>
            <li><strong>Phone:</strong> +44 7513 212782</li>
            <li><strong>Email:</strong> <a href="mailto:Osmannadiim@gmail.com">Osmannadiim@gmail.com</a></li>
            <li><strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/muhammad-usman-nadeem-ab7452290/" target="_blank" rel="noopener">linkedin.com/in/muhammad-usman-nadeem-ab7452290</a></li>
            <li><strong>GitHub:</strong> <a id="ghlink" href="#github" target="_blank">Add your GitHub</a></li>
          </ul>

          <hr style="margin:12px 0; border:none; border-top:1px solid #eef3f9">

          <div>
            <div class="small"><strong>Availability</strong></div>
            <div class="muted">Available for internships / part-time roles — evenings after 5pm preferred.</div>
          </div>

          <hr style="margin:12px 0; border:none; border-top:1px solid #eef3f9">

          <div>
            <div class="small"><strong>Hobbies</strong></div>
            <div class="muted">Badminton • Cricket • Continuous skill development</div>
          </div>
        </div>

        <div class="card" style="margin-top:12px">
          <h3 style="margin:0 0 8px 0">Job Advert (Appendix)</h3>
          <p class="muted" style="font-size:14px">Using this portfolio for the assignment: <strong>The Trade Desk — 2025 Summer Intern (Data Science)</strong>. Save a copy of the advert as PDF and attach for submission.</p>
          <p style="margin-top:8px"><a href="https://www.thefreshdev.com/job/2025-summer-intern-data-science-london-the-trade-desk-2907" target="_blank" rel="noopener" class="muted">View job advert (The Trade Desk)</a></p>
        </div>
      </aside>
    </div>

    <footer id="contact" style="margin-top:18px">
      <div class="muted">© 2025 Muhammad Usman Nadeem — Built for CS21001 portfolio assessment • <a href="#ai">AI usage</a></div>
    </footer>

    <div style="display:none" id="ai">
      <p>AI usage: Assistance was used to draft this portfolio. Final content reviewed and approved by student.</p>
    </div>
  </div>

  <!-- Simple script to help update placeholders quickly -->
  <script>
    // Edit these values to put real links quickly:
    const githubUrl = "https://github.com/YOUR-GITHUB-USERNAME"; // <-- change
    const project1 = "https://github.com/YOUR-GITHUB-USERNAME/battleship-java"; // <-- change
    const project2 = "https://github.com/YOUR-GITHUB-USERNAME/operation-scheduler";
    const project3 = "https://github.com/YOUR-GITHUB-USERNAME/website-project";

    document.getElementById('ghlink').href = githubUrl;
    document.querySelector('#projects a[href="#project1"]').href = project1;
    document.querySelector('#projects a[href="#project2"]').href = project2;
    document.querySelector('#projects a[href="#project3"]').href = project3;
  </script>
</body>
</html>
