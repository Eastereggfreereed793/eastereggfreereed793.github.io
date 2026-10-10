<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="theme-color" content="#f7f6f2">
  <meta name="description" content="Jason P. Terry is a computational astrophysicist at the University of Oxford studying planet formation, protoplanetary disk dynamics, the early Solar System, and machine learning for astronomical observations.">
  <meta name="author" content="Jason P. Terry">
  <meta property="og:type" content="profile">
  <meta property="og:title" content="Jason P. Terry — Computational Astrophysics & Planet Formation">
  <meta property="og:description" content="Research at the intersection of disk dynamics, early Solar System history, astronomical observations, and machine learning.">
  <title>Jason P. Terry | Planet Formation & Computational Astrophysics</title>
  <link rel="icon" type="image/jpeg" href="profile_picture.jpg">
  <style>
    :root {
      --bg:#f7f6f2; --paper:#fffdfa; --ink:#1d2b31; --sub:#4c5c60; --muted:#687779;
      --line:#d9dfdb; --accent:#126d6b; --accent-dark:#0b5554; --copper:#bb7c51;
      --serif: Georgia, 'Times New Roman', serif;
      --sans: -apple-system,BlinkMacSystemFont,'Segoe UI',Roboto,'Helvetica Neue',Arial,sans-serif;
    }
    *{box-sizing:border-box} html{scroll-behavior:smooth;scroll-padding-top:5.5rem}
    body{margin:0;background:var(--bg);color:var(--ink);font-family:var(--sans);font-size:16px;line-height:1.72;-webkit-font-smoothing:antialiased}
    a{color:var(--accent);text-decoration-thickness:1px;text-underline-offset:3px} a:hover{color:var(--accent-dark)}
    a:focus-visible{outline:3px solid #d79b6b;outline-offset:5px;border-radius:2px}
    .wrap{width:min(1120px,calc(100% - 60px));margin-inline:auto}
    .skip{position:absolute;top:-80px;left:16px;z-index:200;background:white;padding:8px 14px}.skip:focus{top:10px}
    header{position:sticky;top:0;z-index:10;background:rgba(247,246,242,.97);border-bottom:1px solid var(--line);backdrop-filter:blur(9px)}
    nav{display:flex;align-items:center;justify-content:space-between;gap:24px;min-height:76px}
    .name{color:var(--ink);font-family:var(--serif);font-size:1.31rem;letter-spacing:-.035em;font-weight:bold;text-decoration:none;white-space:nowrap}
    .navlinks{display:flex;gap:26px;align-items:center;flex-wrap:wrap;justify-content:flex-end}
    .navlinks a{color:#354c50;text-decoration:none;font-size:.87rem;font-weight:650;letter-spacing:.01em}
    .navlinks a:hover{color:var(--accent)}
    .navlinks .nav-contact{border:1px solid #c2ceca;border-radius:4px;padding:7px 13px;color:var(--accent)}
    .hero{padding:82px 0 94px;display:grid;grid-template-columns:minmax(0,1.05fr) minmax(360px,.95fr);align-items:center;gap:70px}
    .eyebrow{text-transform:uppercase;letter-spacing:.18em;font-size:.72rem;font-weight:790;color:var(--accent);margin:0 0 16px}
    h1,h2,h3{font-family:var(--serif);font-weight:normal;line-height:1.13;letter-spacing:-.041em}
    h1{font-size:clamp(3.2rem,5.8vw,5.15rem);margin:0 0 24px;max-width:710px}
    h1 em{font-style:italic;color:var(--accent)}
    .intro{font-size:1.16rem;line-height:1.76;color:#435257;max-width:600px;margin:0 0 27px}
    .position{font-size:.87rem;color:var(--muted);display:flex;align-items:flex-start;gap:10px;margin:0 0 31px}
    .position .dot{flex-shrink:0;margin-top:9px;width:7px;height:7px;background:var(--copper);border-radius:50%}
    .actions{display:flex;flex-wrap:wrap;align-items:center;gap:11px}
    .btn{display:inline-flex;align-items:center;justify-content:center;gap:8px;padding:11px 17px;border-radius:4px;border:1px solid #c1cac7;text-decoration:none;font-size:.88rem;font-weight:700;color:var(--ink);background:transparent}
    .btn.primary{background:var(--accent);border-color:var(--accent);color:#fff}.btn.primary:hover{background:#095856;color:#fff}
    .btn:hover{background:#efeee9}
    .hero-visual{margin:0;width:100%;max-width:240px;min-width:0;justify-self:center}
    .hero-image{display:block;width:100%;height:auto;max-height:560px;object-fit:contain;
      background:#e8ece9;border:1px solid var(--line);border-radius:5px;
      box-shadow:0 20px 48px rgba(24,50,51,.12)}
    .panel-label{position:absolute;left:28px;right:28px;bottom:24px;display:flex;align-items:center;justify-content:space-between;gap:8px;z-index:1;font-size:.66rem;letter-spacing:.15em;text-transform:uppercase;color:#cad9d8}
    .panel-label .square{width:22px;height:1px;background:#b58c69;display:inline-block;margin-right:7px;vertical-align:middle}
    .about-bar{border-top:1px solid var(--line);border-bottom:1px solid var(--line);background:#eeefe9}
    .about-inner{padding:29px 0;display:grid;grid-template-columns:1fr 1fr 1fr;gap:32px}
    .stat{font-size:.88rem;color:#526269;line-height:1.55}.stat strong{display:block;color:var(--ink);font-family:var(--serif);font-size:1.24rem;font-weight:normal;margin-bottom:4px}
    section{padding:84px 0;border-bottom:1px solid var(--line)}
    .section-head{display:grid;grid-template-columns:250px minmax(0,1fr);gap:34px;align-items:start;margin-bottom:34px}
    .section-head h2{font-size:clamp(2.35rem,3.6vw,3.25rem);margin:0}
    .section-head .lead{max-width:710px;color:var(--sub);font-size:1.05rem;margin:5px 0 0;line-height:1.83}
    .research-grid{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:18px}
    .research-card{padding:29px 25px 30px;background:var(--paper);border:1px solid #dfe4e0;border-radius:5px;min-height:303px}
    .research-card .num{font-family:var(--serif);font-style:italic;color:var(--copper);font-size:1.18rem}
    .research-card h3{font-size:1.53rem;margin:24px 0 13px;letter-spacing:-.035em}
    .research-card p{font-size:.94rem;line-height:1.78;color:var(--sub);margin:0}
    .research-tag{color:var(--accent);font-size:.74rem;font-weight:700;letter-spacing:.035em;margin-top:25px}
    /* Featured figure: one simulation, from physical model to observable diagnostic. */
    .featured-research{margin-top:54px;padding-top:36px;border-top:1px solid var(--line)}
    .featured-research-header{display:flex;align-items:end;justify-content:space-between;gap:30px;margin-bottom:22px}
    .featured-research-header .eyebrow{margin-bottom:10px}
    .featured-research h3{font-size:clamp(1.75rem,2.9vw,2.5rem);margin:0;max-width:760px}
    .featured-research-intro{max-width:300px;margin:0 0 3px;color:var(--sub);font-size:.94rem;line-height:1.6}
    .featured-research figure{margin:0}
    .featured-panel-scroll{width:100%;overflow-x:auto;overscroll-behavior-x:contain;border:1px solid var(--line);border-radius:5px;background:var(--bg)}
    .featured-panel-image{display:block;width:100%;height:auto}
    .featured-research figcaption{margin-top:13px;display:flex;justify-content:space-between;align-items:baseline;gap:20px;color:var(--sub);font-size:.86rem;line-height:1.7}
    .featured-caption-text{max-width:835px}
    .featured-research figcaption a{white-space:nowrap;font-weight:700;text-decoration:none;font-size:.83rem}
    .featured-mobile-hint{display:none;color:var(--muted);font-size:.78rem;margin:8px 0 0}
    .paper-list{display:grid;grid-template-columns:1fr 1fr;gap:14px 27px}
    .paper{border-top:1px solid #cbd5d1;padding:21px 4px 23px}
    .paper .meta{color:var(--muted);font-size:.74rem;font-weight:780;letter-spacing:.1em;text-transform:uppercase;margin-bottom:7px}
    .paper h3{font-family:var(--sans);font-size:1.045rem;letter-spacing:-.012em;font-weight:700;line-height:1.5;margin:0 0 7px}
    .paper h3 a{text-decoration:none;color:var(--ink)}.paper h3 a:hover{color:var(--accent);text-decoration:underline}
    .paper p{color:var(--sub);font-size:.9rem;line-height:1.64;margin:0 0 10px}
    .paper .paperlink{font-size:.84rem;font-weight:740;text-decoration:none}
    .paper-footer{margin-top:25px;font-size:.96rem;color:var(--sub)}
    .experience{display:grid;grid-template-columns:1fr 1fr;gap:45px}
    .experience h3{font-size:1.57rem;margin:0 0 15px}
    .experience p{margin:0 0 17px;color:var(--sub);font-size:.97rem;line-height:1.84}
    .experience .small-head{text-transform:uppercase;letter-spacing:.1em;font-size:.72rem;font-weight:760;color:var(--accent);margin-bottom:11px}
    .background{margin-top:22px;padding-top:19px;border-top:1px solid var(--line);font-size:.88rem;color:var(--sub)}
    .closing{background:#e8efeb;border-bottom:none;padding:66px 0}
    .closing-inner{display:grid;grid-template-columns:1.2fr .8fr;align-items:center;gap:40px}
    .closing h2{font-size:clamp(2.2rem,3.4vw,3.05rem);margin:4px 0 15px}.closing p{margin:0;max-width:630px;color:var(--sub)}
    .closing-links{display:flex;justify-content:flex-end;align-items:center;gap:10px;flex-wrap:wrap}
    footer{padding:25px 0 40px}.footer-inner{display:flex;justify-content:space-between;gap:20px;align-items:center;color:#6a7778;font-size:.8rem}.footer-inner a{color:#526967}
    @media(max-width:900px){.hero{gap:32px;grid-template-columns:1.1fr .9fr;padding:65px 0}.section-head{grid-template-columns:180px 1fr}.research-grid{gap:12px}.research-card{padding:23px 18px}.research-card h3{font-size:1.35rem}}
    @media(max-width:700px){.wrap{width:min(100% - 36px,540px)}nav{padding:17px 0;align-items:flex-start;flex-direction:column;gap:10px}.navlinks{gap:16px}.navlinks a{font-size:.8rem}.nav-contact{padding:3px 8px!important}.hero{grid-template-columns:1fr;padding:48px 0 57px;gap:36px}.hero h1{font-size:clamp(3rem,10vw,4rem)}.hero-visual{max-width:200px}.about-inner{grid-template-columns:1fr;gap:16px;padding:25px 0}.stat{padding-bottom:10px;border-bottom:1px solid #d7ddd8}.stat:last-child{border:0;padding:0}section{padding:58px 0}.section-head{grid-template-columns:1fr;gap:13px;margin-bottom:24px}.research-grid,.paper-list,.experience,.closing-inner{grid-template-columns:1fr}.research-card{min-height:unset}.paper{padding:17px 0 18px}.closing{padding:54px 0}.closing-links{justify-content:flex-start}.footer-inner{align-items:flex-start;flex-direction:column;gap:7px}}
    @media(max-width:700px){
      .featured-research{margin-top:38px;padding-top:28px}
      .featured-research-header{display:block;margin-bottom:18px}
      .featured-research-intro{max-width:none;margin:12px 0 0}
      /* The supplied figure is one composite JPEG. Avoid shrinking its labels to illegibility. */
      .featured-panel-image{width:780px;max-width:none}
      .featured-research figcaption{display:block}
      .featured-research figcaption a{display:inline-block;margin-top:10px}
      .featured-mobile-hint{display:block}
    }
    @media(prefers-reduced-motion:reduce){html{scroll-behavior:auto}}
  </style>
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "Person",
    "name": "Jason P. Terry",
    "jobTitle": "Postdoctoral Researcher",
    "affiliation": {"@type":"CollegeOrUniversity","name":"University of Oxford"},
    "email": "mailto:jason.terry@earth.ox.ac.uk",
    "url": "https://www.earth.ox.ac.uk/people/jason-terry",
    "sameAs": ["https://orcid.org/0000-0002-8590-7271","https://www.earth.ox.ac.uk/people/jason-terry"],
    "knowsAbout": ["Protoplanetary disks","Planet formation","Computational astrophysics","Machine learning in astronomy","Solar System evolution","Magnetohydrodynamics"]
  }
  </script>
</head>
<body>
  <a class="skip" href="#main">Skip to content</a>
  <header>
    <nav class="wrap" aria-label="Main navigation">
      <a class="name" href="#top">Jason P. Terry<span style="color:var(--copper)">.</span></a>
      <div class="navlinks">
        <a href="#research">Research</a>
        <a href="#publications">Publications</a>
        <a href="#teaching">Teaching & mentoring</a>
        <a class="nav-contact" href="#contact">Contact ↗</a>
      </div>
    </nav>
  </header>
  <main id="main">
    <div class="wrap hero" id="top">
      <div>
        <p class="eyebrow">Computational astrophysics · Planet formation</p>
        <h1>Understanding how <em>planetary systems</em> take shape.</h1>
        <p class="intro">I study the physics of planet-forming disks and the history of our Solar System, combining numerical simulations, astronomical observations, and machine learning to connect theory with what we can measure.</p>
        <p class="position"><span class="dot" aria-hidden="true"></span><span>Jason P. Terry, PhD · Postdoctoral Researcher<br>Department of Earth Sciences, University of Oxford</span></p>
        <div class="actions">
          <a class="btn primary" href="#research">Explore my research <span aria-hidden="true">↗</span></a>
          <a class="btn" href="#publications">Selected publications</a>
        </div>
      </div>
      <figure class="hero-visual">
        <img class="hero-image" src="profile_picture.jpg" alt="Portrait of Jason P. Terry" decoding="async" fetchpriority="high">
      </figure>
    </div>
    <div class="about-bar">
      <div class="wrap about-inner">
        <div class="stat"><strong>Physical models</strong>Hydrodynamics, self-gravity, magnetic fields, gas–dust evolution</div>
        <div class="stat"><strong>Observational constraints</strong>ALMA, interferometry, disk kinematics, meteoritic records</div>
        <div class="stat"><strong>Data-driven methods</strong>Machine learning, inverse problems, scientific inference</div>
      </div>
    </div>

    <section id="research" aria-labelledby="research-heading"><div class="wrap">
      <div class="section-head">
        <div><p class="eyebrow">01 / Research</p><h2 id="research-heading">Questions that connect scales</h2></div>
        <p class="lead">My work asks how the structures and instabilities of young disks influence what planets form, and how we can recover that history from telescope observations and the Solar System's surviving material.</p>
      </div>
      <div class="research-grid">
        <article class="research-card"><span class="num">01</span><h3>Disk dynamics & planet formation</h3><p>Using three-dimensional simulations to investigate gravitational instability, magnetohydrodynamics, dust–gas interactions, and the structures carved by forming planets.</p><div class="research-tag">Simulations · Disk kinematics</div></article>
        <article class="research-card"><span class="num">02</span><h3>The early Solar System</h3><p>Linking disk evolution to evidence preserved in meteorites, including the transport of solids, magnetic environments, and the role of volatile ices in planetary building blocks.</p><div class="research-tag">Meteorites · Volatiles · Transport</div></article>
        <article class="research-card"><span class="num">03</span><h3>Machine learning for astronomy</h3><p>Developing methods to detect planet signatures, identify anomalous motion, reconstruct interferometric observations, and extract physical parameters from complex data.</p><div class="research-tag">ALMA · VIREO · Inference</div></article>
      </div>
      <div class="featured-research" aria-labelledby="featured-research-title">
        <div class="featured-research-header">
          <div>
            <p class="eyebrow">Research in practice</p>
            <h3 id="featured-research-title">From simulations to observable signatures</h3>
          </div>
          <p class="featured-research-intro">One simulated disk, viewed through physical modelling, synthetic observations, and machine-learning analysis.</p>
        </div>
        <figure>
          <div class="featured-panel-scroll" tabindex="0" role="region" aria-label="Three-panel research figure; scroll horizontally on small screens">
            <img
              class="featured-panel-image"
              src="research_panels.jpg"
              alt="Three views of the same simulated self-gravitating disk: a red-orange hydrodynamical simulation, a purple synthetic ALMA line-emission channel, and a red-blue kinematic anomaly map."
              loading="lazy"
              decoding="async"
            >
          </div>
          <p class="featured-mobile-hint">Scroll horizontally to view all three panels.</p>
          <figcaption>
            <span class="featured-caption-text">Three views of the same self-gravitating protoplanetary disk: the simulated physical structure, a synthetic ALMA line-emission channel, and kinematic anomalies recovered through self-supervised machine learning from differences in velocity-centroid (moment-1) maps.</span>
            <a href="research_panels.jpg" target="_blank" rel="noopener noreferrer" aria-label="Open three-panel research figure at full size">View full-size figure ↗</a>
          </figcaption>
        </figure>
      </div>
    </div></section>

    <section id="publications" aria-labelledby="publications-heading"><div class="wrap">
      <div class="section-head">
        <div><p class="eyebrow">02 / Selected work</p><h2 id="publications-heading">Publications</h2></div>
        <p class="lead">A few examples spanning observations, computational models, machine learning, and early Solar System constraints. This is a selection rather than a complete bibliography.</p>
      </div>
      <div class="paper-list">
        <article class="paper"><div class="meta">2026 · Monthly Notices of the RAS</div><h3><a href="https://academic.oup.com/mnras/advance-article/doi/10.1093/mnras/stag1819/8834037" target="_blank" rel="noopener noreferrer">Denoising Interferometric Observations Using Visibility-Informed Neural Networks ↗</a></h3><p>VIREO: using interferometric response information to improve reconstruction of astronomical observations.</p><a class="paperlink" href="https://academic.oup.com/mnras/advance-article/doi/10.1093/mnras/stag1819/8834037">Journal article →</a></article>
        <article class="paper"><div class="meta">2026 · Earth and Planetary Science Letters</div><h3><a href="https://doi.org/10.1016/j.epsl.2026.119936" target="_blank" rel="noopener noreferrer">A collective trigger for widespread planetesimal formation revealed by accretion ages ↗</a></h3><p>Meteorite records as constraints on the movement of material and the timing of planetesimal formation.</p><a class="paperlink" href="https://doi.org/10.1016/j.epsl.2026.119936">Journal article →</a></article>
        <article class="paper"><div class="meta">2026 · Monthly Notices of the RAS</div><h3><a href="https://doi.org/10.1093/mnras/stag096" target="_blank" rel="noopener noreferrer">Dust morphology under changing dust mass ratios in protoplanetary discs ↗</a></h3><p>Investigating how disk dust content influences the structure traced by observations.</p><a class="paperlink" href="https://doi.org/10.1093/mnras/stag096">Journal article →</a></article>
        <article class="paper"><div class="meta">2023 · The Astrophysical Journal</div><h3><a href="https://doi.org/10.3847/1538-4357/acc737" target="_blank" rel="noopener noreferrer">Kinematic Evidence of an Embedded Protoplanet in HD 142666 Identified by Machine Learning ↗</a></h3><p>Combining learned kinematic signatures with follow-up simulations to investigate a candidate planet in HD 142666.</p><a class="paperlink" href="https://doi.org/10.3847/1538-4357/acc737">Journal article →</a></article>
        <article class="paper"><div class="meta">2022 · The Astrophysical Journal</div><h3><a href="https://doi.org/10.3847/1538-4357/aca477" target="_blank" rel="noopener noreferrer">Locating Hidden Exoplanets in ALMA Data Using Machine Learning ↗</a></h3><p>Machine learning applied to disk kinematics to identify candidate embedded planets.</p><a class="paperlink" href="https://doi.org/10.3847/1538-4357/aca477">Journal article →</a></article>
        <article class="paper"><div class="meta">2022 · Monthly Notices of the RAS</div><h3><a href="https://doi.org/10.1093/mnras/stab3513" target="_blank" rel="noopener noreferrer">Constraining protoplanetary disc mass using the GI wiggle ↗</a></h3><p>Measuring the signatures of gravitational instability to help infer disk mass.</p><a class="paperlink" href="https://doi.org/10.1093/mnras/stab3513">Journal article →</a></article>
      </div>
      <p class="paper-footer">For a more complete publication record, see my <a href="https://orcid.org/0000-0002-8590-7271" target="_blank" rel="noopener noreferrer">ORCID profile ↗</a>.</p>
    </div></section>

    <section id="teaching" aria-labelledby="teaching-heading"><div class="wrap">
      <div class="section-head">
        <div><p class="eyebrow">03 / Academic life</p><h2 id="teaching-heading">Teaching & mentoring</h2></div>
        <p class="lead">I enjoy helping students take ownership of research problems, especially at the intersection of physics, computation, and data analysis.</p>
      </div>
      <div class="experience">
        <div><p class="small-head">Teaching</p><h3>From foundational physics to machine learning</h3><p>My teaching experience includes undergraduate astrophysics tutorials and mathematics teaching at Oxford, introductory physics laboratory instruction, and a graduate seminar on machine learning in the physical sciences.</p><p>I aim to make technical ideas approachable while giving students the confidence to work independently.</p></div>
        <div><p class="small-head">Research supervision</p><h3>Mentoring across disciplines</h3><p>I have mentored undergraduate and graduate researchers on astrophysics and machine-learning projects, including work through the <a href="https://ml4sci.org/" target="_blank" rel="noopener noreferrer">ML4SCI</a> program and collaborations that connect physical modelling with data-driven methods.</p><p>I'm particularly interested in projects where students can develop both scientific intuition and practical computational skills.</p></div>
      </div>
      <div class="background"><strong>Background:</strong> PhD in Physics, University of Georgia (2024); MS in Data Science, Brown University. Currently a postdoctoral researcher in the Department of Earth Sciences at the University of Oxford.</div>
    </div></section>

    <section id="contact" class="closing" aria-labelledby="contact-heading"><div class="wrap closing-inner">
      <div><p class="eyebrow">04 / Contact</p><h2 id="contact-heading">Let's talk research.</h2><p>I'm happy to hear from people interested in disk physics, planet formation, astronomical data analysis, or possible collaborations. You can also request a current CV by email.</p></div>
      <div class="closing-links"><a class="btn primary" href="mailto:jason.terry@earth.ox.ac.uk">Email me ↗</a></div>
      <div class="closing-links"><a class="btn" href="https://www.earth.ox.ac.uk/people/jason-terry" target="_blank" rel="noopener noreferrer">Oxford profile ↗</a><a class="btn" href="https://github.com/j-p-terry" target="_blank" rel="noopener noreferrer">GitHub ↗</a><a class="btn" href="https://orcid.org/0000-0002-8590-7271" target="_blank" rel="noopener noreferrer">ORCID ↗</a><a class="btn" href="https://scholar.google.com/citations?user=CjRkV28AAAAJ&hl=en" target="_blank" rel="noopener noreferrer">Google Scholar ↗</a></div>
    </div></section>
  </main>
  <footer><div class="wrap footer-inner"><span>© Jason P. Terry · University of Oxford</span></div></footer>
</body>
</html>
