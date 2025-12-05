# Riya
**AI/ML Engineer**
Building production LLM systems | Optimizing for cost, latency, and reliability

[![Email](https://img.shields.io/badge/Email-riyasangwan-red?logo=gmail&logoColor=white)](mailto:riyasangwandec19@gmail.com)  [![LinkedIn](https://img.shields.io/badge/LinkedIn-riyasangwan-blue?logo=linkedin)](https://linkedin.com/in/riyasangwan)


**Current Focus:** Fine-tuning specialized models for agent architectures (QLoRA, Unsloth) and shipping hybrid ReAct/Reflexion systems that balance speed vs correctness.

---

## Professional Summary

**Target Roles**: AI/ML Engineer, LLM Engineer, and Agent Systems Engineer

**Key Impact & Competencies:**
*   **Production Engineering:** Reduced LLM costs by 73% via prompt optimization and model routing strategies.
*   **System Design:** Architected hybrid agent systems handling 2,000+ production runs with <5% parser failures.
*   **Cost-Performance Optimization:** Extensive benchmarking of latency, cost, and reliability to drive architectural decisions.
*   **Full-Stack ML:** Expertise in Fine-tuning (QLoRA), RAG (AST-aware chunking), and Infrastructure (Docker, FastAPI).

---

## Featured Projects

### Semantic Router — Fine-Tuned Function Calling Engine
*Goal: Replace GPT-4 with a specialized 8B model for agent tool routing.*
[**View Project**](https://github.com/ria-19/semantic_router)

*   **Problem:** AI agents were incurring high costs ($0.15/call) and latency using GPT-4 for simple tool selection tasks.
*   **Solution:** Fine-tuned Llama-3.1-8B (QLoRA) on 5,000 synthetic examples with strict Pydantic schemas. Implemented anti-hallucination constraints and 20% token compression via null-stripping.
*   **Impact:** Achieved **10x cost reduction** and **5x faster inference** compared to the baseline.

### AI Agent Framework — Hybrid ReAct + Reflexion Architecture
*Goal: Create a "dual-brain" agent switching between fast execution and self-correction.*
[**View Project**](https://github.com/ria-19/ai_agent)

*   **Innovation:** Multi-model orchestration using Llama 3.3 for speed and Gemini 2.5 for evaluation.
*   **Production Wins:** Developed a battle-hardened parser to handle markdown fences and malformed JSON, resulting in ** <5%** parser crashes** across 2,000+ runs.
*   **Optimization:** Implemented strict tool output truncation (reducing 50k to 5k tokens) and exponential backoff for API resilience.

### RepoRAG — AST-Aware Codebase Search
*Goal: Improve RAG accuracy for code generation tasks.*
[**View Project**](https://github.com/ria-19/reporag)

*   **Problem:** Naive chunking split code at arbitrary boundaries, breaking function context and causing hallucinations.
*   **Solution:** Implemented AST-based chunking to treat functions, classes, and methods as atomic units.
*   **Impact:** Increased Q&A accuracy from **45% to 82%**.

### Customer Segmentation ML System
*Goal: Group 10K+ customers by spending behavior for targeted marketing.*

*   **Challenge:** Initial clustering models yielded a low Silhouette score (0.32) due to outliers.
*   **Solution:** Applied Winsorization and advanced feature engineering.
*   **Result:** improved Silhouette score to 0.58; pipeline processes 10,000 records in 2.3 seconds.

---

## Technical Skills

*   **Machine Learning:** PyTorch, Transformers (Hugging Face), QLoRA, Unsloth, LangChain, RAG
*   **LLMs:** Llama 3 (Fine-tuning), GPT-4 (API), Gemini 2.5, Groq (Inference)
*   **Infrastructure:** Docker, FastAPI, PostgreSQL, Redis (Semantic Caching)
*   **Tools:** Git, Linux, VSCode, Jupyter, Pytest

---

## Engineering Philosophy

I focus on **production-ready systems**, moving beyond notebook demos.

1.  **Fail Gracefully:** LLMs hallucinate. Systems must be designed with Pydantic schemas, hardened parsers, and fallback strategies.
2.  **Data Quality > Model Size:** A 7B model on clean data outperforms GPT-4 on poor data. I prioritize data pipelines and cleaning.
3.  **Cost as a Metric:** API tokens are treated as budget items. Every project includes a cost-performance benchmark.
4.  **Build, Measure, Learn:** I prioritize shipping v0.1 quickly to gather usage data and iterate based on production failures rather than theory.

---

## Collaboration & Next Steps

**Active Areas of Interest:**
*   **Mentorship:** Scaling ML systems (10M+ records), distributed training, and Kubernetes.
*   **Open Source:** Contributing to LLM tooling (LangChain, Unsloth, vLLM).
*   **Learning:** Distributed inference (vLLM, Ray), vector databases (Pinecone, Weaviate), and LLM observability (LangSmith, Weights & Biases).
