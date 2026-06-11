
## 🚀 AI Career Coach (Flask + LangChain + FAISS + OpenAI)
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:6a11cb,100:2575fc&height=200&section=header&text=AI%20Career%20Coach&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=AI%20Powered%20Career%20Guidance%20System&descAlignY=55&descAlign=50"/>
</p>
An AI-powered Career Coaching Web Application that analyzes resumes, generates professional summaries, and provides intelligent Q&A over uploaded resume content using LangChain, FAISS, HuggingFace embeddings, and OpenAI GPT-4o.

## 📌 Features
- 📄 Upload Resume (PDF format)
- 🤖 AI-powered Resume Analysis
- 🧠 Career Summary Generation
- 🔍 Ask Questions from Resume (RAG-based QA)
- 📚 Vector Search using FAISS
- 🧩 HuggingFace Embeddings
- ⚡ OpenAI GPT-4o Integration
- 🌐 Flask Web Application

## 🏗️ Project Architecture
```text
User → Upload Resume (PDF)
        ↓
PDF Text Extraction (PyPDF2)
        ↓
Text Splitting (LangChain)
        ↓
Embeddings (HuggingFace)
        ↓
Vector Store (FAISS)
        ↓
LLM (GPT-4o via LangChain)
        ↓
AI Resume Summary + Q&A System
''' 

## 🛠️ Tech Stack

<p align="center">

<img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Flask-Web%20Framework-000000?style=for-the-badge&logo=flask&logoColor=white" />
<img src="https://img.shields.io/badge/LangChain-AI%20Framework-1C3C3C?style=for-the-badge&logo=chainlink&logoColor=white" />
<img src="https://img.shields.io/badge/OpenAI-GPT--4o-412991?style=for-the-badge&logo=openai&logoColor=white" />
<img src="https://img.shields.io/badge/FAISS-Vector%20Database-FF6F00?style=for-the-badge&logo=meta&logoColor=white" />
<img src="https://img.shields.io/badge/HuggingFace-Transformers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" />
<img src="https://img.shields.io/badge/PyPDF2-PDF%20Processing-DC143C?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" />
<img src="https://img.shields.io/badge/HTML5-Frontend-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
<img src="https://img.shields.io/badge/CSS3-Styling-1572B6?style=for-the-badge&logo=css3&logoColor=white" />

</p>


## 📂 Project Structure

```text
AI-Career-Coach/
│
├── app.py
├── uploads/
├── vector_index/
├── templates/
│   ├── index.html
│   ├── results.html
│   ├── ask.html
│   └── qa_results.html
│
├── static/
│
└── README.md
```

