# 🤖 AI Resume Intelligence Hub (RAG-Powered ATS Analyzer)

An advanced AI-powered Resume Analysis and Candidate Ranking platform that leverages Retrieval-Augmented Generation (RAG), Semantic Search, Vector Embeddings, and Google Gemini LLM to evaluate resumes against job descriptions and generate intelligent hiring insights.

---## 🌐 Live Demo

🔗 Streamlit Deployment:
https://rag-powered-resume-analyzer-gj7z8kgfokxgjt9tqgv4ok.streamlit.app

## 💻 Development Environment

🔗 GitHub Codespace:
https://shiny-space-enigma-wrv645ppxp77cgqg4.github.dev/

## 📌 Project Overview

Recruiters often spend significant time manually screening resumes. This application automates the process by:

- Parsing resumes (PDF/DOCX)
- Extracting candidate information
- Matching resumes against job descriptions
- Generating ATS scores
- Ranking multiple candidates
- Providing AI-driven recommendations
- Using RAG architecture for contextual resume analysis

---

## 🚀 Features

### 1. Resume Upload & Parsing
- PDF Resume Support
- DOCX Resume Support
- Automatic Text Extraction
- Candidate Information Processing

### 2. ATS Match Scoring
- Resume vs Job Description Comparison
- Semantic Similarity Analysis
- Overall Match Percentage
- Skills Match Score
- Experience Score
- Education Score

### 3. RAG (Retrieval-Augmented Generation)
- Resume Chunking
- Context Retrieval
- Semantic Search
- Vector Embeddings
- FAISS Vector Database

### 4. AI-Powered Insights
- Resume Strength Analysis
- Weakness Detection
- Missing Skills Identification
- Improvement Suggestions
- Interview Readiness Evaluation

### 5. Multi-Resume Ranking
- Batch Resume Upload
- Candidate Comparison
- Automatic Ranking
- Best Candidate Identification

### 6. Recruiter Dashboard
- ATS Metrics Visualization
- Resume Insights
- Candidate Ranking Table

---

# 🏗️ System Architecture

```text
Resume Upload
      │
      ▼
Text Extraction
(PDF/DOCX Parsing)
      │
      ▼
Resume Chunking
      │
      ▼
Embedding Generation
(HuggingFace)
      │
      ▼
FAISS Vector Store
      │
      ▼
Similarity Retrieval
      │
      ▼
Gemini LLM Analysis
      │
      ▼
ATS Score + Insights
      │
      ▼
Candidate Ranking
```

---

# 🧠 AI Technologies Used

## Large Language Model (LLM)
- Google Gemini

## Retrieval-Augmented Generation (RAG)
- LangChain
- FAISS

## NLP
- Semantic Similarity
- Text Chunking
- Context Retrieval

## Embeddings
- all-MiniLM-L6-v2

---

# 🛠️ Tech Stack

## Frontend
- Streamlit

## Backend
- Python

## AI / ML
- Google Gemini
- LangChain
- Hugging Face

## Vector Database
- FAISS

## NLP Libraries
- Sentence Transformers
- Regex Processing

## Data Processing
- Pandas
- NumPy

## Document Processing
- PDFPlumber
- python-docx

---

# 📂 Project Structure

```text
AI-Resume-Intelligence-Hub/
│
├── app.py
├── requirements.txt
├── README.md
│
├── .streamlit/
│   └── secrets.toml
│
└── assets/
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/anjaliup63/AI-Resume-Intelligence-RAG.git
cd AI-Resume-Intelligence-RAG
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

## Configure Gemini API

Create:

```text
.streamlit/secrets.toml
```

Add:

```toml
GEMINI_API_KEY="YOUR_API_KEY"
```

## Run Application

```bash
streamlit run app.py
```

---

# 📊 ATS Scoring Methodology

The ATS score is calculated using:

### Overall Match Score
- Semantic similarity between resume and JD

### Skills Score
- Matching technical skills
- Domain-specific keywords

### Experience Score
- Relevant experience detection

### Education Score
- Degree and qualification matching

---

# 🔍 Candidate Analysis Workflow

### Individual Analysis

1. Upload Resume
2. Paste Job Description
3. Generate Embeddings
4. Retrieve Relevant Context
5. Calculate ATS Scores
6. Generate AI Recommendations

### Batch Ranking

1. Upload Multiple Resumes
2. Enter Job Description
3. Calculate Similarity Scores
4. Rank Candidates
5. Identify Best Match

---

# 📸 Application Screenshots

### Home Page
Resume Upload + Job Description Input

### ATS Analysis Dashboard
Overall Score, Skills Score, Education Score, Experience Score

### AI Recommendations
Strengths, Weaknesses, Missing Skills, Suggestions

### Candidate Ranking
Ranked Candidate List

---

# 🎯 Use Cases

- HR Screening
- Recruitment Automation
- Placement Cell Evaluation
- Campus Hiring
- Resume Optimization
- ATS Readiness Assessment

---

# 🔮 Future Enhancements

- Resume Keyword Optimization
- Interview Question Generation
- Candidate Skill Gap Analysis
- Resume Summarization
- Recruiter Analytics Dashboard
- Cloud Database Integration

---

# 👩‍💻 Developer

**Anjali Upadhyay**

B.Tech Computer Science Engineering

Galgotias University

GitHub:
https://github.com/anjaliup63

LinkedIn:
https://www.linkedin.com/in/anjali-upadhyay95

---

# 📜 License

This project was developed as part of an AI Engineer Technical Assessment and is intended for educational, research, and recruitment purposes.
