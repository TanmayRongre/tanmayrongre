# 「 ☁️ Cloud Infrastructure & DevOps Architecture 」

> *"A resilient system is defined by its ability to scale effortlessly, recover automatically, and deploy continuously with zero downtime."*

---

## ⚡ 1. Cloud Platforms & Serverless Compute

I leverage distributed cloud environments to host scalable AI microservices and high-availability frontend portals:
* **Google Cloud Platform (GCP):** Cloud Run for containerized backend services, Vertex AI for managed model deployment, and Cloud Storage for dataset archiving.
* **Vercel & Cloudflare Workers:** Edge computing networks for sub-50ms global content delivery, Next.js serverless functions, and API gateways.
* **Firebase Ecosystem:** Real-time synchronization, enterprise-grade authentication (Phone OTP / OAuth), and Firestore NoSQL databases.

---

## 🐳 2. Containerization & Microservices

* **Docker & Compose:** Designing multi-stage Dockerfiles to minimize container image footprints while isolating Python ML dependencies from Node.js gateways.
* **Environment Configuration:** Strict separation of environment variables and secrets via secret managers and `.env` vault protocols.
* **Microservices Routing:** Decoupling heavy LLM inference endpoints from lightweight web REST APIs to prevent resource contention.

---

## 🔄 3. CI/CD & Automated Pipelines

* **GitHub Actions:** Automated linting, build verification, and deployment triggers on branch merges to `main`.
* **Zero-Downtime Deployment:** Implementing blue-green and rolling release patterns for live production environments.
* **Monitoring & Observability:** Real-time log streaming and performance metrics tracking across active deployments.
