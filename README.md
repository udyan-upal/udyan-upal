# Hi, I'm Udyan Upal 👋

I am a Software Engineer with 4+ years of experience building and scaling SaaS platforms end-to-end, from Node.js, Python and TypeScript APIs to PostgreSQL data models and React/Next.js frontends. I specialize in third-party API integrations and production AI features using OpenAI, Claude, RAG, vector databases, background workers, and cloud deployments on AWS and GCP. 

## Projects

### 💼 Work

**[Myndy.ai](https://myndy.ai)**: a business phone number with a 24/7 AI voice receptionist that answers calls, books appointments, updates the CRM, and hands off to a human when needed.

- **Real-time voice pipeline:** telephony (local/toll-free provisioning, number porting) → LiveKit → Google Cloud STT/TTS with VAD and turn detection, for sub-second, interruptible conversations
- **Multi-tenant agent builder:** per-number agent routing; tool/function calling for calendar booking, CRM updates, and human handoff with the full context attached
- **Knowledge-grounded answers (RAG):** website crawling plus PDF/doc ingestion → chunking, embeddings, and re-ranking over Qdrant, so every answer traces back to an editable source
- **Self-learning playbook:** flags questions the agent couldn't answer (with audio); owner-approved answers feed back into retrieval and prompts
- **Unified inbox:** calls, SMS, and voicemail threaded per contact, with AI ↔ human takeover mid-conversation, recordings, transcripts, and summaries with intent and next action
- **Stack:** Node.js/TypeScript, PostgreSQL, React/Next.js, OpenAI/Claude, background workers for ingestion and vector sync

### 🛠️ Open source: built for myself

**[Readr](https://github.com/udyan-upal/readr)**: a distraction-free reader with natural read-aloud and word-by-word highlighting, for web articles (Chrome extension) and PDFs (web app). MIT licensed.

- **Chrome MV3 extension:** Mozilla Readability extraction → clean reader view with highlights, notes, a tl;dr, and Q&A over the article (OpenRouter, NVIDIA fallback)
- **Word-synced neural TTS:** word-boundary events aligned to rendered text with a two-pointer alignment that handles punctuation, contractions, and hyphenation drift
- **Gapless streaming:** progressive chunking (100 → 250 → 400 chars), a 4-clip lookahead buffer with bounded concurrency, and background retry with exponential backoff, so playback doesn't stall even on Cloudflare's 10 ms-CPU free tier
- **Serverless backend:** Next.js 15 on Cloudflare Workers (OpenNext), D1 for notes and sessions, R2 for PDFs, pdf.js for rendering and text extraction
- **Tooling:** pnpm monorepo, TypeScript, Bun, Biome, Conventional Commits

## Skills

| Area | Tools & technologies |
| :--- | :--- |
| **AI / LLM** | OpenAI API, Claude API, Function/Tool Calling, RAG, RAG Fusion, LangChain, LangGraph, LlamaIndex, CrewAI, AutoGen, Prompt Engineering, Fine-tuning, Embeddings |
| **AI Coding Agents** | Claude Code, Codex, OpenCode, Pi Agent |
| **Languages** | JavaScript (ES6+), TypeScript, Python, SQL |
| **Backend** | Node.js, Express.js, REST APIs, GraphQL, FastAPI, Microservices, WebSockets, Nginx |
| **Frontend** | React, Redux, Next.js, ReactFlow, HTML/CSS, Tailwind |
| **Databases** | PostgreSQL, MySQL, MongoDB, Redis, Qdrant, Weaviate |
| **Integrations** | REST/Webhook APIs, OAuth 2.0, LiveKit, Google STT/TTS |
| **Cloud / DevOps** | AWS, GCP, Docker, Kubernetes, Jenkins, CI/CD, Git/GitHub, Grafana, ELK Stack |

## About me

-  Interested in software development and technology
-  Always learning and improving
-  Website: [upal.dev](https://upal.dev)
-  LinkedIn: [udyan-upal](https://www.linkedin.com/in/udyan-upal)
-  X: [@udyan_upal](https://x.com/udyan_upal)
-  Email: [udyan.upal@gmail.com](mailto:udyan.upal@gmail.com)
