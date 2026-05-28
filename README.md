# Hi, I'm Hector Cruz 👋

Senior Full-Stack Engineer with 9+ years of experience building production systems — React/TypeScript frontends, Node.js & Go backends, AWS infrastructure, and LLM-powered clinical AI pipelines.

📍 Playa del Carmen, Mexico · Open to remote opportunities

---

## About me

- 🏥 Currently at **Curie Health** — building clinical AI with RAG pipelines, AWS Bedrock, and HIPAA-compliant LLM workflows
- ⚡ Reduced API response time by **42%** with optimized GraphQL + Redis caching
- 🤖 Experience with **LangChain, vector search, prompt engineering**, and structured output validation in production
- 🐹 Comfortable in both **Node.js** and **Go** for high-performance concurrent systems
- ☁️ Deployed and maintained services on **AWS** with Kubernetes and GitHub Actions CI/CD

---

## Featured projects

Clean, public re-implementations of patterns I work with in production — built to be read, run, and reviewed. Together they span the full stack, from a clinical ingestion backend to the dashboard a clinician would watch.

### 🔍 [rag-pipeline](https://github.com/hernandezcruzhecto/rag-pipeline)
A production-oriented Retrieval-Augmented Generation pipeline.
**Hybrid retrieval** (dense vectors + keyword search) fused with **Reciprocal Rank Fusion**, a **cross-encoder reranking** stage, grounded answer generation with enforced citations, and an **evaluation harness** (hit rate, MRR, faithfulness) so quality changes are measurable.
`Python` · `pgvector` · `Redis` · `LangChain-style RAG`

### ⚡ [graphql-api](https://github.com/hernandezcruzhecto/graphql-api)
A GraphQL API demonstrating the two things that actually move latency: **eliminating N+1 queries with DataLoader** and **Redis response caching with tag-based invalidation**. Includes a reproducible benchmark that counts queries before and after batching.
`TypeScript` · `Apollo Server` · `PostgreSQL` · `Redis`

### 🐹 [go-microservice](https://github.com/hernandezcruzhecto/go-microservice)
A gRPC microservice for real-time clinical data ingestion. **Bounded-concurrency worker pool with backpressure**, context propagation and cancellation, and **graceful shutdown** that drains in-flight work. Concurrency verified with the Go race detector.
`Go` · `gRPC` · `protobuf` · `concurrency`

### 📈 [vitals-dashboard](https://github.com/hernandezcruzhecto/vitals-dashboard)
A real-time clinical vitals monitoring UI — the front end to the ingestion service above. **Memoized rendering** that stays smooth under per-second updates, **hand-rolled SVG sparklines** (no charting dependency), derived state, and accessible severity-based alerting.
`React` · `TypeScript` · `Vite` · `performance`

---

## Tech stack

**Frontend**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat&logo=graphql&logoColor=white)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-4285F4?style=flat&logo=google&logoColor=white)

**Cloud & Infra**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)

**AI / ML**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=chainlink&logoColor=white)
![AWS Bedrock](https://img.shields.io/badge/AWS_Bedrock-FF9900?style=flat&logo=amazon-aws&logoColor=white)
![GCP Vertex AI](https://img.shields.io/badge/Vertex_AI-4285F4?style=flat&logo=google-cloud&logoColor=white)

---

## Most used languages

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=hernandezcruzhecto&layout=compact&hide_border=true&langs_count=8)

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/héctorhernández-cruz)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:hernandezcruzhecto@gmail.com)
