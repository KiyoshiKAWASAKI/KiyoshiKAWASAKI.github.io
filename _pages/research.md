---
layout: archive
title: "Selected Publications"
permalink: /research/
author_profile: true
redirect_from:
  - /projects
  - /projects/
---

<style>
.pub-list { font-size: 0.8rem; }
.pub-list > p.intro { margin-bottom: 44px; text-align: justify; }
.pub-entry { display: flex; align-items: center; padding: 14px 0; margin-bottom: 32px; border-bottom: 1px solid #eee; }
.pub-entry img { width: 220px; margin-right: 20px; flex-shrink: 0; }
.pub-entry h2 { margin: 0 0 4px 0; font-size: 0.95rem; }
.pub-entry p { margin: 2px 0; }
.pub-entry p.desc { margin-top: 8px; text-align: justify; }
</style>

<div class="pub-list">

<p class="intro">I'm interested in Computer Vision and Generative AI. My current research spans controllable image and video generation and editing,
Vision Language Models, video understanding, reinforcement learning and model evaluation. During my Ph.D., I did research in 
Open-Set Recognition and Human Cognitive Science. </p>

<div class="pub-entry">
  <img src="/images/acam_teaser.png">
  <div>
    <h2><a href="https://1yuwen.github.io/ACaM-Project-Page/">ACaM: Natural Language Camera Movement Understanding</a></h2>
    <p>Yuwen Tan, Joey Huang, <strong>Jin Huang</strong>, Haoxiang Li, Boqing Gong</p>
    <p><i>ECCV</i>, 2026 &nbsp;·&nbsp; <a href="https://1yuwen.github.io/ACaM-Project-Page/">project page</a> / <a href="https://arxiv.org/abs/2607.03043">arXiv</a></p>
    <p class="desc">We show that existing vision-language models frequently confuse camera movement with
    object movement, translation with rotation, and left with right. We introduce a two-level cinematographic taxonomy
    and an atomic benchmark of real and synthetic videos, and curate a large-scale training set with targeted
    camera-movement augmentation. Our fine-tuned 8B model outperforms Gemini 3.1 Pro by 10% and 11% on real and
    synthetic videos respectively, though a substantial gap to human performance remains.</p>
  </div>
</div>

<div class="pub-entry">
  <img src="/images/experimental_setup.png">
  <div>
    <h2>Extreme Value Theory for Modeling Category Decision Boundaries in Visual Recognition</h2>
    <p><strong>Jin Huang</strong>, Deeksha Arun, Terrance Boult, Walter Scheirer</p>
    <p><a href="https://www.biorxiv.org/content/10.1101/2025.09.08.673121v1">bioRxiv</a></p>
    <p class="desc">Category learning models vary in how they place decision boundaries relative to
    human behavior. We find evidence that Extreme Value Theory, which preferentially weights the extremes of a
    distribution, better predicts human category judgments than central-tendency models across two experiments with
    line stimuli and face morph sequences, offering new insight into how discriminative information is encoded for
    decision making.</p>
  </div>
</div>

<div class="pub-entry">
  <img src="/images/eyetracking_teaser.png" style="width: 340px;">
  <div>
    <h2>Analysis of Human Perception in Distinguishing Real and AI-Generated Faces: An Eye-Tracking Based Study</h2>
    <p><strong>Jin Huang</strong>, Subhadra Gopalakrishnan, Trisha Mittal, Jake Zuena, Jaclyn Pytlarz</p>
    <p><i>FG</i>, 2025 &nbsp;·&nbsp; <a href="https://ieeexplore.ieee.org/document/11099302">paper</a></p>
    <p class="desc">We investigate how humans perceive and distinguish real faces from AI-generated ones through a
    perceptual experiment using eye-tracking technology. Analyzing StyleGAN-3 generated images, we find that
    participants distinguish real from fake faces with an average accuracy of 76.80%, and that they scrutinize
    images more closely when they suspect a fake.</p>
  </div>
</div>

<div class="pub-entry">
  <img src="/images/har_teaser.png">
  <div>
    <h2>Human Activity Recognition in an Open World</h2>
    <p>Derek Prijatelj, Sam Grieggs, <strong>Jin Huang</strong>, Walter Scheirer, et al.</p>
    <p><i>JAIR</i>, 81 (2024) 85-122 &nbsp;·&nbsp; <a href="https://www.jair.org/index.php/jair/article/view/14476">paper</a> / <a href="https://arxiv.org/abs/2212.12141">arXiv</a></p>
    <p class="desc">Managing novelty in perception-based human activity recognition (HAR) is critical
    for realistic, real-world settings. We formalize novelty for HAR, propose an incremental open world learning (OWL)
    protocol applied to the Kinetics datasets to build a new benchmark (KOWL-718), analyze how current state-of-the-art
    HAR models perform as novelty is introduced over time, and release a containerized pipeline for reproducing and
    extending the protocol.</p>
  </div>
</div>

<div class="pub-entry" style="border-bottom: none;">
  <img src="/images/teaser_4imgs_revision.png" style="width: 320px;">
  <div>
    <h2>Measuring Human Perception to Improve Open-Set Recognition</h2>
    <p><strong>Jin Huang</strong>, Derek Prijatelj, Justin Dulay, Walter Scheirer</p>
    <p><i>T-PAMI</i>, 2023 &nbsp;·&nbsp; <a href="https://ieeexplore.ieee.org/document/10109834">paper</a> / <a href="https://arxiv.org/abs/2209.03519">arXiv</a></p>
    <p class="desc">Human perception, as measured through visual psychophysics, currently outperforms
    machine models at recognizing novelty in visual recognition tasks. We run a large-scale experiment collecting
    over 900,000 human reaction time measurements and use them to design a novel regularization term for the
    Open-Set Recognition loss function.</p>
  </div>
</div>

</div>
