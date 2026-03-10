<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Rahul Kumar — Staff / Platform Engineer</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Syne:wght@400;600;700;800&family=JetBrains+Mono:wght@300;400;500&family=Instrument+Sans:wght@300;400;500&display=swap" rel="stylesheet">
  <style>
    *, *::before, *::after { margin: 0; padding: 0; box-sizing: border-box; }

    :root {
      --bg:       #080C18;
      --bg2:      #0D1220;
      --bg3:      #111827;
      --border:   rgba(0,212,255,0.12);
      --cyan:     #00D4FF;
      --purple:   #8B5CF6;
      --gold:     #F59E0B;
      --text:     #CBD5E1;
      --text-hi:  #F1F5F9;
      --text-lo:  #64748B;
      --mono:     'JetBrains Mono', monospace;
      --display:  'Syne', sans-serif;
      --body:     'Instrument Sans', sans-serif;
    }

    html { scroll-behavior: smooth; }
    body {
      background: var(--bg);
      color: var(--text);
      font-family: var(--body);
      overflow-x: hidden;
      cursor: none;
    }

    /* CUSTOM CURSOR */
    .cursor {
      width: 10px; height: 10px;
      background: var(--cyan);
      border-radius: 50%;
      position: fixed; top: 0; left: 0;
      pointer-events: none; z-index: 9999;
      transition: transform 0.1s;
      mix-blend-mode: screen;
    }
    .cursor-ring {
      width: 36px; height: 36px;
      border: 1px solid rgba(0,212,255,0.5);
      border-radius: 50%;
      position: fixed; top: 0; left: 0;
      pointer-events: none; z-index: 9998;
      transition: transform 0.15s, width 0.2s, height 0.2s;
    }

    /* NAV */
    nav {
      position: fixed; top: 0; left: 0; right: 0; z-index: 100;
      display: flex; justify-content: space-between; align-items: center;
      padding: 1.2rem 4rem;
      background: rgba(8,12,24,0.85);
      backdrop-filter: blur(16px);
      border-bottom: 1px solid var(--border);
    }
    .nav-logo {
      font-family: var(--mono);
      font-size: 0.85rem;
      color: var(--cyan);
      letter-spacing: 0.1em;
    }
    .nav-links { display: flex; gap: 2.5rem; list-style: none; }
    .nav-links a {
      font-family: var(--mono);
      font-size: 0.75rem;
      color: var(--text-lo);
      text-decoration: none;
      letter-spacing: 0.12em;
      text-transform: uppercase;
      transition: color 0.2s;
    }
    .nav-links a:hover { color: var(--cyan); }

    /* SECTIONS */
    section { padding: 7rem 4rem; max-width: 1200px; margin: 0 auto; }

    /* ===================== HERO ===================== */
    #hero {
      min-height: 100vh;
      display: flex; flex-direction: column; justify-content: center;
      padding-top: 8rem;
      position: relative;
      max-width: 100%;
    }
    .hero-inner { max-width: 1200px; margin: 0 auto; padding: 0 4rem; }

    .hero-eyebrow {
      font-family: var(--mono);
      font-size: 0.75rem;
      color: var(--cyan);
      letter-spacing: 0.2em;
      text-transform: uppercase;
      margin-bottom: 1.5rem;
      display: flex; align-items: center; gap: 1rem;
      opacity: 0; animation: fadeUp 0.6s 0.2s forwards;
    }
    .hero-eyebrow::before {
      content: '';
      display: inline-block; width: 40px; height: 1px;
      background: var(--cyan);
    }

    .hero-name {
      font-family: var(--display);
      font-size: clamp(3.5rem, 9vw, 8rem);
      font-weight: 800;
      line-height: 0.95;
      color: var(--text-hi);
      letter-spacing: -0.03em;
      opacity: 0; animation: fadeUp 0.7s 0.35s forwards;
    }
    .hero-name span {
      display: block;
      background: linear-gradient(135deg, var(--cyan) 0%, var(--purple) 100%);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }

    .hero-title {
      font-family: var(--mono);
      font-size: 0.9rem;
      color: var(--text-lo);
      letter-spacing: 0.08em;
      margin-top: 1.5rem;
      opacity: 0; animation: fadeUp 0.7s 0.5s forwards;
    }

    .hero-desc {
      max-width: 560px;
      font-size: 1.05rem;
      line-height: 1.75;
      color: var(--text);
      margin-top: 2rem;
      opacity: 0; animation: fadeUp 0.7s 0.65s forwards;
    }

    .hero-cta {
      display: flex; gap: 1rem; margin-top: 3rem;
      opacity: 0; animation: fadeUp 0.7s 0.8s forwards;
    }
    .btn-primary {
      padding: 0.85rem 2.2rem;
      background: var(--cyan);
      color: var(--bg);
      font-family: var(--mono);
      font-size: 0.8rem;
      letter-spacing: 0.1em;
      text-transform: uppercase;
      text-decoration: none;
      font-weight: 500;
      border: none; cursor: none;
      transition: transform 0.2s, box-shadow 0.2s;
    }
    .btn-primary:hover {
      transform: translateY(-2px);
      box-shadow: 0 0 32px rgba(0,212,255,0.4);
    }
    .btn-ghost {
      padding: 0.85rem 2.2rem;
      border: 1px solid var(--border);
      color: var(--text);
      font-family: var(--mono);
      font-size: 0.8rem;
      letter-spacing: 0.1em;
      text-transform: uppercase;
      text-decoration: none;
      transition: border-color 0.2s, color 0.2s;
    }
    .btn-ghost:hover { border-color: var(--cyan); color: var(--cyan); }

    .hero-stats {
      display: flex; gap: 3rem; margin-top: 5rem;
      padding-top: 3rem;
      border-top: 1px solid var(--border);
      opacity: 0; animation: fadeUp 0.7s 0.95s forwards;
    }
    .stat-num {
      font-family: var(--display);
      font-size: 2.2rem;
      font-weight: 800;
      color: var(--text-hi);
    }
    .stat-num span { color: var(--cyan); }
    .stat-label {
      font-family: var(--mono);
      font-size: 0.7rem;
      color: var(--text-lo);
      letter-spacing: 0.12em;
      text-transform: uppercase;
      margin-top: 0.2rem;
    }

    /* grid background */
    .grid-bg {
      position: fixed; inset: 0;
      background-image:
        linear-gradient(rgba(0,212,255,0.025) 1px, transparent 1px),
        linear-gradient(90deg, rgba(0,212,255,0.025) 1px, transparent 1px);
      background-size: 60px 60px;
      pointer-events: none; z-index: 0;
    }
    #hero, section { position: relative; z-index: 1; }

    /* glow orbs */
    .orb {
      position: fixed;
      border-radius: 50%;
      filter: blur(120px);
      pointer-events: none;
      z-index: 0;
    }
    .orb-1 {
      width: 600px; height: 600px;
      background: rgba(0,212,255,0.06);
      top: -200px; right: -100px;
    }
    .orb-2 {
      width: 500px; height: 500px;
      background: rgba(139,92,246,0.06);
      bottom: 10%; left: -150px;
    }

    /* ===================== SECTION HEADERS ===================== */
    .section-label {
      font-family: var(--mono);
      font-size: 0.72rem;
      color: var(--cyan);
      letter-spacing: 0.2em;
      text-transform: uppercase;
      display: flex; align-items: center; gap: 1rem;
      margin-bottom: 1.2rem;
    }
    .section-label::before {
      content: '';
      display: inline-block; width: 32px; height: 1px;
      background: var(--cyan);
    }
    .section-title {
      font-family: var(--display);
      font-size: clamp(2rem, 4vw, 3rem);
      font-weight: 800;
      color: var(--text-hi);
      line-height: 1.1;
      letter-spacing: -0.02em;
    }
    .section-title span { color: var(--cyan); }

    /* ===================== ABOUT ===================== */
    #about { padding: 7rem 4rem; }
    .about-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 5rem;
      margin-top: 3.5rem;
      align-items: start;
    }
    .about-text p {
      font-size: 1.05rem;
      line-height: 1.8;
      color: var(--text);
      margin-bottom: 1.2rem;
    }
    .about-text p strong { color: var(--text-hi); }
    .about-philosophy {
      margin-top: 2rem;
      padding: 1.5rem;
      border-left: 2px solid var(--cyan);
      background: var(--bg2);
    }
    .about-philosophy p {
      font-family: var(--mono);
      font-size: 0.85rem;
      color: var(--text);
      line-height: 1.7;
      margin: 0;
    }
    .about-philosophy p em { color: var(--cyan); font-style: normal; }

    .about-pillars { display: flex; flex-direction: column; gap: 1rem; }
    .pillar {
      padding: 1.4rem 1.6rem;
      border: 1px solid var(--border);
      background: var(--bg2);
      transition: border-color 0.25s, transform 0.25s;
    }
    .pillar:hover {
      border-color: rgba(0,212,255,0.35);
      transform: translateX(6px);
    }
    .pillar-icon {
      font-size: 1.3rem;
      margin-bottom: 0.5rem;
    }
    .pillar-title {
      font-family: var(--display);
      font-size: 0.95rem;
      font-weight: 700;
      color: var(--text-hi);
      margin-bottom: 0.3rem;
    }
    .pillar-desc {
      font-size: 0.85rem;
      color: var(--text-lo);
      line-height: 1.5;
    }

    /* ===================== SKILLS ===================== */
    #skills { padding: 7rem 4rem; }
    .skills-grid {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 1.5rem;
      margin-top: 3.5rem;
    }
    .skill-card {
      padding: 2rem;
      border: 1px solid var(--border);
      background: var(--bg2);
      transition: border-color 0.25s;
    }
    .skill-card:hover { border-color: rgba(0,212,255,0.3); }
    .skill-card-header {
      display: flex; align-items: center; gap: 0.8rem;
      margin-bottom: 1.2rem;
    }
    .skill-cat-icon {
      width: 36px; height: 36px;
      background: rgba(0,212,255,0.08);
      border: 1px solid var(--border);
      display: flex; align-items: center; justify-content: center;
      font-size: 1rem;
    }
    .skill-cat {
      font-family: var(--display);
      font-size: 0.9rem;
      font-weight: 700;
      color: var(--text-hi);
    }
    .skill-tags { display: flex; flex-wrap: wrap; gap: 0.5rem; }
    .tag {
      padding: 0.3rem 0.8rem;
      font-family: var(--mono);
      font-size: 0.72rem;
      letter-spacing: 0.05em;
      border: 1px solid var(--border);
      color: var(--text-lo);
      transition: all 0.2s;
    }
    .tag:hover, .tag.active {
      background: rgba(0,212,255,0.08);
      border-color: var(--cyan);
      color: var(--cyan);
    }

    /* ===================== EXPERIENCE ===================== */
    #experience { padding: 7rem 4rem; }
    .exp-list { margin-top: 3.5rem; display: flex; flex-direction: column; gap: 0; }
    .exp-item {
      display: grid;
      grid-template-columns: 220px 1fr;
      gap: 3rem;
      padding: 2.5rem 0;
      border-bottom: 1px solid var(--border);
      transition: background 0.2s;
    }
    .exp-item:first-child { border-top: 1px solid var(--border); }
    .exp-meta { padding-top: 0.2rem; }
    .exp-period {
      font-family: var(--mono);
      font-size: 0.75rem;
      color: var(--text-lo);
      letter-spacing: 0.08em;
      margin-bottom: 0.5rem;
    }
    .exp-company {
      font-family: var(--display);
      font-size: 1rem;
      font-weight: 700;
      color: var(--cyan);
    }
    .exp-location {
      font-family: var(--mono);
      font-size: 0.7rem;
      color: var(--text-lo);
      margin-top: 0.3rem;
    }
    .exp-role {
      font-family: var(--display);
      font-size: 1.2rem;
      font-weight: 700;
      color: var(--text-hi);
      margin-bottom: 1rem;
    }
    .exp-points { list-style: none; display: flex; flex-direction: column; gap: 0.6rem; }
    .exp-points li {
      font-size: 0.9rem;
      color: var(--text);
      line-height: 1.6;
      padding-left: 1.2rem;
      position: relative;
    }
    .exp-points li::before {
      content: '▸';
      position: absolute; left: 0;
      color: var(--cyan);
      font-size: 0.7rem;
      top: 0.25rem;
    }

    /* ===================== PROJECTS ===================== */
    #projects { padding: 7rem 4rem; }
    .projects-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 1.2rem;
      margin-top: 3.5rem;
    }
    .project-card {
      padding: 1.8rem;
      border: 1px solid var(--border);
      background: var(--bg2);
      display: flex; flex-direction: column; gap: 0.8rem;
      transition: border-color 0.25s, transform 0.25s;
      text-decoration: none;
    }
    .project-card:hover {
      border-color: rgba(0,212,255,0.3);
      transform: translateY(-4px);
    }
    .project-card-header {
      display: flex; justify-content: space-between; align-items: flex-start;
    }
    .project-icon { font-size: 1.4rem; }
    .project-arrow {
      font-family: var(--mono);
      font-size: 0.8rem;
      color: var(--text-lo);
      transition: color 0.2s;
    }
    .project-card:hover .project-arrow { color: var(--cyan); }
    .project-name {
      font-family: var(--display);
      font-size: 1rem;
      font-weight: 700;
      color: var(--text-hi);
    }
    .project-desc {
      font-size: 0.85rem;
      color: var(--text-lo);
      line-height: 1.55;
    }
    .project-lang {
      font-family: var(--mono);
      font-size: 0.7rem;
      color: var(--cyan);
      letter-spacing: 0.08em;
      margin-top: auto;
    }

    /* ===================== CONTACT ===================== */
    #contact { padding: 7rem 4rem 10rem; }
    .contact-wrapper {
      margin-top: 3.5rem;
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 5rem;
      align-items: start;
    }
    .contact-headline {
      font-family: var(--display);
      font-size: clamp(1.8rem, 3.5vw, 2.8rem);
      font-weight: 800;
      color: var(--text-hi);
      line-height: 1.2;
      letter-spacing: -0.02em;
      margin-bottom: 1.5rem;
    }
    .contact-headline span { color: var(--cyan); }
    .contact-desc {
      font-size: 1rem;
      color: var(--text);
      line-height: 1.75;
      margin-bottom: 2.5rem;
    }
    .contact-links { display: flex; flex-direction: column; gap: 0.8rem; }
    .contact-link {
      display: flex; align-items: center; gap: 1rem;
      padding: 1rem 1.2rem;
      border: 1px solid var(--border);
      text-decoration: none;
      transition: border-color 0.2s, transform 0.2s;
    }
    .contact-link:hover {
      border-color: rgba(0,212,255,0.3);
      transform: translateX(4px);
    }
    .contact-link-icon {
      font-size: 1rem;
      width: 32px; text-align: center;
    }
    .contact-link-label {
      font-family: var(--mono);
      font-size: 0.8rem;
      color: var(--text-lo);
      letter-spacing: 0.08em;
    }
    .contact-link-value {
      font-size: 0.9rem;
      color: var(--text-hi);
      margin-top: 0.1rem;
    }
    .contact-open {
      display: inline-flex; align-items: center; gap: 0.8rem;
      padding: 1.5rem 2rem;
      border: 1px solid var(--border);
      background: var(--bg2);
    }
    .open-dot {
      width: 8px; height: 8px;
      background: #22C55E;
      border-radius: 50%;
      box-shadow: 0 0 10px #22C55E;
      animation: pulse 2s infinite;
    }
    @keyframes pulse {
      0%, 100% { opacity: 1; transform: scale(1); }
      50% { opacity: 0.6; transform: scale(1.2); }
    }
    .open-text {
      font-family: var(--mono);
      font-size: 0.8rem;
      color: var(--text);
      letter-spacing: 0.08em;
    }
    .open-text strong { color: #22C55E; }

    /* FOOTER */
    footer {
      border-top: 1px solid var(--border);
      padding: 2rem 4rem;
      display: flex; justify-content: space-between; align-items: center;
      max-width: 1200px; margin: 0 auto;
    }
    footer p {
      font-family: var(--mono);
      font-size: 0.72rem;
      color: var(--text-lo);
      letter-spacing: 0.08em;
    }
    footer span { color: var(--cyan); }

    /* ANIMATIONS */
    @keyframes fadeUp {
      from { opacity: 0; transform: translateY(20px); }
      to   { opacity: 1; transform: translateY(0); }
    }
    .reveal {
      opacity: 0;
      transform: translateY(24px);
      transition: opacity 0.6s, transform 0.6s;
    }
    .reveal.visible {
      opacity: 1;
      transform: translateY(0);
    }

    /* MOBILE */
    @media (max-width: 768px) {
      nav { padding: 1rem 1.5rem; }
      .nav-links { display: none; }
      section { padding: 5rem 1.5rem; }
      #hero .hero-inner { padding: 0 1.5rem; }
      .hero-stats { gap: 1.5rem; flex-wrap: wrap; }
      .about-grid, .skills-grid, .projects-grid,
      .contact-wrapper { grid-template-columns: 1fr; gap: 2rem; }
      .exp-item { grid-template-columns: 1fr; gap: 0.8rem; }
      footer { flex-direction: column; gap: 0.5rem; text-align: center; }
    }
  </style>
</head>
<body>

<!-- Cursor -->
<div class="cursor" id="cursor"></div>
<div class="cursor-ring" id="cursorRing"></div>

<!-- Background -->
<div class="grid-bg"></div>
<div class="orb orb-1"></div>
<div class="orb orb-2"></div>

<!-- NAV -->
<nav>
  <div class="nav-logo">rk.dev</div>
  <ul class="nav-links">
    <li><a href="#about">About</a></li>
    <li><a href="#skills">Skills</a></li>
    <li><a href="#experience">Experience</a></li>
    <li><a href="#projects">Projects</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>

<!-- HERO -->
<div id="hero">
  <div class="hero-inner">
    <div class="hero-eyebrow">Senior Software Engineer · Open to new opportunities</div>
    <h1 class="hero-name">
      Rahul<br/><span>Kumar</span>
    </h1>
    <div class="hero-title">Senior Software Engineer · Frontend Architecture · Developer Platforms · Micro-Frontends</div>
    <p class="hero-desc">
      I architect and scale enterprise UI platforms, design systems, and developer productivity tooling that enables entire engineering organisations to move faster — together.
    </p>
    <div class="hero-cta">
      <a href="#experience" class="btn-primary">View Experience</a>
      <a href="#contact" class="btn-ghost">Get in Touch</a>
    </div>
    <div class="hero-stats">
      <div>
        <div class="stat-num">11<span>+</span></div>
        <div class="stat-label">Years Experience</div>
      </div>
      <div>
        <div class="stat-num">4<span>+</span></div>
        <div class="stat-label">Enterprise Platforms Built</div>
      </div>
      <div>
        <div class="stat-num">40<span>%</span></div>
        <div class="stat-label">Deployment Efficiency Gained</div>
      </div>
      <div>
        <div class="stat-num">5</div>
        <div class="stat-label">Companies Worked At</div>
      </div>
    </div>
  </div>
</div>

<!-- ABOUT -->
<section id="about">
  <div class="section-label reveal">About</div>
  <h2 class="section-title reveal">Building Systems<br/>That <span>Scale</span></h2>
  <div class="about-grid">
    <div class="about-text reveal">
      <p>I'm a <strong>Senior Frontend & Platform Engineer</strong> with 11+ years of experience building the infrastructure layer that powers other engineers' work — shared libraries, extensibility models, and developer-facing platforms used across multi-team environments at scale.</p>
      <p>Currently at <strong>Walmart Global Tech</strong>, I own the shared frontend platform libraries enabling standardised application bootstrapping across multiple internal product teams — touching React, TypeScript, Module Federation, and CI/CD governance.</p>
      <p>My work lives at the intersection of <strong>engineering excellence and developer experience</strong>: reducing friction, standardising patterns, and making sure the next engineer to join the codebase is grateful they did.</p>
      <div class="about-philosophy">
        <p><em>"Engineering is not just about writing code. It's about making decisions that age well."</em></p>
      </div>
    </div>
    <div class="about-pillars reveal">
      <div class="pillar">
        <div class="pillar-icon">🏗</div>
        <div class="pillar-title">Platform Thinking</div>
        <div class="pillar-desc">I build the layer that accelerates other teams — shared libraries, extensibility frameworks, and reusable architecture that eliminates redundant work across orgs.</div>
      </div>
      <div class="pillar">
        <div class="pillar-icon">📐</div>
        <div class="pillar-title">Architecture Reviews</div>
        <div class="pillar-desc">Cross-team technical alignment, scalable design decisions, and long-term backward-compatibility strategy that lets platforms evolve without breaking consumers.</div>
      </div>
      <div class="pillar">
        <div class="pillar-icon">🧑‍🏫</div>
        <div class="pillar-title">Mentorship & Culture</div>
        <div class="pillar-desc">Mentoring senior engineers on library design principles, performance trade-offs, and the kind of platform thinking that separates good engineers from great ones.</div>
      </div>
      <div class="pillar">
        <div class="pillar-icon">⚡</div>
        <div class="pillar-title">Developer Productivity</div>
        <div class="pillar-desc">Translating systemic developer workflow friction into platform-level solutions — from CI/CD modernisation to standardised onboarding that cuts setup time to near zero.</div>
      </div>
    </div>
  </div>
</section>

<!-- SKILLS -->
<section id="skills">
  <div class="section-label reveal">Expertise</div>
  <h2 class="section-title reveal">Core <span>Skills</span></h2>
  <div class="skills-grid">
    <div class="skill-card reveal">
      <div class="skill-card-header">
        <div class="skill-cat-icon">🧩</div>
        <div class="skill-cat">Platform & Architecture</div>
      </div>
      <div class="skill-tags">
        <span class="tag active">Frontend Architecture</span>
        <span class="tag">Design Systems</span>
        <span class="tag">Micro-Frontends</span>
        <span class="tag">Monorepos</span>
        <span class="tag">System Design</span>
        <span class="tag">API Design</span>
        <span class="tag">Platform Governance</span>
        <span class="tag">Module Federation</span>
        <span class="tag">Extensibility & Versioning</span>
      </div>
    </div>
    <div class="skill-card reveal">
      <div class="skill-card-header">
        <div class="skill-cat-icon">⚛️</div>
        <div class="skill-cat">Frontend</div>
      </div>
      <div class="skill-tags">
        <span class="tag active">React</span>
        <span class="tag">TypeScript</span>
        <span class="tag">Next.js</span>
        <span class="tag">Angular</span>
        <span class="tag">Redux</span>
        <span class="tag">Storybook</span>
        <span class="tag">Web Performance</span>
        <span class="tag">MERN / MEAN</span>
      </div>
    </div>
    <div class="skill-card reveal">
      <div class="skill-card-header">
        <div class="skill-cat-icon">🖥</div>
        <div class="skill-cat">Backend & APIs</div>
      </div>
      <div class="skill-tags">
        <span class="tag active">Node.js</span>
        <span class="tag">Fastify</span>
        <span class="tag">Express</span>
        <span class="tag">REST APIs</span>
        <span class="tag">GraphQL</span>
      </div>
    </div>
    <div class="skill-card reveal">
      <div class="skill-card-header">
        <div class="skill-cat-icon">🚀</div>
        <div class="skill-cat">DevOps & Infrastructure</div>
      </div>
      <div class="skill-tags">
        <span class="tag active">CI/CD</span>
        <span class="tag">GitHub Actions</span>
        <span class="tag">AWS S3</span>
        <span class="tag">AWS Lambda</span>
        <span class="tag">Performance Optimization</span>
        <span class="tag">Release Governance</span>
      </div>
    </div>
  </div>
</section>

<!-- EXPERIENCE -->
<section id="experience">
  <div class="section-label reveal">Career</div>
  <h2 class="section-title reveal">Work <span>Experience</span></h2>
  <div class="exp-list">

    <div class="exp-item reveal">
      <div class="exp-meta">
        <div class="exp-period">Jan 2023 — Present</div>
        <div class="exp-company">Walmart Global Tech</div>
        <div class="exp-location">Bengaluru, India</div>
      </div>
      <div>
        <div class="exp-role">Senior Software Engineer (Platform Focus)</div>
        <ul class="exp-points">
          <li>Technical owner of shared frontend platform libraries enabling standardised application bootstrapping across multiple internal product teams.</li>
          <li>Designed scalable React + TypeScript-based reusable architecture frameworks, reducing project initialisation time and eliminating redundant implementation across teams.</li>
          <li>Defined extensibility, versioning, and backward compatibility strategy to support long-term platform adoption.</li>
          <li>Integrated enterprise services (auth, config, logging, CI hooks) into modular, reusable components.</li>
          <li>Partnered with architects and infra teams to translate systemic developer workflow friction into platform-level solutions.</li>
          <li>Mentored senior engineers on library design principles, performance trade-offs, and platform thinking.</li>
        </ul>
      </div>
    </div>

    <div class="exp-item reveal">
      <div class="exp-meta">
        <div class="exp-period">Apr 2020 — Jan 2023</div>
        <div class="exp-company">Alstom</div>
        <div class="exp-location">Bengaluru, India</div>
      </div>
      <div>
        <div class="exp-role">Technical Expert / UI Architecture Lead</div>
        <ul class="exp-points">
          <li>Owned end-to-end frontend architecture for multiple enterprise-scale platforms: THEMIS, ORION, APSYS, SPDB.</li>
          <li>Designed scalable UI architecture patterns adopted across teams.</li>
          <li>Reduced deployment cycles from weeks to hours by implementing CI/CD modernisation initiatives.</li>
          <li>Improved deployment efficiency by 40% through pipeline optimisation and automation.</li>
          <li>Led cross-functional teams delivering complex enterprise applications with high reliability and performance standards.</li>
          <li>Conducted architecture reviews and guided engineers on scalable design decisions.</li>
        </ul>
      </div>
    </div>

    <div class="exp-item reveal">
      <div class="exp-meta">
        <div class="exp-period">Jun 2017 — Apr 2020</div>
        <div class="exp-company">PowerSchool</div>
        <div class="exp-location">Group LLC</div>
      </div>
      <div>
        <div class="exp-role">Software Engineer (Full Stack)</div>
        <ul class="exp-points">
          <li>Built multiple full-stack MEAN applications from architecture to production.</li>
          <li>Owned performance optimisation, API design, and frontend scalability improvements.</li>
          <li>Delivered greenfield applications with complete lifecycle ownership.</li>
        </ul>
      </div>
    </div>

    <div class="exp-item reveal">
      <div class="exp-meta">
        <div class="exp-period">Nov 2016 — Jun 2017</div>
        <div class="exp-company">SelotSoft</div>
        <div class="exp-location">Software Developer</div>
      </div>
      <div>
        <div class="exp-role">Software Developer — Shipping Domain</div>
        <ul class="exp-points">
          <li>Developed scalable, responsive UI components for a logistics and shipping domain product, improving operator workflows and reducing data entry errors.</li>
          <li>Built modular frontend interfaces using JavaScript and Angular, enabling reuse across multiple views and shipping workflows.</li>
          <li>Collaborated closely with backend teams to integrate REST APIs and ensure seamless data flow across the application.</li>
          <li>Contributed to performance optimisation efforts, improving page load times for data-heavy shipping dashboards.</li>
        </ul>
      </div>
    </div>

    <div class="exp-item reveal">
      <div class="exp-meta">
        <div class="exp-period">Nov 2014 — Oct 2016</div>
        <div class="exp-company">UST Global</div>
        <div class="exp-location">Software Developer</div>
      </div>
      <div>
        <div class="exp-role">Software Developer — Healthcare Domain</div>
        <ul class="exp-points">
          <li>Designed and built scalable UI solutions for healthcare applications, focusing on accessibility, reliability, and compliance requirements.</li>
          <li>Developed reusable frontend components using JavaScript and Angular to support complex patient-facing and administrative workflows.</li>
          <li>Worked within cross-functional agile teams to deliver features across the full software development lifecycle in a regulated healthcare environment.</li>
          <li>Gained strong foundations in UI architecture, API integration, and delivering robust enterprise software under strict quality standards.</li>
        </ul>
      </div>
    </div>
  </div>
</section>

<!-- PROJECTS -->
<section id="projects">
  <div class="section-label reveal">GitHub</div>
  <h2 class="section-title reveal">Open Source &amp; <span>Projects</span></h2>
  <div class="projects-grid">
    <a href="https://github.com/RahulTinku/frontend-learning-kit" target="_blank" class="project-card reveal">
      <div class="project-card-header">
        <span class="project-icon">📚</span>
        <span class="project-arrow">↗</span>
      </div>
      <div class="project-name">Frontend Learning Kit</div>
      <div class="project-desc">A curated collection of highly recommended materials and a comprehensive tech guide for frontend developers at all levels.</div>
      <div class="project-lang">JavaScript · Open Source</div>
    </a>
    <a href="https://github.com/RahulTinku/SmartWatchApp" target="_blank" class="project-card reveal">
      <div class="project-card-header">
        <span class="project-icon">⌚</span>
        <span class="project-arrow">↗</span>
      </div>
      <div class="project-name">SmartWatch App</div>
      <div class="project-desc">A wearable/smart watch companion application demonstrating cross-platform UI design and interaction patterns.</div>
      <div class="project-lang">JavaScript</div>
    </a>
    <a href="https://github.com/RahulTinku/Coursera_React" target="_blank" class="project-card reveal">
      <div class="project-card-header">
        <span class="project-icon">⚛️</span>
        <span class="project-arrow">↗</span>
      </div>
      <div class="project-name">React Deep-Dive</div>
      <div class="project-desc">Projects and exercises from advanced React training — component architecture, hooks, and state management patterns.</div>
      <div class="project-lang">JavaScript · React</div>
    </a>
    <a href="https://github.com/RahulTinku/todoApp" target="_blank" class="project-card reveal">
      <div class="project-card-header">
        <span class="project-icon">✅</span>
        <span class="project-arrow">↗</span>
      </div>
      <div class="project-name">Todo App (TypeScript)</div>
      <div class="project-desc">A clean, typed task management application showcasing TypeScript best practices and scalable component design.</div>
      <div class="project-lang">TypeScript</div>
    </a>
    <a href="https://github.com/RahulTinku/LoginApp" target="_blank" class="project-card reveal">
      <div class="project-card-header">
        <span class="project-icon">🔐</span>
        <span class="project-arrow">↗</span>
      </div>
      <div class="project-name">MEAN Login App</div>
      <div class="project-desc">Full-stack authentication application built on the MEAN stack (MongoDB, Express, Angular, Node.js) with JWT auth flow.</div>
      <div class="project-lang">Angular · Node.js · MongoDB</div>
    </a>
    <a href="https://github.com/RahulTinku/angular2start" target="_blank" class="project-card reveal">
      <div class="project-card-header">
        <span class="project-icon">🅰️</span>
        <span class="project-arrow">↗</span>
      </div>
      <div class="project-name">Angular 2 Starter</div>
      <div class="project-desc">A well-structured Angular starter demonstrating component architecture, routing, and service patterns from the ground up.</div>
      <div class="project-lang">TypeScript · Angular</div>
    </a>
  </div>
</section>

<!-- CONTACT -->
<section id="contact">
  <div class="section-label reveal">Contact</div>
  <div class="contact-wrapper">
    <div class="reveal">
      <h2 class="contact-headline">Let's Build<br/><span>Something Great</span></h2>
      <p class="contact-desc">
        Open to Senior / Staff / Principal Engineer roles, technical collaborations, architecture consulting, and engineering talks. If you're building something interesting — reach out.
      </p>
      <div class="contact-open">
        <div class="open-dot"></div>
        <div class="open-text"><strong>Open to opportunities</strong> — Bengaluru &amp; Remote</div>
      </div>
    </div>
    <div class="contact-links reveal">
      <a href="mailto:rahulkumar271@gmail.com" class="contact-link">
        <span class="contact-link-icon">✉️</span>
        <div>
          <div class="contact-link-label">Email</div>
          <div class="contact-link-value">rahulkumar271@gmail.com</div>
        </div>
      </a>
      <a href="tel:+919020220190" class="contact-link">
        <span class="contact-link-icon">📞</span>
        <div>
          <div class="contact-link-label">Phone</div>
          <div class="contact-link-value">+91-9020220190</div>
        </div>
      </a>
      <a href="https://linkedin.com/in/rahul-kumar-5a576847" target="_blank" class="contact-link">
        <span class="contact-link-icon">💼</span>
        <div>
          <div class="contact-link-label">LinkedIn</div>
          <div class="contact-link-value">linkedin.com/in/rahul-kumar-5a576847</div>
        </div>
      </a>
      <a href="https://github.com/RahulTinku" target="_blank" class="contact-link">
        <span class="contact-link-icon">🐙</span>
        <div>
          <div class="contact-link-label">GitHub</div>
          <div class="contact-link-value">github.com/RahulTinku</div>
        </div>
      </a>
      <a href="https://leetcode.com/rahulkumar271/" target="_blank" class="contact-link">
        <span class="contact-link-icon">🧩</span>
        <div>
          <div class="contact-link-label">LeetCode</div>
          <div class="contact-link-value">leetcode.com/rahulkumar271</div>
        </div>
      </a>
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <p>© 2026 <span>Rahul Kumar</span>. Built with HTML · CSS · JS</p>
  <p>Bengaluru, India · <span>Open to Work</span></p>
</footer>

<script>
  // Custom cursor
  const cursor = document.getElementById('cursor');
  const ring = document.getElementById('cursorRing');
  let mx = 0, my = 0, rx = 0, ry = 0;
  document.addEventListener('mousemove', e => { mx = e.clientX; my = e.clientY; });
  function animCursor() {
    cursor.style.transform = `translate(${mx - 5}px, ${my - 5}px)`;
    rx += (mx - rx) * 0.12;
    ry += (my - ry) * 0.12;
    ring.style.transform = `translate(${rx - 18}px, ${ry - 18}px)`;
    requestAnimationFrame(animCursor);
  }
  animCursor();

  // Scroll reveal
  const reveals = document.querySelectorAll('.reveal');
  const io = new IntersectionObserver(entries => {
    entries.forEach((e, i) => {
      if (e.isIntersecting) {
        setTimeout(() => e.target.classList.add('visible'), 80);
        io.unobserve(e.target);
      }
    });
  }, { threshold: 0.12 });
  reveals.forEach(el => io.observe(el));

  // Stagger children in grids
  document.querySelectorAll('.skills-grid, .projects-grid, .about-pillars').forEach(grid => {
    grid.querySelectorAll('.reveal').forEach((child, i) => {
      child.style.transitionDelay = `${i * 0.08}s`;
    });
  });
</script>
</body>
</html>
