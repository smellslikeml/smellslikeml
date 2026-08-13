<h1 align="center">Terry Rodriguez</h1>

<p align="center">
  <b>Co-founder &amp; CTO of <a href="https://remyx.ai">Remyx AI</a></b><br>
  <sub>Mathematics, UC Berkeley &amp; UNC Chapel Hill &nbsp;·&nbsp; ex-Riot Games, Tubi, Robust.AI &nbsp;·&nbsp; 10+ years in production ML</sub>
</p>

<p align="center">
  <sub>Computer vision &nbsp;·&nbsp; multimodal models &nbsp;·&nbsp; robotics &nbsp;·&nbsp; numerical computing &nbsp;·&nbsp; ML infrastructure</sub>
</p>

<p align="center">
  <a href="https://remyx.ai"><img alt="Remyx AI" src="https://img.shields.io/badge/remyx.ai-Website-E23E3E?style=flat-square&labelColor=0d1117&logo=safari&logoColor=white"></a>
  <a href="https://huggingface.co/remyxai"><img alt="Hugging Face" src="https://img.shields.io/badge/Hugging%20Face-remyxai-FFD21E?style=flat-square&labelColor=0d1117&logo=huggingface&logoColor=white"></a>
  <a href="https://smellslike.ml"><img alt="Blog" src="https://img.shields.io/badge/smellslike.ml-Since%202018-1f6feb?style=flat-square&labelColor=0d1117&logo=jupyter&logoColor=white"></a>
  <a href="https://remyxai.substack.com"><img alt="Substack" src="https://img.shields.io/badge/Substack-Writing-FF6719?style=flat-square&labelColor=0d1117&logo=substack&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/terry-j-rodriguez"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-terry--j--rodriguez-0A66C2?style=flat-square&labelColor=0d1117"></a>
</p>

<p align="center">
  <img alt="ActionAI stars" src="https://img.shields.io/github/stars/smellslikeml/ActionAI?style=flat-square&labelColor=0d1117&color=E23E3E&label=ActionAI&logo=github">
  <img alt="VQASynth stars" src="https://img.shields.io/github/stars/remyxai/VQASynth?style=flat-square&labelColor=0d1117&color=E23E3E&label=VQASynth&logo=github">
  <img alt="FFMPerative stars" src="https://img.shields.io/github/stars/remyxai/FFMPerative?style=flat-square&labelColor=0d1117&color=E23E3E&label=FFMPerative&logo=github">
  <img alt="Outrider release" src="https://img.shields.io/github/v/release/remyxai/outrider?style=flat-square&labelColor=0d1117&color=E23E3E&label=Outrider&logo=github">
  <img alt="SpaceThinker downloads" src="https://img.shields.io/badge/dynamic/json?style=flat-square&labelColor=0d1117&color=FFD21E&label=SpaceThinker&suffix=%2Fmo&query=%24.downloads&url=https%3A%2F%2Fhuggingface.co%2Fapi%2Fmodels%2Fremyxai%2FSpaceThinker-Qwen2.5VL-3B">
</p>

---

## Outrider

[![Marketplace](https://img.shields.io/badge/GitHub%20Marketplace-Remyx%20Outrider-E23E3E?style=flat-square&labelColor=0d1117&logo=github)](https://github.com/marketplace/actions/remyx-outrider)

We use [Outrider](https://github.com/marketplace/actions/remyx-outrider) to implement new ML research against real codebases, test it on forks, and send the useful parts upstream. Every row below was reviewed by maintainers who did not ask for the contribution.

| Repository | Contribution | Status |
|---|---|---|
| [`huggingface/peft`](https://github.com/huggingface/peft) | [#3382 · Riemannian-preconditioned LoRA optimizer](https://github.com/huggingface/peft/pull/3382) | **Merged**, 9 tests |
| [`huggingface/peft`](https://github.com/huggingface/peft) | [#3518 · Super-Tuning as a PEFT method](https://github.com/huggingface/peft/pull/3518) | In review |
| [`huggingface/lerobot`](https://github.com/huggingface/lerobot) | [#4036 · ECoT dense chain-of-thought annotations](https://github.com/huggingface/lerobot/pull/4036) | In review |
| [`huggingface/trl`](https://github.com/huggingface/trl) | [#6167 · STARE surprisal-guided token weighting](https://github.com/huggingface/trl/pull/6167) | In review |

## VQASynth

[![stars](https://img.shields.io/github/stars/remyxai/VQASynth?style=flat-square&labelColor=0d1117&color=E23E3E&logo=github)](https://github.com/remyxai/VQASynth)
[![forks](https://img.shields.io/github/forks/remyxai/VQASynth?style=flat-square&labelColor=0d1117&color=E23E3E&logo=github)](https://github.com/remyxai/VQASynth/forks)
[![HF models](https://img.shields.io/badge/%F0%9F%A4%97%20models-SpaceLLaVA%20family-FFD21E?style=flat-square&labelColor=0d1117)](https://huggingface.co/remyxai)

A pipeline that turns ordinary images into spatial-reasoning training data. CLIP retrieval, RAM and LLaVA captioning, GroundingDINO region proposals, SAM segmentation, ZoeDepth monocular depth, and RANSAC plane fitting.

<a href="https://github.com/remyxai/VQASynth">
  <img alt="VQASynth pipeline stages from semantic filtering through plane segmentation" src="https://raw.githubusercontent.com/remyxai/VQASynth/main/assets/VQASynth-diagram.png" width="100%">
</a>

Trains the [SpaceLLaVA](https://huggingface.co/remyxai) model family. Cited by Google DeepMind and used as an ICLR 2026 benchmark baseline.

## ActionAI

[![stars](https://img.shields.io/github/stars/smellslikeml/ActionAI?style=flat-square&labelColor=0d1117&color=E23E3E&logo=github)](https://github.com/smellslikeml/ActionAI)
[![forks](https://img.shields.io/github/forks/smellslikeml/ActionAI?style=flat-square&labelColor=0d1117&color=E23E3E&logo=github)](https://github.com/smellslikeml/ActionAI/forks)
[![maintained since 2019](https://img.shields.io/badge/maintained-since%202019-E23E3E?style=flat-square&labelColor=0d1117)](https://github.com/smellslikeml/ActionAI)

Real-time human activity recognition from tracked body keypoints, running on edge hardware. Started in 2019, still maintained.

<a href="https://github.com/smellslikeml/ActionAI">
  <img alt="ActionAI classifying activity from tracked pose keypoints in real time" src="https://raw.githubusercontent.com/smellslikeml/ActionAI/master/assets/yogai_squat_or_not.gif" width="100%">
</a>

## Numerical work

### [NLS on the Lumpy Torus](https://smellslikeml.github.io/nls-lumpy-torus/)

Numerical nonlinear Schrödinger evolution on a surface of revolution. Laplace–Beltrami discretization, Crank–Nicolson integration, nonlinear solves, conserved quantities, Gaussian beams, and self-trapping.

<a href="https://smellslikeml.github.io/nls-lumpy-torus/">
  <img alt="Gaussian curvature on a lumpy torus and the corresponding metric coupling seen by the Laplace-Beltrami operator" src="https://smellslikeml.github.io/nls-lumpy-torus/curvature_view.png" width="100%">
</a>

## FFMPerative

[![stars](https://img.shields.io/github/stars/remyxai/FFMPerative?style=flat-square&labelColor=0d1117&color=E23E3E&logo=github)](https://github.com/remyxai/FFMPerative)

Video processing driven by natural language, composing ffmpeg operations from a plain description of the edit.

## Writing

I have been publishing ML experiments at [smellslike.ml](https://smellslike.ml) since 2018: computer vision, recommendation systems, robotics, PDEs, JAX, point clouds, edge inference, and the infrastructure around all of it.

---

<p align="center">
  <a href="https://remyx.ai">Remyx</a> &nbsp;·&nbsp;
  <a href="https://smellslike.ml">smellslike.ml</a> &nbsp;·&nbsp;
  <a href="https://remyxai.substack.com">Writing</a> &nbsp;·&nbsp;
  <a href="https://huggingface.co/remyxai">Hugging Face</a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/terry-j-rodriguez">LinkedIn</a>
</p>
