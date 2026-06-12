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
<p class="update-time">last update: 2026.06</p>

I am a **Senior Data Technologist, Multimodal LLMs** currently working at **ByteDance**. My primary focus is on **GeneralAgent** and **Coding LLM**, along with **Synthetic Data** & **OmniEval**. I have extensive experience in data synthesis and model evaluation, especially for GUI-Agents, CodeAgents, and Embodied AI.

Latest News
======
- 🎉 **[2026.06]** Our work **GUI-ReWalk** has been accepted by **IJCAI 2026**.
- 🔥 **[2026.02]** Released the **Seed2.0** model series, advancing state-of-the-art multimodal agent capabilities.
- 🔥 **[2025.11]** Released the **Seed1.8** model, demonstrating generalized real-world agency.
- 🔥 **[2025.09]** Released **UI-TARS-2**, advancing GUI Agent with Multi-Turn Reinforcement Learning.

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
<p>Designed and implemented a GUI-Agent training data synthesis framework from scratch. Delivered over 5 million cross-platform, multi-app agent trace training data via <strong>GUI-ReWalk</strong>. Developed <strong>GUI-Diver</strong>, the first end-to-end RL synthesis approach for GUI-Agents, enhancing verifiable problem-solving capabilities. <strong>This RL data synthesis work helped internal models achieve SOTA performance (76 points) on OSWorld.</strong></p>
</div>

<div class="project-item">
<div class="project-title">CodeAgent Data Synthesis (CodeDataScaling)</div>
<div class="project-meta">ByteDance | 2025 - Present</div>
<p>Led data synthesis optimization for CodeAgents. Developed <strong>CodeDataScaling</strong>, an RL data synthesis framework that significantly improved model reasoning and execution capabilities in terminal environments, helping the Seed model achieve <strong>65 points on TerminalBench2</strong>.</p>
</div>

<div class="project-item">
<div class="project-title">Embodied AI Data Engineering & Sim2Real</div>
<div class="project-meta">Lightwheel.AI | 2023 - 2025</div>
<p>Built automated attribute inspection pipelines for synthetic assets (e.g., collision boxes, USD formats, physical attributes). Explored Co-Training with Real Data + Synthetic Data, significantly improving model performance by reducing the Sim2Real gap using 3DGS rendering.</p>
</div>

Publications & Technical Reports
======
- 📄 **[Seed2.0 Model Card: Towards Generalized Real-World Agency](https://lf3-static.bytednsdoc.com/obj/eden-cn/lapzild-tss/ljhwZthlaukjlkulzlp/seed2/0214/Seed2.0%20Model%20Card.pdf)**
- 📄 **[Seed1.8 Model Card: Towards Generalized Real-World Agency](https://arxiv.org/abs/2603.20633)**
- 📄 **[UI-TARS-2 Technical Report: Advancing GUI Agent with Multi-Turn Reinforcement Learning](https://arxiv.org/abs/2509.02544)**
- 📄 **[GUI-ReWalk: Massive Data Generation for GUI Agent via Stochastic Exploration and Intent-Aware Reasoning](https://github.com/bytedance/GUI-ReWalk)**
- 📄 **GUI-Diver: Towards Verifiable Synthetic Experience for GUI-Agent Reinforcement Learning**

Open Source Contributions
======
- 💻 **[UI-TARS](https://github.com/bytedance/ui-tars)** & **[UI-TARS-Desktop](https://github.com/bytedance/UI-TARS-desktop)**
- 💻 **[GUI-ReWalk](https://github.com/bytedance/GUI-ReWalk)**
