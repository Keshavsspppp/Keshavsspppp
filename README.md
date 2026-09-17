
<h1 align="center">Hi, I'm Keshav 👋</h1>

<p align="center">
  CS undergrad at <b>IIIT Naya Raipur</b> (2023–2027) · Full-stack & backend developer · Competitive programmer
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/keshavprasad-ai"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-keshavprasad--ai-0A66C2?logo=linkedin&logoColor=white"></a>
  <a href="mailto:keshavdiwan17072004@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-Contact-EA4335?logo=gmail&logoColor=white"></a>
  <img alt="Location" src="https://img.shields.io/badge/Raipur,%20India-555?logo=googlemaps&logoColor=white">
</p>

---

### About me

- I build backend systems and like measuring them: caching, CDNs, concurrency-safe inventory, geospatial allocation.
- I also build LLM apps, both from scratch (my own NumPy vector store) and with LangChain.
- Competitive programming in C++ on Codeforces (Pupil), LeetCode (~1748) and CodeChef (peak ~1669).
- 🏆 1st place, StatHack, IIT Goa 2024.
- 🔭 Currently building **[Weakspot](https://github.com/Keshavsspppp/Weakspot)** and **[Trackerr](https://github.com/Keshavsspppp/Trackerr)**.

---

### Featured projects

#### Systems & backend

| Project | What it does | Stack |
|---|---|---|
| **[SnapCDN](https://github.com/Keshavsspppp/SnapCDN)** · [live](https://snap-cdn-kohl.vercel.app) | Self-hosted image CDN: Nginx edge cache in front of an Express origin, HMAC-signed URLs and Cloudflare R2 storage. A cache hit takes **~3 ms**; a full origin trip takes **~1.6 s**. | Node.js, Express, Nginx, R2, MongoDB, Docker |
| **[StockGuard](https://github.com/Keshavsspppp/StockGuard)** | Multi-store inventory backend that doesn't oversell under concurrent orders. Overselling dropped from **156% to 0%** with 200 concurrent orders against 50 units of stock. Stock reconciliation runs asynchronously, and there's a live ops dashboard. | Django, DRF, PostgreSQL, Celery, Redis, React |
| **[Darkstore Dispatch](https://github.com/Keshavsspppp/darkstore-allocation-engine)** | Assigns each order to the nearest dark store that has the items and reserves stock atomically. A 9-candidate allocation went from **364 ms to 158 ms**. | Next.js, MongoDB (geospatial), Leaflet, Zod |
| **[PolyCache](https://github.com/Keshavsspppp/PolyCache)** | Redis-inspired in-memory cache with pluggable O(1) LRU, LFU and FIFO eviction, live metrics and a React dashboard. On one workload, the policies' hit ratios differ by **49 points**. 44 tests. | TypeScript, Node.js, React |

#### AI / LLM

| Project | What it does | Stack |
|---|---|---|
| **[Weakspot](https://github.com/Keshavsspppp/Weakspot)** | Combines your Codeforces, LeetCode, CodeChef and AtCoder submissions into one dashboard. It merges each platform's topic tags and uses AI to summarize your weakest topics. | React, Express, MongoDB, Groq, GitHub OAuth |
| **[PrepWise AI](https://github.com/Keshavsspppp/PrepWise-AI)** | Study platform built on your PDF notes: Q&A grounded in the notes, quizzes, revision planning, readiness scoring and mock viva. | FastAPI, MongoDB, fastembed, React |
| **[DeepRAG](https://github.com/Keshavsspppp/DeepRAG)** | RAG built from scratch without LangChain or a vector DB. It uses a custom NumPy vector store, cites sources and pages, and shows a fallback when retrieval confidence is low. | Python, SentenceTransformers, Groq, Streamlit |
| **[SignalForge](https://github.com/Keshavsspppp/MultiAgent)** | Four-stage multi-agent research pipeline: search → read → write → critique. | LangChain, Tavily, Streamlit |
| **[BasicRAG](https://github.com/Keshavsspppp/BasicRAG)** | RAG experiments and evaluation notebooks: FAISS, Chroma, Typesense and an agentic RAG built with LangGraph. | LangChain, LangGraph, FAISS |

#### Full-stack apps

| Project | What it does | Stack |
|---|---|---|
| **[Trackerr](https://github.com/Keshavsspppp/Trackerr)** | Internship application tracker with analytics and daily email digests of stale applications. 131 tests. | Next.js 15, TypeScript, MongoDB, NextAuth, Resend, Vitest |
| **[Kiln](https://github.com/Keshavsspppp/codeeditor)** | Code playground that runs Node.js in the browser with WebContainers, plus a Monaco editor with AI inline completions. | Next.js, WebContainers, Monaco, Prisma, NextAuth |

---

### Tech I use

**Languages**
<p>
  <img src="https://img.shields.io/badge/C++-00599C?logo=cplusplus&logoColor=white">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black">
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white">
</p>

**Backend & data**
<p>
  <img src="https://img.shields.io/badge/Node.js-5FA04E?logo=nodedotjs&logoColor=white">
  <img src="https://img.shields.io/badge/Express-000000?logo=express&logoColor=white">
  <img src="https://img.shields.io/badge/Django-092E20?logo=django&logoColor=white">
  <img src="https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white">
  <img src="https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white">
  <img src="https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white">
  <img src="https://img.shields.io/badge/Celery-37814A?logo=celery&logoColor=white">
  <img src="https://img.shields.io/badge/Prisma-2D3748?logo=prisma&logoColor=white">
</p>

**Frontend**
<p>
  <img src="https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB">
  <img src="https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white">
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=white">
</p>

**AI / LLM**
<p>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?logo=langchain&logoColor=white">
  <img src="https://img.shields.io/badge/Groq-F55036?logoColor=white">
  <img src="https://img.shields.io/badge/FAISS-0467DF?logoColor=white">
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white">
</p>

**Infra & tooling**
<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/Nginx-009639?logo=nginx&logoColor=white">
  <img src="https://img.shields.io/badge/Cloudflare_R2-F38020?logo=cloudflare&logoColor=white">
  <img src="https://img.shields.io/badge/Vercel-000000?logo=vercel&logoColor=white">
  <img src="https://img.shields.io/badge/Render-46E3B7?logo=render&logoColor=black">
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white">
  <img src="https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white">
</p>

---

### GitHub stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Keshavsspppp&show_icons=true&hide_border=true&count_private=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Keshavsspppp&layout=compact&hide_border=true" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Keshavsspppp&hide_border=true" />
</p>
