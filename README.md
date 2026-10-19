[README.md](https://github.com/user-attachments/files/33651767/README.md)
# strufiber
STRUFIBER – Digital Inspection, Pathological Diagnosis and FRP-Based Structural Rehabilitation
# STRUFIBER

Public demonstration page for the STRUFIBER research software.

The website is published through GitHub Pages. The Windows installer should be published through a GitHub Release and linked from `index.html`.
[index.html](https://github.com/user-attachments/files/33651781/index.html)
<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<meta name="description" content="STRUFIBER research software demonstration">
<title>STRUFIBER | Demonstration Version</title>
<style>
:root{--ink:#18212b;--muted:#5f6b76;--line:#dce2e7;--soft:#f4f7f9;--accent:#0f5f78;--dark:#132b36}
*{box-sizing:border-box}body{margin:0;font-family:Segoe UI,Arial,sans-serif;color:var(--ink);background:var(--soft);line-height:1.65}
a{color:inherit}.wrap{max-width:1120px;margin:auto}.hero{background:linear-gradient(135deg,#132b36,#0f5f78);color:#fff;padding:72px 24px 64px}
.eyebrow{text-transform:uppercase;letter-spacing:.14em;font-size:12px;font-weight:700;opacity:.82}
h1{font-size:clamp(42px,7vw,76px);margin:8px 0 12px;letter-spacing:-.04em}.subtitle{max-width:900px;font-size:20px}
.hero-note{margin-top:26px;font-size:14px;opacity:.8}.cta{display:flex;flex-wrap:wrap;gap:12px;margin-top:28px}
.button{display:inline-block;padding:12px 18px;border-radius:10px;text-decoration:none;font-weight:700;border:1px solid var(--line);background:#fff;color:#174a5b}
nav{position:sticky;top:0;z-index:5;background:#fff;border-bottom:1px solid var(--line)}
nav .wrap{display:flex;gap:24px;overflow:auto;padding:14px 20px}nav a{text-decoration:none;font-size:14px;font-weight:650;color:#174a5b;white-space:nowrap}
main{padding:52px 20px 80px}section{margin-bottom:58px}h2{font-size:30px;margin:0 0 16px}.lead{font-size:18px;color:var(--muted);max-width:900px}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:18px;margin-top:26px}.card{background:#fff;border:1px solid var(--line);border-radius:16px;padding:24px;box-shadow:0 8px 25px #14232d0d}
.card p{color:var(--muted);margin-bottom:0}.notice{border-left:4px solid var(--accent);background:#fff;padding:18px 20px;border-radius:0 12px 12px 0;color:var(--muted)}
.step{position:relative;padding-left:54px;margin:24px 0}.step:before{content:counter(step);counter-increment:step;position:absolute;left:0;top:0;width:34px;height:34px;border-radius:50%;background:var(--accent);color:#fff;display:grid;place-items:center;font-weight:800}
.workflow{counter-reset:step}footer{background:var(--dark);color:#fff;padding:32px 20px;font-size:14px}footer p{opacity:.78}
code{background:#eef2f4;padding:2px 6px;border-radius:5px}
@media(max-width:820px){.grid{grid-template-columns:1fr}.hero{padding-top:52px}}
</style>
</head>
<body>
<header class="hero"><div class="wrap">
<div class="eyebrow">Research software demonstration</div>
<h1>STRUFIBER</h1>
<div class="subtitle">A Hybrid Computational System for Digital Inspection, Pathological Diagnosis, and FRP-Based Rehabilitation of Reinforced Concrete Heritage Buildings in Resource-Constrained Contexts.</div>
<div class="cta"><a class="button" href="#about">Explore the system</a></div>
<div class="hero-note">Public demonstration page associated with the STRUFIBER research project.</div>
</div></header>
<nav><div class="wrap">
<a href="#about">About</a><a href="#architecture">Architecture</a><a href="#modules">Modules</a><a href="#workflow">Workflow</a><a href="#case">Case study</a><a href="#limitations">Limitations</a>
</div></nav>
<main><div class="wrap">
<section id="about"><h2>About STRUFIBER</h2>
<p class="lead">STRUFIBER is a computational research system developed to support digital inspection, pathological diagnosis, preliminary structural assessment and FRP-based rehabilitation of reinforced concrete heritage buildings. The system integrates field inspection data, testing information and computational structural assessment within a unified workflow.</p>
<div class="notice"><strong>Demonstration status.</strong> This website documents the research software and its demonstrative implementation. It is not a replacement for detailed engineering design software, professional inspection, structural safety assessment or experimental validation.</div>
</section>

<section id="architecture"><h2>Computational architecture</h2><div class="grid">
<div class="card"><h3>Flutter / Dart</h3><p>User interface, navigation, project records, dashboards and presentation of inspection and assessment information.</p></div>
<div class="card"><h3>Rust</h3><p>Computational layer intended to provide efficient numerical and engineering processing with low runtime overhead.</p></div>
<div class="card"><h3>Hybrid workflow</h3><p>Connects digital inspection, diagnosis, structural assessment and preliminary FRP rehabilitation within one research-oriented workflow.</p></div>
</div></section>

<section id="modules"><h2>Demonstrated modules</h2><div class="grid">
<div class="card"><h3>Building registry</h3><p>Organisation of building information, inspection records and project-level data.</p></div>
<div class="card"><h3>Pathology mapping</h3><p>Recording and organisation of visible deterioration and pathological manifestations observed during inspection.</p></div>
<div class="card"><h3>Inspection & testing</h3><p>Integration of information associated with visual inspection and non-destructive or complementary testing.</p></div>
<div class="card"><h3>Structural assessment</h3><p>Preliminary computational assessment of reinforced concrete structural members within the defined system scope.</p></div>
<div class="card"><h3>FRP library</h3><p>Organisation of FRP strengthening alternatives including GFRP, CFRP and AFRP materials and application forms.</p></div>
<div class="card"><h3>FRP rehabilitation</h3><p>Preliminary reinforcement and rehabilitation calculations based on the implemented engineering methodology and selected design standards.</p></div>
</div></section>

<section id="workflow" class="workflow"><h2>Research workflow</h2>
<div class="step"><h3>Digital inspection</h3><p>Register building information, observed defects and inspection data.</p></div>
<div class="step"><h3>Pathological diagnosis</h3><p>Organise pathological manifestations and supporting test information to assist interpretation.</p></div>
<div class="step"><h3>Structural assessment</h3><p>Evaluate defined reinforced concrete structural members using the computational procedures implemented in the system.</p></div>
<div class="step"><h3>FRP-based rehabilitation</h3><p>Investigate preliminary FRP strengthening solutions according to the selected material and design methodology.</p></div>
</section>

<section id="case"><h2>Case study: FAPA Building</h2>
<p class="lead">The STRUFIBER research was applied to the FAPA Building in Huambo, Angola, as a case study for digital inspection, pathological diagnosis, structural assessment and preliminary CFRP rehabilitation.</p>
<p>The case study demonstrates the proposed computational workflow in a real heritage-building context. Results should be interpreted together with the assumptions, data limitations and modelling constraints reported in the associated scientific work.</p>
</section>

<section id="limitations"><h2>Scope and limitations</h2>
<div class="notice"><p>STRUFIBER is a research and decision-support system. The current demonstrative implementation does not replace specialised structural analysis software or a qualified structural engineer's professional assessment.</p>
<p>The case study is subject to the availability and quality of field data, existing documentation, accessibility of structural elements and modelling assumptions. Experimental validation and broader multi-building validation remain outside the demonstrative scope where stated in the associated publication.</p></div>
</section>

<section><h2>Software access</h2>
<p class="lead">A Windows installer can be provided as the executable demonstration version associated with this research project.</p>
<div class="card"><h3>Windows demonstration</h3><p>The download button will be activated after <code>StructFiber.exe</code> is uploaded to a public GitHub Release.</p><a class="button" href="#">Download StructFiber for Windows</a></div>
</section>
</div></main>
<footer><div class="wrap"><strong>STRUFIBER</strong><p>Research software demonstration. For scientific and demonstrative use. Please consult the associated publication for methodology, assumptions, validation status and limitations.</p><p>© 2026 STRUFIBER Research Project</p></div></footer>
</body></html>
