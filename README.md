
# AI Resume Screening System

## Project Overview

The AI Resume Screening System is an NLP-based application designed to automate the resume screening process. The system analyzes resume text and predicts the most suitable job category using Machine Learning techniques.

This project helps recruiters reduce manual effort by automatically categorizing resumes into different domains such as:

- Data Science
- Python Developer
- Java Developer
- Web Developer
- HR
- Testing
- DevOps
- Sales
- Business Analyst

---

## Problem Statement

Recruiters receive hundreds of resumes for a single job opening. Manually reviewing each resume is time-consuming and inefficient.

This system automates the initial screening process using Natural Language Processing (NLP) and Machine Learning.

---

## Dataset

Dataset contains:

- Resume Text
- Job Category

Example:

| Resume | Category |
|----------|----------|
| Python, Machine Learning, Pandas | Data Science |
| Selenium, Manual Testing | Testing |

---

## Technologies Used

### Programming Language

- Python

### Data Analysis

- Pandas
- NumPy

### Visualization

- Matplotlib
- Seaborn

### Machine Learning

- Scikit-Learn

### NLP

- NLTK
- TF-IDF Vectorization

### Deployment

- Streamlit

---

## Workflow

### Data Collection

Resume dataset containing resumes and job categories.

### Data Preprocessing

- Lowercase Conversion
- Removing URLs
- Removing Special Characters
- Removing Stopwords
- Tokenization

### Feature Engineering

TF-IDF Vectorization

### Model Building

Algorithms Tested:

- Logistic Regression
- Random Forest
- Naive Bayes
- Support Vector Machine

### Hyperparameter Tuning

GridSearchCV

### Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## Project Architecture

Resume Input
↓
Text Cleaning
↓
TF-IDF Vectorization
↓
Machine Learning Model
↓
Category Prediction

---

## Features

✔ Upload Resume

✔ Automatic Resume Categorization

✔ Fast Prediction

✔ User-Friendly Interface

✔ Streamlit Web Application

---

## Results

Achieved high classification accuracy using TF-IDF and Machine Learning models.

Best Model:
Support Vector Machine (SVM)

Accuracy:
95%+

---

## Future Enhancements

- Resume Ranking
- Job Recommendation System
- Resume Parsing
- Skill Extraction
- LLM-Based Resume Analysis
- ATS Score Prediction

---

## Installation

```bash
git clone https://github.com/yourusername/resume-screening-system.git# Project Folder Structure
Resume-Screening-System/
│
├── data/
│   └── resume_dataset.csv
│
├── notebooks/
│   └── Resume_Screening.ipynb
│
├── models/
│   └── resume_classifier.pkl
│
├── screenshots/
│   ├── home_page.png
│   ├── prediction_page.png
│
├── app.py
├── train.py
├── requirements.txt
├── README.md
├── .gitignore
└── LICENSE
