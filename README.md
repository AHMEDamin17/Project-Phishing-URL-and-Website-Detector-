<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Ahmed Amin — Portfolio</title>
  <meta name="description" content="Ahmed Amin — Aspiring Developer & Cybersecurity Enthusiast | Projects: Phishing Awareness Simulation, Phishing URL Detector" />
  <style>
    :root{ --bg:#f2f6f9; --card:#ffffff; --accent:#ff6b6b; --muted:#617085; --text:#0f1724; }
    *{box-sizing:border-box}
    body{margin:0;font-family:Inter,system-ui,-apple-system,'Segoe UI',Roboto,Helvetica,Arial; background:linear-gradient(180deg,#f6fbff 0%,var(--bg) 100%);color:var(--text);}
    .container{max-width:1100px;margin:32px auto;padding:0 20px}

    header{display:flex;align-items:center;justify-content:space-between;gap:16px}
    .brand{display:flex;gap:16px;align-items:center}
    .avatar{
      width:100px;
      height:100px;
      border-radius:50%; /* circular */
      overflow:hidden;
      box-shadow:0 4px 10px rgba(0,0,0,0.1);
    }
    .avatar img{
      width:100%;
      height:100%;
      object-fit:cover;
      display:block;
    }
    h1{margin:0;font-size:28px}
    p.lead{margin:6px 0 0;color:var(--muted)}

    .hero{display:grid;grid-template-columns:1fr 360px;gap:24px;margin-top:18px;align-items:center}
    @media(max-width:880px){.hero{grid-template-columns:1fr}}
    .card{background:var(--card);border-radius:14px;padding:18px;box-shadow:0 8px 24px rgba(16,24,40,.06);border:1px solid rgba(16,24,40,.04)}

    .cta-row{display:flex;gap:12px;align-items:center}
    .btn{padding:10px 14px;border-radius:10px;border:none;cursor:pointer;font-weight:600}
    .btn-primary{background:var(--accent);color:white}
    .btn-ghost{background:transparent;border:1px solid rgba(16,24,40,.06);color:var(--text)}

    .skills{display:grid;grid-template-columns:repeat(2,1fr);gap:12px}
    .skill{display:flex;flex-direction:column;gap:8px}
    .progress{height:10px;background:#eef3f9;border-radius:999px;overflow:hidden}
    .progress > i{display:block;height:100%;background:linear-gradient(90deg,#ff9a9e,#ff6b6b);}

    .projects{display:grid;grid-template-columns:repeat(2,1fr);gap:16px;margin-top:12px}
    @media(max-width:880px){.projects{grid-template-columns:1fr}}
    .project-card{display:flex;flex-direction:column;border-radius:12px;overflow:hidden}
    .thumb{height:160px;background:#f3f6fb;border-bottom:1px solid rgba(0,0,0,.04);display:grid;place-items:center;color:var(--muted)}
    .proj-body{padding:12px;background:var(--card)}
    .proj-title{font-weight:700;margin:0}
    .proj-meta{color:var(--muted);font-size:13px;margin-top:6px}
    .proj-actions{margin-top:10px;display:flex;gap:8px}

    footer{margin:26px 0 90px;text-align:center;color:var(--muted)}

    .muted{color:var(--muted)}
    .section-title{font-size:16px;margin:0 0 10px;font-weight:700}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">
        <div class="avatar">
          <img src="black.jpg" alt="Ahmed Amin">
        </div>
        <div>
          <h1>Ahmed Amin K</h1>
          <p class="lead">Aspiring Developer • Cybersecurity Enthusiast — Building secure, user-centered web apps</p>
        </div>
      </div>
      <div class="cta-row">
        <a class="btn btn-ghost"
           href="https://drive.google.com/file/d/1BviVr4a3twb8yHM2I87gG92icLi1Ix8C/view?usp=drivesdk"
           target="_blank" rel="noreferrer">
          Resume (PDF)
        </a>
        <a class="btn btn-primary" href="https://github.com/AHMEDamin17" target="_blank" rel="noreferrer">GitHub</a>
      </div>
    </header>

    <main class="hero">
      <section class="card">
        <h2 class="section-title">About Me</h2>
        <p>I’m currently pursuing my Master of Computer Applications (MCA) at Sathyabama Institute of Science and Technology. I previously graduated with a Bachelor of Computer Applications and have hands-on experience building web apps with a growing focus on cybersecurity. I build practical tools to detect and mitigate common threats — currently working on web security patterns, secure coding, and cloud basics.</p>

        <div style="margin-top:14px">
          <h3 class="section-title">Skills</h3>
          <div class="skills">
            <div class="skill">
              <div style="display:flex;justify-content:space-between"><span>HTML / CSS</span><span class="muted">80%</span></div>
              <div class="progress"><i style="width:80%"></i></div>
            </div>
            <div class="skill">
              <div style="display:flex;justify-content:space-between"><span>JavaScript</span><span class="muted">70%</span></div>
              <div class="progress"><i style="width:70%"></i></div>
            </div>
            <div class="skill">
              <div style="display:flex;justify-content:space-between"><span>SQL / DBMS</span><span class="muted">60%</span></div>
              <div class="progress"><i style="width:60%"></i></div>
            </div>
            <div class="skill">
              <div style="display:flex;justify-content:space-between"><span>UI/UX (Adobe XD)</span><span class="muted">65%</span></div>
              <div class="progress"><i style="width:65%"></i></div>
            </div>
          </div>

          <div style="margin-top:12px">
            <h3 class="section-title">Certifications</h3>
            <p class="muted">UI/UX Design (Coursera) • NPTEL DBMS • AWS (in progress)</p>
          </div>
        </div>
      </section>

      <aside class="card">
        <h3 class="section-title">Contact</h3>
        <p style="margin:0 0 8px"><strong>Ahmed Amin K</strong><br>
        Chennai • <a href="tel:+919894478873">9894478873</a><br>
        <a href="mailto:aminkhizer377@gmail.com">aminkhizer377@gmail.com</a></p>
        <div style="margin-top:12px">
          <a class="btn btn-ghost" href="https://www.linkedin.com/in/Ahmed%20amin-90049528a" target="_blank">LinkedIn</a>
        </div>

        <div style="margin-top:18px">
          <h4 class="section-title">Quick Info</h4>
          <p class="muted" style="margin:6px 0">MCA — Sathyabama Institute of Science and Technology (Pursuing)<br>BCA — Sri Manakula Vinayagar Engineering College (2021–2024) • CGPA: 7.0</p>
        </div>
      </aside>
    </main>

    <section style="margin-top:18px">
      <h2 class="section-title">Projects</h2>
      <div class="projects">
        <div class="project-card card">
          <div class="thumb">Phishing Awareness Simulation</div>
          <div class="proj-body">
            <div class="proj-title">Phishing Awareness Simulation</div>
            <div class="proj-meta">Kali Linux • Social Engineering Toolkit</div>
            <p class="muted">Created in a controlled environment to demonstrate how phishing pages are crafted and to train users in recognizing phishing attempts. Built purely for educational awareness.</p>
            <div class="proj-actions">
              <a class="btn btn-primary" href="#">Case Study</a>
            </div>
          </div>
        </div>

        <div class="project-card card">
          <div class="thumb">Phishing URL Detector (live demo)</div>
          <div class="proj-body">
            <div class="proj-title">Phishing URL & Website Detector</div>
            <div class="proj-meta">HTML • JavaScript • Client-side security analyzer</div>
            <div class="proj-actions">
              <a class="btn btn-ghost"
                 href="https://github.com/AHMEDamin17/Project-Phishing-URL-and-Website-Detector-"
                 target="_blank">
                View Code
              </a>
              <a class="btn btn-primary"
                 href="https://AHMEDamin17.github.io/phishing-url-detector"
                 target="_blank">
                Live Demo
              </a>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section style="margin-top:18px" class="card">
      <h3 class="section-title">Internships & Experience</h3>
      <p style="margin:6px 0"><strong>Sai Technologies</strong> — UI/UX Design Intern (1 month). Designed mobile app interfaces using Adobe XD.</p>
      <p style="margin:6px 0"><strong>Askan Technologies</strong> — Android App Dev Intern (1 month). Built a basic app using Flutter.</p>
    </section>

    <section style="margin-top:18px" class="card">
      <h3 class="section-title">Volunteer & Leadership</h3>
      <p class="muted">Student leadership roles and organizer of academic events.</p>
    </section>

    <footer>
      <p class="muted">© Ahmed Amin K — Built with HTML/CSS • For educational purposes. Phishing simulation project conducted ethically in controlled environment.</p>
    </footer>
  </div>
</body>
</html>
