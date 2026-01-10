---
layout: about
title: about
permalink: /
nav: false
nav_order: 1
subtitle:

profile:
  align: right
  image: pp.jpg
  image_circular: false
  more_info:

news: true
selected_papers: false
social: true
---
I am an ML/AI Engineer and graduate student at [**Université Paris-Saclay**](https://www.universite-paris-saclay.fr/) pursuing a Master's degree in Artificial Intelligence. My research interests span machine learning, NLP, computer vision, and pre and post training of LLMs.

Previously,I worked at **Azercosmos** (National Space Agency of Azerbaijan) and interned at **Huawei China**, where I worked on reinforcement learning training of multi-step agents.

My current focus is on distributed training of LLMs and advancements in LLM architecture.

If you are interested in collaboration or have any questions, feel free to reach out to me via email.

<div class="cv-sections">

<!-- Education Section -->
<h2 class="cv-section-title">Education</h2>
<div class="education-grid">
  <div class="education-card">
    <div class="education-logo">
      <img src="{{ '/assets/img/ups.png' | relative_url }}" alt="University">
    </div>
    <div class="education-content">
      <h3><a href="https://www.universite-paris-saclay.fr/" target="_blank">Université Paris-Saclay</a></h3>
      <p class="education-degree">Master of Science in Computer Science</p>
      <p class="education-date">Sep 2024 - Jun 2026 | Paris, France</p>
      <p class="education-details">Specialization in Artificial Intelligence</p>
    </div>
  </div>
  <div class="education-card">
    <div class="education-logo">
      <img src="{{ '/assets/img/ufaz.jpg' | relative_url }}" alt="University">
    </div>
    <div class="education-content">
      <h3><a href="https://www.ufaz.az/en/" target="_blank">UFAZ</a></h3>
      <p class="education-degree">Bachelor of Science in Petroleum Engineering</p>
      <p class="education-date">Sep 2020 - Jun 2024 | Baku, Azerbaijan</p>
      <p class="education-details">Focus on Oil and Gas Exploration</p>
    </div>
  </div>
</div>

<!-- Experience Section -->
<h2 class="cv-section-title">Experience</h2>
<div class="timeline">
  <div class="timeline-item">
    <div class="timeline-date">Jun 2025 - Sep 2025</div>
    <div class="timeline-content">
      <h3>ML Engineer</h3>
      <h4><a href="https://digitalpower.huawei.com/resource/public/campus/en/songshanlake.html" target="_blank">Huawei Dongguan R&D Center</a></h4>
      <p> Designed and implemented a Smolagents-compatible RL training framework within rLLM which reduced integration friction for future agents. Trained and validated multi step language agents.</p>
      <div class="tech-tags">
        <span>reinforcement learning</span>
        <span>smolagents</span>
        <span>rLLM</span>
        <span>verl</span>
      </div>
    </div>
  </div>
  <div class="timeline-item">
    <div class="timeline-date">Aug 2023 - Sep 2024</div>
    <div class="timeline-content">
      <h3>Computer Vision Engineer</h3>
      <h4><a href="https://azercosmos.az/en" target="_blank">Azercosmos</a></h4>
      <p>Developed aerial image segmentation/detection pipelines (U-Net/DeepLab style) and data curation workflows for satellite imagery.</p>
      <div class="tech-tags">
        <span>pytorch</span>
        <span>docker</span>
        <span>ArcGIS</span>
      </div>
    </div>
  </div>
  <div class="timeline-item">
    <div class="timeline-date">May 2023 - Aug 2023</div>
    <div class="timeline-content">
      <h3>Machine Learning Intern</h3>
      <h4><a href="https://azai.tech/" target="_blank">AZAI Tech</a></h4>
      <p>Implemented on-device face detection/recognition using ML Kit and MobileNetV2; optimized preprocessing and model packaging for Android.</p>
      <div class="tech-tags">
        <span>tensorflow lite</span>
        <span>ml kit</span>
        <span>kotlin</span>
      </div>
    </div>
  </div>
</div>

<!-- Projects Section -->
<h2 class="cv-section-title">Projects</h2>
<div class="projects-grid">
  <div class="project-card">
    <h3><a href="https://github.com/RasulAlakbarli/llm-encyclopedia" target="_blank">LLM Encyclopedia</a></h3>
    <ul class="project-description">
      <li>Implemented core LLM building blocks from scratch: scaled dot-product attention, multi-head attention, grouped-query attention, byte-level BPE tokenizer.</li>
      <li>Built models like: Transformer from ”Attention is all you need”, and a GPT-2 style decoder-only model.</li>
    </ul>
    <div class="tech-tags">
      <span>pytorch</span>
      <span>transformers</span>
      <span>numpy</span>
    </div>
  </div>
  <div class="project-card">
    <h3><a href="https://github.com/RasulAlakbarli/HRTF-Prediciton" target="_blank">Personalized Spatial Audio (HRTF Prediction) from Pinna images</a></h3>
    <ul class="project-description">
      <li>Developed an LSTM-based encoder–decoder model that infers individual HRTFs from ear images and anthropometric cues; implemented training/eval loops and metrics.</li>
    </ul>
    <div class="tech-tags">
      <span>pytorch</span>
        <span>albumentations</span>
    </div>
  </div>
</div>

</div>

<style>
.cv-sections {
  margin-top: 2rem;
}

.cv-section-title {
  font-size: 1.5rem;
  font-weight: 400;
  margin-top: 2.5rem;
  margin-bottom: 1.5rem;
  color: var(--global-text-color);
  border-bottom: 1px solid var(--global-divider-color);
  padding-bottom: 0.5rem;
}

/* Education */
.education-grid {
  display: flex;
  flex-direction: column;
  gap: 1.5rem;
}

.education-card {
  display: flex;
  gap: 1.5rem;
  align-items: flex-start;
}

.education-logo {
  flex-shrink: 0;
  width: 60px;
  height: 60px;
}

.education-logo img {
  width: 100%;
  height: 100%;
  object-fit: contain;
}

.education-content h3 {
  margin: 0 0 0.25rem 0;
  font-size: 1.1rem;
  font-weight: 500;
}

.education-content h3 a {
  color: var(--global-theme-color);
  text-decoration: none;
}

.education-content h3 a:hover {
  text-decoration: underline;
}

.education-degree {
  margin: 0;
  font-weight: 500;
  color: var(--global-text-color);
}

.education-date {
  margin: 0.25rem 0;
  font-size: 0.9rem;
  color: var(--global-text-color-light);
}

.education-details,
.education-coursework {
  margin: 0.25rem 0;
  font-size: 0.9rem;
  color: var(--global-text-color-light);
}

/* Experience Timeline */
.timeline {
  position: relative;
  padding-left: 1.5rem;
  border-left: 2px solid var(--global-divider-color);
}

.timeline-item {
  position: relative;
  padding-bottom: 1.5rem;
}

.timeline-item::before {
  content: '';
  position: absolute;
  left: -1.65rem;
  top: 0.5rem;
  width: 10px;
  height: 10px;
  background: var(--global-theme-color);
  border-radius: 50%;
}

.timeline-date {
  font-size: 0.85rem;
  color: var(--global-text-color-light);
  margin-bottom: 0.25rem;
}

.timeline-content h3 {
  margin: 0;
  font-size: 1.1rem;
  font-weight: 500;
  color: var(--global-text-color);
}

.timeline-content h4 {
  margin: 0.25rem 0 0.5rem 0;
  font-size: 1rem;
  font-weight: 400;
}

.timeline-content h4 a {
  color: var(--global-theme-color);
  text-decoration: none;
}

.timeline-content h4 a:hover {
  text-decoration: underline;
}

.timeline-content p {
  margin: 0.5rem 0;
  font-size: 0.95rem;
  color: var(--global-text-color);
}

/* Tech Tags */
.tech-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
  margin-top: 0.75rem;
}

.tech-tags span {
  background: var(--global-code-bg-color);
  color: var(--global-text-color);
  padding: 0.2rem 0.6rem;
  border-radius: 4px;
  font-size: 0.8rem;
  font-family: monospace;
}

/* Projects */
.projects-grid {
  display: flex;
  flex-direction: column;
  gap: 1.5rem;
}

.project-card {
  padding: 1rem;
  border: 1px solid var(--global-divider-color);
  border-radius: 8px;
}

.project-card h3 {
  margin: 0 0 0.75rem 0;
  font-size: 1.1rem;
  font-weight: 500;
  color: var(--global-text-color);
}

.project-description {
  margin: 0 0 0.5rem 0;
  padding-left: 1.25rem;
  font-size: 0.95rem;
  color: var(--global-text-color);
}

.project-description li {
  margin-bottom: 0.25rem;
}

/* Responsive */
@media (max-width: 576px) {
  .education-card {
    flex-direction: column;
    gap: 1rem;
  }

  .education-logo {
    width: 50px;
    height: 50px;
  }
}
</style>
