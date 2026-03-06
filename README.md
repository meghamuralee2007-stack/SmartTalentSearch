SmartTalent AI – Semantic Resume Ranking Engine

Project Title

SmartTalent AI: Semantic Talent Selection Engine


---

The Problem

Recruiters face a major challenge during high-volume hiring when a single job posting receives hundreds or even thousands of resumes. Traditional Applicant Tracking Systems (ATS) rely on basic keyword matching, which often fails to understand the semantic meaning of a candidate's experience.

As a result, highly qualified candidates may be rejected simply because they used different terminology than the job description. At the same time, recruiters spend significant time manually reviewing resumes, leading to inefficiencies, fatigue, and missed talent opportunities.


---

The Solution

SmartTalent AI is an AI-powered semantic resume analysis platform that intelligently parses resumes, extracts candidate profiles, and ranks applicants based on their compatibility with a given Job Description (JD).

Instead of relying on simple keyword matching, the system uses semantic understanding and skill mapping to recognize related technologies, experience levels, and project depth.

The platform provides recruiters with:

Bulk Resume Upload Portal

Intelligent Resume Parsing

Semantic Skill Mapping

Candidate Ranking Dashboard

AI-generated candidate fit summaries


This allows recruiters to quickly identify the top candidates from large applicant pools, reducing manual effort and improving hiring accuracy.


---

Key Features

1. Multi-Format Resume Upload Portal

Recruiters can upload multiple resumes simultaneously.

Supported formats:

PDF

DOCX

JPG / PNG (image resumes)


Capabilities:

Bulk upload support

File validation

Upload progress tracking

Batch grouping by job role



---

2. Intelligent Resume Parser

The system extracts structured data from unstructured resumes.

Extracted information includes:

Candidate Name

Contact Information

Skills

Work Experience

Academic Projects

Certifications

Education


The parser can handle:

Two-column layouts

Tables

Complex resume designs



---

3. Semantic Skill Mapping Engine

The platform understands relationships between technologies.

Examples:

React → Frontend Development

PyTorch → Machine Learning

Node.js → Backend Development


This ensures candidates are not rejected simply due to different wording.


---

4. JD-to-Candidate Ranking System

Recruiters upload a Job Description, and the system ranks candidates automatically.

Features include:

Compatibility Score (0–100%)

Skill Matching

Experience Weighting

Semantic Similarity Analysis



---

5. AI Candidate Justification

For the Top 5 candidates, the system generates an AI summary explaining why they are a strong match.

Example:

> "The candidate matches the required 3+ years of React experience and demonstrates strong backend API development skills using Node.js."




---

Tech Stack

Frontend

React.js

Tailwind CSS

Axios

Chart.js (for analytics visualization)


Backend

Python

FastAPI

LangChain

Sentence Transformers (semantic similarity)


Resume Processing

PyMuPDF

python-docx

Tesseract OCR (for image resumes)


Database

MongoDB


AI / NLP

Sentence-BERT

OpenAI / LLM APIs



---

System Architecture

Recruiter Uploads Resumes
        │
        ▼
Resume Parsing Engine
        │
        ▼
Structured Candidate Profiles
        │
        ▼
Semantic Skill Mapping Engine
        │
        ▼
JD Similarity Scoring Model
        │
        ▼
Candidate Ranking Dashboard


---

Setup Instructions

1. Clone the Repository

git clone (git url)
cd smarttalent-ai


---

2. Backend Setup

Install dependencies:

pip install -r requirements.txt

Run the backend server:

uvicorn server:app --reload

Backend will run on:

http://localhost:8000


---

3. Frontend Setup

Navigate to frontend directory:

cd frontend

Install dependencies:

npm install

Start the frontend:

npm start

Frontend will run on:

http://localhost:3000


---

4. Environment Variables

Create .env file in backend folder.

Example:

OPENAI_API_KEY=your_api_key
MONGO_URI=mongodb://localhost:27017


---

Usage Workflow

1. Recruiter logs into dashboard


2. Uploads multiple resumes


3. System parses and extracts candidate data


4. Recruiter uploads Job Description


5. AI engine calculates compatibility score


6. Candidates are ranked automatically


7. Recruiter reviews top candidates with AI explanations




---

Video Demo

Duration: 2–3 minutes

The demo video demonstrates:

Resume upload

Parsing process

Job description upload

Candidate ranking dashboard

AI justification for top candidates



---

Live Demo (Optional)

Example:

https://


---

Future Improvements

LinkedIn profile analysis

Automated interview question generation

Bias detection in hiring

Candidate skill graph visualization

ATS integration
