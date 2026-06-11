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
      <p style="margin: 0; color: #475569;">Building production AI systems with rigour and precision</p>
    </div>
  </div>

  <!-- Main Bio -->
  <p class="bio-text">
    I'm an <strong>AI & LLM Engineer</strong> specialising in large language models, RAG systems, AI agents, and NLP. 
    My approach is shaped by a solid background in physics research — where I developed expertise in 
    <strong>computational modelling, numerical simulations, and large-scale data analysis</strong> — which I now bring 
    to building reliable, high-performance AI systems.
  </p>

  <!-- Core Expertise Areas -->
  <div class="expertise-pills">
    <span class="pill pill-highlight">Enterprise RAG</span>
    <span class="pill pill-highlight">Graph RAG</span>
    <span class="pill pill-highlight">AI Agents</span>
    <span class="pill pill-highlight">Agentic Workflows</span>
    <span class="pill">LLM Evaluation</span>
    <span class="pill">Retrieval Benchmarking</span>
    <span class="pill">Synthetic Data Pipelines</span>
    <span class="pill">NLP Pipelines</span>
    <span class="pill">Text Classification</span>
    <span class="pill">Topic Modelling</span>
    <span class="pill">Terminology Extraction</span>
    <span class="pill">Semantic Search</span>
    <span class="pill">Vector Databases</span>
    <span class="pill">Fine-tuning</span>
    <span class="pill">Distributed Inference</span>
    <span class="pill">Docker + Ray</span>
    <span class="pill">HPC Deployment</span>
  </div>

  <div class="divider"></div>

  <!-- Expertise Narrative -->
  <p class="bio-text">
    My work centres on <strong>end-to-end AI system development</strong> — from retrieval pipeline architecture and 
    benchmark-driven evaluation to production deployment. I specialise in <strong>Needle-in-a-Haystack evaluation frameworks</strong> 
    for long-context LLMs, <strong>agentic workflow automation</strong>, and building scalable <strong>RAG systems</strong> 
    with vector databases like FAISS and Chroma.
  </p>

  <p class="bio-text">
    Beyond LLMs, I bring deep experience in <strong>computational modelling</strong> — numerical simulations, 
    Monte Carlo methods, and large-scale simulation workflows — which gives me a unique ability to design 
    rigorous evaluation pipelines and data-driven AI solutions.
  </p>

  <p class="bio-text" style="margin-bottom: 0;">
    I have applied these skills across <strong>healthcare</strong> (medical NLP and LLM fine-tuning), 
    <strong>industrial automation</strong> (enterprise RAG and AI agents), and <strong>digital humanities</strong> 
    (computational text analysis and machine-generated content detection).
  </p>

</div>
