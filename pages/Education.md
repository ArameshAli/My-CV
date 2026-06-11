---
layout: page
title: Education
permalink: /Education/
subtitle: ""
feature-img: "assets/img/pexels/travel2.JPG"
position: 4
---

<style>
  /* ============================================ */
  /* CSS VARIABLES FOR LIGHT/DARK MODE             */
  /* ============================================ */
  
  :root {
    /* Light mode colors */
    --text-primary: #1e293b;
    --text-secondary: #334155;
    --text-muted: #555;
    --text-light: #64748b;
    --bg-tag: #f0f5fc;
    --tag-text: #2e7dd1;
    --timeline-line: #d0dff0;
    --dot-bg: #fff;
    --dot-border: #2e7dd1;
    --year-color: #2e7dd1;
    --degree-color: #0f1f3d;
    --institution-color: #888;
    --thesis-label: #2e7dd1;
    --thesis-text: #555;
  }

  /* Dark mode overrides */
  [data-theme="dark"],
  body.dark-mode,
  .dark-mode {
    --text-primary: #e2e8f0;
    --text-secondary: #cbd5e1;
    --text-muted: #94a3b8;
    --text-light: #94a3b8;
    --bg-tag: #1e293b;
    --tag-text: #60a5fa;
    --timeline-line: #334155;
    --dot-bg: #0f172a;
    --dot-border: #60a5fa;
    --year-color: #60a5fa;
    --degree-color: #e2e8f0;
    --institution-color: #94a3b8;
    --thesis-label: #60a5fa;
    --thesis-text: #cbd5e1;
  }

  /* Also support prefers-color-scheme for system preference */
  @media (prefers-color-scheme: dark) {
    :root:not([data-theme="light"]) {
      --text-primary: #e2e8f0;
      --text-secondary: #cbd5e1;
      --text-muted: #94a3b8;
      --text-light: #94a3b8;
      --bg-tag: #1e293b;
      --tag-text: #60a5fa;
      --timeline-line: #334155;
      --dot-bg: #0f172a;
      --dot-border: #60a5fa;
      --year-color: #60a5fa;
      --degree-color: #e2e8f0;
      --institution-color: #94a3b8;
      --thesis-label: #60a5fa;
      --thesis-text: #cbd5e1;
    }
  }

  /* ============================================ */
  /* INCREASE BANNER IMAGE HEIGHT                  */
  /* ============================================ */
  
  .page-header {
    min-height: 450px !important;
    position: relative;
  }
  
  .page-header .header-image,
  .page-header img,
  .feature-img img,
  .page__hero-image {
    height: 450px !important;
    object-fit: cover !important;
    width: 100%;
  }
  
  .page__hero--overlay {
    min-height: 450px !important;
  }
  
  .page-content {
    padding-top: 2rem !important;
  }
  
  .main-content {
    margin-top: 1rem;
  }

  /* ============================================ */
  /* EDUCATION TIMELINE STYLES                    */
  /* ============================================ */
  
  .edu-timeline { 
    position: relative; 
    max-width: 680px; 
    margin: 2rem auto; 
    padding: 0 1rem; 
  }
  
  .edu-timeline::before { 
    content: ''; 
    position: absolute; 
    left: 28px; 
    top: 0; 
    bottom: 0; 
    width: 1px; 
    background: var(--timeline-line); 
  }
  
  .edu-entry { 
    position: relative; 
    padding-left: 72px; 
    margin-bottom: 2.5rem; 
  }
  
  .edu-dot { 
    position: absolute; 
    left: 20px; 
    top: 6px; 
    width: 16px; 
    height: 16px; 
    border-radius: 50%; 
    background: var(--dot-bg); 
    border: 2.5px solid var(--dot-border); 
  }
  
  .edu-year { 
    font-size: 0.78rem; 
    font-weight: 700; 
    color: var(--year-color); 
    letter-spacing: 0.04em; 
    margin-bottom: 6px; 
  }
  
  .edu-degree { 
    font-size: 1.1rem; 
    font-weight: 700; 
    color: var(--degree-color); 
    margin-bottom: 3px; 
  }
  
  .edu-institution { 
    font-size: 0.92rem; 
    color: var(--institution-color); 
    font-style: italic; 
    margin-bottom: 12px; 
  }
  
  .edu-thesis-label { 
    font-size: 0.75rem; 
    font-weight: 700; 
    letter-spacing: 0.06em; 
    color: var(--thesis-label); 
    text-transform: uppercase; 
    margin-bottom: 5px; 
  }
  
  .edu-thesis { 
    font-size: 0.95rem; 
    color: var(--thesis-text); 
    line-height: 1.75; 
    margin-bottom: 10px; 
  }
  
  .tag-row { 
    display: flex; 
    flex-wrap: wrap; 
    gap: 6px; 
  }
  
  .tag { 
    font-size: 0.8rem; 
    font-weight: 600; 
    padding: 4px 11px; 
    border-radius: 20px; 
    background: var(--bg-tag); 
    color: var(--tag-text); 
  }

  @media (max-width: 600px) {
    .page-header {
      min-height: 250px !important;
    }
    
    .page-header .header-image,
    .page-header img,
    .feature-img img,
    .page__hero-image {
      height: 250px !important;
    }
    
    .edu-timeline {
      margin: 1rem auto;
    }
    
    .edu-entry {
      padding-left: 56px;
    }
    
    .edu-dot {
      left: 12px;
    }
    
    .edu-timeline::before {
      left: 20px;
    }
  }
</style>

<div class="edu-timeline">

  <div class="edu-entry">
    <div class="edu-dot"></div>
    <p class="edu-year">2023 – 2025</p>
    <p class="edu-degree">Master of Digital Text Analysis</p>
    <p class="edu-institution">University of Antwerp — Belgium</p>
    <p class="edu-thesis-label">Thesis</p>
    <p class="edu-thesis">Investigated retrieval effectiveness, local awareness, and context utilisation in long-context LLMs using large-scale Needle-in-a-Haystack evaluation frameworks. Designed large-scale benchmarking frameworks using synthetic data and evaluation pipelines.</p>
    <div class="tag-row">
      <span class="tag">LLMs</span><span class="tag">RAG</span><span class="tag">Benchmarking</span><span class="tag">NLP</span>
    </div>
  </div>

  <div class="edu-entry">
    <div class="edu-dot"></div>
    <p class="edu-year">2017 – 2021</p>
    <p class="edu-degree">Ph.D. in Physics</p>
    <p class="edu-institution">University of Antwerp — Belgium</p>
    <p class="edu-thesis-label">Thesis</p>
    <p class="edu-thesis">Developed numerical simulations, computational models, and data analysis workflows to study charge transport and electronic properties in quantum materials.</p>
    <div class="tag-row">
      <span class="tag">Computational modelling</span><span class="tag">Quantum materials</span><span class="tag">Python</span><span class="tag">VASP</span>
    </div>
  </div>

  <div class="edu-entry">
    <div class="edu-dot"></div>
    <p class="edu-year">2011 – 2014</p>
    <p class="edu-degree">M.Sc. in Physics</p>
    <p class="edu-institution">Institute for Advanced Studies in Basic Science — Iran</p>
    <p class="edu-thesis-label">Thesis</p>
    <p class="edu-thesis">Studied quantum interaction effects on anisotropic properties of materials.</p>
    <div class="tag-row">
      <span class="tag">Quantum physics</span><span class="tag">Anisotropy</span><span class="tag">Condensed matter</span>
    </div>
  </div>

</div>
