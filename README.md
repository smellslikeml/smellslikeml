# Terry Rodriguez

**Co-founder & CTO, [Remyx AI](https://remyx.ai)** — experiment orchestration for AI teams.

Open source contributions across **spatial-reasoning VLMs**, **agentic research automation**, generative & multimodal AI, computer vision, robotics, and ML infrastructure.

[![Hugging Face](https://img.shields.io/badge/🤗%20Hugging%20Face-remyxai-FFD21E?style=flat-square)](https://huggingface.co/remyxai)
[![Docker Hub](https://img.shields.io/badge/Docker%20Hub-remyxai-2496ED?style=flat-square&logo=docker&logoColor=white)](https://hub.docker.com/u/remyxai)
[![Blog](https://img.shields.io/badge/Blog-smellslike.ml-1f6feb?style=flat-square&logo=rss&logoColor=white)](https://smellslike.ml)
[![Substack](https://img.shields.io/badge/Substack-Myx'd%20Results-FF6719?style=flat-square&logo=substack&logoColor=white)](https://remyxai.substack.com/)
[![Hackster](https://img.shields.io/badge/Hackster-terry--rodriguez-2E9FE6?style=flat-square&logo=hackster&logoColor=white)](https://www.hackster.io/terry-rodriguez)
[![X](https://img.shields.io/badge/X-@smellslikeml-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/smellslikeml)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-terry--j--rodriguez-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/terry-j-rodriguez/)
[![Discord](https://img.shields.io/badge/Discord-Remyx%20AI-5865F2?style=flat-square&logo=discord&logoColor=white)](https://discord.com/invite/b2yGuCNpuC)
[![Alchemist Accelerator](https://img.shields.io/badge/backed%20by-Alchemist%20Accelerator-6E4AFF?style=flat-square)](https://www.alchemistaccelerator.com/)
[![NVIDIA Inception](https://img.shields.io/badge/NVIDIA-Inception-76B900?style=flat-square&logo=nvidia&logoColor=white)](https://www.nvidia.com/en-us/startups/)

---

<p align="center">
  <img src="assets/journey.png" alt="The Remyx AI journey as a transit map: edge computer vision → multimodal spatial AI → agentic research automation, 2019–2026" width="100%">
  <br><sub><b>The journey</b> — from edge computer vision to agentic research automation (2019 → 2026)</sub>
</p>

### 📊 By the numbers
🤗 **283K+ downloads** across **70+ open models & datasets** ([@remyxai](https://huggingface.co/remyxai) — 21 models · 50 datasets)  ·  ⭐ **1.4K+ GitHub stars** across open-source projects

<table>
<tr>
<td width="50%"><img src="https://github.com/smellslikeml/ActionAI/raw/HEAD/assets/ActionAI_main.gif" width="100%"><br><sub><b>ActionAI</b> — real-time activity recognition from body keypoints, on the edge</sub></td>
<td width="50%"><img src="https://github.com/smellslikeml/nls-lumpy-torus/raw/HEAD/nls_selftrap_collapse_torus.gif" width="100%"><br><sub><b>nls-lumpy-torus</b> — mass-critical collapse on a curved manifold, from the spectral-geometry gallery</sub></td>
</tr>
</table>

## ⚙️ The engines

**[VQASynth](https://github.com/remyxai/VQASynth)** — the open pipeline that turns raw images into spatial-reasoning datasets: CLIP retrieval → RAM/LLaVA captions → GroundingDINO/CLIPSeg → SAM → ZoeDepth → RANSAC planes.

<p align="center"><img src="https://github.com/remyxai/VQASynth/raw/HEAD/assets/VQASynth-diagram.png" width="100%"></p>

**[Outrider](https://github.com/remyxai/outrider)** — brief-to-PR research automation: arXiv → rank & license-enrich → select & preflight gates → draft → fidelity / convention / test audits → PR, with automated + human refinement loops and full run telemetry.

<p align="center"><img src="assets/outrider-pipeline.png" width="100%"></p>

## 🛰️ Open models & datasets
Fine-tuned VLMs for quantitative **spatial reasoning** (distances, sizes, directions — for robotics & embodied AI) and the synthetic-data pipelines that train them.

- **[SpaceQwen2.5-VL-3B](https://huggingface.co/remyxai/SpaceQwen2.5-VL-3B-Instruct)** — grounded spatial VQA · **150K+ downloads**, the flagship
- **[SpaceThinker-Qwen2.5VL-3B](https://huggingface.co/remyxai/SpaceThinker-Qwen2.5VL-3B)** — a *reasoning* spatial VLM (test-time compute) · 30K+ downloads
- **[SpaceOm](https://huggingface.co/remyxai/SpaceOm)** · **[SpaceLLaVA (13B)](https://huggingface.co/remyxai/SpaceLLaVA)** · **SpaceMantis** · **SpaceQwen3-VL-2B-Thinking**
- **Datasets:** SpaceThinker · Robo2VLM-Reasoning · OpenSpaces · SpaceJudge — spatial VQA + reasoning traces

> 🗣️ The **SpatialVLM** research community credited **remyxai** for the open-source data-synthesis pipeline behind these models.

## 🛠️ Open-source projects
[![ActionAI](https://img.shields.io/github/stars/smellslikeml/ActionAI?style=flat-square&logo=github&label=ActionAI)](https://github.com/smellslikeml/ActionAI) — real-time spatio-temporal activity recognition from body keypoints; runs on Jetson-class edge devices.

[![VQASynth](https://img.shields.io/github/stars/remyxai/VQASynth?style=flat-square&logo=github&label=VQASynth)](https://github.com/remyxai/VQASynth) — compose multimodal spatial-reasoning datasets from raw images. 🎹

[![FFMPerative](https://img.shields.io/github/stars/remyxai/FFMPerative?style=flat-square&logo=github&label=FFMPerative)](https://github.com/remyxai/FFMPerative) — chat to compose video. [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/149byzCNd17dAehVuWXkiFQ2mVe_icLCa)

[![Outrider](https://img.shields.io/badge/GitHub%20Marketplace-Outrider-2088FF?style=flat-square&logo=githubactions&logoColor=white)](https://github.com/marketplace/actions/remyx-outrider) — a **brief-to-PR** research harness: scouts arXiv for a codebase and drafts *testable* implementations into existing call sites. ([demo ▶️](https://www.youtube.com/watch?v=N_FNfZ71s2I))

[![nls-lumpy-torus](https://img.shields.io/badge/gallery-nls--lumpy--torus-8a4fb0?style=flat-square&logo=github)](https://smellslikeml.github.io/nls-lumpy-torus/) — a spectral-geometry NLS/Gross–Pitaevskii solver + a gallery of numerical experiments (solitons, analog gravity & cosmology, quantum chaos, topological & Floquet transport), packaged as an **MCP toolkit for verification-grounded agent inference**.

## 🔀 Recent upstream contributions
Often drafted with **Outrider**, then verified and refined:
- **[huggingface/peft](https://github.com/huggingface/peft/pull/3382)** — *Riemannian-preconditioned LoRA optimizer* (**merged** ✅)
- **[DCDmllm/InstructSAM](https://github.com/DCDmllm/InstructSAM/pull/4)** — inference fix + native C++/ggml runtime docs (**merged** ✅)
- in flight toward **diffusers** (a training-free 4K FLUX community pipeline), **LeRobot**, and **TRL**

## 📣 Talks, events & media
- 🏆 **Awards:** [#TFWorld TF 2.0 Challenge — **Winner**](https://devpost.com/software/everybody-dance-faster) (*Everybody Dance Faster* — real-time motion-transfer booth, EdgeTPU + TF 2.0) · [NVIDIA AI-at-the-Edge Challenge — **2nd prize**](https://www.hackster.io/smellslikeml/saving-bandwidth-with-anomaly-detection-16eb67) (*Saving Bandwidth with Anomaly Detection*)
- 🎪 **Hosted:** [Experiment 2025](https://experiment.remyx.ai/) — Remyx's inaugural event, [hundreds in attendance](https://luma.com/experiment-2025)
- 🎤 **Conferences (2024–2025):** [ODSC West 2024](https://odsc.com/blog/speaker/terry-rodriguez/) (*LLMOps & MLOps* track) · GitHub Universe · AI Agent Builders Summit — SF
- 🎙️ **Podcasts:** Generationship (Heavybit) — [Ep. 20 *Smells Like ML*](https://www.heavybit.com/library/podcasts/generationship/ep-20-smells-like-ml-with-salma-mayorquin-and-terry-rodriguez-of-remyx-ai) & [Ep. 40 *ExperimentOps*](https://www.heavybit.com/library/podcasts/generationship/ep-40-experimentops-with-salma-mayorquin-of-remyx-ai) · [Adventures in ML (ML-149)](https://topenddevs.com/podcasts/adventures-in-machine-learning/adaptive-industry-ml-challenges-automation-and-model-applications-ml-149) · Code & Caffeine
- 📰 **Press & features:** [NVIDIA “Meet the Maker”](https://blogs.nvidia.com/blog/smells-like-ml/) spotlight · [The MagPi #80](https://www.raspberrypi.com/news/yoga-training-with-yogai-and-a-raspberry-pi-smart-mirror-the-magpi-issue-80/) (*YogAI* smart mirror) · [Cerebral Valley](https://cerebralvalley.ai/blog/remyx-your-ai-production-assistant-3tNSKSCJzRp6LbSxMCjLed) (founder interview) · [NVIDIA “AI at the Edge”](https://news.developer.nvidia.com/ai-at-the-edge-challenge-spotlight-saving-bandwidth-with-anomaly-detection/) spotlight · *SpatialVLM* community shout-out
- ▶️ **Demo:** [GitRank — Research to Testable PRs in Minutes](https://www.youtube.com/watch?v=N_FNfZ71s2I)

## 🧭 Background
10+ years building production ML — **Riot Games, Tubi, Robust.AI, Remyx**. Mathematics at **UC Berkeley** & **UNC Chapel Hill**.
**Remyx AI** is an [**Alchemist Accelerator**](https://www.alchemistaccelerator.com/) company (investors include Generationship & Roble Ventures).

## 🔗 Connect
[remyx.ai](https://remyx.ai) · [🤗 remyxai](https://huggingface.co/remyxai) · [Docker Hub](https://hub.docker.com/u/remyxai) · [smellslike.ml](https://smellslike.ml) · [Substack](https://remyxai.substack.com/) · [Hackster](https://www.hackster.io/terry-rodriguez) · [YouTube](https://www.youtube.com/watch?v=N_FNfZ71s2I) · [Discord](https://discord.com/invite/b2yGuCNpuC) · [X](https://x.com/smellslikeml) · [LinkedIn](https://www.linkedin.com/in/terry-j-rodriguez/) · [Reddit](https://www.reddit.com/user/remyxai/)
