---
layout: page
permalink: /highlights/
title: Highlights
description: 
nav: true
nav_order: 4
---

<!-- Flickity CSS & JS -->
<link rel="stylesheet" href="https://unpkg.com/flickity@2/dist/flickity.min.css">
<script src="https://unpkg.com/flickity@2/dist/flickity.pkgd.min.js"></script>

<h2>Snaps</h2>

<div class="gallery js-flickity"
     data-flickity-options='{ 
       "wrapAround": true, 
       "autoPlay": 3000, 
       "imagesLoaded": true, 
       "cellAlign": "left", 
       "contain": true 
     }'>

  <div class="gallery-cell"><img src="/assets/img/highlights/orga.jpeg" alt="Workshop Image 0"></div>
  <div class="gallery-cell"><img src="/assets/img/highlights/keynote.jpeg" alt="Workshop Image 1"></div>
  <div class="gallery-cell"><img src="/assets/img/highlights/networking.jpeg" alt="Workshop Image 2"></div>
  <div class="gallery-cell"><img src="/assets/img/highlights/poster.jpeg" alt="Workshop Image 3"></div>
  <div class="gallery-cell"><img src="/assets/img/highlights/poster2.jpeg" alt="Workshop Image 4"></div>
  <div class="gallery-cell"><img src="/assets/img/highlights/poster3.jpeg" alt="Workshop Image 5"></div>
  <div class="gallery-cell"><img src="/assets/img/highlights/audience.jpeg" alt="Workshop Image 6"></div>

</div>

<h2>Accepted Papers – NLPSI 2025</h2>
<ul>
  <li><a href="https://workshop-proceedings.icwsm.org/pdf/2025_30.pdf" target="_blank">Simulating Persuasive Dialogues on Meat Reduction with Generative Agents</a> – Georg Ahnert, Elena Wurth, Markus Strohmaier, Jutta Mata</li>
  <li><a href="https://workshop-proceedings.icwsm.org/pdf/2025_31.pdf" target="_blank">Automatically Coding Implicit Motives in Picture Story Exercises: The Automated Motive Coder</a> – Max Brede, Felix Schönbrodt, Birk Hagemeyer, Veronika Lerche</li>
  <li><a href="https://workshop-proceedings.icwsm.org/pdf/2025_32.pdf" target="_blank">What Does it Take to Effectively Communicate Fact Checking Results?</a> – Amelie Wuehrl</li>
  <li><a href="https://workshop-proceedings.icwsm.org/pdf/2025_33.pdf" target="_blank">Lexpansion: Evaluating Dictionary Based Lexicon Expansion for Social Media Analysis</a> – Mohamed Bahgat, Steven R Wilson, Walid Magdy</li>
  <li><a href="https://workshop-proceedings.icwsm.org/pdf/2025_34.pdf" target="_blank">Explicit Cooperation Shapes Human‑Like Multi‑agent LLM Negotiation</a> – Yanru Jiang, Gülşah Akçakır</li>
  <li><a href="https://workshop-proceedings.icwsm.org/pdf/2025_35.pdf" target="_blank">Scaling Implicature via Structured Interaction in Multi‑Agent LLMs</a> – Harvey Bonmu Ku</li>
  <li><a href="https://workshop-proceedings.icwsm.org/pdf/2025_36.pdf" target="_blank">Basic Psychological Need Fulfillment in AI‑Mediated Communication</a> – Eileen Wemmer, Carsten Röcker</li>
  <li><a href="https://workshop-proceedings.icwsm.org/pdf/2025_37.pdf" target="_blank">Assessing Perspective‑Taking in Texts</a> – Paul Compensis</li>
  <li><a href="https://workshop-proceedings.icwsm.org/pdf/2025_38.pdf" target="_blank">A Hybrid Theory and Data‑driven Approach to Persuasion Detection with Large Language Models</a> – Gia Bao Hoang et al.</li>
  <li><a href="https://workshop-proceedings.icwsm.org/pdf/2025_39.pdf" target="_blank">The Utility of LLM Text Generation in Longitudinal Psychological Datasets</a> – Jari Zegers, Bennett Kleinberg</li>
</ul>


<style>
.gallery {
  background: #f8f8f8;
  margin-top: 1rem;
}

/* Each cell can vary in width */
.gallery-cell {
  margin-right: 10px;
  flex: 0 0 auto;
  max-width: 90vw; /* Optional: prevent overflow */
}

/* Images scale to fit width; height adjusts automatically */
.gallery-cell img {
  display: block;
  width: 100%;
  height: auto;
  max-height: 80vh; /* Prevent super tall portraits from taking over */
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.2);
}
</style>
