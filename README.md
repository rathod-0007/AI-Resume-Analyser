# 🚀 AI Resume Analyser

![Resume Analyzer Banner](https://img.shields.io/badge/AI-Resume%20Analyser-blue)
![Python](https://img.shields.io/badge/Python-3.9%2B-brightgreen)
![Streamlit](https://img.shields.io/badge/Streamlit-Docker%20Space-red)
![Groq LLM](https://img.shields.io/badge/LLM-Groq-lightgrey)

An AI-powered resume analyser that compares resumes to job descriptions using NLP and vector similarity, offers tailored feedback, and even generates cover letters. Built with Streamlit, Groq API, SentenceTransformers, and deployed on Hugging Face via Docker.

<div align="center">
 <img src="https://github.com/rathod-0007/AI-Resume-Analyser/blob/main/assets/screenshot.png" alt="AI Resume Analyzer Screenshot" width="80%">
</div>

## 🌐 Live Demo

Try it instantly online:  
[🔗 AI Resume Analyser Web App](https://ai-resume-analyser-app.streamlit.app/)

## ✨ Features

- **Resume Upload**: Upload one or more PDF resumes for evaluation  
- **Job Description Input**: Paste or upload a JD to analyze against  
- **AI Cover Letter**: Get an AI-generated cover letter tailored to the job  
- **Match Scoring**: See how well your resume aligns with the job  
- **Skill Radar**: Visual radar chart of your skill alignment  
- **Missing Keywords**: Identify key skills missing from your resume  
- **Q&A Chatbot**: Ask questions based on your resume or JD  
- **Voice Input**: Use whisper to input JD via speech  
- **Groq API LLM**: High-speed inference with Groq LLM  
- **Streamlit Docker**: Fully containerized and deployed on Hugging Face

## 📸 Screenshots

<div align="center">
  <img src="https://github.com/rathod-0007/AI-Resume-Analyser/blob/main/assets/analysis.png" width="48%">
  <img src="https://github.com/rathod-0007/AI-Resume-Analyser/blob/main/assets/chat.png" width="48%">
  <p><i>Visual analysis and AI chat support</i></p>
</div>

## 📋 Prerequisites

- Python 3.9+
- Hugging Face Account (for deployment)
- Groq API Key ([Get it here](https://console.groq.com/))
- Docker (for container deployment)

## 🔧 Installation (Local)

```bash
git clone https://github.com/rathod-0007/AI-Resume-Analyser.git
cd AI-Resume-Analyser
pip install -r requirements.txt
streamlit run resume_analyser.py
