# 👋 Hi, I'm Riya Sangwan

**Software Engineer** | Building end-to-end AI/ML systems and learning in public

🎯 **Applied AI/ML Engineer in training** — Currently in the **"build, break, learn, rebuild"** phase, shipping projects to understand how AI systems work in practice.

---

## 🛠️ What I've Shipped Recently

### **[RepoRAG](https://github.com/ria-19/reporag)** — Question Answering for Code Repositories
> Helping developers understand unfamiliar codebases through natural language queries

A RAG-based system that lets you ask questions about any GitHub repository. Built to learn how retrieval quality impacts LLM responses in code contexts.

- **Tech Stack**: RAG, Hybrid Search (BM25 + Semantic), Cross-Encoder Re-ranking, FastAPI, Docker, Ollama
- **What works**: Hybrid search improved top-3 accuracy from 45% → 82%
- **Key learning**: Code chunking is hard — naive token splitting breaks function boundaries. Built AST-based chunking to preserve context
- **What I'm still fixing**: LLM hallucination (currently ~8%, was ~30%). Experimenting with stricter prompts + source attribution
- **Next iteration**: Adding knowledge graph integration to better understand code relationships
- **Status**: V1 shipped, open for contributions

**Production metrics coming soon:** Planning to deploy as internal tool and measure actual usage patterns.

---

### **Customer Segmentation ML System** — RFM Analysis + K-Means
> Automated customer segmentation for e-commerce/SaaS

Production-ready ML pipeline with business metrics, Docker deployment, and system design for scale.

- **Tech Stack**: scikit-learn, pandas, FastAPI, Docker
- **Results**: 4 distinct segments, silhouette score 0.58, processes 10K customers in 2.3s
- **Key Finding**: 15% "VIP" customers generating 45% of revenue in test dataset
- **Key Learning**: Data quality matters more than model complexity. Initial clustering failed (silhouette 0.32) until I handled outliers with winsorization
- **System Design**: Documented scaling considerations for 10K → 1M customers
- [GitHub](link) • [System Design Doc](link)

**Business impact metrics:** Working on deploying to real use case to measure actual marketing ROI.

---

## 🌱 Current Focus (November 2025)

### **DevAgent** — Autonomous Coding Assistant *(In Progress)*
> Exploring what happens when you give an AI agent write access to a codebase

Building an AI agent that can understand codebases and take autonomous actions (write code, run tests, create PRs). This is my learning ground for understanding agent capabilities and limitations.

**What I'm exploring:**
- **Knowledge graphs for code** — Testing if graph traversal improves generation vs flat vector search
- **Agent failure modes** — Running real GitHub issues to see when agents succeed vs when they need humans
- **Confidence scoring** — How to make agents say "I don't know" instead of hallucinating

**Tech Stack**: LangChain, Ollama, NetworkX, AST parsing, RepoRAG (as knowledge base)

**Current status:** Built MVP. Now systematically testing on real tasks to document what breaks and why.

---

## 🧠 Core Capabilities

### **Building & Training Models**
- **Classical ML**: Supervised/unsupervised learning, ensembles (XGBoost, Random Forest), regularization (L1/L2)
- **Deep Learning**: CNNs (ResNet, EfficientNet), Transformers (GPT, BERT, T5), GANs (DCGAN, WGAN)
- **Time Series**: LSTM/GRU for forecasting, Seq2Seq, walk-forward validation
- **Evaluation**: Precision, Recall, F1, ROC-AUC, silhouette scores, cross-validation

### **Deploying Models to Production**
- **APIs**: FastAPI/Flask with Docker containerization
- **Monitoring**: Drift detection, A/B testing, confidence scoring
- **MLOps**: MLflow for experiment tracking, model registry, checkpointing
- **System Thinking**: Ingestion → Feature Engineering → Model → API → Monitor

### **Working with Modern AI Tools**
- **RAG Pipelines**: LangChain, LlamaIndex, vector databases (FAISS, Pinecone, Chroma)
- **LLM Engineering**: Prompt engineering, fine-tuning, retrieval optimization
- **Agents**: Building autonomous systems that take actions, not just answer questions
- **Embeddings**: OpenAI, SentenceTransformers, hybrid search (semantic + keyword)

---

## 🧩 Domains I'm Exploring Through Projects

**🤖 Developer Tools**  
Built RepoRAG for codebase Q&A. Currently building DevAgent (autonomous coding). Learning: Code context is hard — AST parsing + knowledge graphs beat naive chunking.

**👥 Customer Intelligence**  
Built a customer segmentation system (K-means + RFM). Key insight: High silhouette score doesn't mean actionable segments — had to add business constraints.

**🏠 Real Estate** *(Planned)*  
Next: Price prediction using ensemble methods. Want to understand feature engineering for location data.

**💰 Finance** *(Exploring)*  
Experimenting with LSTM-based forecasting. Early takeaway: Time series is hard, and most tutorials oversimplify the problem.

---

## 💻 Tech Stack

**ML & Data**  
Python, NumPy, Pandas, Matplotlib, Seaborn, scikit-learn, XGBoost, PyTorch, TensorFlow

**NLP & LLMs**  
Transformers, LangChain, LlamaIndex, Ollama, spaCy, NLTK, SentenceTransformers

**Data Engineering**  
PostgreSQL, MongoDB, SQLite, Vector DBs (FAISS, Pinecone, Chroma)

**Deployment**  
FastAPI, Flask, Streamlit, Docker, AWS, GitHub Actions, MLflow

---

## 🚧 Growing Edges (What I'm Learning Next)

- **Production deployment at scale** — Moving from prototype datasets to real user traffic
- **Distributed systems** — Understanding how to parallelize training and serve models at scale
- **Advanced MLOps** — Feature stores, model monitoring, A/B testing frameworks

---

## 📊 How I Think About ML Systems

I'm learning to build systems that **work reliably in production, not just in controlled environments.**

Key principles I'm developing:
- **Data quality matters more than model complexity** — Spent 3 days debugging clustering, root cause was outliers
- **Business metrics ≠ ML metrics** — High accuracy doesn't mean stakeholders can act on it
- **Production ≠ Notebook** — 10-min notebook code → 5-sec production API requires different thinking
- **Failure modes matter** — Understanding when models break is more valuable than perfect accuracy on test sets

---

## 🤝 Open to Collaboration

I'm actively seeking:
- **Mentorship** — Learning from experienced ML engineers on production systems, MLOps, and system design
- **Collaborations** — Building with other engineers on interesting ML problems
- **Open Source Contributors** — All my projects are open source and welcome contributions

### **Current projects open for contribution:**
- **[RepoRAG](https://github.com/ria-19/reporag)** — Help improve retrieval quality, add new features, or optimize performance
- **DevAgent** — Test on real codebases, add new capabilities, improve agent reasoning
- **Customer Segmentation** — Add new clustering algorithms, visualization improvements

See `CONTRIBUTING.md` in each repo for how to get started. Issues labeled `good-first-issue` are great entry points.

**Want to collaborate on something new?** Reach out — always interested in exploring new ML problems together.

---

## 📫 Let's Connect

**I'm open to:**
- 🎓 Mentorship from experienced ML engineers
- 🤝 Collaborating on ML projects
- 💬 Technical discussions about RAG, agents, or MLOps
- 🌟 Contributing to open source ML tools
- 💼 Early-stage opportunities, contract work, or internships

**Find me at:**
- **LinkedIn**: [Your LinkedIn](link)
- **GitHub**: [@ria-19](https://github.com/ria-19) — All projects open source & accepting contributions
- **Twitter**: [@YourHandle](link)
- **Email**: your.email@example.com

---

## 📈 Project Progress

| Project | Status | Current Focus |
|---------|--------|---------------|
| **RepoRAG** | V1 Shipped | Adding knowledge graphs, planning production deployment |
| **Customer Segmentation** | Complete | Exploring real business use case for impact measurement |
| **DevAgent** | MVP Stage | Testing on real coding tasks, documenting failure modes |

---

## 🔥 What I'm Learning Right Now

- 🚀 Building DevAgent MVP — testing autonomous coding capabilities
- 📊 Understanding when hybrid search beats pure semantic (and when it doesn't)
- 🎯 Learning to measure agent confidence and reduce hallucination
- 📚 Studying: Multi-agent systems, graph-based RAG, production LLM patterns

---

**TL;DR:** Software engineer learning Applied AI/ML by shipping end-to-end systems. Built RepoRAG (code Q&A) and customer segmentation tools. Currently building DevAgent (autonomous coding assistant). Open to collaboration, mentorship, and contributions to open source projects.

---

<div align="center">

**⭐ Star my repos if you find them interesting • 🤝 Open to collaboration • 📬 Always happy to chat about ML, DL and AI**

</div>
