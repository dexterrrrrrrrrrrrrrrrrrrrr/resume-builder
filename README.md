# AI Resume Builder

[![Python](https://img.shields.io/badge/python-3.10+-blue)](https://www.python.org/) 
[![Streamlit](https://img.shields.io/badge/streamlit-v1.28-orange)](https://streamlit.io/) 
[![License](https://img.shields.io/badge/license-MIT-green)](LICENSE) 
[![Demo](https://img.shields.io/badge/live-demo-blue)](YOUR_DEPLOYED_LINK_HERE)

**AI Resume Builder** is a production-ready Streamlit web application that converts your raw career data into **ATS-optimized, professional DOCX resumes**. Paste a job description to receive **real-time ATS scoring** using TF-IDF cosine similarity, **AI-powered skill gap analysis**, and keyword matching powered by **Groq's Llama-3.3-70b**. Enhance project descriptions with quantifiable achievements and generate smart skill recommendations automatically. Preview live HTML resumes with professional typography and export polished DOCX files that pass ATS parsers. Graceful fallbacks ensure full functionality without API keys.  

**Live Demo:** [Try it here](https://resume-builder-q6rfrkomvtunq6j8q2sevj.streamlit.app/)  

---

## 🚀 Quick Start
```bash
# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py
```

## 🌟 Features
	•	✅ ATS Score – Evaluate resumes using TF-IDF & keyword matching
	•	✅ AI Resume Coaching – Personalized suggestions powered by Groq Llama-3.3
	•	✅ Live HTML Preview – Check formatting in real-time
	•	✅ Professional DOCX Export – Generate ATS-friendly resumes
	•	✅ Skill Gap Analysis – Identify missing skills for your target role
	•	✅ Enhanced Project Descriptions – Auto-improve experiences with measurable achievements

⸻

## 🛠 Built With
	•	Streamlit – Web app framework
	•	python-docx – DOCX generation
	•	scikit-learn – ATS scoring & TF-IDF
	•	Groq Llama-3.3-70b – AI-powered skill analysis

⸻

## ⚡ How It Works
	1.	Paste your career data and the target job description
	2.	View ATS score and skill gap analysis instantly
	3.	Auto-enhanced project descriptions with measurable achievements
	4.	Preview live HTML resume
	5.	Export polished DOCX ready for submission
