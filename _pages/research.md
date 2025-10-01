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
    background: #f8f9fa;
    border-radius: 10px;
}

.research-section img {
    width: 300px;
    height: 300px;
    object-fit: cover;
    border-radius: 10px;
    flex-shrink: 0;
}

.research-section .text {
    flex: 1;
}

.research-section h3 {
    margin-top: 0;
    color: #2c3e50;
    margin-bottom: 15px;
}

/* Reverse layout for alternating sections */
.research-section.reverse {
    flex-direction: row-reverse;
}

/* Mobile responsive */
@media (max-width: 768px) {
    .research-section, .research-section.reverse {
        flex-direction: column;
    }
    
    .research-section img {
        width: 100%;
        height: auto;
    }
}
</style>

<!-- Section 1: Image on Left -->
<div class="research-section">
    <img src="/images/research1.jpg" alt="Research Project 1">
    <div class="text">
        <h1>Measuring attention in "the wild"</h1>
        <p><span style="font-size:0.9em;">Traditional visual attention studies have largely relied on paradigms where eye movements are restricted, as they are often considered a source of oculomotor artefacts, particularly in electrophysiological recordings. However, evidence from my reading study shows that eye movements are not random but are instead timed by ongoing alpha oscillations and carry important cognitive significance <a href="https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.3001968">(Pan et al., PLOS Biology, 2023)</a>. This suggests that eye movements should not be dismissed as mere artefacts but rather treated as cognition-related signals. The challenge then becomes: how can we measure attention in the presence of natural eye movements?</p>
<p>Rapid Invisible Frequency Tagging (RIFT), an adaptation of steady-state visually evoked potentials (SSVEPs), offers a powerful solution. RIFT uses high-frequency flicker (≥60 Hz), imperceptible to participants yet capable of eliciting rhythmic activity in the visual cortex. By “tagging” specific items, RIFT allows us to track the dynamics of attentional allocation even in the presence of eye movements. This technique has already proven effective in measuring attention during natural reading<a href="https://www.nature.com/articles/s41467-021-25571-x">(Pan et al., Nature Communications, 2021)</a><a href="https://elifesciences.org/articles/91327">(Pan et al., eLife, 2024)</a><a href="https://www.biorxiv.org/content/10.1101/2025.05.27.656336v1.full.pdf">(Pan et al., bioRxiv, 2025)</a>, visual search <a href="https://www.nature.com/articles/s42003-025-08321-3">(Duecker et al., Communications Biology, 2025)</a>, video watching (with Hyojin Park, in preparation), and decision making (with Laurence Hunt, in preparation).</p>
<p>A key advantage of RIFT is its ability to track attention to multiple items simultaneously, including both foveal and parafoveal regions—even before fixation occurs. This capability opens the door to studying attention in naturalistic, ecologically valid contexts, where eye movements are not treated as noise but as an integral part of cognitive processing.</span></p>
    </div>
</div>

<!-- Section 2: Image on Right -->
<div class="research-section reverse">
    <img src="/images/research2.jpg" alt="Research Project 2">
    <div class="text">
        <h3>Rapid Invisible Frequency Tagging (RIFT)</h3>
        <p>I pioneered the RIFT method to directly measure attention during naturalistic reading. By combining MEG with eye-tracking, we can precisely track how attention is deployed across words in real-time. This technique opens new avenues for understanding the neural mechanisms underlying reading comprehension.</p>
    </div>
</div>

<!-- Section 3: Image on Left -->
<div class="research-section">
    <img src="/images/research3.jpg" alt="Research Project 3">
    <div class="text">
        <h3>Children's Reading Development with OPM-MEG</h3>
        <p>My current research explores how children's brains develop reading skills using cutting-edge OPM-MEG technology. This non-invasive technique allows us to measure brain activity in naturalistic settings, providing unprecedented insights into developmental trajectories. This work is funded by the Leverhulme Trust and the Royal Society.</p>
    </div>
</div>

<!-- Section 4: Image on Right -->
<div class="research-section reverse">
    <img src="/images/research4.jpg" alt="Research Project 4">
    <div class="text">
        <h3>Brain-Inspired AI for Language Processing</h3>
        <p>I am exploring whether knowledge from neuroscience can help build smarter AI models. By incorporating principles of how the human brain processes language, we aim to develop more efficient and interpretable neural networks. This interdisciplinary approach bridges cognitive neuroscience and machine learning.</p>
    </div>
</div>
