---
layout: home
permalink: /
title:
author_profile: false
excerpt: "MS student at SCUT and intern with the Kling Team at Kuaishou, working on reinforcement learning, agents, and multimodal generation."
redirect_from:
  - /about/
  - /about.html
---

{% include base_path %}

<section class="home-hero">
  <div class="home-hero__content">
    <p class="home-kicker">South China University of Technology · Kling Team, Kuaishou</p>
    <h1>Hohei Chan</h1>
    <p class="home-hero__subtitle">陈浩熙 (Haoxi Chen) · M.S. student in Software Engineering</p>
    <p class="home-hero__lead">
      I am an M.S. student at the
      <a href="https://www2.scut.edu.cn/sse/">School of Software Engineering, South China University of Technology</a>
      and a research intern with the <a href="https://kling.ai/">Kling Team</a> at
      <a href="https://www.kuaishou.com/">Kuaishou Technology</a>. My current research focuses on <strong>Reinforcement Learning</strong> and <strong>MLLM-based Agents</strong>, advised by Prof.
      <a href="https://batmanzzmc.github.io/">Mengchen Zhao</a>.
    </p>
    <div class="home-links" aria-label="Profile links">
      <a href="mailto:hoheichanchx@gmail.com">Email</a>
      <span>/</span>
      <a href="https://scholar.google.com/citations?hl=zh-CN&user=FJvUjiIAAAAJ">Google Scholar</a>
      <span>/</span>
      <a href="{{ base_path }}/publications/">Publications</a>
    </div>
  </div>

  <figure class="home-portrait">
    <img src="{{ base_path }}/images/profile.png" alt="Hohei Chan">
  </figure>
</section>

<main class="home-stack" aria-label="Homepage content">
  <section class="home-section">
    <header class="section-heading">
      <p class="home-kicker">News</p>
      <h2>News</h2>
    </header>
    <ul class="news-list">
      <li><time>2025.11</time><span>One paper was accepted by AAAI.</span></li>
      <li><time>2025.9</time><span>Joined the Kling Team at Kuaishou.</span></li>
      <li><time>2025.5</time><span>One paper was accepted by ICML.</span></li>
    </ul>
  </section>

  <section class="home-section">
    <header class="section-heading">
      <p class="home-kicker">Research</p>
      <h2>Publications</h2>
    </header>
    <div class="work-list">
      <article class="work-item">
        <div class="work-item__year">2026</div>
        <div class="work-item__body">
          <h3>PADiff: Predictive and Adaptive Diffusion Policies for Ad Hoc Teamwork</h3>
          <p class="work-item__meta"><strong>Hohei Chan</strong>, Xinzhi Zhang, Antao Xiang, Weinan Zhang, and Mengchen Zhao · AAAI</p>
          <div class="home-pub-actions">
            <a class="home-pub-link home-pub-link--pdf" href="{{ base_path }}/files/aaai2026-padiff.pdf" target="_blank" rel="noopener">PDF</a>
            <input class="home-tldr-input" id="home-tldr-padiff" type="checkbox">
            <label class="home-pub-link" for="home-tldr-padiff">TLDR</label>
            <div class="home-tldr">
              In offline multi-agent collaboration scenarios, we propose a diffusion-based decision framework that enables the modeling of various collaboration modes for unknown teammate agents.
            </div>
          </div>
        </div>
      </article>

      <article class="work-item">
        <div class="work-item__year">2025</div>
        <div class="work-item__body">
          <h3>Ad Hoc Teamwork via Offline Goal-Based Decision Transformers</h3>
          <p class="work-item__meta">Xinzhi Zhang, <strong>Hohei Chan</strong>, Deheng Ye, Yi Cai, and Mengchen Zhao · ICML</p>
          <div class="home-pub-actions">
            <a class="home-pub-link home-pub-link--pdf" href="{{ base_path }}/files/icml2025-taget.pdf" target="_blank" rel="noopener">PDF</a>
            <input class="home-tldr-input" id="home-tldr-taget" type="checkbox">
            <label class="home-pub-link" for="home-tldr-taget">TLDR</label>
            <div class="home-tldr">
              In offline multi-agent collaboration scenarios, we propose a transformer-based hierarchical sequence decision-making framework that enables rapid adaptation to unknown teammate agents.
            </div>
          </div>
        </div>
      </article>
    </div>
  </section>

  <section class="home-section">
    <header class="section-heading">
      <p class="home-kicker">Experience</p>
      <h2>Experience</h2>
    </header>
    <div class="timeline-list">
      <div class="timeline-item">
        <span>2025.9 - Present</span>
        <div>
          <h3>Research Intern</h3>
          <p>Kling Team, Kuaishou Technology</p>
        </div>
      </div>
    </div>
  </section>

  <section class="home-section">
    <header class="section-heading">
      <p class="home-kicker">Education</p>
      <h2>Education</h2>
    </header>
    <div class="timeline-list">
      <div class="timeline-item">
        <span>2026 - Present</span>
        <div>
          <h3>M.S. Student</h3>
          <p>School of Software Engineering, South China University of Technology</p>
        </div>
      </div>
      <div class="timeline-item">
        <span>2022.9 - 2026.6</span>
        <div>
          <h3>Undergraduate Student</h3>
          <p>School of Software Engineering, South China University of Technology</p>
        </div>
      </div>
    </div>
  </section>

  <section class="home-section">
    <header class="section-heading">
      <p class="home-kicker">Awards</p>
      <h2>Awards</h2>
    </header>
    <div class="simple-list">
      <p><strong>National Scholarship</strong><br>2025</p>
    </div>
  </section>

  <section class="home-section">
    <header class="section-heading">
      <p class="home-kicker">Advisor</p>
      <h2>Advisor</h2>
    </header>
    <div class="simple-list">
      <p>Prof. <a href="https://batmanzzmc.github.io/">Mengchen Zhao</a><br>2024 - Present</p>
    </div>
  </section>
</main>
