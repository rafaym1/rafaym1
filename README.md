<div align="center">

# Hi, I'm Rafay 👋

**Researcher · AI Enthusiast · Software Engineer · Content Creator · EdTech Advocate**

<br/>

<a href="https://cohere.com/research">
  <img src="https://img.shields.io/badge/Cohere%20For%20AI-Community%20Lead%2C%20EdTech-39594D?style=for-the-badge&logo=cohere&logoColor=white" alt="Cohere For AI"/>
</a>
&nbsp;
<a href="https://github.com/Legesher">
  <img src="https://img.shields.io/badge/Legesher-Open%20Source%20Researcher-7B2FBE?style=for-the-badge&logo=github&logoColor=white" alt="Legesher"/>
</a>
&nbsp;
<a href="https://topmate.io">
  <img src="https://img.shields.io/badge/TopMate-Research%20Mentor-FF5722?style=for-the-badge&logoColor=white" alt="TopMate"/>
</a>

</div>


## About Me

Rafay is a researcher, an AI enthusiast, software engineer, content creator, and advocate for AI EdTech.


## Current Projects

### \[Open Source\] Language, Decoded
> *Exploring the Impact of Native-Language Code on Multilingual Models*

[Legesher](https://github.com/Legesher) lets developers write code in their native language — replacing English Python keywords with translated equivalents in 52 languages. The premise: **programming shouldn't require knowing English.**

In this research, we ask whether exposing large language models to Legesher-style native-language code during fine-tuning actually improves their multilingual reasoning abilities. Using `CohereLabs/tiny-aya-base` (3.35B params) with QLoRA 4-bit quantization, we fine-tuned on datasets where Python keywords were swapped into Chinese, Urdu, and Spanish, then evaluated on XNLI, CSQA, and MGSM benchmarks across languages.

*Produced as part of Cohere's Expedition Tiny Aya program (March 2026), in collaboration with Legesher and Grayhat.*


### \[Upcoming Publication\] Towards Adaptive and Human-Centric Explainability

Research replicating and extending simulation-based evaluation frameworks for Explainable AI (XAI). Implements the XAIsim2real pipeline (HCOMP/AAAI-22) to compare explanation properties — faithfulness, sparsity, and robustness — across synthetic human proxy models and target functions.

Extends the Chen et al. (NeurIPS 2021) framework with forward simulation and data-bug detection experiments, benchmarking SHAP and LIME across multiple tabular datasets (UCI Adult, Credit Default, Diabetes, Bank Marketing). Introduces a novel **LLM-as-Cognitive-Proxy** experiment (Exp. 3b) that replaces statistical agents with an LLM required to verbalize causal reasoning — measuring not just prediction accuracy but reasoning quality, causal correctness, and uncertainty calibration against SHAP ground truth.


## Volunteer Work

- **Community Lead, EdTech** — [Cohere For AI](https://cohere.com/research), a non-profit open science organization with 3,000+ members from 100+ countries
- **Research Mentor** — [TopMate](https://topmate.io), helping students navigate their higher education journey


## Areas of Interest

**Language Models & Training**
- LLM interpretability & explainability
- Training LLMs from scratch / open-source LLM pipelines
- Multilingual AI & low-resource language modeling

**Agents & Interaction**
- Conversational AI & user simulation
- AI agents for human-AI interaction
- AI-powered adaptive learning systems

**Vision & Generation**
- Object detection & image recognition
- Image generation & diffusion models
