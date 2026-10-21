<h1 align="center">Hi, I'm Abdelhak 👋</h1>

<p align="center">
  <b>AI Engineering student · LLMs · RAG · AI Agents · MCP</b><br/>
  I build retrieval and agentic systems — and I measure whether they actually work.
</p>

<p align="center">
  <a href="mailto:abdelhakemabdelhak@gmail.com"><img src="https://img.shields.io/badge/Email-abdelhakemabdelhak%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white" /></a>
  <a href="https://huggingface.co/abdelhak-abdelhakem"><img src="https://img.shields.io/badge/Hugging%20Face-abdelhak--abdelhakem-FFD21E?style=flat&logo=huggingface&logoColor=black" /></a>
  
</p>

---

### 🧭 About me

- 🎓 5th-year Computer Science Engineering student, **AI specialty** — Université Djillali Liabès, Sidi Bel Abbès 🇩🇿
- 💼 6-month internship at **Groupe Hasnaoui** (Feb–Jun 2026), where I built a production multilingual RAG pipeline
- 🔬 Member of **AiQC** (AI & Quantum Community) — studying **Mamba / State Space Models vs Transformers**, 🥈 2nd place at the AiQC Mini-Hackathon (Apr 2026)
- 🌍 Arabic (native) · English (B2) · French (B1 → B2)

---

### 🚀 Featured projects

#### 🏢 Hasnaoui Bot — Enterprise multilingual RAG
Production chatbot over internal company documents in **Arabic, French and English**.
- Hybrid retrieval: **BM25 + ChromaDB + Cohere reranking**
- FastAPI backend · React/Tailwind frontend · LangSmith observability with per-query cost tracking
- RAGAS evaluation: **Context Precision 0.892 · Context Recall 0.812** · ~$0.0008 / query

#### 🛰️ JobRadar AI — Agentic job-market monitor
A **LangGraph** multi-node agent that scrapes, ranks and analyzes job offers, then drafts tailored cover letters.
- Hybrid RAG over **153 scraped offers** · Mistral API
- Served as the base for my fine-tuning project below

#### 🧪 mistral-cover-letter-fr — QLoRA fine-tuning
Fine-tuned **Mistral-7B-Instruct** on French job-description → cover-letter pairs.
- QLoRA / PEFT on a T4 · custom 60-pair dataset built from real postings
- Evaluated against the base model (BERTScore + manual review) · published on 🤗 Hugging Face
- Plugged back into JobRadar AI as a local LLM backend

#### 🎓 UniBot DZ — Student RAG assistant
Personal RAG project for Algerian university information.
- **Answer Relevancy 0.921**, +7.4% gained through A/B testing of retrieval/prompt variants

---

### 🔭 What I'm working on now

- **Tool-Use Optimization for agentic LLMs** — detecting when an agent *shouldn't* call a tool, and routing to cheaper models when it doesn't need to. Agents waste a lot of money on unnecessary calls; observability tools show it, few things fix it.
- **DZ Campus Agent** — a multi-tool agent that helps students navigate studying in France.

---

### 🛠️ Tech stack

**LLM & Agents**
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat&logo=langchain&logoColor=white)
![Mistral](https://img.shields.io/badge/Mistral-FA520F?style=flat&logo=mistralai&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![Cohere](https://img.shields.io/badge/Cohere-39594D?style=flat)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat)

**Retrieval & Evaluation**
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F61?style=flat)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat&logo=meta&logoColor=white)
![BM25](https://img.shields.io/badge/BM25-555555?style=flat)
![RAGAS](https://img.shields.io/badge/RAGAS-6A5ACD?style=flat)
![LangSmith](https://img.shields.io/badge/LangSmith-1C3C3C?style=flat&logo=langchain&logoColor=white)

**Fine-tuning & ML**
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat&logo=huggingface&logoColor=black)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![PEFT](https://img.shields.io/badge/PEFT%20%2F%20QLoRA-FFD21E?style=flat&logo=huggingface&logoColor=black)

**Backend, Frontend & Ops**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat&logo=microsoftsqlserver&logoColor=white)

---

### 📊 GitHub stats

<p align="center">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=abdelhak-abdelhakem&show_icons=true&hide_border=true&theme=transparent" />
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=abdelhak-abdelhakem&layout=compact&hide_border=true&theme=transparent" />
</p>

---

<p align="center"><i>"If you can't evaluate it, you haven't built it yet."</i></p>
