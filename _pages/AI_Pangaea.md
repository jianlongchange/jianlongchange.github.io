---
layout: Pangaea
title: AI Pangaea
permalink: /AI_Pangaea/
nav: true
nav_order: 1
---
<!-- 项目标题 -->
<div style="text-align:center; margin-top:40px; margin-bottom:30px;">
  <h1 style="font-size:2.6em; font-weight:600; margin-bottom:10px; color:#222;">
    AI Pangaea: Unifying Intelligence Islands for Adapting Myriad Tasks
  </h1>
</div>

<!-- hero 图 -->
<figure style="margin: 0; text-align: center;">
  <img src="/assets/img/Intelligence Islands.png" 
       alt="Pangaea Banner" 
       style="width:100%; height:auto; display:block; margin:0;">
  <figcaption style="font-size:0.9em; color:#666; margin-top:8px;">
    a, AI models build intelligence from data relying on modality-specific data encodings, leading to Intelligence Islands; b, Pangaea unifies Intelligence Islands through unified data encoding, constructing an AI supercontinent.
  </figcaption>
</figure>

<!-- tagline / 背景介绍 -->
<div style="text-align:left; margin-top:35px; margin-bottom:40px;">
  <p style="font-size:1.15em; color:#444; margin:0 auto 25px auto; line-height:1.55;">
    The pursuit of artificial general intelligence (AGI) continuously demands generalization in one model across myriad tasks, even those not seen before. However, current AI models are isolated from each other for being limited to specific tasks, now first defined as <em>Intelligence Islands</em>. To unify Intelligence Islands into one, we propose <strong>Pangaea</strong>, the first AI supercontinent akin to the geological Pangaea. Pangaea encodes any data into a unified format and accumulates universal knowledge through pre-training on 296 datasets across diverse modalities. Eventually, it demonstrates remarkable generalization across 45 general tasks and 15 scientific tasks encompassing a wide range of scientific subjects. By investigating Pangaea deeper, the scaling effect of modality is revealed, quantifying the universal knowledge accumulation across modalities as the cumulative distribution function of a geometric distribution. On the whole, Pangaea shows strong potential to handle myriad tasks, indicating a new direction toward AGI.
  </p>
</div>

<p align="center">
  <a href="https://arxiv.org/abs/xxxx.xxxxx" target="_blank" style="display:inline-block; padding:10px 20px; background:#0056d2; color:#fff; border-radius:6px; text-decoration:none; font-weight:bold; box-shadow:0 2px 6px rgba(0,0,0,0.15);">
    📄 Read on arXiv
  </a>
</p>
---

## ✨ Highlights

<style>
  .highlight-box {
    background: #f9f9f9;
    border-radius: 12px;
    padding: 16px;
    box-shadow: 0 2px 6px rgba(0,0,0,0.08);
    transition: transform 0.2s ease, box-shadow 0.2s ease, background 0.2s ease;
    text-align: left;
  }
  .highlight-box:hover {
    transform: translateY(-4px) scale(1.02);
    box-shadow: 0 6px 12px rgba(0,0,0,0.15);
    background: #ffffff;
  }
  .highlight-box h3 {
    font-size: 16px;
    font-weight: bold;
    margin-bottom: 6px;
  }
  .highlight-box p {
    font-size: 14px;
    margin: 0;
  }
</style>

<div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 20px;">

  <a href="#unified-encoding" style="text-decoration:none; color:inherit;">
    <div class="highlight-box">
      <h3>🗂️ Unified Data Encoding</h3>
      <p>A unified representation that maps diverse modalities into a shared space.</p>
    </div>
  </a>

  <a href="#cross-modal-learning" style="text-decoration:none; color:inherit;">
    <div class="highlight-box">
      <h3>🔄 Cross-Modal Learning</h3>
      <p>Knowledge flows seamlessly across modalities, enhancing generalization.</p>
    </div>
  </a>

  <a href="#knowledge-transfer" style="text-decoration:none; color:inherit;">
    <div class="highlight-box">
      <h3>🔗 Knowledge Transfer</h3>
      <p>Capabilities learned in one domain accelerate progress in another.</p>
    </div>
  </a>

  <a href="#scientific-discovery" style="text-decoration:none; color:inherit;">
    <div class="highlight-box">
      <h3>🧪 Scientific Discovery</h3>
      <p>Applied to drug design, weather forecasting, geology, and medical diagnosis.</p>
    </div>
  </a>

  <a href="#scaling-effect" style="text-decoration:none; color:inherit;">
    <div class="highlight-box">
      <h3>📈 Scaling Effect</h3>
      <p>Revealing new scaling behaviors when expanding across multiple modalities.</p>
    </div>
  </a>

  <a href="#modality-affinity" style="text-decoration:none; color:inherit;">
    <div class="highlight-box">
      <h3>💞 Modality Affinity</h3>
      <p>Capturing hidden relationships among modalities to improve learning synergy.</p>
    </div>
  </a>

</div>

---

## 🗂️ Unified Data Encoding {#unified-encoding}
<figure style="margin: 0; text-align: center;">
  <img src="/assets/img/data_encoding.png" 
       style="width:100%; height:auto; display:block; margin:0;">
  <figcaption style="font-size:0.9em; color:#666; margin-top:8px;">
    a, Pangaea architecture; b, Pre-training dataset. c, Sample and feature distributions of table datasets for pre-training. d, Pre-training convergence curve of Pangaea.
  </figcaption>
</figure>

---

## 🔄 Cross-Modal Learning {#cross-modal-learning}
<figure style="margin: 0; text-align: center;">
  <img src="/assets/img/cross_modal_learning.png" 
       style="width:100%; height:auto; display:block; margin:0;">
  <figcaption style="font-size:0.9em; color:#666; margin-top:8px;">
    a, Pangaea architecture; b, Pre-training dataset. c, Sample and feature distributions of table datasets for pre-training. d, Pre-training convergence curve of Pangaea.
  </figcaption>
</figure>

---

## 🔗 Knowledge Transfer {#knowledge-transfer}
<figure style="margin: 0; text-align: center;">
  <img src="/assets/img/knowledge_transfer.png" 
       style="width:100%; height:auto; display:block; margin:0;">
  <figcaption style="font-size:0.9em; color:#666; margin-top:8px;">
    a, Pangaea architecture; b, Pre-training dataset. c, Sample and feature distributions of table datasets for pre-training. d, Pre-training convergence curve of Pangaea.
  </figcaption>
</figure>

---

## 🧪 Scientific Discovery {#scientific-discovery}
<figure style="margin: 0; text-align: center;">
  <img src="/assets/img/sci1.png" 
       style="width:100%; height:auto; display:block; margin:0;">
  <figcaption style="font-size:0.9em; color:#666; margin-top:8px;">
    a, Overview of the performance comparison between Pangaea and competitive models on all 15 scientific tasks. b-e, Pangaea is applied in Health and Biological sciences.
  </figcaption>
</figure>
<figure style="margin: 0; text-align: center;">
  <img src="/assets/img/sci2.png" 
       style="width:100%; height:auto; display:block; margin:0;">
  <figcaption style="font-size:0.9em; color:#666; margin-top:8px;">
    a-f, Pangaea is applied in Earth and environmental, and Physical sciences.
  </figcaption>
</figure>
<figure style="margin: 0; text-align: center;">
  <img src="/assets/img/sci3.png" 
       style="width:100%; height:auto; display:block; margin:0;">
  <figcaption style="font-size:0.9em; color:#666; margin-top:8px;">
    a-e, Pangaea is applied in Business and commerce, Humanities, Astronomy, Mathematical, and Social sciences.
  </figcaption>
</figure>

---

## 📈 Scaling Effect {#scaling-effect}
<figure style="margin: 0; text-align: center;">
  <img src="/assets/img/scaling_effect.png" 
       style="width:100%; height:auto; display:block; margin:0;">
  <figcaption style="font-size:0.9em; color:#666; margin-top:8px;">
    a, Scaling effect of pre-training modalities; b, Scaling effect of unseen modalities.
  </figcaption>
</figure>

---

## 💞 Modality Affinity {#modality-affinity}
<figure style="margin: 0; text-align: center;">
  <img src="/assets/img/modality_affinity.png" 
       style="width:100%; height:auto; display:block; margin:0;">
  <figcaption style="font-size:0.9em; color:#666; margin-top:8px;">
    a, Scaling effect of pre-training modalities; b, Scaling effect of unseen modalities. c, Affinity phenomenon of modality.
  </figcaption>
</figure>

---

## 📚 Citation

If you find **Pangaea** useful for your research, please cite our work:

<pre style="background:#f7f7f7; padding:15px; border-radius:8px; overflow:auto;">
<code>
@article{pangaea2025,
  title   = {Pangaea: A Unified Multimodal Framework},
  author  = {First Author and Second Author and Others},
  journal = {arXiv preprint arXiv:xxxx.xxxxx},
  year    = {2025}
}
</code>
</pre>
