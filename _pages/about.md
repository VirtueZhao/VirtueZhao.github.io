---
layout: about
title: about
permalink: /
subtitle: PhD Student · <a href='https://www.auckland.ac.nz/'>University of Auckland</a> · [your research area] <em>(placeholder)</em>

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>[Building / Room] (placeholder)</p>
    <p>University of Auckland</p>
    <p>Auckland, New Zealand</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: false # using custom pill links below instead of the default icon row

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: true
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<!-- ============================================================= -->
<!-- Custom link buttons + research-interest grid.                 -->
<!-- Edit the hrefs / text below. Styling is in the <style> block  -->
<!-- at the bottom and follows al-folio's theme color + dark mode. -->
<!-- ============================================================= -->

<div class="dz-links">
  <a class="dz-pill" href="https://scholar.google.com/citations?user=XXXXXXXX" target="_blank" rel="noopener"><i class="ai ai-google-scholar"></i>Google Scholar</a>
  <a class="dz-pill" href="https://github.com/VirtueZhao" target="_blank" rel="noopener"><i class="fa-brands fa-github"></i>GitHub</a>
  <a class="dz-pill" href="#" target="_blank" rel="noopener"><i class="fa-solid fa-people-group"></i>[Your Lab]</a>
  <a class="dz-pill" href="https://www.auckland.ac.nz/" target="_blank" rel="noopener"><i class="fa-solid fa-building-columns"></i>University of Auckland</a>
  <a class="dz-pill" href="#" target="_blank" rel="noopener"><i class="fa-brands fa-x-twitter"></i>X</a>
  <a class="dz-pill" href="#" target="_blank" rel="noopener"><i class="fa-brands fa-linkedin-in"></i>LinkedIn</a>
  <a class="dz-pill" href="/cv/"><i class="fa-solid fa-address-card"></i>Short Bio</a>
</div>

*This is placeholder text — replace it with your own biography.*

I am a PhD student at the **University of Auckland**, working on *[your research area]*.
My research interests include *[topic 1]*, *[topic 2]*, and *[topic 3]*.

Before joining the University of Auckland, I received my *[degree]* from *[university]*
in *[year]*. *(Update this with your background, advisor, and lab.)*

Feel free to reach out if you would like to collaborate or chat about research.

<h2 class="dz-ri-title">Research Interests</h2>

<div class="dz-ri">
  <div class="dz-card">
    <div class="dz-card-head"><i class="fa-solid fa-brain"></i><h3>Continual &amp; Lifelong Learning</h3></div>
    <ul>
      <li>Forgetting mitigation</li>
      <li>Agentic &amp; online learning</li>
      <li>Continual learning LLMs &amp; MLLMs</li>
    </ul>
  </div>
  <div class="dz-card">
    <div class="dz-card-head"><i class="fa-solid fa-sliders"></i><h3>Foundation Model Training</h3></div>
    <ul>
      <li>Post-training</li>
      <li>Test-time learning</li>
      <li>Efficient alignment and fine-tuning</li>
    </ul>
  </div>
  <div class="dz-card">
    <div class="dz-card-head"><i class="fa-solid fa-palette"></i><h3>Generative Models</h3></div>
    <ul>
      <li>Image &amp; video generation</li>
      <li>Diffusion models</li>
      <li>Control &amp; alignment</li>
    </ul>
  </div>
  <div class="dz-card">
    <div class="dz-card-head"><i class="fa-solid fa-diagram-project"></i><h3>Adaptive &amp; Modular Learning</h3></div>
    <ul>
      <li>Memory model &amp; mechanism</li>
      <li>(Dynamic) mixture-of-experts</li>
    </ul>
  </div>
  <div class="dz-card">
    <div class="dz-card-head"><i class="fa-solid fa-eye"></i><h3>Vision &amp; Multimodal Learning</h3></div>
    <ul>
      <li>Semantic and depth perception</li>
      <li>Image restoration &amp; enhancement</li>
    </ul>
  </div>
  <div class="dz-card dz-card--end">
    <i class="fa-solid fa-infinity"></i>
  </div>
</div>

<style>
/* ---- custom link pills ---- */
.dz-links{display:flex;flex-wrap:wrap;gap:.6rem;margin:.2rem 0 1.4rem;}
.dz-pill{display:inline-flex;align-items:center;gap:.45rem;padding:.42rem 1rem;
  border:1.6px solid var(--global-theme-color);border-radius:2rem;
  color:var(--global-theme-color);font-size:.9rem;font-weight:500;line-height:1;
  text-decoration:none;white-space:nowrap;transition:background-color .18s ease,color .18s ease;}
.dz-pill:hover{background:var(--global-theme-color);color:#fff;text-decoration:none;}
.dz-pill i{font-size:.95rem;}

/* ---- research interests grid ---- */
.dz-ri-title{margin:1.8rem 0 .9rem;font-weight:700;}
.dz-ri{display:grid;grid-template-columns:repeat(3,1fr);gap:1rem;margin:0 0 1.5rem;}
@media(max-width:900px){.dz-ri{grid-template-columns:repeat(2,1fr);}}
@media(max-width:560px){.dz-ri{grid-template-columns:1fr;}}
.dz-card{border:1px solid var(--global-divider-color);border-radius:.8rem;
  padding:1rem 1.15rem;background:var(--global-card-bg-color);
  transition:box-shadow .2s ease,transform .2s ease;}
.dz-card:hover{box-shadow:0 6px 20px rgba(0,0,0,.09);transform:translateY(-2px);}
.dz-card-head{display:flex;align-items:center;gap:.6rem;margin-bottom:.55rem;}
.dz-card-head i{color:var(--global-theme-color);font-size:1.2rem;width:1.4rem;text-align:center;}
.dz-card-head h3{margin:0;font-size:1rem;font-weight:700;color:var(--global-text-color);}
.dz-card ul{margin:0;padding-left:1.15rem;list-style:disc;}
.dz-card li{font-size:.86rem;color:var(--global-theme-color);margin:.18rem 0;}
.dz-card--end{display:flex;align-items:center;justify-content:center;min-height:120px;}
.dz-card--end i{font-size:2.1rem;color:var(--global-theme-color);}
</style>
