<html><head></head><style>
  :root{--bg:#0b1020;--bg2:#111936;--card:#121b35;--text:#eaf0ff;--muted:#a9b5d3;--brand:#78a6ff;--brand2:#8b5cf6;--line:rgba(255,255,255,.10);--shadow:0 20px 60px rgba(0,0,0,.35)}
  *{box-sizing:border-box}html{scroll-behavior:smooth}body{margin:0;font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,Arial,sans-serif;background:radial-gradient(circle at top,#172449 0,#0b1020 45%,#070b15 100%);color:var(--text);line-height:1.6}
  a{color:inherit;text-decoration:none}img{max-width:100%;display:block}
  .page{min-height:100vh}
  .container{width:min(1120px,calc(100% - 32px));margin:0 auto}
  .header{position:sticky;top:0;z-index:20;background:rgba(7,11,21,.72);backdrop-filter:blur(16px);border-bottom:1px solid var(--line)}
  .nav{display:flex;align-items:center;justify-content:space-between;padding:18px 0;gap:16px;flex-wrap:wrap}
  .brand{display:flex;flex-direction:column;gap:2px}
  .brand strong{font-size:1.05rem;letter-spacing:.2px}
  .brand span,.nav a{color:var(--muted);font-size:.95rem}
  .nav-links{display:flex;gap:18px;flex-wrap:wrap}
  .hero{padding:88px 0 56px}
  .hero-grid{display:grid;grid-template-columns:1.2fr .8fr;gap:28px;align-items:center}
  .eyebrow{display:inline-flex;align-items:center;gap:8px;padding:8px 14px;border:1px solid var(--line);border-radius:999px;background:rgba(255,255,255,.04);color:var(--muted);font-size:.92rem}
  h1{margin:18px 0 14px;font-size:clamp(2.4rem,5vw,4.8rem);line-height:1.05;letter-spacing:-.04em}
  .lead{font-size:1.08rem;color:var(--muted);max-width:62ch}
  .cta{display:flex;gap:14px;flex-wrap:wrap;margin-top:28px}
  .btn{display:inline-flex;align-items:center;justify-content:center;padding:14px 20px;border-radius:14px;font-weight:700;border:1px solid var(--line);transition:.2s ease}
  .btn-primary{background:linear-gradient(135deg,var(--brand),var(--brand2));color:#fff;box-shadow:var(--shadow)}
  .btn-secondary{background:rgba(255,255,255,.04);color:var(--text)}
  .btn:hover{transform:translateY(-1px)}
  .panel{background:linear-gradient(180deg,rgba(255,255,255,.08),rgba(255,255,255,.04));border:1px solid var(--line);border-radius:24px;padding:24px;box-shadow:var(--shadow)}
  .profile{display:grid;gap:18px}
  .avatar{width:104px;height:104px;border-radius:28px;background:linear-gradient(135deg,#78a6ff,#8b5cf6);display:grid;place-items:center;font-size:2.6rem;font-weight:800;color:#fff}
  .meta{display:grid;gap:10px;color:var(--muted)}
  .section{padding:22px 0 56px}
  .section h2{font-size:clamp(1.6rem,2.6vw,2.4rem);margin:0 0 16px}
  .grid{display:grid;grid-template-columns:repeat(3,1fr);gap:18px}
  .card{background:rgba(255,255,255,.04);border:1px solid var(--line);border-radius:20px;padding:22px}
  .card h3{margin:0 0 8px;font-size:1.08rem}
  .card p,.card li{color:var(--muted)}
  .split{display:grid;grid-template-columns:1fr 1fr;gap:18px}
  .timeline{display:grid;gap:16px}
  .timeline-item{padding:18px 20px;border-left:3px solid var(--brand);background:rgba(255,255,255,.04);border-radius:0 16px 16px 0;border-top:1px solid var(--line);border-right:1px solid var(--line);border-bottom:1px solid var(--line)}
  .footer{padding:28px 0 42px;border-top:1px solid var(--line);color:var(--muted)}
  .chips{display:flex;flex-wrap:wrap;gap:10px;margin-top:16px}.chip{padding:8px 12px;border-radius:999px;background:rgba(255,255,255,.06);border:1px solid var(--line);font-size:.92rem}
  @media (max-width: 860px){.hero-grid,.grid,.split{grid-template-columns:1fr}.nav{justify-content:center;text-align:center}.brand{align-items:center}}
</style>
<div class="page">
  <header class="header">
    <div class="container nav">
      <div class="brand"><strong>Chirag Dodiya</strong><span>Senior Engineer</span></div>
      <nav class="nav-links" aria-label="Primary">
        <a href="#about">About</a>
        <a href="#experience">Experience</a>
        <a href="#skills">Skills</a>
        <a href="#contact">Contact</a>
      </nav>
    </div>
  </header>

  <main>
    <section class="hero">
      <div class="container hero-grid">
        <div>
          <div class="eyebrow">Senior Engineer · Product-minded problem solver</div>
          <h1>Chirag Dodiya</h1>
          <p class="lead">I build reliable, scalable digital products with a focus on clean architecture, thoughtful user experience, and pragmatic execution. I help teams ship faster without sacrificing quality.</p>
          <div class="cta">
            <a class="btn btn-primary" href="#contact">Contact Me</a>
            <a class="btn btn-secondary" href="#experience">View Experience</a>
          </div>
        </div>
        <aside class="panel profile" aria-label="Profile summary">
          <div class="avatar" aria-hidden="true">CD</div>
          <div class="meta">
            <div><strong>Role:</strong> Senior Engineer</div>
            <div><strong>Focus:</strong> Scalable web applications, systems thinking, and delivery excellence</div>
            <div><strong>Location:</strong> Available for remote and hybrid opportunities</div>
          </div>
        </aside>
      </div>
    </section>

    <section class="section" id="about">
      <div class="container">
        <h2>About Me</h2>
        <div class="card">
          <p>I'm Chirag Dodiya, a Senior Engineer who enjoys turning complex requirements into simple, maintainable solutions. My approach blends strong technical foundations with collaboration, ownership, and a strong sense of product impact.</p>
          <div class="chips">
            <span class="chip">Engineering Leadership</span>
            <span class="chip">Frontend Systems</span>
            <span class="chip">Performance Optimization</span>
            <span class="chip">Cross-functional Collaboration</span>
          </div>
        </div>
      </div>
    </section>

    <section class="section" id="experience">
      <div class="container split">
        <div>
          <h2>Experience</h2>
          <div class="timeline">
            <div class="timeline-item">
              <h3>Senior Engineer</h3>
              <p>Led delivery of customer-facing experiences, improved maintainability, and partnered with design and product to raise quality standards.</p>
            </div>
            <div class="timeline-item">
              <h3>Technical Contributor</h3>
              <p>Built reusable UI patterns, integrated APIs, and optimized application performance across critical user journeys.</p>
            </div>
          </div>
        </div>
        <div id="skills">
          <h2>Skills</h2>
          <div class="grid">
            <div class="card"><h3>Frontend</h3><p>HTML, CSS, responsive design, component architecture.</p></div>
            <div class="card"><h3>Backend</h3><p>API integration, data flow design, reliability-minded development.</p></div>
            <div class="card"><h3>Delivery</h3><p>Agile execution, mentoring, review rigor, stakeholder communication.</p></div>
          </div>
        </div>
      </div>
    </section>

    <section class="section" id="contact">
      <div class="container">
        <h2>Contact</h2>
        <div class="card">
          <p>If you'd like to collaborate, discuss opportunities, or learn more about my work, feel free to reach out.</p>
          <p><strong>Name:</strong> Chirag Dodiya<br><strong>Title:</strong> Senior Engineer</p>
        </div>
      </div>
    </section>
  </main>

  <footer class="footer">
    <div class="container">© 2026 Chirag Dodiya. Personal resume website.</div>
  </footer>
</div></html>