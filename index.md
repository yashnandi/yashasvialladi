# Yashasvi Alladi — AI Engineer | Data Scientist | GenAI Specialist

📍 Hyderabad, India · [LinkedIn](https://linkedin.com/in/yashasvialladi-52215bb1) · yashasvi.alladi@gmail.com

Data Scientist and AI Engineer with 8+ years across BFSI and health insurance, now focused full-time on building production-grade Generative AI systems — from fine-tuned SLMs and custom embedding models to citation-grounded RAG pipelines. This repo is a portfolio index of my GenAI work; each project below links out to more detail.

---

## 🧠 Featured Projects

### 1. AtmicAcharya — Fine-Tuned, Citation-Grounded RAG System
*Personal / Research Project · 2026*

A full-stack, production-grade AI application built end-to-end — data pipeline, model training, retrieval architecture, backend, and frontend — developed under the SriRamanaAtmic Research Initiative.

**Highlights**
- **AtmicIntelv1** — QLoRA fine-tuning of Microsoft Phi-3 Mini (SFT + DPO) on an NVIDIA A100 80GB GPU, with a custom instruction-tuning dataset built from a domain corpus of authenticated source texts.
- **AtmicEmbeddingv2** — Multilingual-E5-Large embedding model fine-tuned with contrastive learning for domain-specific semantic search (1024-d).
- **AtmicQuoter** — a dedicated citation-retrieval embedding model (BGE-small, 384-d) for high-precision quote grounding, [published on Hugging Face](https://huggingface.co/SriRamanaAtmic).
- Multi-slot retrieval architecture combining dense + sparse (BM25) retrieval with Reciprocal Rank Fusion, backed by a dual-Qdrant-collection design.
- FastAPI backend with Aspect-Oriented Programming for structured cross-cutting logging; Angular frontend; PostgreSQL observability schema; Hugging Face Inference Endpoints with scale-to-zero serving.

**Stack:** `Python` `PyTorch` `Transformers` `PEFT/QLoRA` `sentence-transformers` `Qdrant` `FastAPI` `Angular` `PostgreSQL` `Redis` `Hugging Face Inference Endpoints`

---

### 2. PySpark Assistant — RAG-Powered Internal AI Tool
*Synchrony · 2025 – 2026*

An end-to-end RAG system built to close a PySpark skills gap for Transaction Fraud analysts.

**Highlights**
- Retrieval corpus curated from licensed PySpark references and a risk-team-validated code snippet library.
- Custom Multilingual-E5-Large embedding model fine-tuned on synthetic query-passage pairs via contrastive learning for domain-specific retrieval.
- LangChain-based retrieval + generation pipeline with systematic prompt engineering to reduce hallucinations.
- GPT-5-mini backend, HTML/CSS Grid frontend for internal analyst use.
- **Impact:** reduced analyst dependency on ad-hoc support and enabled junior team members to independently write validated PySpark code.

**Stack:** `Python` `LangChain` `sentence-transformers` `GPT-5-mini` `HTML/CSS`

---

## 💼 Professional Experience

**Assistant Vice President II — Credit Model Development (Transaction Fraud)** · Synchrony, Hyderabad · *Apr 2025 – Present*
- Oversee vendor model validation and performance reporting for existing production models.
- Drive GenAI adoption by showcasing AI use cases to senior leadership.

**Assistant Vice President - Credit Model Development** · Synchrony, Hyderabad · *Dec 2022 – Mar 2025*
- Led migration of the SAS codebase to PySpark, including full replication of Adverse Action generation logic for Acquisition Credit models.
- Built an alternative Acquisition Credit model using U.S. bureau attributes to benchmark against an existing production ML model.

**Manager — Credit Models** · Synchrony, Hyderabad · *Jan 2022 – Dec 2022*
- Built a Bankruptcy Model (KGB/AGB) for acquisition credit, used in customer onboarding to filter high-risk applicants.
- Prepared data in SAS/PySpark from 4,000+ bureau attributes, reducing to 100 via Gradient Boosting and stepwise regression.
- Achieved a KS of 0.50 on out-of-time test data — a significant lift over prior bureau-based models.
- Conducted outcome analysis for Acquisition Credit and Fraud models; delivered ongoing monitoring reports for First Payment Default models across multiple quarters.

**Data Scientist** · Actify Data Labs, Mumbai / Bangalore · *Apr 2019 – Jan 2022*
- Developed health insurance fraud detection models, delivering significant ROI and reduced turnaround time.
- Managed end-to-end model deployment and production monitoring, handling real-time stakeholder requirements.
- Managed cloud ML services for automated model development and deployment pipelines.
- Created dashboards and visualizations for retail business stakeholders.

---

## 🛠️ Core Skills

| Area | Tools |
|---|---|
| **AI / GenAI** | Azure OpenAI, RAG Pipelines, LangChain, LlamaIndex, Prompt Engineering, LoRA/QLoRA Fine-Tuning, Custom Embedding Models |
| **ML / Modelling** | Gradient Boosting, Logistic Regression, Reject Inference, Credit Scorecard Development |
| **Data & Backend** | PySpark, SQL Server, MySQL, SAS, Python, FastAPI |
| **Cloud & DevOps** | AWS SageMaker, AWS Lambda, Azure Machine Learning Studio, Hugging Face Inference Endpoints |
| **Frontend** | JavaScript, jQuery, Angular |

## 🎓 Education

- **B.Tech., Engineering Physics** — Indian Institute of Technology (IIT) Bombay, 2010–2014
- **PG Certificate, Software Engineering for Data Science** — IIIT Hyderabad, 2022–2023

## 📄 Resume

A detailed resume is available on request or via [LinkedIn](https://linkedin.com/in/yashasvialladi-52215bb1).

---

*This README is intended as a portfolio index for GitHub/LinkedIn. Individual project repos and write-ups are linked as they're published.*
