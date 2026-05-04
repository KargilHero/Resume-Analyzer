# AI Hiring Platform – Smart Resume Analyzer & Job Matcher

## Overview

This project is a full-stack AI-powered hiring platform designed to streamline the recruitment process by intelligently analyzing resumes and matching candidates with suitable job roles.

The system processes uploaded resumes, extracts key information using Natural Language Processing (NLP), and evaluates candidate-job compatibility through a scoring mechanism.

---

## Key Features

### Resume Analysis

* Upload PDF resumes
* Extract skills, education, and experience
* Generate structured candidate profiles

### Intelligent Matching

* Match candidates with job roles
* Calculate Job Fit Score (JFS)
* Rank candidates based on relevance

### Dashboard

* Visual representation of:

  * Skill match percentage
  * Candidate ranking
  * Resume insights

### Recruiter Module

* Post job listings
* View matched candidates
* Filter applicants

### Candidate Module

* Upload resume
* Get personalized feedback
* View suggested roles

---

## Tech Stack

### Frontend

* React.js
* Modern UI with responsive design

### Backend

* Node.js
* Express.js

### Machine Learning

* Python
* NLP-based resume parsing

### Database

* MongoDB

---

## System Architecture

```id="arch123"
User Upload Resume
        ↓
Backend (Node.js)
        ↓
Resume Parsing + NLP
        ↓
ML Processing (Skill Extraction + Matching)
        ↓
Job Fit Score Calculation
        ↓
Results Stored in Database
        ↓
Frontend Dashboard Display
```

---

##  Project Structure

```id="struct123"
client/           → Frontend (React)
server/           → Backend (Node.js)
ml-module/        → Resume analysis (Python NLP)
database/         → Data storage logic
```

---

## ⚙️ Installation & Setup

### 1. Clone Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
```

### 2. Install Dependencies

#### Frontend

```bash
cd client
npm install
npm start
```

#### Backend

```bash
cd server
npm install
npm run dev
```

#### ML Module

```bash
cd ml-module
pip install -r requirements.txt
python app.py
```

---

##  Future Enhancements

*  Advanced ML models for better prediction
*  Real-time analytics dashboard
*  AI chatbot for career guidance
*  Resume improvement suggestions using LLMs

---

##  Key Learning Outcomes

* Built a scalable full-stack application
* Implemented NLP for real-world data processing
* Designed a modular architecture with ML integration
* Worked on candidate-job matching logic

---

##  Conclusion

This project demonstrates the integration of web development and machine learning to solve a real-world hiring problem. It highlights the ability to design, build, and scale intelligent systems.

---
