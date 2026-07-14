<h1 align="center">Aditya Guha</h1>
<h3 align="center">AI Engineer | Machine Learning | Robotics | Local LLM Infrastructure</h3>

<p align="center">
<a href="https://adityaguha.tech"><img src="https://img.shields.io/badge/Portfolio-adityaguha.tech-00C853?style=for-the-badge"/></a>
<a href="https://www.linkedin.com/in/adityaguha1/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin"/></a>
<a href="https://www.instagram.com/adityaguha_/"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/></a>
<a href="https://www.youtube.com/@adityaguha"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white"/></a>
</p>

<p align="center">
📫 <a href="mailto:adityaaguha@gmail.com">adityaaguha@gmail.com</a> &nbsp;|&nbsp; 📞 +91 7304748055
</p>

---

### Currently

- Building the scanner module for **MacBenchForge**, a macOS Apple Silicon GPU benchmarking tool
- Final-year B.Tech CSE (AI & ML), graduating 2026
- Job hunting for full-time AI Engineer / Applied AI Developer roles (Pune, remote)

---

## About

Final-year AI & ML engineer with hands-on research at DRDO on reinforcement learning for quadruped robotics, and a track record of shipping local-first AI systems end to end, agentic assistants, LLM inference servers, and custom benchmarking tools built in C++ and Python. I care about privacy-focused, self-hosted AI infrastructure and getting real performance out of consumer hardware. Outside of core dev work, I run a freelance computer consultancy and create AI/dev-focused content for Instagram and YouTube.

## Experience

**Defence Research and Development Organisation (DRDO), Pune**
*Robotics & Machine Learning Research Intern*

**Project:** Reinforcement Learning Based Quadruped Handstand and Footstand using MuJoCo and JAX

- Developed reinforcement learning control strategies for quadruped robotic balance and posture stabilization
- Worked with the MuJoCo physics simulation environment for robotics modeling
- Implemented and analyzed control policies using JAX-based reinforcement learning, including PPO with curriculum learning
- Contributed to simulation-driven learning and control optimization research

**Freelance Computer Consultancy**
- Independent consulting on hardware builds, benchmarking, and system setup for individual clients

## Education

**B.Tech, Computer Science Engineering (AI & ML)**
Bharati Vidyapeeth Deemed University, DET, Navi Mumbai — CGPA ~8.5, Class of 2026

## Selected Projects

### [NexusAgent](https://github.com/AdityaGuhaa/NexusAgent)
Local-first ReAct agentic AI assistant. FastAPI backend with SSE streaming, llama.cpp inference (Qwen3-8B), Serper.dev web search, and a Perplexity-style vanilla JS frontend.

### [PixelStudio Pro](https://github.com/AdityaGuhaa/Pixel-Studio-Pro)
Local image generation stack: FastAPI + llama.cpp (Gemma, Metal GPU) + ComfyUI running headless on a MacBook Pro M1 Pro, with one-command install and launch scripts.

### BenchForge
Open-source C++ GPU/CPU benchmarking tool for Windows, built and tuned against an RTX 4050. *(add repo link)*

### MacBenchForge
Companion benchmarking tool for macOS Apple Silicon, using IOKit for GPU detection. *(add repo link)*

### SwachNet
Automated road-littering detection and e-Challan system using YOLOv8, PaddleOCR, and FastAPI. In progress. *(add repo link)*

### Anti-Cheat Examination Engine
Final-year project: multimodal AI proctoring system combining MediaPipe face/gaze tracking, YOLOv8, and CNN-based audio analysis for exam integrity monitoring. *(add repo link)*

<details>
<summary><strong>More Projects</strong></summary>

<br>

**NeuroCourier / GuhaGPT** — Multimodal AI agent on Telegram and Discord, Ollama backend, supporting text and image input for privacy-focused interaction. *(add repo link)*

**MeetingMind** — Local-first meeting transcription and RAG system: pyannote diarization, faster-whisper, ChromaDB, Ollama, FastAPI + WebSocket. *(add repo link)*

**VisionSense** — Real-time scene description combining YOLOv8 object detection with Qwen2.5-VL-3B. *(add repo link)*

**NutriLens** — FastAPI + Gemini Vision Telegram bot for food label analysis. *(add repo link)*

**CortexCLI** — Textual-based multi-provider chat CLI, with a planned agentic-tool-calling upgrade (GuhaCLI). *(add repo link)*

**n8n Bank Statement Analyser** — Local workflow: PDF bank statements parsed and analyzed by AI, results delivered via Telegram, containerized with Docker.

**YOLOv8 Vehicle Detection** — Custom-trained 6-class vehicle detection model built on a Roboflow dataset. *(add repo link)*

**MiniZIP++** — Custom C++ archiver with a Huffman coding compression layer. *(add repo link)*

**Local LLM Server** — FastAPI backend serving locally hosted LLMs via structured APIs, used across several of the projects above. *(add repo link)*

**Encrypted NAS** — Fully encrypted, self-hosted network-attached storage with LUKS + Samba, multi-user access across platforms.

**TripMind** — FastAPI + React + Gemini 2.5 Flash travel planner MVP. *(add repo link)*

**BhashaMitra** — Gamified Indian language learning platform, built for a hackathon. *(add repo link)*

**Celestique** — Salon platform startup concept.

**IVA** — Donor-NGO bridge startup concept.

</details>

## Hardware & Infrastructure

I run and benchmark a small fleet of machines, and treat hardware tuning as seriously as the software on top of it:

- **Lenovo LOQ (RTX 4050)** — Fedora 44 with a full CUDA + llama.cpp rebuild, ~103 tok/s on Gemma 4 E2B
- **MacBook Pro M1 Pro (14", 16GB)** — Metal-accelerated inference benchmarking, ComfyUI, PixelStudio Pro host
- **ThinkCentre M91p** — Repurposed as an OpenMediaVault NAS (Debian 13), SMB shares, CPU-only llama.cpp benchmarking on Sandy Bridge
- **ASUS Vivobook OLED 15 (Ryzen 5 7520U)** — Cross-platform llama.cpp benchmarking (Vulkan/CPU)

All machines are tied together over **Tailscale** for remote SSH access, and I regularly run cross-device llama.cpp benchmarks comparing CUDA, Metal, and CPU-only inference paths.

## Technical Skills

**Languages:** Python, C++, JavaScript

**AI / ML:** PyTorch, OpenCV, YOLO, MediaPipe, Reinforcement Learning (PPO, Curriculum RL)

**Robotics & Simulation:** MuJoCo, JAX, Gymnasium

**LLM Infrastructure:** llama.cpp, Ollama, ComfyUI, GPU inference (CUDA, Metal, Vulkan), FastAPI, SSE streaming, RAG (ChromaDB)

**Computer Vision:** YOLOv8, MediaPipe, PaddleOCR, Qwen2.5-VL

**Systems:** Linux (Fedora, Debian, Ubuntu), self-hosted NAS, Tailscale, Docker, computer architecture and hardware benchmarking

## Content Creation

I post AI and developer-focused content on [Instagram](https://www.instagram.com/adityaguha_/) and [YouTube](https://www.youtube.com/@adityaguha) under **@adityaguha_**, covering local LLM builds, benchmarking, and practical AI engineering.

## Leadership & Community

- **GDSC Chapter Lead** (2023-24)
- **PR Executive**, BVDU DET
- **Campus Executive**, GeeksforGeeks

## Latest Video

[![Watch the video](https://img.youtube.com/vi/OOZIgZx5NrE/maxresdefault.jpg)](https://www.youtube.com/watch?v=OOZIgZx5NrE)

---

<p align="center">
📫 <a href="mailto:adityaaguha@gmail.com">adityaaguha@gmail.com</a> &nbsp;|&nbsp; 📞 +91 7304748055 &nbsp;|&nbsp; <a href="https://adityaguha.tech">adityaguha.tech</a>
</p>
