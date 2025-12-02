# 👋 Hi, I'm Riya

<div align="center">
  <img src="https://media.giphy.com/media/26tn33aiTi1jkl6H6/giphy.gif" width="600" />
</div>

<br/>

**Software Engineer** | Building end-to-end AI/ML systems | *Turning coffee into JSON*

🎯 **Applied AI/ML Engineer in training** — Currently in the **"build, break, cry, fix, learn"** phase. I ship projects to understand how AI systems work in practice (and occasionally how to bankrupt myself with OpenAI API credits).

---

## 💼 Open to Opportunities

**Seeking**: Applied AI/ML Engineering roles where I can turn my spaghetti code into production pipelines.

**What I Bring**:
- **Production Mindset**: I know that "it works in the notebook" is a lie.
- **Cost Optimization**: I reduced token costs by 73% because I'm cheap.
- **Full-Stack ML**: I can fine-tune a model *and* center a `<div>` (okay, maybe just the model part).

📧 **Email**: riyasangwandec19@gmail.com  
💼 **LinkedIn**: [linkedin.com/in/riyasangwan](https://linkedin.com/in/riyasangwan/)  

---

## 🛠️ What I've Shipped (and barely survived)

### 1. [AI Agent Framework](https://github.com/ria-19/ai_agent) — Hybrid ReAct + Reflexion Architecture

**The Project**: A "Dual-Brain" agent that knows when to "Think Fast" and "Think Slow". Basically, it has better impulse control than I do.

- **The Struggle**: At one point, the agent got into a loop apologizing to itself for 40 turns. I fixed it.
- **Engineering Wins**:
    - **Parser Hardening**: Zero crashes across 100+ runs (after fighting Regex for 3 days).
    - **Cost Optimization**: **73% reduction** in token usage. My wallet thanked me.
    - **Architecture**: Implements ReAct (System 1) + Reflexion (System 2).

**Status**: v0.2 Stable | [View Project →](https://github.com/ria-19/ai_agent)

---

### 2. Semantic Router — Fine-Tuned Function Calling Model

**The Problem**: GPT-4 is smart but expensive. Base Llama-3 is cheap but hallucinates JSON like it's abstract art.

**My Solution**: Bullying a small model (Llama-3-8B) into following instructions via LoRA fine-tuning.

- **Progress**: 
    - ✅ Generated 2K synthetic training examples.
    - 🚧 Training LoRA adapter (My GPU fan sounds like a jet engine right now).
    - 📊 Target: <5% hallucination rate.
- **Goal**: Make a local 8B model behave like a senior engineer.

**Status**: Active Development (Praying for convergence) | [View Project →](https://github.com/ria-19/semantic_router)

---

### 3. [RepoRAG](https://github.com/ria-19/reporag) — Chat with your Codebase

**The Project**: A RAG system because reading documentation is hard.

- **The "Aha!" Moment**: I realized that blindly chopping code into 500-token chunks is a terrible idea. Implemented **AST-based chunking** so the LLM actually sees full functions.
- **Results**: Accuracy jumped from 45% → 82%. The other 18% is the model confidently lying.

**Status**: V1 Shipped | [View Project →](https://github.com/ria-19/reporag)

---

### 4. Customer Segmentation ML System

**The Project**: Grouping customers based on spending habits so marketing teams can target them better.

- **Key Learning**: My initial model was garbage (Silhouette score 0.32). Turned out real data is messy and has outliers. Who knew? 
- **The Fix**: Winsorization + proper preprocessing = Score 0.58.
- **Performance**: Processes 10K records in 2.3s. Faster than I can open Excel.

**Status**: V1 Shipped

---

## ⚡ Tech Stack (The tools I yell at)

<div align="center">
  <img src="https://skillicons.dev/icons?i=python,pytorch,docker,aws,gcp,fastapi,postgres,git,linux,vscode" />
</div>

<br/>

**ML/AI**: PyTorch (Love/Hate), Transformers, RAG, LoRA  
**LLMs**: Llama-3 (My best friend), GPT-4 (My expensive friend), Groq  
**Infrastructure**: Docker (Because "it works on my machine" is not a valid excuse)  
**Vibe Check**: ☕ Coffee, 🎧 Lo-Fi Beats, 🐛 Debugger  

---

## 📊 How I Think About ML Systems

I focus on building systems that work reliably in production, not just in a sterile Jupyter Notebook.

**Principles I follow**:

1.  **Fail Gracefully**: If the LLM hallucinates, the system catches it. If *I* hallucinate, hopefully code review catches it.
2.  **Data Quality First**: 3 days of debugging a model usually ends with realizing I fed it garbage data.
3.  **Cost Awareness**: I treat API tokens like actual gold coins. We optimize for the cheapest model that works.

---

## 🤝 Open to Collaboration

I'm actively seeking:

- **Mentorship**: Please teach me how to fix `CUDA error: device-side assert triggered` without questioning my life choices.
- **Collaborations**: Building cool stuff with other engineers.
- **Jobs**: *Please hire me, I promise I write tests.*

---

<div align="center">

<img src="https://media.giphy.com/media/du3J3cXyzhj75IOgvA/giphy.gif" width="150" />

**⭐ Star my repos if you found them cool! (It validates my existence)**

</div>
