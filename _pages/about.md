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
    .experience-logo {
        width: 50px;
        height: 50px;
        margin-right: 15px;
        border-radius: 8px;
        object-fit: contain;
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

I am a **Senior Data Technologist, Multimodal LLMs** currently working at **ByteDance**. My primary focus is on **Synthetic Data** & **OmniEval for LLM & Robotics**. I have extensive experience in data synthesis and model evaluation, especially for GUI-Agents, CodeAgents, and Embodied AI.

Latest News
======
- 🚀 **[2025.04 - Present]** Joined **ByteDance** as a Senior Data Technologist, Multimodal LLMs, focusing on GUI-Agent data synthesis and evaluation.
- 🏆 **[2023.07 - 2025.03]** Worked at **Lightwheel.AI** as a Perception Algorithm Engineer, specializing in Embodied AI data engineering.

Experiences
======
<div class="experience-container">
  <div class="experience-card">
      <img src="https://avatars.githubusercontent.com/u/4158466?v=4" alt="ByteDance" class="experience-logo">
      <div class="experience-info">
          <strong>ByteDance</strong><br>
          2025.04 - Present<br>
          <em>Senior Data Technologist, Multimodal LLMs</em>
      </div>
  </div>

  <div class="experience-card">
      <img src="/images/lightwheel.jpeg" alt="Lightwheel.AI" class="experience-logo">
      <div class="experience-info">
          <strong>Lightwheel.AI</strong><br>
          2023.07 - 2025.03<br>
          <em>Perception Algorithm Engineer</em>
      </div>
  </div>
</div>

Education
======
<div class="experience-container">
  <div class="experience-card">
      <img src="/images/BIT.png" alt="BIT" class="experience-logo">
      <div class="experience-info">
          <strong>Beijing Institute of Technology</strong><br>
          2021 - 2024<br>
          <em>M.S. in Image Processing / Optical Engineering</em>
      </div>
  </div>

  <div class="experience-card">
      <img src="/images/HEU.webp" alt="HEU" class="experience-logo">
      <div class="experience-info">
          <strong>Harbin Engineering University</strong><br>
          2017 - 2021<br>
          <em>B.S. in Optoelectronic Information Science and Engineering</em>
      </div>
  </div>
</div>

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
<div class="project-meta">Lightwheel.AI | 2023 - 2025</div>
<p>Built automated attribute inspection pipelines for synthetic assets (e.g., collision boxes, USD formats, physical attributes). Explored Co-Training with Real Data + Synthetic Data, significantly improving model performance by reducing the Sim2Real gap using 3DGS rendering.</p>
</div>

Publications & Technical Reports
======
- 📄 **[Seed1.8 Model Card: Towards Generalized Real-World Agency](https://arxiv.org/abs/2603.20633)**
- 📄 **[UI-TARS-2 Technical Report: Advancing GUI Agent with Multi-Turn Reinforcement Learning](https://arxiv.org/abs/2509.02544)**
- 📄 **[GUI-ReWalk: Massive Data Generation for GUI Agent via Stochastic Exploration and Intent-Aware Reasoning](https://github.com/bytedance/GUI-ReWalk)**
- 📄 **GUI-Diver: Towards Verifiable Synthetic Experience for GUI-Agent Reinforcement Learning**

Open Source Contributions
======
- 💻 **[UI-TARS](https://github.com/bytedance/ui-tars)** & **UI-TARS-Desktop**
- 💻 **[GUI-ReWalk](https://github.com/bytedance/GUI-ReWalk)**
