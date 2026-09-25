---
title: "Research Projects"
permalink: /projects/
author_profile: true
page_class: projects-page
---

<div class="projects-showcase">
  <p class="projects-showcase__intro">My work spans AI for scientific computing, generative modeling, efficient adaptation, multimodal learning, and personalized language models.</p>

  <div class="project-list">
    <article class="project-card">
      <div class="project-card__body">
        <p class="project-card__eyebrow">NeurIPS 2026 · AI for scientific computing</p>
        <h2>Breakeven Complexity</h2>
        <p>Supervised by <a href="https://pages.cs.wisc.edu/~khodak/index.html">Prof. Misha Khodak</a>, we developed an evaluation framework centered on breakeven complexity: the number of forward solves required before a learned solver becomes cost-effective relative to an error-equivalent traditional solver.</p>
        <div class="project-card__highlight">Oral Presentation · Top 0.36%</div>
        <div class="project-card__topics" aria-label="Topics">
          <span>Scientific Machine Learning</span><span>Neural PDE Solvers</span><span>Scaling Laws</span><span>Evaluation</span>
        </div>
        <div class="project-card__links">
          <a href="https://arxiv.org/abs/2605.15399">Paper</a>
          <a href="https://github.com/yijingz02/breakeven_complexity">Code</a>
          <a href="https://huggingface.co/datasets/yijingz/breakeven_complexity">Dataset</a>
          <a href="https://www.mixtureofexperts.co/p/the-breakeven-point-rethinking-ai">Interview</a>
        </div>
      </div>
    </article>

    <article class="project-card">
      <div class="project-card__body project-card__body--with-media">
        <div class="project-card__copy">
          <p class="project-card__eyebrow">AI for scientific computing · Plasma physics</p>
          <h2>Driftless-Star</h2>
          <p>An interdisciplinary UW–Madison project developing an end-to-end pipeline for transport-consistent stellarator optimization. The work brings together machine learning, computational optimization, plasma physics, and fusion science.</p>
          <div class="project-card__topics" aria-label="Topics">
            <span>Stellarator Optimization</span><span>Plasma Physics</span><span>Fusion</span><span>Scientific Machine Learning</span>
          </div>
          <div class="project-card__links">
            <a href="https://github.com/driftless-star/driftless-star">Project Page</a>
          </div>
        </div>
        <img class="project-card__media" src="{{ '/images/driftless-star.png' | relative_url }}" alt="Illustration of the Driftless-Star stellarator geometry">
      </div>
    </article>

    <article class="project-card">
      <div class="project-card__body project-card__body--with-media">
        <div class="project-card__copy">
          <p class="project-card__eyebrow">ECCV 2024 · Multimodal generation</p>
          <h2>Audio-Guided Visual Animation</h2>
          <p>Supervised by <a href="https://pedro-morgado.github.io/">Prof. Pedro Morgado</a>, we developed audio-to-video generation methods focused on producing highly synchronized visual animations from audio guidance.</p>
          <div class="project-card__highlight">Oral Presentation · Top 2.3%</div>
          <div class="project-card__topics" aria-label="Topics">
            <span>Computer Vision</span><span>Generative Models</span><span>Audio-to-Video</span>
          </div>
          <div class="project-card__links">
            <a href="https://arxiv.org/abs/2403.05659">Paper</a>
            <a href="https://github.com/lzhangbj/ASVA">Code</a>
          </div>
        </div>
        <img class="project-card__media" src="{{ '/images/agva.gif' | relative_url }}" alt="Audio-Guided Visual Animation example">
      </div>
    </article>

    <article class="project-card">
      <div class="project-card__body">
        <p class="project-card__eyebrow">NAACL 2025 · Model personalization</p>
        <h2>CHAMELEON</h2>
        <p>Supervised by <a href="https://pages.cs.wisc.edu/~fredsala/">Prof. Frederic Sala</a>, we extended AlignEZ to personalize language models for many users while keeping resource requirements low.</p>
        <div class="project-card__topics" aria-label="Topics">
          <span>Personalization</span><span>Language Models</span><span>Efficient Adaptation</span>
        </div>
        <div class="project-card__links">
          <a href="https://arxiv.org/abs/2503.01048">Paper</a>
        </div>
      </div>
    </article>

     <article class="project-card">
      <div class="project-card__body">
        <p class="project-card__eyebrow">Training-free alignment</p>
        <h2>AlignEZ</h2>
        <p>Supervised by <a href="https://pages.cs.wisc.edu/~fredsala/">Prof. Frederic Sala</a>, we developed a nearly cost-free approach to model alignment using self-generated preference data and representation editing—without additional model training.</p>
        <div class="project-card__topics" aria-label="Topics">
          <span>NLP</span><span>LLM Alignment</span><span>Representation Editing</span>
        </div>
        <div class="project-card__links">
          <a href="https://arxiv.org/abs/2406.03642">Paper</a>
        </div>
      </div>
    </article>

    <!-- <article class="project-card">
      <div class="project-card__body">
        <p class="project-card__eyebrow">Data-Centric AI · Synthetic data</p>
        <h2>Better Instruction-Tuning Data</h2>
        <p>Supervised by <a href="https://cs.brown.edu/people/sbach/index.html">Prof. Stephen Bach</a> and <a href="https://pages.cs.wisc.edu/~fredsala/">Prof. Frederic Sala</a>, this work explored methods for generating higher-quality instruction-tuning datasets from unannotated text.</p>
        <div class="project-card__topics" aria-label="Topics">
          <span>Instruction Tuning</span><span>Data Generation</span><span>NLP</span>
        </div>
      </div>
    </article> -->

    <article class="project-card">
      <div class="project-card__body">
        <p class="project-card__eyebrow">Honors Thesis · Data-efficient learning</p>
        <h2>Domain-Specific Fine-Tuning for Generative Models</h2>
        <p>My senior honors thesis, supervised by <a href="https://pages.cs.wisc.edu/~fredsala/">Prof. Frederic Sala</a>, studied whether synthetic datasets from fine-tuned generative models can improve downstream classification and how to generate higher-quality data efficiently.</p>
        <div class="project-card__topics" aria-label="Topics">
          <span>NLP</span><span>Foundation Models</span><span>Fine-Tuning</span><span>Data Efficiency</span><span>Thesis</span>
        </div>
      </div>
    </article>
  </div>
</div>
