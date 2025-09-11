
---
layout: default
title: Home
description: Brightpath AI builds pragmatic, private, and reliable AI systems for real businesses. Privacy-first. Currently in stealth — early partners welcome.
image: /assets/img/og-bpai.png   # <— social preview image for WhatsApp/Facebook/Twitter
permalink: /
---


<style>
:root{
  --ink:#1f2328; --ink2:#5a616b; --line:#e6e8ef;
  --panel:#f7f8fb; --brand:#9b9b9b;
}
.page-header { background: #ffffff; color: var(--ink); border-bottom: 1px solid var(--line); }
.project-name { color: #2a2e34; }
.project-tagline { color: var(--ink2); }
.btn { color:#222; border:1px solid var(--line); background: linear-gradient(180deg,#f2f3f6,#eceef2); font-weight:700; border-radius:10px; padding:10px 16px; }
.btn:hover{ border-color:#cfd3da; background:linear-gradient(180deg,#fefefe,#f5f5f5); }
.main-content { color: var(--ink); }
.section { background:#fff; border:1px solid var(--line); border-radius:18px; padding:22px; box-shadow:0 14px 40px rgba(15,17,24,.06); margin-top:22px; }
.grid { display:grid; grid-template-columns: repeat(12, 1fr); gap:18px; }
.card { grid-column: span 6; background:#fff; border:1px solid var(--line); border-radius:16px; padding:18px; }
@media (max-width: 900px){ .card{ grid-column: span 12; } }
.badge{display:inline-block;border:1px solid var(--line);border-radius:999px;padding:6px 10px;background:#fff;color:#3f444b;font-weight:700}
.kicker{letter-spacing:.18em;text-transform:uppercase;color:#6b6f75;font-weight:800;font-size:.78rem}
.hero-logo{width:min(420px,90%);height:auto;filter:drop-shadow(0 8px 24px rgba(0,0,0,.08));margin:0 auto 8px;display:block}
.chips{margin-top:10px;display:flex;gap:10px;flex-wrap:wrap}
.chips span{border:1px solid var(--line);border-radius:999px;padding:6px 10px;background:#fff;color:#3f444b;font-weight:600}
.footer-note{color:var(--ink2);font-size:.95rem;margin-top:8px}

/* Hide GitHub Pages default footer */
.site-footer { display: none !important; }

/* Hide the Cayman header GitHub button */
.page-header .btn { display: none !important; }
</style>

<div align="center">
  <img class="hero-logo" src="{{ site.logo }}" alt="Brightpath AI logo" />
  <p class="kicker">Brightpath Technology &amp; Services Private Limited</p>
  <h1 class="project-name">Cutting-edge AI. Production-ready.</h1>
  <p class="project-tagline">
    We build pragmatic, private, and reliable AI systems for real businesses.<br />
    Currently in stealth — early partners welcome.
  </p>
  <p>
    <a href="mailto:team@bpai.in?subject=Early%20Access%20Request" class="btn">Request early access</a>
    <a href="#values" class="btn">Our values</a>
  </p>
</div>

<div class="section">
  <div class="grid">
    <div class="card">
      <span class="badge">Vision</span>
      <h3>AI that’s useful from day one</h3>
      <p>
        The next wave isn’t about demos—it’s about dependable, domain-aware systems
        that quietly deliver outcomes. We focus on <strong>latency-tuned inference</strong>,
        <strong>cost-efficient deployment</strong>, and <strong>privacy-first design</strong>.
      </p>
      <div class="chips" aria-hidden="false">
        <span>Agentic</span><span>Private RAG</span><span>Observability</span>
        <span>Safety &amp; evals</span><span>Edge inference</span>
      </div>
    </div>

    <div class="card">
      <span class="badge">Focus</span>
      <h3>What we build</h3>
      <p>
        • Agentic workflows for ops &amp; support<br />
        • Enterprise-ready private RAG<br />
        • Evaluation, safety &amp; observability<br />
        • On-device &amp; edge inference
      </p>
    </div>
  </div>
</div>

<div id="values" class="section">
  <span class="badge">Values</span>
  <h3>How we work</h3>
  <ul>
    <li><strong>Client data privacy</strong>: zero-retention by default, least-privilege access, encryption in transit &amp; at rest.</li>
    <li><strong>Ethical AI</strong>: transparent evaluation, bias testing, auditability, and human-in-the-loop for sensitive actions.</li>
    <li><strong>Security first</strong>: rigorous secrets management, vendor due-diligence, and continuous monitoring.</li>
    <li><strong>Measurable value</strong>: latency, accuracy, and unit-economics are tracked and reported.</li>
    <li><strong>Ship small, iterate fast</strong>: quick cycles, clear metrics, and delightful details.</li>
  </ul>
  <p class="footer-note">
    Interested in co-building? Email <a href="mailto:team@bpai.in">team@bpai.in</a> with your use-case.
  </p>
</div>

<div align="center" class="footer-note" style="margin-top:40px; padding:20px; border-top:1px solid #eee;">
  © {{ "now" | date: "%Y" }} Brightpath Technology &amp; Services Private Limited • Stealth mode
</div>
