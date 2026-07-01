<div align="center">

# Dina Usman

### Full Stack Developer · Python · Django · FastAPI · React · AI/RAG Systems

CSE Graduate (KTU, 2026) · 3 production-deployed platforms · Building at the intersection of backend engineering and GenAI

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/dina-usman888)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dinausman2001@gmail.com)
[![Portfolio](https://img.shields.io/badge/Live_Projects-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://github.com/dinamain)

</div>

---

## What I build

I don't just write code — I build systems that work in production.

Over the last year I've solo-built and deployed three full-stack platforms: a real-time messaging system, an AI-powered event platform, and a RAG document Q&A system. I own every layer — backend architecture, REST APIs, React frontends, PostgreSQL schema design, Docker containerisation, and CI/CD pipelines.

A few things that happened along the way:
- Found and fixed a real scoping bug in Django REST Framework's `ScopedRateThrottle` by reading the framework source code
- Resolved an OOM crash on Render's free tier by switching from PyTorch-based embeddings (~2GB) to FastEmbed ONNX (~130MB)
- Debugged a Windows-specific SQLite file lock in ChromaDB by switching to a shared vectorstore instance at FastAPI startup

---

## Featured projects

### 🔴 [RAG Document Q&A System](https://github.com/dinamain/rag-document-qa) — Live
> Upload any PDF and ask questions. Get answers with source citations — powered by RAG.

PDF ingestion → FastEmbed ONNX embeddings → ChromaDB vector store → semantic retrieval → Groq Llama 3.1 inference → source-cited answer

**Stack:** LangChain · ChromaDB · FastEmbed (ONNX) · Groq · FastAPI · React · Docker Compose · GitHub Actions

🔗 [Live API](https://rag-document-qa-yrtf.onrender.com) · [API Docs](https://rag-document-qa-yrtf.onrender.com/docs)

---

### 💬 [SwiftChat](https://github.com/dinamain/swiftchat-secure-messaging-platform) — Real-Time Messaging Platform
> Production-grade messaging app built solo, end-to-end.

Django Channels + Redis pub/sub WebSocket layer with typing indicators, delivery receipts, online presence, emoji reactions, group management, and Cloudinary file uploads. JWT auth with token blacklisting and silent auto-refresh.

**Stack:** Django Channels · Redis · PostgreSQL · React · Docker · GitHub Actions · JWT

🔗 [Live Demo](https://swiftchat-frontend-beta.vercel.app)

---

### 🎫 [Event Registration Platform](https://github.com/dinamain/event-registration-platform) — AI-Powered Event Management
> Full-stack event platform with LLM integration and async task processing.

Groq Llama 3.3 for AI-generated event descriptions · Celery + Redis async email pipeline · DRF ScopedRateThrottle (with a bug I found and fixed) · Pytest suite · Kubernetes manifests · GitHub Actions CI/CD

**Stack:** Django · DRF · FastAPI · Celery · Redis · React · PostgreSQL · Docker · Kubernetes

🔗 [Live Demo](https://event-registration-platform-rho.vercel.app)

---

## Tech stack

**Backend**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/Django%20REST-ff1709?style=flat-square&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

**AI / GenAI**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6F00?style=flat-square&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square&logoColor=white)

**DevOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

---

## GitHub stats

<div align="center">
<img height="165" src="https://github-readme-stats.vercel.app/api?username=dinamain&show_icons=true&theme=default&hide_border=true&count_private=true" />
<img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=dinamain&theme=default&hide_border=true" />
</div>

<div align="center">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=dinamain&layout=compact&theme=default&hide_border=true" />
</div>

---

## Education & certifications

**B.Tech — Computer Science Engineering** · College of Engineering Thalassery, KTU, Kerala · CGPA: 8.06/10 · 2022–2026

- Introduction to Artificial Intelligence (AI) — IBM · Coursera
- Artificial Intelligence Essentials V2 — IBM · Coursera
- Machine Learning through Python — ICFOSS · Central University of Kerala

---

<div align="center">

📫 dinausman2001@gmail.com · [LinkedIn](https://linkedin.com/in/dina-usman888)

</div>
