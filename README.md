# Resume-Relevance-Checker-System
How much percent will employess resume gives max score based on job description
Automated Resume Relevance Check System
📌 Overview

This project implements an AI-powered Resume Relevance Checker that evaluates resumes against job descriptions (JDs). It automates resume screening, generates a relevance score, highlights missing skills, and provides a fit verdict (High / Medium / Low) along with personalized improvement feedback.

The system is designed to reduce manual effort in resume shortlisting and make the evaluation process faster, consistent, and scalable.

🎯 Objectives

Automate resume evaluation against job requirements.

Generate a Relevance Score (0–100).

Highlight missing skills, certifications, and projects.

Provide a fit verdict: High / Medium / Low suitability.

Offer personalized improvement feedback to students.

Enable easy storage & visualization of results.

🛠️ Features

✔️ Resume & JD Parsing – Extracts structured text from resumes (PDF/DOCX) and job descriptions.
✔️ Hard Matching – Matches keywords, skills, and qualifications.
✔️ Semantic Matching – Uses embeddings to compare resumes with job descriptions contextually.
✔️ Scoring – Combines hard & semantic matches to calculate a relevance score.
✔️ Verdict – Classifies candidates into High / Medium / Low fit.
✔️ Feedback – Suggests missing skills and improvements.
✔️ Extensible – Can integrate with a dashboard / database for recruiters.

⚙️ Workflow

Job Requirement Upload – Placement team uploads JD.

Resume Upload – Candidate uploads resume.

Parsing – Extract text & clean formatting.

Relevance Analysis

Hard Match (keywords & skills)

Semantic Match (embeddings similarity)

Weighted Score calculation

Output

Relevance Score (0–100)

Missing Skills/Certifications/Projects

Fit Verdict: High / Medium / Low

Personalized Feedback

(Optional) – Store results in database / show on dashboard.

🧑‍💻 Tech Stack

Language: Python

Text Extraction: PyMuPDF / pdfplumber / python-docx

NLP & Preprocessing: spaCy / NLTK

Semantic Matching: Sentence Transformers / HuggingFace Embeddings / OpenAI Embeddings

Similarity Search: FAISS / Chroma / Pinecone

LLM Integration (optional): GPT / Gemini / Claude for advanced feedback

Frontend / Dashboard (optional): Streamlit or Flask + SQLite/PostgreSQL

🚀 Getting Started
1️⃣ Clone Repository
git clone https://github.com/yourusername/Resume_Relevance_Checker.git
cd Resume_Relevance_Checker

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run the Notebook

Open Resume_Relevance_Checker.ipynb in Jupyter/Colab and run all cells.

4️⃣ Upload Resume & JD

Resume: PDF/DOCX file

Job Description: TXT/PDF file

5️⃣ Get Results

Relevance Score (0–100)

Missing Skills / Gaps

Fit Verdict (High / Medium / Low)

Personalized Suggestions

📊 Example Output
Relevance Score: 72/100
Verdict: Medium Fit
Missing Skills: SQL, Cloud Computing
Feedback: Add a project showcasing cloud deployment and SQL database integration.

✅ Compliance with Theme 2 Requirements
Requirement	Status
Resume & JD Parsing	✅ Implemented
Hard & Semantic Matching	✅ Implemented
Relevance Score (0–100)	✅ Implemented
Fit Verdict (High/Medium/Low)	✅ Implemented
Missing Skills/Certifications/Projects	✅ Implemented
Personalized Feedback	⚠️ Basic (improvable with LLMs)
Dashboard & Storage	⚠️ Optional / not fully implemented in notebook
📌 Future Improvements

Build a recruiter dashboard with search & filtering.

Store evaluations in a database (SQLite/PostgreSQL).

Improve semantic feedback using LLMs.

Handle large-scale resume uploads and real-time scoring.

✍️ Author: Sreeram Venkata Phani Kiranmau  
🏫 Institution:JOY UNIVERSITY (Innomatics Research Labs (Hackathon Project))
