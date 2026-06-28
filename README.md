<!--
  ─────────────────────────────────────────────────────────────
  README de perfil · José Luis
  Antes de publicar, reemplaza los marcadores entre {{ }}:
    {{USERNAME}}   → tu usuario de GitHub
    {{LINKEDIN}}   → la parte final de tu URL de LinkedIn (linkedin.com/in/XXXX)
    {{PORTFOLIO}}  → la URL de tu portfolio
    {{EMAIL}}      → tu correo
    {{X}}          → tu usuario de X/Twitter (opcional)
  ─────────────────────────────────────────────────────────────
-->

<div align="center">

# José Luis

<a href="https://github.com/{{USERNAME}}">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=22&duration=3200&pause=900&color=8B949E&center=true&vCenter=true&width=620&lines=AI+Product+Designer;AI+Engineer;Enterprise+AI+Builder;Designing+intelligent+systems%2C+end+to+end" alt="AI Product Designer · AI Engineer · Enterprise AI Builder" />
</a>

<br/>

<p>
  <strong>11+ years</strong> in Product Design&nbsp;&nbsp;·&nbsp;&nbsp;Banking&nbsp;&nbsp;·&nbsp;&nbsp;Government&nbsp;&nbsp;·&nbsp;&nbsp;Enterprise&nbsp;&nbsp;·&nbsp;&nbsp;Design Systems
  <br/>
  <em>Now building at the intersection of product and AI engineering.</em>
</p>

<p>
  <a href="https://linkedin.com/in/{{LINKEDIN}}"><img src="https://img.shields.io/badge/LinkedIn-0D1117?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://{{PORTFOLIO}}"><img src="https://img.shields.io/badge/Portfolio-0D1117?style=flat-square&logo=vercel&logoColor=white" alt="Portfolio"/></a>
  <a href="mailto:{{EMAIL}}"><img src="https://img.shields.io/badge/Email-0D1117?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://x.com/{{X}}"><img src="https://img.shields.io/badge/X-0D1117?style=flat-square&logo=x&logoColor=white" alt="X"/></a>
</p>

</div>

<br/>

---

## The bridge I build on

I don't sit inside a single discipline. I connect them — from the business problem all the way down to the running system.

```mermaid
flowchart LR
    A[Business]:::node --> B[UX]:::node --> C[AI]:::node --> D[Engineering]:::node
    classDef node fill:#161b22,stroke:#30363d,stroke-width:1px,color:#e6edf3,font-weight:500;
```

Most people own one of those boxes. My work is the arrows between them.

<br/>

## About

I'm a Lead Product Designer with more than a decade shaping enterprise software for **banking, fintech and government**, across **Europe and the Middle East**. My focus has long been the hard end of design: complex domains, design systems and products that have to hold up at scale.

For the last stretch I've been moving deliberately into **AI engineering** — not to become *"just another AI engineer,"* but to design and build complete AI systems from both the product and the engineering side. I care as much about retrieval architecture, evaluation and infrastructure as I do about the interface in front of it.

<br/>

## Featured projects

| Project | What it does |
| :-- | :-- |
| **AI Regulatory & Banking Intelligence Platform** | A Retrieval-Augmented Generation platform that answers banking and regulatory questions with **explainable, source-grounded citations**. |
| **Banking AI Copilot** | A conversational assistant for banking products — transfers, loans, cards, payments and financial insights. |
| **AI Portfolio Review Agent** | An agent that analyses Product Design portfolios and generates **personalised, structured recommendations**. |
| **Local AI Infrastructure** | A fully local AI stack on Mac Studio — Ollama, open-source LLMs, vector databases and private RAG systems. |

<br/>

## How I think about an AI system

The pattern behind most of my work — retrieval grounded in real sources, with citations as a first-class output, not an afterthought.

```mermaid
flowchart LR
    Q([User query]):::io --> E[Embed]:::step
    E --> V[(Vector DB)]:::store
    V --> R[Retrieve + rerank]:::step
    R --> P[Context + prompt]:::step
    P --> L{{LLM}}:::model
    L --> O([Answer + citations]):::io
    L -.evaluate.-> EV[Eval / guardrails]:::eval
    EV -.feedback.-> P

    classDef io fill:#161b22,stroke:#58a6ff,color:#e6edf3;
    classDef step fill:#161b22,stroke:#30363d,color:#e6edf3;
    classDef store fill:#161b22,stroke:#3fb950,color:#e6edf3;
    classDef model fill:#161b22,stroke:#d29922,color:#e6edf3;
    classDef eval fill:#161b22,stroke:#a371f7,color:#e6edf3;
```

<br/>

## Current focus

Right now I'm going deep on the engineering layer of AI products:

![FastAPI](https://img.shields.io/badge/FastAPI-0D1117?style=flat-square&logo=fastapi&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-0D1117?style=flat-square&logo=langchain&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-0D1117?style=flat-square&logoColor=white)
![Agentic AI](https://img.shields.io/badge/Agentic_AI-0D1117?style=flat-square&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-0D1117?style=flat-square&logoColor=white)
![AI Evaluation](https://img.shields.io/badge/AI_Evaluation-0D1117?style=flat-square&logoColor=white)
![Local LLMs](https://img.shields.io/badge/Local_LLM_Infra-0D1117?style=flat-square&logo=ollama&logoColor=white)

<br/>

## Learning roadmap

A systems view of where I'm heading — foundations to production.

```mermaid
flowchart LR
    F["Foundations<br/>Python · FastAPI"]:::n --> R["Retrieval<br/>RAG · Vector DBs"]:::n
    R --> A["Agents<br/>LangGraph · MCP"]:::n
    A --> E["Evaluation<br/>AI Eval · Guardrails"]:::n
    E --> P["Production<br/>Local LLM Infra"]:::n
    classDef n fill:#161b22,stroke:#30363d,stroke-width:1px,color:#e6edf3,font-weight:500;
```

<br/>

## Tech stack

**AI & LLMs**

![OpenAI](https://img.shields.io/badge/OpenAI-0D1117?style=flat-square&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-0D1117?style=flat-square&logo=anthropic&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-0D1117?style=flat-square&logo=googlegemini&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-0D1117?style=flat-square&logo=ollama&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-0D1117?style=flat-square&logo=langchain&logoColor=white)
![LlamaIndex](https://img.shields.io/badge/LlamaIndex-0D1117?style=flat-square&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-0D1117?style=flat-square&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-0D1117?style=flat-square&logo=pinecone&logoColor=white)

**Backend & data**

![Python](https://img.shields.io/badge/Python-0D1117?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-0D1117?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-0D1117?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-0D1117?style=flat-square&logo=docker&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-0D1117?style=flat-square&logo=react&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-0D1117?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-0D1117?style=flat-square&logo=typescript&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-0D1117?style=flat-square&logo=tailwindcss&logoColor=white)

**Design & tooling**

![Figma](https://img.shields.io/badge/Figma-0D1117?style=flat-square&logo=figma&logoColor=white)
![Storybook](https://img.shields.io/badge/Storybook-0D1117?style=flat-square&logo=storybook&logoColor=white)
![Git](https://img.shields.io/badge/Git-0D1117?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-0D1117?style=flat-square&logo=github&logoColor=white)

<br/>

## GitHub

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username={{USERNAME}}&show_icons=true&hide_border=true&bg_color=0D1117&title_color=58a6ff&icon_color=8B949E&text_color=e6edf3&hide=contribs&count_private=true" alt="GitHub stats" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username={{USERNAME}}&layout=compact&hide_border=true&bg_color=0D1117&title_color=58a6ff&text_color=e6edf3&langs_count=8" alt="Top languages" />

</div>

<br/>

## Research interests

Enterprise AI · RAG · Agentic AI · LLM evaluation · Knowledge retrieval · AI UX · Human–AI interaction · Design systems · Developer experience · AI infrastructure

<br/>

---

<div align="center">

<sub>I like understanding how things work all the way down — architectures, AI workflows, the engineering underneath the interface.</sub>

<br/><br/>

<a href="https://linkedin.com/in/{{LINKEDIN}}"><img src="https://img.shields.io/badge/Let's_talk-0D1117?style=flat-square&logo=linkedin&logoColor=white" alt="Let's talk"/></a>

</div>
