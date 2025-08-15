# 🚀 AI Resume Analyser

![Resume Analyzer Banner](https://img.shields.io/badge/AI-Resume%20Analyser-blue)
![Python](https://img.shields.io/badge/Python-3.9%2B-brightgreen)
![Streamlit](https://img.shields.io/badge/Streamlit-Docker%20Space-red)
![Groq LLM](https://img.shields.io/badge/LLM-Gemini-lightgrey)

An AI-powered resume analyser that compares resumes to job descriptions using NLP and vector similarity, offers tailored feedback, and even generates cover letters. Built with Streamlit, Gemini API, SentenceTransformers, and deployed on Streamlit.

<div align="center">
 <img src="https://github.com/pawan941394/-AI-Resume-Analyzer/blob/main/screenshoots/Screenshot%202025-03-29%20115400.png" alt="AI Resume Analyzer Screenshot">
</div>

## 🌐 Live Demo

Try it instantly online:  
[🔗 AI Resume Analyser Web App](https://ai-resume-analyser-app.streamlit.app/)

## ✨ Features

- **Resume Upload**: Upload one or more PDF resumes for evaluation  
- **Job Description Input**: Paste or upload a JD to analyze against  
- **AI Cover Letter**: Get an AI-generated cover letter tailored to the job  
- **Match Scoring**: See how well your resume aligns with the job   
- **Missing Keywords**: Identify key skills missing from your resume  
- **Q&A Chatbot**: Ask questions based on your resume or JD  
- **Gemini API LLM**: High-speed inference with Gemini LLM  
- **Streamlit Docker**: Fully containerized and deployed on Streamlit
## 🎥 Live Demo & Walkthrough

[![Watch the demo](https://img.youtube.com/vi/VIDEO_ID_HERE/0.jpg)](https://github.com/user-attachments/assets/5f177f81-bd94-452e-a377-e1b84f6474fa)

<p align="center"><i>Click the image above to watch a quick demo of the AI Resume Analyzer</i></p>



## 📋 Prerequisites

- Python 3.9+
- Hugging Face Account (for deployment)
- Gemini API Key ([Get it here](https://ai.google.dev/gemini-api/docs/api-key))
- Streamlit (for opensource deployment)

## 🔧 Installation (Local)

```bash
git clone https://github.com/rathod-0007/AI-Resume-Analyser.git
cd AI-Resume-Analyser
pip install -r requirements.txt
streamlit run resume_analyser.py
```
---

## 🛠 How It Works
- Extract Resume Text using **PyPDF2**
- Embed Texts with **sentence-transformers**
- Compare with JD using **cosine similarity**
- Score & Recommend improvements
- Generate a Cover Letter
- Use **Gemini LLM** to accelerate responses

---

## 📦 Tech Stack
- **Python**, **Streamlit**
- **SentenceTransformers** (NLP)
- **Gemini API** (LLM)
- **PyPDF2** (PDF parsing)
- **Docker**, **Streamlit**

---

## 🐳 Streamlit Deployment (For streamlitshare.io)
1. Ensure your main.py runs: `streamlit run resume_analyser.py`
2. Push to Streamlit
3. Add environment secret `GEMINI_API_KEY` from Google Gemini Studio
4. Done! App will run on `Streamlit`

---

## 🔐 API Key Setup
- Get your **Gemini API key** from [Google Gemini Studio](https://ai.google.dev/gemini-api/docs/api-key)
- Set it as an environment variable:
  - In `.env`: `GEMINI_API_KEY=your_key`

---

## 👤 Author
**Rathod Pavan Kumar Naik**  
GitHub: [@rathod-0007](https://github.com/rathod-0007)  
Project: [AI-Resume-Analyser](https://github.com/rathod-0007/AI-Resume-Analyser)

---

## 📄 License
This project is licensed under the **Apache License 2.0** — see the [LICENSE](https://github.com/rathod-0007/AI-Resume-Analyser/blob/main/LICENSE) file.

---

## ⭐️ Support
If you found this project helpful, consider giving it a **⭐️** on GitHub!
