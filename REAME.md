# 🧠 AI Resume Critiquer  
**ATS-Aware Resume Analysis Platform powered by LLMs**  

An AI-driven system that evaluates resumes against job descriptions using NLP, similarity scoring, and large language models to provide ATS-style feedback and actionable improvements.

---

## 📌 Problem Statement  
Over **75% of resumes** are rejected by Applicant Tracking Systems (ATS) before reaching recruiters.  
Candidates — especially freshers — lack visibility into:  
- Keyword mismatches  
- Weak project descriptions  
- Resume-to-role alignment  

This results in qualified candidates being filtered out prematurely.

---

## 🎯 Solution Overview  
**AI Resume Critiquer** simulates how modern hiring pipelines evaluate resumes by:  
- Parsing resumes (PDF/DOCX)  
- Extracting role-specific keywords from job descriptions  
- Scoring alignment using similarity metrics  
- Generating structured, actionable AI feedback  

👉 The system focuses on **explainability**, not just scoring.

---

## ✨ Key Features  

### Core Capabilities  
- 📄 Resume upload (PDF / DOCX)  
- 📝 Job description ingestion  
- 📊 ATS-style match score (0–100)  
- 🔍 Keyword gap analysis  
- 🧩 Section-wise feedback (Skills, Projects, Experience)  

### Advanced Capabilities  
- ✏️ AI-powered bullet rewrite suggestions  
- 🧠 Context-aware critique using LLMs  
- 📈 Resume ↔ JD similarity scoring  
- 🧪 Prompt-engineered structured outputs  
- 🖥 Interactive, recruiter-friendly UI  

---

## 🏗️ System Architecture  

```
User Input (Resume + JD)
        ↓
Document Parsing Layer
        ↓
Text Normalization & Cleaning
        ↓
Keyword Extraction + Vectorization
        ↓
Similarity Scoring (ATS Simulation)
        ↓
LLM-based Structured Critique
        ↓
Streamlit UI
```

---

## 🛠 Tech Stack  

**Frontend**  
- Streamlit – rapid UI for ML-backed applications  

**Backend & AI**  
- Python  
- LangChain – orchestration & prompt pipelines  
- LLMs – OpenAI / Groq / Gemini (pluggable)  

**NLP & Scoring**  
- TF-IDF / Embeddings  
- Cosine similarity  
- Prompt-engineered scoring rubric  

**Resume Parsing**  
- pdfplumber  
- python-docx  

---

## 📊 Scoring Methodology (ATS Simulation)  

The ATS score is derived from:  
- Keyword coverage (% match)  
- Semantic similarity (resume ↔ JD)  
- Section relevance weighting  
- Skill-to-role alignment  

✅ Scores are **explainable**, not opaque — every deduction is justified.

---

## 🧪 Example Output  

**ATS Match Score:** `68 / 100`  

**Missing Keywords:**  
- Docker  
- REST APIs  
- PostgreSQL  

**Weak Section:**  
- Projects – lacks measurable impact  

**AI Rewrite Suggestion:**  
```
“Built a CRUD application”
→ “Designed and implemented a RESTful CRUD API using Python and PostgreSQL,
   improving data access efficiency by ~30%”
```

---

## 🧠 Engineering Highlights  
- Modular, extensible architecture  
- Clear separation of concerns  
- Prompt design for deterministic output  
- Pluggable LLM backend  
- Explainable scoring logic  
- Real-world hiring pipeline simulation  

---

## 📈 Scalability & Extensions  
- Vector DB (FAISS) for large resume datasets  
- Resume history & versioning  
- Role-specific scoring rubrics  
- Multi-resume comparison  
- Resume export with AI edits applied  
- Authentication & persistence  

---

## 👤 Author  
**Ramya Kannan**  
Aspiring Software Engineer | Python | AI Systems | Backend  

---

## ⭐ Why This Project Matters  
This project demonstrates:  
- Real-world problem solving  
- Applied NLP & LLM usage  
- Product-level thinking  
- Engineering clarity & design  
- Hiring-pipeline awareness  

