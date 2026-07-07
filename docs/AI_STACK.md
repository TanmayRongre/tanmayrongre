# 「 🤖 AI & Machine Learning Tech Stack 」

> *"The future belongs to those who build bridges between foundational LLM capabilities and practical, real-world user workflows."*

---

## ⚡ 1. Primary Model Ecosystems

I leverage a multi-provider strategy to balance reasoning capability, latency, and operational costs:
* **Google Gemini Ecosystem:** Utilizing **Gemini 3.1 Pro** and **Gemini Flash** for complex reasoning, multi-modal analysis, and deep context windows.
* **Anthropic Claude Series:** Leveraging Claude 3.5 Sonnet / Opus for high-precision code generation and architectural synthesis.
* **OpenAI Models:** Using GPT-4o and O1/O3 models for structured JSON tool-calling and agentic orchestration.
* **Open-Source & Fast Inference:** Deploying Llama 3, DeepSeek, and Mistral via Groq for ultra-low latency real-time interactions.

---

## 🛠️ 2. Orchestration & Frameworks

* **LangChain & LlamaIndex:** Building custom document loaders, prompt pipelines, and evaluation loops.
* **Blackboard Shared Memory:** Custom state management implementations for multi-agent collaboration.
* **Vector Stores:** Pinecone, ChromaDB, and PostgreSQL (PGVector) for scalable embeddings retrieval.
* **Embeddings:** OpenAI `text-embedding-3-large`, Google Text Embeddings, and HuggingFace BGE models.

---

## 🚀 3. MLOps & Deployment

* **Containerization:** Docker & Docker Compose for isolated microservices.
* **Serverless Inference:** Cloudflare Workers, Vercel Edge Functions, and AWS Lambda for API routing.
* **Monitoring:** Tracing prompt execution and token metrics via LangSmith and Helicone.
