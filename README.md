Hi, I'm Chisom Ujoatu 👋

Agentic AI Systems Engineer building production-ready AI systems that combine tool-calling agents, workflow orchestration, and scalable backend infrastructure.

I design and deploy:

- Agent systems with tool routing (MCP-style architectures)
- Workflow orchestration using n8n (production pipelines)
- Retrieval-Augmented Generation (RAG) systems
- Async job systems (Redis, polling, event-driven flows)
- Distributed AI backends (FastAPI, Node.js, Docker)

🚀 Currently building:
- AI Agent SaaS system (MCP + n8n + FastAPI + Redis)

---

## Core Technologies

### Backend
- Python (FastAPI)
- Node.js (Express)
- REST APIs, WebSockets
- Microservices architecture

### Agent Systems
- MCP (Model Context Protocol)
- Tool routing & execution engines
- Agent decision systems

### AI Systems
- RAG (Retrieval-Augmented Generation)
- Vector DBs (Pinecone, Chroma)
- OpenAI APIs
- Prompt engineering

### Orchestration
- n8n (production workflows)
- Make / Zapier (comparative)

### Databases 
- PostgreSQL
- Redis (job queues, caching)

### Infrastructure
- Docker
- Git & GitHub
- AWS

## System Architecture Focus

- Designing async AI pipelines (job → queue → result pattern)
- Separating orchestration (n8n) from execution (API workers)
- Building resilient systems with retries, polling, and fault handling
- Containerized multi-service architectures (Docker Compose)
- Debugging real-world issues (timeouts, service communication, orchestration failures)
---

## Engineering Focus

- Designing AI-native backend systems
- Building retrieval and vector search pipelines
- Developing automation systems with LLMs
- Architecting scalable APIs and services
- Integrating AI into real-world production workflows

---

## Featured Engineering Projects


## 🤖 AI Agent SaaS System (MCP + n8n + FastAPI)

Built a production-style agent system with proper separation of concerns between agent logic, orchestration, and execution.

### Key Features:
- MCP-style tool system (generate_post, get_result)
- Agent decision engine for tool selection
- Async job handling using Redis (job_id pattern)
- n8n as orchestration layer (NOT execution)
- Polling-based result retrieval system
- Multi-container architecture (API, agent, DB, queue)

### Architecture:
Agent (Node.js)
→ API (FastAPI)
→ Redis (job state)
→ n8n (workflow orchestration)
→ API (result fetch)

### Key Learnings:
- Avoid circular dependencies between API and orchestrator
- Proper async design using job queues
- Debugging container networking + timeouts
- Designing production-ready AI workflows

### Tech Stack:
FastAPI • Node.js • Redis • n8n • Docker • OpenAI

### 🚕 SmartKeke Ride Platform Backend

Built a real-time distributed backend system for ride coordination with live state synchronization.

- Designed REST + WebSocket architecture for real-time communication
- Implemented state management using Redis (live updates)
- Built scalable APIs for trip lifecycle and matching logic
- Ensured low-latency updates across distributed clients

**Tech Stack:** FastAPI • PostgreSQL • Redis • WebSockets

---

### 🧠 AI Retrieval System (RAG Pipeline)

Developed an LLM-powered retrieval system that processes documents into embeddings and generates context-aware responses.

- Built document ingestion and embedding pipeline
- Integrated Pinecone for vector storage and similarity search
- Implemented retriever + LLM response flow
- Automated workflows using n8n for data processing

**Architecture:**
Documents → Embeddings → Vector DB → Retriever → LLM Response

**Tech Stack:** Python • FastAPI • Pinecone • OpenAI • n8n

---

### 🛒 E-Commerce Marketplace Platform

Developed a scalable marketplace backend supporting vendors, products, and customer transactions.

- Designed backend APIs for product listings, user management, and orders
- Implemented real-time inventory updates using Redis
- Built secure checkout and transaction flow
- Structured system for scalability using modular services

**Architecture:**
Frontend (Next.js) → Backend API → PostgreSQL → Redis

**Tech Stack:** Next.js • TypeScript • PostgreSQL • Redis • REST APIs

---

### ⚙️ AI Workflow Automation Platform

Built AI-driven automation pipelines that integrate APIs, decision logic, and data systems.

- Designed workflows for automating content and operational tasks
- Integrated LLMs for intelligent decision-making
- Connected APIs and databases for end-to-end automation
- Orchestrated workflows using n8n

**Tech Stack:** n8n • Python • APIs • LLMs

---

## Contact

📧 Email: ujoatuchisom@gmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/chisom-ujoatu-b325221ab/  
💻 GitHub: https://github.com/UjoatuChisom
