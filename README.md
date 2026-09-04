<div align="center">

# Prasangeet Dongre

### AI Systems · Software Engineering · Applied Research

Building intelligent software at the intersection of **LLMs, systems engineering, and scientific computing**.

<p>
  <a href="https://www.linkedin.com/in/prasangeetdongre01"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://leetcode.com/u/prasangeet_dongre/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=black" alt="LeetCode" /></a>
  <a href="https://github.com/prasangeet"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://github.com/Limbo-corps"><img src="https://img.shields.io/badge/Limbo%20Corps-Organization-8A2BE2?style=flat-square&logo=github&logoColor=white" alt="Limbo Corps" /></a>
</p>

</div>

---

## 👋 About

I’m a **B.Tech Chemical Engineering student at IIT Jodhpur with a Minor in Artificial Intelligence**, interested in building software that combines strong engineering fundamentals with modern AI.

My work spans several layers of the stack:

- **AI systems** — LLM orchestration, RAG, agents, memory, tool use, vision pipelines
- **Backend & distributed applications** — APIs, realtime systems, databases, caching, authentication
- **Systems programming** — C++, Rust, Linux, networking, native applications
- **Applied ML & scientific computing** — computer vision, deep learning, process modeling and reinforcement learning

I enjoy projects where the difficult part is not just calling a model, but designing the **system around it**: data flow, state, memory, reliability, observability, and the interface between software components.

Currently, I’m focused on **AI Engineering and SDE roles**, while continuing to explore systems programming and applied research.

---

## 🔬 Research

### IIT Hyderabad — SURE'26
**Research Intern · Global Optimization and Knowledge Unearthing Laboratory**

Worked on a scientific-document intelligence workflow for extracting structured information from research papers.

The pipeline combines:

`PDF / Document Parsing → Layout Detection → OCR → Relationship Extraction → Figure Understanding`

Technologies explored include **YOLO, Tesseract OCR, LaTeX OCR, vision-language models, Python, React, Vite, and Electron**.

A major focus was extracting quantitative information from scientific figures, particularly **temperature vs. conversion/selectivity curves**, while preserving the experimental conditions, catalysts, promoters, captions, and relationships needed for downstream retrieval and analysis.

---

## 🚀 Featured Work

### 🧠 ORION — Local-First AI Assistant
**Rust · Python · LangGraph · Neo4j · Qdrant · MCP**

A systems-oriented AI assistant designed around the idea that an assistant should be more than a chat interface.

**Architecture highlights**

- Rust terminal client for the interactive shell
- Python runtime for orchestration and AI workflows
- Async IPC over Unix sockets
- LangGraph-based agent coordination
- Neo4j for structured / relational memory
- Qdrant for semantic retrieval
- MCP-based tool integration
- Modular services for memory, reasoning, execution, and observability

> The goal is to build an assistant whose **state, memory, tools, and reasoning are explicit system components** rather than hidden behind a single model call.

---

### 🔎 Research Paper Data Extractor
**Python · YOLO · OCR · Vision Models · React · Vite · Electron**

A desktop research tool built during my IIT Hyderabad internship to turn unstructured scientific PDFs into structured, machine-readable research data.

The system focuses on scientific figures and their surrounding context, including:

- figure / chart detection
- layout-region extraction
- OCR and mathematical text extraction
- figure-caption relationships
- vision-model interpretation
- extraction of plotted data and experimental conditions
- structured outputs suitable for search and RAG pipelines

---

### 🗄️ LimboDB — Database Engine in C++
**C++ · CMake · SQL · Storage Engines**

A lightweight SQL database engine built from scratch as a systems project.

Implemented components include:

- SQL parsing and execution
- record management
- indexing
- table catalogs
- disk-based storage
- memory management
- debugging infrastructure

This project is part of my interest in understanding software **below the application layer** — how databases, storage, and execution engines actually work.

---

### ♟️ Chess — Native C++ / Qt Application
**C++17 · Qt 6 · CMake · QGraphicsView**

A desktop chess application with a native GUI and a complete rules engine.

Supports:

- legal move validation
- check / checkmate
- stalemate
- castling
- en passant
- pawn promotion
- move highlighting
- scalable board rendering

A useful combination of **object-oriented design, graphics programming, game-state modeling, and rule validation**.

---

### 🎛️ TD3 PID Tuner
**Python · PyTorch · Reinforcement Learning · Process Control**

An applied RL project exploring automatic PID tuning for nonlinear process systems.

The project reproduces and extends a TD3-based controller-tuning approach with techniques such as:

- modified reward design using control-rate penalties
- prioritized experience replay
- curriculum learning
- evaluation across multiple plant models
- comparison against classical control behavior

It sits directly at the intersection of my Chemical Engineering and AI background: **dynamic systems + control theory + reinforcement learning**.

---

### 🌐 NeutronVPN
**Django · PostgreSQL · React · Electron · WireGuard · Paramiko**

A full-stack VPN management system with a desktop client and remote server management.

The project brings together:

`WireGuard ↔ Django REST API ↔ PostgreSQL ↔ Electron/React Client ↔ SSH Infrastructure`

with features for peer management, VPN configuration, connection statistics, and remote server administration.

---

### 📄 ARAA — Autonomous Research & Action Agent
**Python · LangChain · Local LLMs · Ollama · RAG**

An early exploration into autonomous research workflows: taking a high-level objective, decomposing it into tasks, searching for information, and synthesizing results through an agentic workflow.

ARAA became one of the foundations for my later interest in **agent orchestration, tool use, memory, and research automation**.

---

## 🧰 Engineering Toolbox

### Languages
<p>
  <img src="https://skillicons.dev/icons?i=python,cpp,rust,typescript,go,java,bash" alt="Languages" />
</p>

### AI / ML
<p>
  <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,opencv" alt="AI and ML" />
</p>

`LangChain` · `LangGraph` · `RAG` · `Computer Vision` · `OCR` · `Reinforcement Learning` · `LLM Agents` · `Ollama`

### Web & Backend
<p>
  <img src="https://skillicons.dev/icons?i=nextjs,react,tailwind,django,nestjs,nodejs,express,fastapi" alt="Web and Backend" />
</p>

### Data & Infrastructure
<p>
  <img src="https://skillicons.dev/icons?i=postgresql,mongodb,redis,docker,linux,git,github,nginx" alt="Data and Infrastructure" />
</p>

`Neo4j` · `Qdrant` · `REST APIs` · `WebSockets` · `Unix Sockets` · `CMake` · `WireGuard`

### Desktop / Native
<p>
  <img src="https://skillicons.dev/icons?i=qt,cpp,rust,linux,electron" alt="Desktop and Native" />
</p>

---

## 🧭 What I Like Building

```text
                ┌─────────────────────────┐
                │      AI / Reasoning     │
                │  LLMs · Agents · RAG    │
                └────────────┬────────────┘
                             │
                ┌────────────▼────────────┐
                │      Application        │
                │ APIs · Realtime · UX    │
                └────────────┬────────────┘
                             │
                ┌────────────▼────────────┐
                │        Systems          │
                │ C++ · Rust · Linux      │
                └────────────┬────────────┘
                             │
                ┌────────────▼────────────┐
                │   Scientific Domains    │
                │ Process · ML · Research │
                └─────────────────────────┘
```

The common thread across these projects is **turning ideas into working systems** — not just prototypes, but architectures that can be reasoned about, extended, and operated.

---

## 🧩 Limbo Corps

<div align="center">
<a href="https://github.com/Limbo-corps">
  <img src="https://img.shields.io/badge/LIMBO%20CORPS-Engineering%20%26%20AI-111827?style=for-the-badge&logo=github&logoColor=white" alt="Limbo Corps" />
</a>
<br />
A space for building **AI systems, developer tools, infrastructure, and experimental software**.
</div>

---

## 🧠 LeetCode

<div align="center">
<a href="https://leetcode.com/u/prasangeet_dongre/">
  <img src="https://leetcard.jacoblin.cool/prasangeet_dongre?theme=dark&font=baloo&ext=heatmap" alt="Prasangeet's LeetCode Stats" />
</a>
</div>

---

## 📊 GitHub

<div align="center">

<a href="https://github.com/prasangeet">
  <img src="https://ghstats.dev/api/card?username=prasangeet&theme=midnight&size=compact&hide_border=true&show_icons=true" alt="Prasangeet's GitHub Stats" />
</a>

</div>

---

## 👾 Contribution Pac-Man

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/prasangeet/prasangeet/output/pacman-contribution-graph-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/prasangeet/prasangeet/output/pacman-contribution-graph.svg">
  <img src="https://raw.githubusercontent.com/prasangeet/prasangeet/output/pacman-contribution-graph.svg" alt="Pac-Man contribution graph" width="100%">
</picture>
</div>

> Automatically regenerated by the repository's `pacman.yml` workflow.

---

## 🧩 Beyond the Projects

I also maintain smaller projects and experiments across:

`DSA` · `Computer Vision` · `NLP` · `Web Applications` · `Qt` · `Networking` · `Control Systems` · `Deep Learning` · `Developer Tooling`

Some of these are deliberately small — they are experiments for learning a technology, testing an idea, or understanding an implementation from first principles.

---

## 📫 Contact

I’m interested in **AI engineering, software engineering, systems, developer infrastructure, and applied research**.

<p>
  <a href="https://www.linkedin.com/in/prasangeetdongre01">LinkedIn</a> ·
  <a href="https://leetcode.com/u/prasangeet_dongre/">LeetCode</a> ·
  <a href="https://github.com/prasangeet">GitHub</a> ·
  <a href="https://github.com/Limbo-corps">Limbo Corps</a>
</p>

---

<div align="center">

### Build systems. Understand the fundamentals. Then make them intelligent.

</div>
