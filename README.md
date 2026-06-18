# 👋 Hello, I'm Nitin Singh

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1200&color=2196F3&center=true&vCenter=true&width=560&lines=AI+Engineer+%7C+2+Years+Experience;%F0%9F%8E%AF+Machine+Learning+Engineer;Multi-Agent+%26+LLM+Systems+Builder;Generative+AI+%26+Diffusion+Models;Full-Stack+AI+Product+Developer;Open+to+AI+%2F+ML+Engineer+Roles" alt="Typing SVG" />
</div>

---

BTech in Artificial Intelligence & Data Science · 2 years as an AI Engineer. I build production-ready systems: multi-agent LLM pipelines, generative AI (LoRA training, diffusion, video generation), and full-stack AI products. Based in India.

---

## What I Build

**🤖 Agentic & LLM Systems** — Multi-agent pipelines (LangGraph), RAG with structured evidence passing, fine-tuning with SFT + GRPO on Qwen and Llama models

**🎨 Generative AI & Vision** — LoRA training pipelines (Kohya_ss → SD / FLUX.1), text-to-video (Wan2.2), computer vision (CLIP · RetinaFace · YOLOv5)

**🏗️ Full-Stack AI Products** — FastAPI + Next.js + PostgreSQL, deployed apps on Render, deterministic safety layers over LLM outputs

**📊 Data & Financial ML** — Time series forecasting, crypto/retail analytics on Snowflake, clustering and EDA pipelines

---

## Tech Stack

### Languages
<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="40" alt="Python" title="Python" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" alt="JavaScript" title="JavaScript" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="40" alt="TypeScript" title="TypeScript" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" height="40" alt="C++" title="C++" />
</div>

### ML / DL
<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" height="40" alt="PyTorch" title="PyTorch" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tensorflow/tensorflow-original.svg" height="40" alt="TensorFlow" title="TensorFlow" />
  <img width="12" />
  <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" height="40" alt="Scikit-learn" title="Scikit-learn" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" height="40" alt="NumPy" title="NumPy" />
  <img width="12" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pandas/pandas-original.svg" height="40" alt="Pandas" title="Pandas" />
</div>

### Web / Backend
<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" height="40" alt="FastAPI" title="FastAPI" />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=flask" height="40" alt="Flask" title="Flask" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" height="40" alt="Next.js" title="Next.js" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" height="40" alt="React" title="React" />
</div>

### Databases & Cloud
<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" height="40" alt="PostgreSQL" title="PostgreSQL" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" height="40" alt="Docker" title="Docker" />
  <img width="12" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" height="40" alt="AWS" title="AWS" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/googlecloud/googlecloud-original.svg" height="40" alt="GCP" title="GCP" />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" height="40" alt="Git" title="Git" />
</div>

### LLMs & Agent Tooling
`LangGraph` `OpenAI API` `Anthropic API` `Gemini API` `DeepSeek` `Llama 3.x` `Qwen` `Hugging Face` `Pathway`

### Generative AI
`Stable Diffusion` `FLUX.1-dev` `Wan2.2` `LoRA · Kohya_ss` `CatVTON` `CLIP` `AMD ROCm`

---

## Projects

### 🤖 Agentic & LLM Systems

| Project | What it does | Stack |
|---|---|---|
| [**Multi-Agent RAG**](https://github.com/NI3singh/IIT-Kharagpur-Data-Science-Hackathon-Submission) | Three-agent literary consistency pipeline: Llama 3.3-70B decomposes claims into atomic facts, Qwen3-Embedding-8B retrieves evidence from a Pathway vector store, DeepSeek-R1 judges contradictions. Structured Python object passing preserves similarity scores and claim provenance across agents. 98.3% success rate on 60 test cases. *IIT Kharagpur Hackathon* | Llama 3.3, DeepSeek-R1, Qwen3, Pathway |
| [**BTC-Forecaster**](https://github.com/NI3singh/BTC-forecaster) | Fork of TradingAgents repurposed for intraday BTC forecasting. Multi-agent pipeline: technical + news + sentiment analysts → bull/bear debate → trader → risk → final forecast. Emits 1h/4h price predictions with a self-scoring track record logged against realized prices. | LangGraph, Python, Yahoo Finance |
| [**AMD AIPL**](https://github.com/NI3singh/AMD-AI-Premiere-League-Hackathon) | Fine-tuned Qwen3-4B using SFT + GRPO for a 1v1 Q-agent vs A-agent tournament. Custom reward function; self-play loop where question and answer models iteratively improve each other. *AMD Hackathon at IIT Bombay* | Qwen3-4B, PyTorch, GRPO |

### 🎨 Generative AI & Vision

| Project | What it does | Stack |
|---|---|---|
| [**AI-Avtaar**](https://github.com/NI3singh/AI-Avtaar) | End-to-end character pipeline: upload photos → automated LoRA training → SDXL image generation → virtual clothing try-on. Four isolated Python environments orchestrated through a single Streamlit UI. | Kohya_ss, FLUX.1 / A1111, CatVTON, Streamlit |
| [**AI Video Creator**](https://github.com/NI3singh/ARON) | Three-stage generation pipeline: Llama 3.1-8B writes a storyboard → FLUX.1-dev renders per-scene images → Wan2.2-T2V animates them. Gradio tabbed interface. Tested on AMD MI300X with ROCm. | Llama 3.1, FLUX.1-dev, Wan2.2, Gradio, ROCm |
| [**Gender Detection API**](https://github.com/NI3singh/Gender-detection) | FastAPI endpoint using RetinaFace for face detection and CLIP for gender classification. Handles multiple faces, non-human images, and mismatches as distinct typed error responses. | FastAPI, CLIP, RetinaFace, PyTorch |

### 🏗️ Full-Stack AI Products

| Project | What it does | Stack |
|---|---|---|
| [**ResumeTeX**](https://github.com/NI3singh/AI-Resume-Updater) | Browser-based LaTeX resume builder: manual form, AI import from PDF/DOCX (extract → parse → verify pipeline), AI tailoring to job descriptions. Deterministic anti-fabrication guard restores all original facts post-AI. Deployed on Render. | Next.js 14, FastAPI, PostgreSQL, Nebius LLM |
| [**Stock News Summarizer**](https://github.com/NI3singh/stock-news-summarizer) | Scrapes TradingView, Finviz, and Polygon; Gemini Pro selects top articles and writes <500-word summaries with 7-day "what changed today" diffs. SQLite history, daily refresh at 8 AM IST. Free-tier deployed on Render. | Flask, Gemini Pro, SQLite |
| [**Student Performance Analysis**](https://github.com/NI3singh/Student-Performance-Analysis) | CSV upload → K-Means / Agglomerative clustering → per-student performance dashboard with trend charts, subject breakdowns, class comparisons, and Excel export. | React, Flask, Scikit-learn, MUI |

### 🛠️ Tooling & Extensions

| Project | What it does | Stack |
|---|---|---|
| [**Auto-Doc**](https://marketplace.visualstudio.com/items?itemName=ni3dev.auto-document) [![VS Code](https://img.shields.io/visual-studio-marketplace/v/ni3dev.auto-document?color=green&label=v)](https://marketplace.visualstudio.com/items?itemName=ni3dev.auto-document) | VS Code extension that logs every file save as a timestamped Markdown diff with line numbers. Published on VS Code Marketplace (v1.0.0). | TypeScript, VS Code API |
| [**Support Finder**](https://github.com/NI3singh/support-finder-extension) | MV3 Chrome extension with a four-layer deterministic pipeline: DOM scan → same-domain path probing → schema.org extraction → confidence scoring. Returns ranked support contacts with explanations. No AI; no fabrication. | TypeScript, React, MV3 |
| [**android-compose-design**](https://github.com/NI3singh/android-compose-design-skill) | Agent skill for Claude Code. Guides AI to produce distinctive Jetpack Compose UI — intentional color, type hierarchy, shape language, and motion — instead of Material 3 defaults. | Jetpack Compose, Kotlin |

### 📊 Data & Financial Analysis

| Project | What it does | Stack |
|---|---|---|
| [**Solana Price Analysis**](https://github.com/NI3singh/Solana-Data-Analysis) | OHLCV data (2021–2024), 44-column feature set via the `ta` library, ML price prediction model, and live Binance price dashboard. | Python, Streamlit, Binance API |
| [**Rossmann Retail Analysis**](https://github.com/NI3singh/Snowflake-Project) | 1M+ row sales dataset: cleaning, feature engineering, EDA on Snowflake. Quantified 81.5% sales uplift from promotional periods. | Snowflake, SQL |
| [**Time Series Forecasting**](https://github.com/NI3singh/Time-Series-Model-Performance-Comparison) | Four-framework side-by-side: LSTM on temperature data (TF), airline passengers (PyTorch), ACGL stock SARIMAX (Statsmodels), MSFT stock LSTM (Keras). Flask web interface for the SARIMAX model. | TF, PyTorch, Statsmodels, Keras |

---

## GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=NI3singh&show_icons=true&theme=radical&hide_border=true&count_private=true" alt="GitHub Stats" width="48%" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=NI3singh&layout=compact&theme=radical&hide_border=true" alt="Top Languages" width="48%" />
</div>

---

## Connect

<div align="center">
  <a href="https://www.linkedin.com/in/nitinsinghr/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="https://x.com/NitinSingh333?t=p3JinE7cpVu7sq4GUjYebw&s=09" target="_blank">
    <img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X" />
  </a>
  <a href="https://youtube.com/@NitinSinghCreation?si=ipFZhXw8rbZ8Epyq" target="_blank">
    <img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube" />
  </a>
  <a href="https://www.instagram.com/ni.3.singh?igsh=eGlrNTJmajd2aDRk" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" />
  </a>
  <a href="https://discord.com/channels/780066247601291285/@home" target="_blank">
    <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" />
  </a>
</div>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=NI3singh&label=Profile%20views&color=0e75b6&style=flat" alt="Profile Views" />
</div>
