<!DOCTYPE html><html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Sohail Ali — Portfolio & Updates</title>
  <meta name="description" content="Official portfolio and live updates for Sohail Ali: projects, skills, timeline, and ways to reach me." />
  <meta property="og:title" content="Sohail Ali — Portfolio & Updates" />
  <meta property="og:description" content="Projects, skills, timeline, and ways to reach me." />
  <meta property="og:type" content="website" />
  <meta property="og:image" content="https://dummyimage.com/1200x630/0f172a/ffffff&text=Sohail+Ali" />
  <link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Crect width='100' height='100' rx='24' fill='%230f172a'/%3E%3Ctext x='50' y='58' font-size='56' text-anchor='middle' fill='%23fff' font-family='Segoe UI, Roboto, Helvetica, Arial, sans-serif'%3ESA%3C/text%3E%3C/svg%3E" />
  <style>
    /* Styling same as before */
    :root{
      --bg: #0b1220;
      --panel: rgba(255,255,255,0.06);
      --card: rgba(255,255,255,0.08);
      --text: #e5e7eb;
      --muted:#9ca3af;
      --brand:#7c3aed;
      --brand-2:#06b6d4;
      --ok:#22c55e;
      --warn:#f59e0b;
      --danger:#ef4444;
      --shadow: 0 10px 30px rgba(0,0,0,.35), inset 0 1px 0 rgba(255,255,255,.04);
      --radius: 22px;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0; font-family: Inter, ui-sans-serif, system-ui, Segoe UI, Roboto, Helvetica, Arial, Apple Color Emoji, Noto Color Emoji, sans-serif; color:var(--text); background: radial-gradient(800px 800px at 80% -10%, rgba(124,58,237,.2), transparent 50%), radial-gradient(700px 700px at -10% 10%, rgba(6,182,212,.18), transparent 40%), var(--bg);
      line-height:1.6; letter-spacing:.2px;
    }
    a{color:inherit; text-decoration:none}
    .container{max-width:1100px; margin:0 auto; padding: 24px;}
    .nav{position:sticky; top:0; z-index:40; backdrop-filter: blur(12px); background:linear-gradient(180deg, rgba(11,18,32,.85), rgba(11,18,32,.55)); border-bottom:1px solid rgba(255,255,255,.06)}
    .nav-inner{display:flex; align-items:center; justify-content:space-between; gap:16px; padding:14px 0}
    .brand{display:flex; align-items:center; gap:10px; font-weight:700}
    .brand-dot{width:12px; height:12px; border-radius:999px; background:linear-gradient(135deg, var(--brand), var(--brand-2)); box-shadow:0 0 16px rgba(124,58,237,.8), 0 0 24px rgba(6,182,212,.6)}
    .nav a{opacity:.9}
    .nav-links{display:flex; gap:18px; flex-wrap:wrap}
    .btn{display:inline-flex; align-items:center; gap:10px; padding:10px 16px; border-radius:999px; background:linear-gradient(135deg, var(--brand), var(--brand-2)); color:#fff; font-weight:600; box-shadow: var(--shadow); border:1px solid rgba(255,255,255,.08)}
    .btn:hover{transform: translateY(-1px); filter:saturate(110%)}.hero{display:grid; grid-template-columns: 1.1fr .9fr; gap:28px; padding: 28px 0 26px}
.card{background: var(--card); border:1px solid rgba(255,255,255,.08); border-radius: var(--radius); box-shadow: var(--shadow)}
.panel{background: var(--panel); border:1px solid rgba(255,255,255,.06); border-radius: var(--radius); box-shadow: var(--shadow)}
.hero h1{font-size: clamp(32px, 4vw, 52px); line-height:1.1; margin:0}
.hero p{color:var(--muted); margin:10px 0 22px}

.tag{display:inline-flex; align-items:center; gap:8px; padding:6px 12px; border-radius:999px; background:rgba(124,58,237,.12); border:1px solid rgba(124,58,237,.25); color:#d6bbfb; font-weight:600; font-size:12px; letter-spacing:.4px}
.grid{display:grid; gap:18px}
.grid.cols-3{grid-template-columns: repeat(3, minmax(0,1fr))}
.grid.cols-2{grid-template-columns: repeat(2, minmax(0,1fr))}

.avatar{aspect-ratio:1/1; border-radius: var(--radius); overflow:hidden; position:relative}
.avatar img{width:100%; height:100%; object-fit:cover; display:block; filter: saturate(105%)}
.glow{position:absolute; inset: -2px; border-radius: inherit; padding:2px; background: linear-gradient(135deg, rgba(124,58,237,.7), rgba(6,182,212,.7)); -webkit-mask: linear-gradient(#000 0 0) content-box, linear-gradient(#000 0 0); -webkit-mask-composite: xor; mask-composite: exclude;}

section{margin: 24px 0}
section h2{font-size: clamp(22px, 2.4vw, 30px); margin: 0 0 12px}
.section-sub{color:var(--muted); margin: 0 0 12px}

.skill{display:flex; align-items:center; justify-content:space-between; padding:12px 14px; border-radius:14px; background:rgba(255,255,255,.04); border:1px solid rgba(255,255,255,.06)}
.bar{height:8px; background:rgba(255,255,255,.1); border-radius:8px; overflow:hidden}
.bar>i{display:block; height:100%; background:linear-gradient(90deg, var(--brand), var(--brand-2));}

.project{display:flex; gap:16px; padding:14px; border-radius:16px; background:rgba(255,255,255,.04); border:1px solid rgba(255,255,255,.06)}
.project img{width:120px; height:90px; object-fit:cover; border-radius:12px}
.project h3{margin:0 0 6px; font-size:18px}
.project p{margin:0; color:var(--muted); font-size:14px}
.project .tags{display:flex; gap:8px; margin-top:10px; flex-wrap:wrap}
.chip{font-size:12px; padding:4px 10px; border-radius:999px; background:rgba(255,255,255,.06); border:1px solid rgba(255,255,255,.08)}

.timeline{position:relative; padding-left:24px}
.timeline::before{content:""; position:absolute; left:6px; top:0; bottom:0; width:2px; background:linear-gradient(var(--brand), var(--brand-2))}
.t-item{position:relative; margin:14px 0; padding:10px 14px; background:rgba(255,255,255,.04); border:1px solid rgba(255,255,255,.06); border-radius:14px}
.t-item::before{content:""; position:absolute; left:-10px; top:16px; width:14px; height:14px; border-radius:999px; background:linear-gradient(135deg, var(--brand), var(--brand-2)); box-shadow:0 0 0 3px rgba(124,58,237,.25)}
.t-item .when{font-size:12px; color:var(--muted)}

.cta{display:flex; gap:12px; flex-wrap:wrap}
.cta .ghost{background:transparent; border:1px solid rgba(255,255,255,.14)}

footer{margin: 24px 0 40px; color:var(--muted); font-size:14px; display:flex; align-items:center; justify-content:space-between; gap:10px; flex-wrap:wrap}
.socials{display:flex; gap:10px}
.socials a{padding:10px 12px; border-radius:12px; border:1px solid rgba(255,255,255,.12); background:rgba(255,255,255,.04)}

@media (max-width: 920px){
  .hero{grid-template-columns: 1fr;}
}

  </style>
</head>
<body>
  <header class="nav">
    <div class="container nav-inner">
      <div class="brand"><span class="brand-dot"></span> <span>Sohail Ali</span></div>
      <nav class="nav-links">
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#timeline">Timeline</a>
        <a href="#contact">Contact</a>
      </nav>
      <a class="btn" href="#contact" title="Contact me">Hire Me</a>
    </div>
  </header>  <main class="container">
    <section class="hero">
      <div class="card" style="padding:20px;display:flex;flex-direction:column;justify-content:center">
        <span class="tag">OPEN • Up to date info</span>
        <h1>Hi, I'm <span style="background:linear-gradient(90deg,var(--brand),var(--brand-2)); -webkit-background-clip:text; background-clip:text; color:transparent">Sohail Ali</span> — developer, gamer & builder.</h1>
        <p>I craft fast, clean experiences with a focus on gaming, fighting/action vibes, and professional projects. This page shows my latest updates, projects, and ways to reach me.</p>
        <div class="cta">
          <a class="btn" href="#projects">View Projects</a>
          <a class="btn ghost" href="#about">About Me</a>
        </div>
      </div>
      <div class="panel" style="padding:18px">
        <div class="avatar">
          <img src="https://images.unsplash.com/photo-1527980965255-d3b416303d12?q=80&w=1200&auto=format&fit=crop" alt="Sohail — portrait placeholder" />
          <i class="glow"></i>
        </div>
        <div style="display:grid; grid-template-columns:1fr 1fr; gap:10px; margin-top:12px">
          <div class="skill"><span>Availability</span> <span style="color:var(--ok);font-weight:700">Taking work</span></div>
          <div class="skill"><span>Location</span> <span>India (IST)</span></div>
          <div class="skill"><span>Last update</span> <span id="lastUpdate">—</span></div>
          <div class="skill"><span>Contact</span> <span><a href="mailto:sohailali8480@gmail.com">sohailali8480@gmail.com</a></span></div>
        </div>
      </div>
    </section><section id="about">
  <h2>About Me</h2>
  <p class="section-sub">Quick intro you can tweak anytime.</p>
  <div class="grid cols-2">
    <div class="panel" style="padding:16px">
      <p>I'm Sohail — a part‑time creator who jams on game concepts, clean UI, and performance. When I'm not building, I'm in the gym or exploring new horror/action titles. I like shipping small things fast and scaling what works.</p>
      <ul>
        <li>🛠️ <b>Focus:</b> gameplay systems, leaderboards, dashboards</li>
        <li>💼 <b>Open to:</b> internships, collabs, freelance</li>
        <li>🎯 <b>Goals 2025:</b> publish a fighting‑style indie prototype</li>
      </ul>
    </div>
    <div class="panel" style="padding:16px">
      <div class="grid cols-2">
        <div>
          <div class="skill"><span>JavaScript</span><div class="bar" style="width:48%"><i style="width:85%"></i></div></div>
          <div class="skill"><span>React / React Native</span><div class="bar" style="width:48%"><i style="width:78%"></i></div></div>
          <div class="skill"><span>HTML/CSS</span><div class="bar" style="width:48%"><i style="width:90%"></i></div></div>
        </div>
        <div>
          <div class="skill"><span>Unity / C#</span><div class="bar" style="width:48%"><i style="width:70%"></i></div></div>
          <div class="skill"><span>Node.js</span><div class="bar" style="width:48%"><i style="width:72%"></i></div></div>
          <div class="skill"><span>SQL / Firebase</span><div class="bar" style="width:48%"><i style="width:64%"></i></div></div>
        </div>
      </div>
    </div>
  </div>
</section>

<section id="projects">
  <h2>Projects</h2>
  <p class="section-sub">A few things I've shipped or I'm building now.</p>
  <div class="grid">
    <article class="project">
      <img src="https://images.unsplash.com/photo-1542751110-97427bbecf20?q=80&w=1200&auto=format&fit=crop" alt="Project preview" />
      <div>
        <h3>Top Tier — Leaderboard App</h3>
        <p>Mobile‑first leaderboard tracker for fighting games with live tiers, player stats, and season resets.</p>
        <div class="tags">
          <span class="chip">React Native</span>
          <span class="chip">Firebase</span>
          <span class="chip">Realtime</span>
        </div>
      </div>
    </article>
    <article class="project">
      <img src="https://images.unsplash.com/photo-1547658719-da2b51169166?q=80&w=1200&auto=format&fit=crop" alt="Project preview" />
      <div>
        <h3>Pulse — Status Dashboard</h3>
        <p>Clean, fast system status & analytics for small teams. Built for clarity under pressure.</p>
        <div class="tags">
          <span class="chip">Next.js</span>
          <span class="chip">Tailwind</span>
          <span class="chip">Charts</span>
        </div>
      </div>
    </article>
    <article class="project">
      <img src="https://images.unsplash.com/photo-1520975922215-c0be2679c3a5?q=80&w=1200&auto=format&fit=crop" alt="Project preview" />
      <div>
        <h3>Night Shift — Horror Prototype</h3>
        <p>Short, tense experience with simple stealth mechanics and tight sound design.</p>
        <div class="tags">
          <span class="chip">Unity</span>
          <span class="chip">C#</span>
          <span class="chip">Game Design</span>
        </div>
      </div>
    </article>
    <article class="project">
      <img src="https://images.unsplash.com/photo-1556157382-97eda2

# index.html
My Portfolio.
