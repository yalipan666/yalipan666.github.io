---
layout: archive
title: "Research"
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
        <h3>Visual Working Memory and Neural Oscillations</h3>
        <p>During my PhD, I investigated the role of neuronal oscillations in visual working memory using intracranial EEG (iEEG). This research revealed how different frequency bands coordinate to maintain visual information in short-term memory. Our findings demonstrated that theta-gamma coupling plays a crucial role in encoding and maintaining visual representations.</p>
        <p>📄 <a href="/files/paper1.pdf" target="_blank">Paper</a> | 💻 <a href="https://github.com/username/vwm" target="_blank">Code</a></p>
    </div>
</div>

<!-- Section 2: Image on Right -->
<div class="research-section reverse">
    <img src="/images/research2.jpg" alt="Research Project 2">
    <div class="text">
        <h3>Rapid Invisible Frequency Tagging (RIFT)</h3>
        <p>I pioneered the RIFT method to directly measure attention during naturalistic reading. By combining MEG with eye-tracking, we can precisely track how attention is deployed across words in real-time. This technique opens new avenues for understanding the neural mechanisms underlying reading comprehension.</p>
        <p>📄 <a href="/files/paper2.pdf" target="_blank">Paper</a> | 💻 <a href="https://github.com/username/rift" target="_blank">Code</a> | 📊 <a href="https://osf.io/data" target="_blank">Data</a></p>
    </div>
</div>

<!-- Section 3: Image on Left -->
<div class="research-section">
    <img src="/images/research3.jpg" alt="Research Project 3">
    <div class="text">
        <h3>Children's Reading Development with OPM-MEG</h3>
        <p>My current research explores how children's brains develop reading skills using cutting-edge OPM-MEG technology. This non-invasive technique allows us to measure brain activity in naturalistic settings, providing unprecedented insights into developmental trajectories. This work is funded by the Leverhulme Trust and the Royal Society.</p>
        <p>📄 <a href="/files/paper3.pdf" target="_blank">Paper</a> | 💻 <a href="https://github.com/username/opm-reading" target="_blank">Code</a></p>
    </div>
</div>

<!-- Section 4: Image on Right -->
<div class="research-section reverse">
    <img src="/images/research4.jpg" alt="Research Project 4">
    <div class="text">
        <h3>Brain-Inspired AI for Language Processing</h3>
        <p>I am exploring whether knowledge from neuroscience can help build smarter AI models. By incorporating principles of how the human brain processes language, we aim to develop more efficient and interpretable neural networks. This interdisciplinary approach bridges cognitive neuroscience and machine learning.</p>
        <p>💻 <a href="https://github.com/username/brain-ai" target="_blank">Code</a> | 📊 <a href="https://osf.io/data" target="_blank">Data</a></p>
    </div>
</div>
