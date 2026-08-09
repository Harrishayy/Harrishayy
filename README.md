<h1 align="center">Harrish Ayyanar</h1>

<p align="center">
  <i>Engineering @ HyBird · ex-Research Engineer @ Cisco · ex-Engineering @ RevisionDojo · Robotics & AI @ UCL</i>
</p>

<p align="center">
  <a href="https://scholar.google.com/citations?user=_2UtegcAAAAJ&hl=en">Google Scholar</a> ·
  <a href="https://www.linkedin.com/in/harrish-ayyanar/">LinkedIn</a>
  <!-- · <a href="https://YOUR-PORTFOLIO-URL">Portfolio</a> -->
</p>

---

<p align="center"><sub><b>DOMAINS</b></sub></p>

<p align="center">
  <a href="#user-content-robotics-open"><img src="https://img.shields.io/badge/Robotics-1f6feb?style=for-the-badge" /></a>
  <a href="#user-content-spatial-open"><img src="https://img.shields.io/badge/Spatial%20%26%20Perception-238636?style=for-the-badge" /></a>
  <a href="#user-content-ai-open"><img src="https://img.shields.io/badge/AI%20Research-a371f7?style=for-the-badge" /></a>
  <a href="#user-content-ml-open"><img src="https://img.shields.io/badge/Machine%20Learning-0891b2?style=for-the-badge" /></a>
  <a href="#user-content-software-open"><img src="https://img.shields.io/badge/Software%20%26%20Systems-d1242f?style=for-the-badge" /></a>
</p>

> Click a badge above to jump to a domain, or expand any section below.

<p align="center"><sub><b>TECH STACK</b></sub></p>

<p align="center">
  <code>Python</code> · <code>C++</code> · <code>Go</code> · <code>TypeScript</code> · <code>MATLAB</code> · <code>PyTorch</code> · <code>ROS 2</code> · <code>MuJoCo</code> · <code>Isaac Lab</code> · <code>Fusion 360</code> · <code>Linux</code>
</p>

---

## About

My interests span a wide range: robotics, perception and spatial computing (computer vision and SLAM), AI research, reinforcement learning, and simulation. I enjoy working across the stack, from low-level systems to learning-based methods, and tying it all back to real hardware. Right now I'm focused on building robots and [Ultras](https://theultras.app).

---

<h2 id="-robotics">🤖 Robotics</h2>

<details open>
<summary><b>Autonomous systems, control, and grasp/manipulation</b></summary>
<a id="robotics-open"></a>

<br />

_Hardware, control, and simulation for real-world robots — from autonomous platforms to manipulation._

| Project | Description | Stack | Link |
|---|---|---|---|
| **Subterra Nav** | Multi-rate EKF fusing IMU, magnetometer, and ToF sensors for 2D localisation of a Mecanum robot. 2nd in cohort at 3.58 cm RMSE. | MATLAB, Simulink | [Repo](https://github.com/EdwinIsCoding/Subterranean_Navigation) |
| **IGGY** | Autonomous quadruped "robot dog" that detects a ball with YOLO and tracks/pursues it through a PID control loop, running onboard in real time. | Python, YOLO, OpenCV | [Repo](https://github.com/Harrishayy/IGGY) |
| **Kinesis** | 6-DoF end-effector tracking for a Franka Panda in MuJoCo: residual RL (PPO) layered on a damped-least-squares Jacobian IK feedforward, robust to observation noise and control delay (0.46 mm RMS). | Python, MuJoCo, PyTorch | [Repo](https://github.com/Harrishayy/Kinesis) |
| **Dynamic-Gripper-Sim** | PyBullet grasping simulation that generates data across gripper-object pairs (2/3-finger, arm) and trains ML classifiers to predict grasp success. | Python, PyBullet, scikit-learn | [Repo](https://github.com/Harrishayy/Dynamic-Gripper-Sim) |
| **SystemsEngineering_IP** | Stabilised an underactuated physical cart-pole on limited embedded compute; benchmarked LQR, cascaded inner-outer PID, and pole-placement controllers solved offline via the continuous-time Riccati equation and Ackermann's formula. | C++, Python, NumPy | [Repo](https://github.com/Harrishayy/SystemsEngineering_IP) |

**Skills:** EKF / sensor fusion · PID · LQR · Pole placement · MPC · RL (Residual RL, PPO, GRPO) · Grasp planning · MuJoCo / PyBullet · ROS 2

</details>

---

<h2 id="-spatial--perception">🛰️ Perception & Spatial</h2>

<details>
<summary><b>Computer vision, 3D reconstruction, and spatial computing</b></summary>
<a id="spatial-open"></a>

<br />

_Turning pixels into 3D — reconstruction, segmentation, and perception for spatial understanding._

| Project | Description | Stack | Link |
|---|---|---|---|
| **NeMo-Ray** | 🏆 Winner of NVIDIA Hack for Impact London. Raytracing radio propagations of networks in the city of London using SionnaRT on a 3D digital twin, helping improve the Emergency Services Network (ESN) of the UK. Utilised Nemotron-3-Super and CuOpt to determine the fastest and most efficient way to restoring services in London in case of downed signals. | Python, NIM, NextJS | [Repo](https://github.com/Harrishayy/NeMo-Ray) |
| **spatiality_v2** | Reconstructs 3D scenes from video using a Flash-VGGT backbone paired with a multi-stage segmentation pipeline for clean, properly annotated geometry. | Python, PyTorch, VGGT | [Repo](https://github.com/Harrishayy/spatiality_v2) |
| **Innovation Lab Twin** | Dense 3D digital twin of the UCL robotics lab in Open3D (RGBD registration, pose-graph optimisation, TSDF integration), used as a ground-truth benchmark across 30+ student perception projects. | Open3D, Python | _Private_ |
| **spatiality** | Lifts 2D photos into 3D meshes using a standard VGGT reconstruction backbone combined with SAM 3 segmentation. | TypeScript, Python, VGGT, SAM 3 | [Repo](https://github.com/Harrishayy/spatiality) |
| **skillforge** | Interactive, segmentation-based annotation tool that speeds up data labelling for blue-collar and industrial workflows. | TypeScript | [Repo](https://github.com/Harrishayy/skillforge) |

**Skills:** 3D reconstruction · Segmentation · Monocular/stereo depth · Point clouds · OpenCV

</details>

---

<h2 id="-ai-research">🧠 AI Research</h2>

<details open>
<summary><b>Publications & research</b></summary>
<a id="ai-open"></a>

<br />

_Adaptive multi-agent systems and learning-science-grounded evaluation of LLMs._

| Work | Venue / Affiliation | Links |
|---|---|---|
| **ASpec** — Automated Stateful Specialization for Adaptive Agent Systems | ICLR 2026 | [Paper](https://openreview.net/pdf?id=UESTP6dR1K) · [Code](https://github.com/myanvoos/ASpec) |
| **PEBBLE** — A Pedagogical and SRL-Aware Benchmark for Evaluating LLM Tutors | NeurIPS 2025 Workshop | [Paper](https://openreview.net/pdf?id=ffvNvoJVgE) |
| **Cereberus** — Agent security enforced at the kernel level | Open source @ Cisco | [Code](https://github.com/Harrishayy/Cereberus) |

**Skills:** Multi-agent systems · LLM evaluation · Benchmark design · Agent security

</details>

---

<h2 id="-machine-learning">🧪 Machine Learning</h2>

<details>
<summary><b>Reinforcement learning, deep learning, and experiments</b></summary>
<a id="ml-open"></a>

<br />

_Coursework, competitions, and hands-on ML experiments outside the research track._

| Project | Description | Stack | Link |
|---|---|---|---|
| **Nemotron Reasoning Challenge** | 🥈 Silver Medal, 114th place in the [NVIDIA Nemotron Model Reasoning Challenge](https://www.kaggle.com/competitions/nvidia-nemotron-model-reasoning-challenge) (Kaggle). Built a corpus of verifier-checked, faithful derivations from deterministic per-category solvers and a cryptarithm DSL, then fine-tuned a rank-32 LoRA over Nemotron-3-Nano-30B, with synthetic augmentation and RFT self-distillation. | Python, PyTorch, LoRA | [Repo](https://github.com/MehulChourasia28/NVIDIA-NemotronKaggleChallenge) |
| **Gomoku RL** | AlphaZero-style agent for 9×9 Gomoku: PUCT Monte Carlo Tree Search guided by a dual-headed (policy + value) ResNet trained through self-play, with a Dueling Double DQN baseline. Passed 19/20 tactical benchmarks. | Python, PyTorch | [Repo](https://github.com/EdwinIsCoding/Gomoku_AI) |

**Skills:** Reinforcement learning · Self-play & MCTS · Deep RL · LoRA / SFT fine-tuning · PyTorch

</details>

---

<h2 id="-software--systems">💻 Software & Systems</h2>

<details>
<summary><b>Systems, full-stack, and applied engineering</b></summary>
<a id="software-open"></a>

<br />

_Shipped products and full-stack engineering._

| Project | Description | Stack | Link |
|---|---|---|---|
| **General Learning (YC F24)** | Exam-prep platform: built a Glicko-2 rating system, backend microservices, and two React Native mobile apps, plus reinforcement fine-tuning of models. | TypeScript, Python, React Native | [Site](https://revisiondojo.com) |
| **Ultras** | A football prediction market, a fresh take on fantasy leagues where users trade on real match outcomes. | TypeScript | [Site](https://theultras.vercel.app) |
| **uncookd** | Multi-agent teacher-student meeting session that helps students learn through an agentic whiteboard. Next.js frontend over a CrewAI multi-agent Python backend. 🏆 **1st place, AgentVerse Hackathon** (UCL · AWS · Anthropic · Cisco · EF). | TypeScript, Next.js, Python, CrewAI | [Repo](https://github.com/Harrishayy/uncookd) |
| **tiramisu** | Tells small businesses what to post by mining top-performing YouTube content in their niche and generating shot-by-shot storyboards ranked by outperformance over a channel's own average, not raw views. Next.js web + Expo mobile over a FastAPI backend, using Gemini, Nano Banana, and Veo for generation. | Python, FastAPI, Next.js, React Native | [Repo](https://github.com/Harrishayy/tiramisu) |

**Skills:** TypeScript · Python · React Native · Next.js · Microservices · Full-stack

</details>

---

<!-- ============================================================
     QUANT — commented out until there's something worth showing.
     Uncomment this block (and add the badge back to the tab bar:
       <a href="#-quant"><img src="https://img.shields.io/badge/Quant-d29922?style=for-the-badge" /></a>
     ) when ready. Candidates: imcprosperity4, Finanalyser.
============================================================

<h2 id="-quant">📈 Quant</h2>

<details>
<summary><b>Quantitative finance & systematic trading</b></summary>

<br />

_Signal research, backtesting, and market analysis._

| Project | Description | Stack | Link |
|---|---|---|---|
| **imcprosperity4** | IMC Prosperity algorithmic trading competition | TypeScript | [Repo](https://github.com/Harrishayy/imcprosperity4) |
| **Finanalyser** | High-level financial analyser for retail equity investors | TypeScript | [Repo](https://github.com/Harrishayy/Finanalyser) |

**Skills:** Time-series analysis · Backtesting · Portfolio optimization · Market microstructure

</details>

---
============================================================ -->

<p align="center"><sub>Open to roles in robotics, perception, and AI research.</sub></p>
