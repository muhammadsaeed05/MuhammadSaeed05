<h1 align="center">Muhammad Saeed</h1>
<h3 align="center">AI Engineer & Cloud/DevOps Engineer — Generative AI systems on production-grade cloud infrastructure</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Google_Cloud-Professional_Cloud_Architect-4285F4?style=flat&logo=googlecloud&logoColor=white" alt="GCP Professional Cloud Architect"/>
  <img src="https://img.shields.io/badge/Google_Cloud-Professional_Data_Engineer-4285F4?style=flat&logo=googlecloud&logoColor=white" alt="GCP Professional Data Engineer"/>
  <img src="https://komarev.com/ghpvc/?username=muhammadsaeed05&label=Profile%20Views&color=4285f4&style=flat" alt="Profile Views"/>
</p>

<p align="center">
  <a href="https://linkedin.com/in/muhammad-saeed-569527204"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:saeedsaleem.04@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://saeeddigital.netlify.app"><img src="https://img.shields.io/badge/Portfolio-000000?style=flat&logo=vercel&logoColor=white" alt="Portfolio"/></a>
  <a href="https://medium.com/@saeedsaleem.04"><img src="https://img.shields.io/badge/Medium-12100E?style=flat&logo=medium&logoColor=white" alt="Medium"/></a>
  <a href="https://github.com/muhammadsaeed05"><img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white" alt="GitHub"/></a>
</p>

---

### Professional Overview

Engineer with 4+ years of software engineering experience specializing in **Generative AI systems, cloud architecture (GCP/AWS), and automated DevOps/IaC pipelines**. 

My core focus bridges the gap between **AI application engineering** (multi-agent orchestration, RAG optimization, LLM evaluation) and **scalable cloud infrastructure** (event-driven architectures, Kubernetes, Terraform, and automated CI/CD).

* **AI & LLMOps:** Multi-agent workflows (LangGraph, MCP), context optimization (SlimPrompt), automated regression testing & evaluation (TruEval), and fine-tuning (LoRA/QLoRA).
* **Cloud & Infrastructure:** GCP-native enterprise architectures (Cloud Run, GKE, BigQuery, Pub/Sub, Datastream), AWS services, and Infrastructure as Code (Terraform).
* **DevOps & Platform Automation:** Automated CI/CD (GitHub Actions, Cloud Build), containerization (Docker), least-privilege security (Cloud IAM, KMS, Secret Manager), and observability (Cloud Logging/Monitoring, LangSmith).
* **Systems & Backend Foundation:** Python (FastAPI, Flask, asyncio), TypeScript/Node.js, PostgreSQL, and resilient REST/GraphQL API design.

---

### Technical Stack

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **AI, LLMs & Multi-Agent** | LangGraph, LangChain, Model Context Protocol (MCP), LiteLLM, LangSmith, LLM-as-Judge, Prompt Engineering (CoT, CoVe, Self-Refinement), Hugging Face, PEFT (LoRA/QLoRA), RAG |
| **Vector Search & Embeddings** | Pinecone, ChromaDB, pgvector, Semantic Search, Chunk Deduplication |
| **Cloud Platforms** | Google Cloud Platform (Compute Engine, Cloud Run, GKE, Cloud Functions, Pub/Sub, Datastream, BigQuery, Cloud SQL, Firestore), AWS (EC2, Lambda, Bedrock, SageMaker) |
| **DevOps & Infrastructure** | Terraform (IaC), Docker, Kubernetes, Google Cloud Build, GitHub Actions, Jenkins, Artifact Registry |
| **Backend & Systems** | Python (FastAPI, Flask, asyncio, Pydantic), Node.js, NestJS, Express.js, REST APIs, GraphQL |
| **Data Engineering & Storage** | PostgreSQL, BigQuery, Datastream, Cloud SQL, MongoDB, Firestore, SQL |
| **Frontend & UI (Supporting)** | TypeScript, React, Next.js, Redux Toolkit, RTK Query, Tailwind CSS, Flutter |

---

### Featured Projects

#### [Agent Atlas](https://github.com/muhammadsaeed05/agent-atlas) — Multi-Agent Travel Planning System
*An autonomous multi-agent orchestration platform built with native tool-calling and observability.*
* **Architecture:** Implemented LangGraph `StateGraph` using fan-out/fan-in parallel orchestration across specialized agent nodes.
* **Tool & Model Integration:** Connected stdio and streamable HTTP tool servers via Model Context Protocol (MCP), including a custom FastMCP weather server. Engineered a LiteLLM gateway with automated fallback routing (OpenRouter → Groq).
* **Observability & Testing:** Integrated LangSmith for agent-run state tracking; built an asynchronous Pytest suite (14 test cases) validating orchestration and fallback behavior.
* **Stack:** LangGraph, Python, FastAPI, Model Context Protocol (MCP), LiteLLM, LangSmith, React, TypeScript, Pytest.
* **Links:** [Repository](https://github.com/muhammadsaeed05/agent-atlas)

#### [TruEval](https://github.com/muhammadsaeed05/trueval) — Asynchronous LLM Evaluation Harness
*An async-first evaluation framework for automated quality and regression detection across LLM pipelines.*
* **Evaluation Engine:** Implemented pluggable rule-based and LLM-as-Judge evaluators with configurable scoring criteria across OpenAI, Anthropic, Gemini, and local models via LiteLLM.
* **Regression Prevention:** Built baseline run-pinning using SQLite to automatically catch quality degradation across prompt and model updates.
* **Reporting:** Delivered interactive CLI summaries using Rich alongside standalone HTML evaluation reports.
* **Stack:** Python, LiteLLM, SQLite, asyncio, Pydantic, Rich, LLM-as-Judge.
* **Links:** [Repository](https://github.com/muhammadsaeed05/trueval)

#### [SlimPrompt](https://github.com/muhammadsaeed05/slimprompt) — Prompt Compression & RAG Optimization Middleware
*Middleware designed to reduce context-window latency and token costs between vector retrieval and LLM ingestion.*
* **Compression & Deduplication:** Cuts context token usage by up to 80% using LLMLingua-2 combined with cosine-similarity chunk deduplication.
* **Adaptive Calibration:** Implemented a binary-search Compression Judge to automatically determine optimal compression ratios without manual tuning.
* **Hybrid Compute:** Architected modular preprocessing pipelines with remote GPU offloading via Modal to eliminate vendor lock-in.
* **Stack:** Python, LLMLingua-2, Modal (GPU Compute), Transformers, RAG, PyTorch.
* **Links:** [Repository](https://github.com/muhammadsaeed05/slimprompt)

#### [Acadify](https://github.com/muhammadsaeed05/acadify) — AI-Powered Educational Assessment Engine
*A cloud-native educational platform converting unstructured lecture audio into structured learning artifacts.*
* **Multimodal Ingestion:** Built an end-to-end pipeline leveraging OpenAI Whisper for audio transcription and OpenAI/Groq for automated notes, flashcards, and quiz generation.
* **Interactive Workflows:** Implemented instructor and student role-based dashboards with real-time assessment tracking backed by Firestore and Express.js.
* **Stack:** Python, Whisper, OpenAI/Groq API, Node.js, Express.js, React, Firebase Firestore.
* **Links:** [Repository](https://github.com/muhammadsaeed05/acadify)

---

### Certifications

* **Google Cloud Certified — Professional Cloud Architect** | Google Cloud • [Verify Credential](https://www.credly.com/badges/14c80804-f184-4e0a-bf0f-cb0ffcef7d73/public_url)
* **Google Cloud Certified — Professional Data Engineer** | Google Cloud • [Verify Credential](https://www.credly.com/badges/c50e999e-a1df-4926-b63b-09f8fc52e4c8/public_url)

---

### Engineering & Repository Highlights

<p align="center">
  <img src="https://img.shields.io/github/followers/muhammadsaeed05?label=Followers&style=flat-square&logo=github&color=181717" alt="Followers"/>
  <img src="https://img.shields.io/badge/Orchestration-LangGraph-FF6F00?style=flat-square" alt="LangGraph"/>
  <img src="https://img.shields.io/badge/Tool_Standard-MCP-10B981?style=flat-square" alt="Model Context Protocol"/>
  <img src="https://img.shields.io/badge/IaC-Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white" alt="Terraform"/>
  <img src="https://img.shields.io/badge/Containers-Docker%20%26%20K8s-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker and Kubernetes"/>
</p>
---

### Connect

* **LinkedIn:** [linkedin.com/in/muhammad-saeed-569527204](https://www.linkedin.com/in/muhammad-saeed-569527204/)
* **Email:** [saeedsaleem.04@gmail.com](mailto:saeedsaleem.04@gmail.com)
* **GitHub:** [github.com/muhammadsaeed05](https://github.com/muhammadsaeed05)
* **Portfolio:** [saeeddigital.netlify.app](https://saeeddigital.netlify.app)
