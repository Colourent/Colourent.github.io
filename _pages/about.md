---
permalink: /
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
    .experience-card {
        display: flex;
        align-items: center;
        background: #F9F9F9;
        border-radius: 12px;
        padding: 16px;
        margin-bottom: 0px;
        border-left: 4px solid #4A90E2;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.05);
        transition: transform 0.3s, box-shadow 0.3s;
    }
    .experience-card:hover {
        box-shadow: 0 8px 16px rgba(0, 0, 0, 0.1);
    }
    .experience-info {
        font-size: 15px;
        color: #494E52;
        font-family: "Segoe UI", sans-serif;
    }
    .experience-info strong {
        font-size: 16px;
        color: #494E52;
    }
    .experience-container {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
        gap: 20px;
    }
    .project-item {
        border: 1px solid #DDDDDD;
        margin: 15px 0;
        background-color: #F9F9F9;
        padding: 15px 20px;
        border-radius: 8px;
        box-shadow: 0 2px 5px rgba(0, 0, 0, 0.05);
        transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .project-title {
        color: #2E5C8A;
        font-weight: bold;
        font-size: 1.1em;
        margin-bottom: 5px;
    }
    .project-meta {
        color: #4A90E2;
        font-size: 0.9em;
    }
    .main-heading {
        font-size: 35px;
        font-family: 'Lora', serif;
        font-weight: 500;
        text-align: center;
        color: #2E86C1;
    }
    .update-time {
        font-size: 12px;
        color: #6B9BD1;
        font-style: italic;
        text-align: right;
        margin-bottom: 20px;
    }
</style>

<h1 class="main-heading">👋 Hi there, I'm Taoran Lu</h1>
<p class="update-time">last update: 2026.04</p>

I am an **AI Multimodal Data Tech Expert** currently working at **ByteDance**. My primary focus is on **Synthetic Data** & **OmniEval for LLM & Robotics**. I have extensive experience in data synthesis and model evaluation, especially for GUI-Agents, CodeAgents, and Embodied AI.

Latest News
======
- 🚀 **[2025.04 - Present]** Joined **ByteDance** as an AI Multimodal Data Tech Expert, focusing on GUI-Agent data synthesis and evaluation.
- 🏆 **[2023.07 - 2025.03]** Worked at **Guanglun Intelligence** as a Perception Algorithm Engineer, specializing in Embodied AI data engineering.

Experiences
======
<div class="experience-container">
  <div class="experience-card">
      <div class="experience-info">
          <strong>ByteDance</strong><br>
          2025.04 - Present<br>
          <em>AI Multimodal Data Tech Expert</em>
      </div>
  </div>

  <div class="experience-card">
      <div class="experience-info">
          <strong>Guanglun Intelligence</strong><br>
          2023.07 - 2025.03<br>
          <em>Perception Algorithm Engineer</em>
      </div>
  </div>
</div>

Education
======
- **Beijing Institute of Technology** (2021 - 2024)<br>
  *M.S. in Image Processing / Optical Engineering*
- **Harbin Engineering University** (2017 - 2021)<br>
  *B.S. in Optoelectronic Information Science and Engineering*

Projects & Work
======
<div class="project-item">
<div class="project-title">Seed1.8 & 2.0 Data Engineering Pipeline</div>
<div class="project-meta">ByteDance | 2025 - Present</div>
<p>Built a 0-1 data pipeline for Seed models during the SFT phase, covering data collection, compliance cleaning, automated quality evaluation, and bad pattern filtering. Processed TB-level data, providing high-quality, compliant training data for Seed1.8 and Seed2.0.</p>
</div>

<div class="project-item">
<div class="project-title">GUI-Agent Data Synthesis (GUI-ReWalk & GUI-Diver)</div>
<div class="project-meta">ByteDance | 2025 - Present</div>
<p>Designed and implemented a GUI-Agent training data synthesis framework from scratch. Delivered over 5 million cross-platform, multi-app agent trace training data via <strong>GUI-ReWalk</strong>. Developed <strong>GUI-Diver</strong>, the first end-to-end RL synthesis approach for GUI-Agents, enhancing verifiable problem-solving capabilities.</p>
</div>

<div class="project-item">
<div class="project-title">Embodied AI Data Engineering & Sim2Real</div>
<div class="project-meta">Guanglun Intelligence | 2023 - 2025</div>
<p>Built automated attribute inspection pipelines for synthetic assets (e.g., collision boxes, USD formats, physical attributes). Explored Co-Training with Real Data + Synthetic Data, significantly improving model performance by reducing the Sim2Real gap using 3DGS rendering.</p>
</div>

Publications & Technical Reports
======
- 📄 **Seed1.8 Model Card**: Towards Generalized Real-World Agency
- 📄 **UI-TARS-2 Technical Report**: Advancing GUI Agent with Multi-Turn Reinforcement Learning
- 📄 **GUI-ReWalk**: Massive Data Generation for GUI Agent via Stochastic Exploration and Intent-Aware Reasoning
- 📄 **GUI-Diver**: Towards Verifiable Synthetic Experience for GUI-Agent Reinforcement Learning

Open Source Contributions
======
- 💻 **UI-TARS** & **UI-TARS-Desktop**
- 💻 **GUI-ReWalk**
