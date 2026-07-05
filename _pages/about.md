---
layout: about
title: Home
nav: false # al-folio auto-adds the Home link; keep this false to avoid a duplicate
permalink: /
subtitle:

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <div style="display:flex;flex-wrap:wrap;gap:.4rem;justify-content:center;margin-top:.7rem;">
    <a href="https://scholar.google.com/citations?user=RmvtaO4AAAAJ" target="_blank" rel="noopener" style="display:inline-flex;align-items:center;gap:.35rem;padding:.28rem .7rem;border:1.4px solid var(--global-theme-color);border-radius:2rem;color:var(--global-theme-color);font-size:.78rem;font-weight:500;text-decoration:none;white-space:nowrap;"><i class="ai ai-google-scholar"></i>Scholar</a>
    <a href="https://github.com/VirtueZhao" target="_blank" rel="noopener" style="display:inline-flex;align-items:center;gap:.35rem;padding:.28rem .7rem;border:1.4px solid var(--global-theme-color);border-radius:2rem;color:var(--global-theme-color);font-size:.78rem;font-weight:500;text-decoration:none;white-space:nowrap;"><i class="fa-brands fa-github"></i>GitHub</a>
    <a href="mailto:di.zhao@auckland.ac.nz" style="display:inline-flex;align-items:center;gap:.35rem;padding:.28rem .7rem;border:1.4px solid var(--global-theme-color);border-radius:2rem;color:var(--global-theme-color);font-size:.78rem;font-weight:500;text-decoration:none;white-space:nowrap;"><i class="fa-solid fa-envelope"></i>Email</a>
    </div>

selected_papers: false # rendered manually in the body instead (single-page layout)
social: false # using the custom pill links below instead of the default icon row

announcements:
  enabled: false # News section replaced by a Service section in the body
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false # Latest Posts section removed from the homepage
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<div style="margin:.1rem 0 1.2rem;line-height:1.6;font-size:1.05rem;">
Postdoc Fellow,<br>
<a href="https://www.auckland.ac.nz/en/science/about-the-faculty/school-of-computer-science.html" target="_blank" rel="noopener" style="color:var(--global-theme-color);text-decoration:none;">School of Computer Science,</a><br>
<a href="https://www.auckland.ac.nz/" target="_blank" rel="noopener" style="color:var(--global-theme-color);text-decoration:none;">University of Auckland</a>
</div>

<p style="text-wrap:pretty;">I am currently a Postdoctoral Researcher at the University of Auckland. My research aims to develop machine learning systems capable of operating reliably beyond static and controlled settings. My doctoral research focused on domain generalization, studying how models can remain robust when deployed in unseen domains. My current research extends this line of work to continual learning and embodied agents, with a focus on agents that adapt to evolving tasks and interactive environments. My work is grounded in real-world applications where robustness and adaptation are critical, including animal re-identification for wildlife monitoring and interdisciplinary scientific applications.</p>

<div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:1rem;margin:1.5rem 0;align-items:start;">

<div style="border:1px solid var(--global-divider-color);border-radius:.8rem;padding:1rem 1.15rem;background:var(--global-card-bg-color);">
<div style="font-weight:700;font-size:1.02rem;color:var(--global-text-color);">Embodied Agent</div>
</div>

<div style="border:1px solid var(--global-divider-color);border-radius:.8rem;padding:1rem 1.15rem;background:var(--global-card-bg-color);">
<div style="font-weight:700;font-size:1.02rem;color:var(--global-text-color);margin-bottom:.5rem;">Continual Learning</div>
<ul style="margin:0;padding-left:1.15rem;"><li style="font-size:.86rem;color:var(--global-theme-color);margin:.18rem 0;">Continual Learning MLLMs</li><li style="font-size:.86rem;color:var(--global-theme-color);margin:.18rem 0;">Self-Evolving Agents</li></ul>
</div>

<div style="border:1px solid var(--global-divider-color);border-radius:.8rem;padding:1rem 1.15rem;background:var(--global-card-bg-color);">
<div style="font-weight:700;font-size:1.02rem;color:var(--global-text-color);margin-bottom:.5rem;">Transfer Learning</div>
<ul style="margin:0;padding-left:1.15rem;"><li style="font-size:.86rem;color:var(--global-theme-color);margin:.18rem 0;">Domain Generalization</li><li style="font-size:.86rem;color:var(--global-theme-color);margin:.18rem 0;">Bridging Simulation to Reality</li></ul>
</div>

</div>

<h2 style="font-size: 1.3rem; font-family: 'Courier New', Courier, monospace; font-weight: 700; color: var(--global-theme-color); margin-top: 1.8rem;">Service</h2>

<div class="dz-service">
<div class="dz-svc-label">Organizing Committee</div>
<div class="dz-svc-body">Workshop on AI for Environmental Science (AI4ES), AAAI 2026</div>
<div class="dz-svc-label">Conference Reviewer / PC Member</div>
<div class="dz-svc-body">NeurIPS, ICLR, AAAI, IJCAI, ACM MM</div>
<div class="dz-svc-label">Journal Reviewer</div>
<div class="dz-svc-body">IEEE Transactions on Information Forensics and Security (TIFS); Artificial Intelligence Review</div>
<div class="dz-svc-label">Session Chair</div>
<div class="dz-svc-body">IJCAI 2025</div>
</div>

<h2 style="font-size: 1.3rem; font-family: 'Courier New', Courier, monospace; font-weight: 700; color: var(--global-theme-color); margin-top: 1.8rem;">Selected Publications</h2>

{% include selected_papers.liquid %}
