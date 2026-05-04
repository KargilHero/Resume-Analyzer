## AI-Powered Hiring Platform

## Overview

Smart Hire is a full-stack web application designed to streamline the recruitment process using intelligent resume analysis and candidate-job matching.

This project is inspired by existing open-source implementations and further explored to understand real-world system design involving frontend, backend, and machine learning integration.

---

## Features

### For Job Seekers

* Upload resume (PDF)
* Automatic extraction of:

  * Skills
  * Education
  * Experience
* Profile generation with minimal manual input
* Get feedback on:

  * Missing skills
  * Job suitability

---

### For Recruiters

* Create job postings with requirements
* View candidate applications
* Filter candidates based on relevance
* Analyze applicants using scoring system

---

### AI / ML Capabilities

* Resume parsing using NLP techniques
* Candidate-job matching
* Job Fit Score (JFS) calculation (based on skills and criteria)

---

## Tech Stack

### Frontend

* React.js
* Next.js

### Backend

* Node.js
* Express.js

### Machine Learning

* Python
* Streamlit

### Database

* MongoDB

---

## Project Structure

```id="tree001"
client/             → Frontend application  
server/             → Backend APIs  
resume-analyser/    → ML-based resume processing  
cv-builder/         → Resume builder module  
chat/               → Communication module  
```

---

## Local Setup

### 1. Clone the Repository

```bash id="cmd001"
git clone <your-repo-link>
```

---

### 2. Start Frontend

```bash id="cmd002"
cd client
npm install
npm start
```

---

### 3. Start Backend

```bash id="cmd003"
cd server
npm install
npm start
```

---

### 4. Run Resume Analyzer

```bash id="cmd004"
cd resume-analyser
pip install -r requirements.txt
python app.py
```

---

## System Flow

```id="flow001"
User uploads resume
        ↓
Backend processes request
        ↓
Resume Analyzer extracts data
        ↓
Matching logic calculates score
        ↓
Results displayed on dashboard
```

---

## Learning Outcomes

* Understanding full-stack architecture
* Integrating ML with web applications
* Working with REST APIs and modular systems
* Resume parsing and data extraction techniques

---

## Note

This project is based on an open-source implementation and has been used for learning and experimentation purposes. Further enhancements and custom features can be added to improve scalability and accuracy.

---

## Future Improvements

* Advanced ML models for better prediction
* Real-time analytics dashboard
* AI-based career assistant chatbot
* Improved ranking algorithms

---
