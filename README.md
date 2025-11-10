<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Sean Kamugasa — AI Engineer | Software Engineer | Business Data Analyst | Project Manager</title>
  <meta name="description" content="Sean Kamugasa — AI Engineer, Senior Backend Software Engineer, and Senior Business Data Analyst. Live projects, tech stack and contact links." />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#0f1724;
      --card:#0b1320;
      --muted:#9aa4b2;
      --accent1:#6ee7b7;
      --accent2:#60a5fa;
      --glass: rgba(255,255,255,0.03);
      color-scheme: dark;
      font-family: 'Inter', system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
    }
    *{box-sizing:border-box}
    body{margin:0;background:linear-gradient(180deg,#071020 0%, #0f1724 100%);color:#e6eef8;min-height:100vh;}
    .container{max-width:980px;margin:48px auto;padding:24px}

    header{display:flex;align-items:center;gap:20px}
    .avatar{width:96px;height:96px;border-radius:14px;background:linear-gradient(135deg,var(--accent1),var(--accent2));display:flex;align-items:center;justify-content:center;font-weight:700;color:#042027;font-size:36px}
    h1{margin:0;font-size:28px}
    p.lead{margin:6px 0 0;color:var(--muted)}

    .card{background:var(--card);border-radius:12px;padding:20px;margin-top:20px;box-shadow:0 6px 30px rgba(0,0,0,0.6);}

    .projects{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:16px;margin-top:16px}
    .project{background:var(--glass);padding:16px;border-radius:10px}
    .project h3{margin:0 0 8px;font-size:18px}
    .project p{margin:0 0 12px;color:var(--muted);font-size:14px}
    .btn{display:inline-block;padding:8px 12px;border-radius:8px;background:linear-gradient(90deg,var(--accent2),var(--accent1));color:#042027;text-decoration:none;font-weight:600}

    .techs{display:flex;flex-wrap:wrap;gap:8px;margin-top:12px}
    .badge{display:inline-flex;align-items:center;padding:6px 8px;border-radius:999px;background:rgba(255,255,255,0.03);font-weight:600;font-size:13px;color:var(--muted)}

    .contact{display:flex;gap:12px;align-items:center;margin-top:14px}
    .contact a{color:inherit;text-decoration:none}

    footer{margin-top:28px;color:var(--muted);font-size:13px;text-align:center}

    @media (max-width:520px){.avatar{width:76px;height:76px;font-size:28px}.container{padding:14px}}
  </style>
</head>
<body>
  <main class="container">
    <header>
      <div class="avatar" aria-hidden="true">SK</div>
      <div>
        <h1>Hi, I'm <strong>Sean Kamugasa</strong> 👋</h1>
        <p class="lead">AI Engineer • Senior Backend Software Engineer • Senior Business Data Analyst</p>
      </div>
    </header>

    <section class="card" aria-labelledby="about-heading">
      <h2 id="about-heading">About — What I do</h2>
      <p style="color:var(--muted);margin-top:8px;">I design and build production-ready AI systems, scalable backend services, and data-driven analytics that help organizations make smarter decisions. I combine practical engineering with clear business insight to deliver measurable results.</p>

      <div class="techs" aria-hidden="false" style="margin-top:12px">
        <span class="badge">Python</span>
        <span class="badge">Node.js</span>
        <span class="badge">Docker</span>
        <span class="badge">PostgreSQL</span>
        <span class="badge">Kubernetes</span>
        <span class="badge">Machine Learning</span>
      </div>
    </section>

    <section class="card" aria-labelledby="projects-heading">
      <h2 id="projects-heading">🔭 Current &amp; Live Projects</h2>
      <div class="projects">
        <article class="project">
          <h3>AI Voice Assistant 🔊</h3>
          <p>Real-time voice interaction &amp; agent orchestration. Focus areas: speech-to-text, intent routing, low-latency voice UX.</p>
          <a class="btn" href="https://pynovavoiceagent-production-8358.up.railway.app/" target="_blank" rel="noopener noreferrer">Open Live Demo</a>
        </article>

        <article class="project">
          <h3>AgroVerse AI 🌾</h3>
          <p>Agricultural intelligence chatbot providing domain-specific advisory and decision support for farmers and agritech teams.</p>
          <a class="btn" href="https://pynovaultrafastaichatbot-production-84aa.up.railway.app/" target="_blank" rel="noopener noreferrer">Open Live Demo</a>
        </article>
      </div>

      <p style="margin-top:12px;color:var(--muted);">For a deeper look at case studies and projects, visit my portfolio:</p>
      <a class="btn" href="https://www.seankamz.ink" target="_blank" rel="noopener noreferrer">Visit seankamz.ink</a>
    </section>

    <section class="card" aria-labelledby="contact-heading">
      <h2 id="contact-heading">Connect with me 📫</h2>
      <div class="contact">
        <a href="https://www.linkedin.com/in/sean-kamugasa/" target="_blank" rel="noopener noreferrer" aria-label="LinkedIn profile">
          <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn icon" width="36" height="36">
        </a>

        <div style="display:flex;flex-direction:column">
          <a href="https://www.linkedin.com/in/sean-kamugasa/" target="_blank" rel="noopener noreferrer" style="font-weight:700;color:inherit;text-decoration:none">LinkedIn — sean-kamugasa</a>
          <a href="https://www.seankamz.ink" target="_blank" rel="noopener noreferrer" style="color:var(--muted);text-decoration:none;font-size:13px;">Portfolio — seankamz.ink</a>
        </div>
      </div>

      <p style="margin-top:12px;color:var(--muted);">Feel free to reach out if you have an AI/automation problem to solve, a collaboration, or a role that needs end-to-end delivery. 🚀</p>
    </section>

  </main>
</body>
</html>
