# SmartResumeAI – Resume Analyzer Baseline

**Course:** CSE 598 – Capstone Project  
**University:** Arizona State University

## Project Overview

SmartResumeAI is a baseline AI-inspired Resume Analyzer developed as part of the CSE598 Capstone Project.

The system compares a candidate's resume with a given job description and provides an Applicant Tracking System (ATS)-style analysis.

The goal of this baseline is to demonstrate a complete, runnable, and reproducible workflow that can later be extended using Large Language Models (LLMs), Retrieval-Augmented Generation (RAG), or Agentic AI.

---

# Features

- Upload Resume (PDF)
- Extract Resume Text
- Compare Resume with Job Description
- Detect Technical Skills
- Calculate ATS Compatibility Score
- Identify Matching Skills
- Identify Missing Skills
- Identify Extra Skills
- Generate Resume Summary
- Generate Resume Improvement Suggestions
- Generate Interview Questions
- Export Report as:
  - TXT
  - PDF
  - DOCX
  - HTML

---

# Project Structure

```
SmartResumeAI/

│── SmartResumeAI_Baseline.ipynb

│── README.md

│── requirements.txt

│── sample_resume.pdf

│── sample_job.txt

│── screenshots/
│      baseline_output.png

│── reports/
│      SmartResumeAI_Report.txt
│      SmartResumeAI_Report.pdf
│      SmartResumeAI_Report.docx
│      SmartResumeAI_Report.html
```

---

# Requirements

Python 3.10 or later

Required Libraries

- pypdf
- python-docx
- reportlab
- ipywidgets

Install all dependencies using

```bash
pip install -r requirements.txt
```

---

# Running the Project

This project is designed to run in **Google Colab**.

Steps:

1. Open `SmartResumeAI_Baseline.ipynb`.
2. Run all notebook cells from top to bottom.
3. Upload a resume in PDF format.
4. Enter or edit the provided job description.
5. View the generated ATS analysis.
6. Download the generated report in the desired format (TXT, PDF, DOCX, or HTML).

---

# Input

### Resume

Upload

```
sample_resume.pdf
```

### Job Description

Edit or replace

```
sample_job.txt
```

with the desired job description.

---

# Output

The notebook generates:

- Resume Summary
- ATS Compatibility Score
- Matching Skills
- Missing Skills
- Extra Skills
- Resume Improvement Suggestions
- Suggested Interview Questions

The report can be downloaded as:

- TXT
- PDF
- DOCX
- HTML

---

# Sample Test Case

### Resume

Software Engineering student with experience in:

- Python
- SQL
- React
- Git

### Job Description

Software Engineer Intern

Required Skills

- Python
- SQL
- Docker
- AWS
- Git
- REST API

### Expected Output

- ATS Score
- Matching Skills
- Missing Skills
- Resume Suggestions
- Interview Questions

---

# Screenshot

A sample execution screenshot is available in

```
screenshots/baseline_output.png
```

---

# Limitations

This baseline uses rule-based keyword matching for resume analysis.

Current limitations include:

- No semantic skill matching
- No Large Language Model integration
- Single resume analysis
- Limited predefined skills database

---

# Future Improvements

The baseline will be extended to include:

- Google Gemini Integration
- Retrieval-Augmented Generation (RAG)
- Semantic Resume Matching
- Multi-Agent Resume Evaluation
- Personalized Resume Recommendations
- Improved ATS Scoring

---

# Author

Your Name

Master of Science in Computer Science

Arizona State University