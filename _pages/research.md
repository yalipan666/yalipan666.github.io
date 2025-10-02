---
layout: archive
title: ""
permalink: /research/
author_profile: true
---

<style>
.research-section {
    display: flex;
    align-items: center;
    gap: 30px;
    margin-bottom: 50px;
    padding: 20px;
    background: transparent;
    border-radius: 10px;
    border: 1px solid rgba(128, 128, 128, 0.2);
}

.research-section img {
    width: 300px;
    height: 300px;
    object-fit: contain;
    object-position: center;
    border-radius: 10px;
    flex-shrink: 0;
}

.research-section .text {
    flex: 1;
}

.research-section h3 {
    margin-top: 0;
    margin-bottom: 15px;
    font-size: 22px;  /* Heading size */
}
    
.research-section p {
    font-size: 0.9em;  /* 90% of default size */
    line-height: 1.15;  /* Space between lines */
}
   
/* Reverse layout for alternating sections */
.research-section.reverse {
    flex-direction: row-reverse;
}
    
/* Mobile responsive */
@media (max-width: 768px) {
    .research-section, .research-section.reverse  {
        flex-direction: column;
    }
    
    .research-section img {
        width: 100%;
        height: auto;
    }
      .research-section h3 {
        font-size: 20px;  /* Smaller heading on mobile */
    }
    
    .research-section p {
        font-size: 15px;  /* Smaller text on mobile */
    }
}
</style>

<!-- Section 1: Image on Left -->
<div class="research-section">
    <img src="/images/wild.jpg" alt="Research Project 1">
    <div class="text">
        <h3>Measuring Attention in "the Wild"</h3>
        <p>Traditional attention studies restricted eye movements, treating them as artefacts, yet growing evidence shows they carry cognitive significance. The challenge then becomes: how can we measure attention in the presence of natural eye movement? Rapid Invisible Frequency Tagging (RIFT) uses high-frequency flicker (≥60 Hz) that is imperceptible to participants yet evokes rhythmic activity in the visual cortex. By “tagging” specific items, RIFT allows us to track attention to multiple items simultaneously, including both foveal and parafoveal regions (i.e., even before fixating on the item). This capability opens the door to studying attention in "the wild", i.e., more naturalistic and ecological contexts, where eye movements are not treated as noise but as an integral part of cognitive processing.</p>
    </div>
</div>

<!-- Section 2: Image on the Right -->
<div class="research-section reverse">
    <img src="/images/reading.jpg" alt="Research Project 2">
    <div class="text">
        <h3>"Looking Ahead" in Reading</h3>
        <p>Skilled readers can extract information from a word even before directly fixating on it, but how much can actually be gathered from the parafoveal region? To address this, we co-registered eye tracking with MEG (and OPM-MEG for studying reading development in children) and applied a range of methods, including eye movement measures, event-related potentials (ERPs), rapid invisible frequency tagging (RIFT), and multivariate analyses. We provide robust neural evidence that substantial information (including the meaning of a word) can be pre-processed before fixation, a result not always reflected in eye movement data, underscoring the importance of integrating neural evidence when building theories of reading.</p>
    </div>
</div>

<!-- Section 3 -->
<div class="research-section">
    <img src="/images/alignment.jpg" alt="Research Project 3">
    <div class="text">
        <h3>"Anchoring" Transformers with Human Attention</h3>
        <p>The landmark paper “Attention is All You Need” established attention as the core mechanism of transformer-based large language models (LLMs). Yet, the notion of “attention” in LLMs differs fundamentally from human cognition. When humans process written language, eye movements serve as a precise and well-studied marker of where human attention is allocated in real-time. In this research direction, we aim to incorporate human eye movement data, i.e.,knowledge-grounded attention, into the attention matrices of LLMs, with the goal of improving performance on tasks that demand deeper language understanding, such as reasoning. If successful, we will further examine why this improvement occurs, for instance, whether the activation patterns of LLMs become more aligned with those observed in the human brain.</p>
    </div>
</div>

<!-- Section 4: Image on Right -->
<div class="research-section reverse">
    <img src="/images/mindreading.jpg" alt="Research Project 4">
    <div class="text">
        <h3>"Reading" the Mind</h3>
        <p> Mind-reading has long been a theme in science fiction, but advances in neuroimaging and data analysis are bringing it closer to reality. Using representational similarity analysis (RSA), we have decoded word information during sentence reading, and with support vector machines (SVM), during speech listening. These approaches provide powerful tools to probe how the brain encodes and processes information. Looking ahead, we aim to explore how word meaning is represented in both the brain and large language models (LLMs). For example, whether analogies such as north and south are represented as close (because they both describe directions) or far apart (because they are opposites) in their respective semantic spaces.</p>
    </div>
</div>




