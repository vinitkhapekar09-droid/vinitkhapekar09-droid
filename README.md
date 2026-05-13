## Hi there 👋

<!--
**vinitkhapekar09-droid/vinitkhapekar09-droid** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<div align="center">

# Hey, I'm Vinit Khapekar 👋

**AI/ML Engineer · Full-Stack Developer · IoT Builder**

*Final-year B.Tech (Electronics & Computer Science) @ RCOEM, Nagpur*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-vinit--khapekar-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/vinit-khapekar)
[![Email](https://img.shields.io/badge/Email-vinitkhapekar09%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:vinitkhapekar09@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-vinitkhapekar09--droid-181717?style=flat&logo=github&logoColor=white)](https://github.com/vinitkhapekar09-droid)

</div>

---

## About Me

I build end-to-end AI products — from raw datasets and model fine-tuning to deployed, production-ready systems. My work spans LLM pipelines, RAG architectures, IoT platforms, and multi-agent systems.

Currently wrapping up my B.Tech while actively shipping projects and looking for **AI/ML Engineering roles** where I can keep building things that matter.

- 🧠 Research Intern in AI text detection — achieved **99.44% accuracy** with a hybrid BERT + stylometric model on 114K+ samples
- 🤖 Built multi-agent systems from scratch using Groq's free tier (no LangChain, pure Python)
- 📡 Developing an AIoT platform for pharma cold-chain monitoring with an LLM-powered query interface
- 🎯 Currently exploring: LLM fine-tuning (LoRA/QLoRA), agentic AI patterns, and scaling solo-dev workflows with AI

---

## 🛠️ Tech Stack

**AI / ML**
`LLMs` `RAG` `BERT Fine-tuning` `LoRA / QLoRA` `Prompt Engineering` `NLP` `MLflow` `Scikit-learn` `TensorFlow`

**Fine-tuning**
`Unsloth` `PEFT` `TRL (SFTTrainer)` `bitsandbytes (4-bit)` `accelerate`

**LLM APIs**
`Groq (LLaMA 3.1 / Qwen 2.5)` `Gemini API` `OpenAI-compatible clients`

**Backend**
`FastAPI` `Flask` `Pydantic` `SQLAlchemy` `Alembic` `Celery` `SlowAPI`

**Frontend**
`React` `Vite` `Axios`

**Databases**
`PostgreSQL` `pgvector` `Redis` `Firebase`

**Auth / Security**
`PyJWT` `python-jose` `passlib (Argon2)` `API key hashing`

**DevOps & Cloud**
`Docker` `Docker Compose` `Git` `Render` `Vercel` `DigitalOcean`

**Languages**
`Python` `SQL` `Java` `JavaScript`

**Other**
`ESP32 (IoT)` `REST APIs` `Resend`

---

## 🚀 Featured Projects

### 🔍 AI Intelligence Hub
> RAG system over live AI research — arXiv + news, daily ingested, embedded, and queryable

- Daily ingestion pipeline: arXiv papers + news → chunking → Gemini embeddings (768-dim) → pgvector store
- Multi-step LLM pipeline: query sanitization → follow-up enrichment → retrieval rewriting → top-k retrieval → grounded answer via Groq LLaMA 3.1 8B
- MLflow run tracking; deployed on DigitalOcean
- **Stack:** FastAPI · PostgreSQL · pgvector · Gemini API · Groq · Docker · DigitalOcean

---

### 📡 AIoT Monitoring Platform
> Full-stack IoT platform with real-time sensor monitoring and an LLM-powered natural language query interface

- FastAPI backend + React/Vite frontend; real-time ingestion and visualization of sensor data
- Dual auth: JWT for web users, hashed API key auth for IoT devices
- 5-table schema with SQLAlchemy ORM + Alembic migrations
- LLM chatbot for natural language queries over sensor data
- **Stack:** FastAPI · React · Neon PostgreSQL · JWT · Docker · Vercel · Render · ESP32

---

### 🧮 Qwen2-VL Fine-tuning: Math Equation → LaTeX
> Multimodal VLM fine-tuned to convert images of math equations into LaTeX markup

- Fine-tuned Qwen2-VL-7B-Instruct on the `unsloth/Latex_OCR` dataset
- 4-bit quantization + LoRA (r=16) via Unsloth FastVisionModel; fine-tuned vision, language, attention, and MLP layers
- Training loss: **1.34 → 0.08** over 30 steps with SFTTrainer + AdamW 8-bit + cosine LR scheduler
- **Stack:** Python · Unsloth · PEFT · TRL · bitsandbytes · Google Colab

---

### 🤖 AutoREADME Generator
> Multi-agent system that autonomously scans a project and generates a polished README

- 5-agent pipeline: Scanner → File Summarizer → Project Analyzer → README Writer → Quality Checker
- Pure Python, no LangChain — built on Groq API with OpenAI-compatible endpoints
- **Stack:** Python · Groq API · Multi-Agent Architecture

---

### 🧬 AI Text Detection — Research (RCOEM, 2026)
> Hybrid Stylometric-BERT framework for detecting AI-generated text

- Curated and merged 3 public datasets → 114K+ samples; prevented data leakage via prompt-based stratification
- Baseline: TF-IDF + Logistic Regression → **94.04% accuracy**
- BERT fine-tuned classifier → **98.77% accuracy · 0.9868 F1 · 0.9995 ROC-AUC**
- **Stack:** Python · BERT · Scikit-learn · NLP

---

## 📊 GitHub Stats

<div align="center">

![Vinit's GitHub Stats](https://github-readme-stats.vercel.app/api?username=vinitkhapekar09-droid&show_icons=true&theme=default&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=vinitkhapekar09-droid&layout=compact&theme=default&hide_border=true)

</div>

---

## 🎓 Education

**B.Tech — Electronics and Computer Science**
RCOEM, Nagpur · 2022–2026 · CGPA: **8.0**

---

## 📫 Let's Connect

If you're building something in AI, IoT, or just want to talk about agentic systems — reach out.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/vinit-khapekar)
[![Email](https://img.shields.io/badge/Email-Say%20Hi-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:vinitkhapekar09@gmail.com)

</div>
