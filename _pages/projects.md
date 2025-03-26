---
layout: archive
title: "Selected Projects"
permalink: /projects/
author_profile: true
redirect_from:
  - /projects
---
---
<H2> Learning at the Edge: an Extreme Value Theory for Visual Recognition (ND CVRL)</H2>

<div style="display: flex; align-items: center;">
    <img src="/images/experimental_setup.png" style="width: 400px; margin-right: 20px;">
    <p style="text-align: justify;">Several possibilities exist for modeling decision boundaries in category learning, with varying
degrees of human fidelity. This projects finds evidence for preferentially focusing representational
resources on the extremes of the distribution of visual inputs in a generative model as an alternative 
to the central tendency models that are commonly used for prototypes and exemplars.
Here we suggest that the statistical Extreme Value Theory provides such a framework. 
In two experiments with line stimuli and face morph sequences, respectively, Weibull fit better predicts an
observed human shift when training data are sampled in uniform, enriched tail and long tail manners.
This suggests an extrema-based model lends new insight into how discriminative information is encoded in the
brain with implications for decision making in machine learning.</p>

</div>
---

<H2> Unified Embedding with Large Foundation Models for Improved MRO Retrieval (Grainger) </H2>
<div style="display: flex; justify-content: center; align-items: center; width: 100%;">
    <img src="/images/grainger.png" style="width: 600px;">
</div>

<div><p style="text-align: justify;"> In this project, we fine-tune multi-modal foundational models to 
address the complex challenges of MRO (Maintenance, Repair, and Operations) retrieval. 
MRO data often includes a mix of text (like maintenance logs and technical manuals) 
and visual content (like schematics and part images), which can be difficult to retrieve effectively 
due to inconsistent formats and specialized terminology. By fine-tuning these models on MRO-specific data,
we look to enhance their ability to recognize and interpret domain-specific language and visual cues, 
leading to more accurate and context-aware retrieval.</p>

</div>
---
<H2> Improving GAN-based Image Generation with Human Eye-Tracking (Dolby Laboratories) </H2>

<div style="display: flex; align-items: center;">
    <img src="/images/dolby.png" style="width: 500px; margin-right: 20px;">
    <p style="text-align: justify;">Generative models have made remarkable progress in generating 
highly realistic images over the years. These models have been improved in architecture, 
dataset quality, data augmentation methods, and so on. 
However, these model are still far from perfect and still fails in lots of cases even when we only 
focus on the area of face generation. We observe the flaws in these generated images, 
and at the same time we know humans have better knowledge of real world. 
In this project we explore the possibility of using eye-tracking data as an 
additional source of information to improve StyleGAN-3.</p>

</div>

---
<H2> Measuring Human Reaction Time to Improve Open-Set Recognition (ND CVRL)</H2>

<div style="display: flex; justify-content: center; align-items: center; width: 100%;">
    <img src="/images/teaser_4imgs_revision.png" style="width: 600px;">
</div>

<div><p style="text-align: justify;">The human ability to recognize that something is new currently 
outperforms all machine models on visual recognition tasks which include some aspect of novelty. 
Human perception as measured by the methods and procedures of visual psychophysics from psychology 
can provide vital information for detecting novelty in visual recognition tasks. In this project, 
we design and perform a large-scale experiment to collect over 900,000 human reaction time 
measurements and design a novel way to regularize the loss function for Open-Set Recognition task.</p>

</div>

---

<H2>Human Activity Recognition in an Open World (ND CVRL, Kitware Inc)</H2>

<div style="display: flex; align-items: center;">
    <img src="/images/har_teaser.png" style="width: 400px; margin-right: 20px;">
    <p style="text-align: justify;">
Managing novelty in perception-based human activity recognition (HAR) is critical in realistic
settings to improve task performance over time and ensure solution generalization outside of prior
seen samples. Novelty manifests in HAR as unseen samples, activities, objects, environments,
and sensor changes, among other ways. Novelty may be task-relevant, such as a new class or
new features, or task-irrelevant resulting in nuisance novelty, such as never before seen noise,
blur, or distorted video recordings. To perform HAR optimally, algorithmic solutions must be
tolerant to nuisance novelty, and learn over time in the face of novelty. This project 1) formalizes the
definition of novelty in HAR building upon the prior definition of novelty in classification tasks,
2) proposes an incremental open world learning (OWL) protocol and applies it to the Kinetics
datasets to generate a new benchmark KOWL-718, 3) analyzes the performance of current state-
of-the-art HAR models when novelty is introduced over time, 4) provides a containerized and
packaged pipeline for reproducing the OWL protocol and for modifying for any future updates to
Kinetics. </p>

</div>
