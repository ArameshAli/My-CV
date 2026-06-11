---
layout: page
title: About
permalink: /about/
position: 1
feature-img: "assets/img/pexels/travel2.JPG"
---

<style>
  .about-container {
    max-width: 900px;
    margin: 0 auto;
  }

  .profile-row {
    display: flex;
    align-items: center;
    gap: 2rem;
    flex-wrap: wrap;
    margin-bottom: 2rem;
  }

  .profile-img {
    width: 160px;
    height: 160px;
    object-fit: cover;
    border-radius: 50%;
    border: 3px solid white;
    box-shadow: 0 8px 20px rgba(0,0,0,0.1);
  }

  .tagline {
    font-size: 1.1rem;
    color: #4f46e5;
    font-weight: 600;
    letter-spacing: -0.01em;
    margin-bottom: 0.5rem;
  }

  .name {
    font-size: 2rem;
    font-weight: 700;
    margin-bottom: 0.5rem;
    color: #1e293b;
  }

  .bio-text {
    font-size: 1rem;
    line-height: 1.7;
    color: #334155;
    margin-bottom: 1.5rem;
    text-align: justify;
  }

  .expertise-pills {
    display: flex;
    flex-wrap: wrap;
    gap: 0.6rem;
    margin: 1.5rem 0;
  }

  .pill {
    background: #f1f5f9;
    padding: 0.3rem 1rem;
    border-radius: 30px;
    font-size: 0.8rem;
    font-weight: 500;
    color: #1e293b;
  }

  .pill-highlight {
    background: #e0e7ff;
    color: #4f46e5;
  }

  .divider {
    height: 3px;
    width: 50px;
    background: linear-gradient(90deg, #4f46e5, #a855f7);
    margin: 1.5rem 0;
    border-radius: 3px;
  }

  .current-role {
    background: #f8fafc;
    border-left: 4px solid #4f46e5;
    padding: 1rem 1.25rem;
    border-radius: 12px;
    margin: 1.5rem 0;
  }

  @media (max-width: 600px) {
    .profile-row {
      flex-direction: column;
      text-align: center;
    }
    .divider {
      margin-left: auto;
      margin-right: auto;
    }
  }
</style>

<div class="about-container">

  <!-- Profile Header -->
  <div class="profile-row">
    <img src="{{ '/assets/img/llm.jpg' | relative_url }}" alt="Amir Sabzalipour" class="profile-img">
    <div>
      <div class="tagline">AI & LLM Engineer</div>
      <div class="name">Amir Sabzalipour</div>
      <p style="margin: 0; color: #475569;">Building production AI systems with a physicist's precision</p>
    </div>
  </div>

  <!-- Main Bio -->
  <p class="bio-text">
    I'm an <strong>AI & LLM Engineer</strong> specialising in large language models, RAG systems, AI agents, and NLP. 
    My work bridges rigorous research — from a <strong>PhD in Physics</strong> and a <strong>Master in Digital Text Analysis</strong> — 
    with end-to-end engineering for production AI systems. I currently build enterprise solutions at <strong>ORCALYS</strong>, 
    where I design retrieval pipelines, agentic workflows, and scalable AI infrastructure for industrial automation and knowledge management.
  </p>

  <!-- Core Areas (compact) -->
  <div class="expertise-pills">
    <span class="pill pill-highlight">Enterprise RAG</span>
    <span class="pill pill-highlight">AI Agents</span>
    <span class="pill pill-highlight">LLM Evaluation</span>
    <span class="pill">NLP Pipelines</span>
    <span class="pill">Vector Databases</span>
    <span class="pill">Distributed Inference</span>
    <span class="pill">FastAPI + Docker</span>
  </div>

  <div class="divider"></div>

  <!-- Brief Research-to-Engineering Statement -->
  <p class="bio-text">
    My approach is shaped by years of <strong>computational modelling and data analysis</strong> in quantum materials research, 
    which taught me to build systems that are not just functional but methodically sound. Whether it's 
    <strong>Needle-in-a-Haystack benchmarking</strong> for long-context LLMs or deploying medical NLP pipelines on HPC clusters, 
    I focus on measurable performance and production reliability.
  </p>

  <!-- Current Role Snapshot -->
  <div class="current-role">
    <strong style="color: #1e293b;">📍 Currently @ ORCALYS</strong><br>
    <span style="font-size: 0.9rem; color: #475569;">
      Full-stack AI platform: LLMs + vector databases + agentic workflows + FastAPI + Docker. 
      Previously: medical NLP at KdG University (LLM fine-tuning, terminology extraction).
    </span>
  </div>

  <!-- Closing -->
  <p class="bio-text" style="margin-bottom: 0;">
    I bring the analytical depth of a physicist and the practical focus of an engineer to every system I build — 
    across <strong>healthcare</strong>, <strong>industrial automation</strong>, and <strong>digital humanities</strong>.
  </p>

</div>
