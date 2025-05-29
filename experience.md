---
layout: default
title: Experience
---

<h1>Work Experience</h1>

<div class="timeline-alt">
  <div class="timeline-container left">
    <div class="content">
      <h3>🔧 Compiler Researcher — MPS Lab, ASU</h3>
      <span class="date">Aug 2024 – Present</span>
      <p>Working on LLVM backend for TI DSP; optimizing MLIR passes for DSP hardware.</p>
    </div>
  </div>

  <div class="timeline-container right">
    <div class="content">
      <h3>💻 Technical Intern — 3Blocks</h3>
      <span class="date">May 2023 – Aug 2023</span>
      <p>Integrated OpenAI APIs, developed internal productivity tools, and explored language models in production.</p>
    </div>
  </div>

  <div class="timeline-container left">
    <div class="content">
      <h3>🧠 Smart Contract Dev — Dapp World</h3>
      <span class="date">Jan 2022 – Apr 2022</span>
      <p>Wrote Solidity smart contracts and built dApps using React and Web3.js.</p>
    </div>
  </div>
</div>

<style>
.timeline-alt {
  position: relative;
  max-width: 900px;
  margin: 2rem auto;
  padding: 1rem;
}

.timeline-container {
  padding: 1rem 2rem;
  position: relative;
  width: 50%;
}

.timeline-container.left {
  left: 0;
}

.timeline-container.right {
  left: 50%;
}

.timeline-container::after {
  content: "";
  position: absolute;
  width: 25px;
  height: 25px;
  right: -13px;
  background-color: #38bdf8;
  border: 3px solid #0ea5e9;
  top: 15px;
  border-radius: 50%;
  z-index: 1;
}

.timeline-alt::before {
  content: '';
  position: absolute;
  width: 4px;
  background-color: #38bdf8;
  top: 0;
  bottom: 0;
  left: 50%;
  margin-left: -2px;
}

.content {
  padding: 1rem;
  background-color: #f8fafc;
  position: relative;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.05);
}

.content h3 {
  margin-top: 0;
  color: #0f172a;
}

.content .date {
  font-size: 0.9rem;
  color: #64748b;
  display: block;
  margin-bottom: 0.5rem;
}

@media screen and (max-width: 768px) {
  .timeline-container {
    width: 100%;
    left: 0 !important;
  }

  .timeline-container::after {
    left: calc(50% - 12px);
  }

  .timeline-alt::before {
    left: 50%;
  }
}
</style>
