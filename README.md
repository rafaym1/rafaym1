<div align="center">

# Greetings, I'm Rafay 😊

**Researcher · AI Enthusiast · Software Engineer · Content Creator · EdTech Advocate**

<br/>

<a href="https://sites.google.com/cohere.com/coherelabs-community/community-programs/edtech">
  <img src="./cohere.webp" width="45" alt="Cohere For AI" title="Cohere For AI"/>
</a>
&nbsp;&nbsp;
<a href="https://github.com/Legesher">
  <img src="./leh.png" width="45" alt="Legesher" title="Legesher"/>
</a>
&nbsp;&nbsp;
<a href="https://topmate.io/rafay_mustafa">
  <img src="./topmate.jpg" width="45" alt="TopMate" title="TopMate"/>
</a>
&nbsp;&nbsp;
<a href="https://scholar.google.com/citations?user=kesh5K4AAAAJ&hl=en&oi=ao">
  <img src="./google%20scholar.png" width="45" alt="Google Scholar" title="Google Scholar"/>
</a>

</div>


## About Me

Rafay is a researcher, an AI enthusiast, software engineer, content creator, and advocate for AI EdTech.


## Publications

- [**AdaptiveCloset: Reinforcement Learning in Personalized Clothing Recommendations**](https://ieeexplore.ieee.org/abstract/document/10375063/)
- [**Deciphering Faces: Enhancing Emotion Detection with Machine Learning Techniques**](https://ieeexplore.ieee.org/abstract/document/10374955)
- [**Development of a Smart Shoe for Blind and Visual Impaired People**](https://ieeexplore.ieee.org/abstract/document/10581187)
- [**Customized Learning for ADHD: An AI-Driven Assistive Study App**](https://sciforum.net/paper/view/20771)
- [**Robotrolley: Customer Following Trolley (CFT)**](https://ieeexplore.ieee.org/abstract/document/10414202)

## Current Projects

### \[Open Source\] Language, Decoded: Exploring the Impact of Native-Language Code on Multilingual Models

[Legesher](https://github.com/Legesher) lets developers write code in their native language; replacing English Python keywords with translated equivalents in 52 languages. The premise: **programming shouldn't require knowing English.**

In Legesher research, we ask whether exposing large language models to Legesher-style native-language code during fine-tuning actually improves their multilingual reasoning abilities. Using `CohereLabs/tiny-aya-base` (3.35B params) with QLoRA 4-bit quantization, we fine-tuned on datasets where Python keywords were swapped into Chinese, Urdu, and Spanish, then evaluated on XNLI, CSQA, and MGSM benchmarks across languages.

*Produced as part of Cohere's Expedition Tiny Aya program (March 2026), in collaboration with Legesher and Grayhat.*


### \[Upcoming Publication\] Towards Adaptive and Human-Centric Explainability

Research replicating and extending simulation-based evaluation frameworks for Explainable AI (XAI). Implements the XAIsim2real pipeline (HCOMP/AAAI-22) to compare explanation properties; faithfulness, sparsity, and robustness across synthetic human proxy models and target functions.

Extends the Chen et al. (NeurIPS 2021) framework with forward simulation and data-bug detection experiments, benchmarking SHAP and LIME across multiple tabular datasets (UCI Adult, Credit Default, Diabetes, Bank Marketing). Introduces a novel **LLM-as-Cognitive-Proxy** experiment that replaces statistical agents with an LLM required to verbalize causal reasoning; measuring not just prediction accuracy but reasoning quality, causal correctness, and uncertainty calibration against SHAP ground truth.

---

## Past Projects

### Multiagent Classroom MVP

A voice-first AI system built on the LiveKit Agents framework that uses multiple LLM-backed agents within a shared real-time audio session. The architecture uses a two-stage agent pipeline: a **ModeratorAgent** (OpenAI gpt-4o-mini + Deepgram nova-3 STT) that onboards the presenter via natural conversation and triggers a tool call to hand off control, and a **PresentationAgent** (OpenAI Realtime API) that dynamically switches between an expert persona and a beginner persona using function tools and shared RunContext state.


### Topology of Culture

Benchmarked cultural competence of South Asian multilingual LLMs across 7 Indic languages using two evaluation frameworks:
1. **DOSA** — surface artifact recall
2. **MILU** — ~79K MCQs from Indian competitive exams

Compared three Tiny Aya variants (South Asian, African, and global post-training) to isolate the effect of regional post-training data on cultural reasoning. Found that South Asian-focused post-training (Fire) significantly outperformed both baselines on 5/7 languages (p < 0.05), and surpassed Aya-23-35B — a 4× larger model — on three low-resource languages, demonstrating that targeted post-training can offset scale disadvantages in culturally situated tasks.

## Volunteer Work

- **Community Lead, EdTech** — [Cohere For AI](https://cohere.com/research), a non-profit open science organization with 3,000+ members from 100+ countries
- **Research Mentor** — [TopMate](https://topmate.io), helping students navigate their higher education journey


## Areas of Interest

**Language Models & Training**
-LLM interpretability & explainability
-Pre-training and fine-tuning pipelines
-Low-resource NLP with cross-lingual transfer and data augmentation

**Agents & Interaction**
-Dialogue systems with intent classification, slot filling, and retrieval-augmented response generation 
-LLM-based agent frameworks for multi-turn human-AI interaction
-Adaptive learning systems

**Vision & Generation**
-Object detection and image classification/segmentation
-Text-to-image generation using latent diffusion models
