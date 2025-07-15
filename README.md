# Resume-Shortlisting-System-Using-NLP-and-Machine-Learning
Automatically classifies resumes into job roles using NLP and ML. Uses SVM as the final model with 99.5% accuracy to help recruiters quickly filter candidates.
---

##  Project Overview

This project helps automate the process of resume screening by predicting the most suitable job role from resume text.  
It uses:
- **Natural Language Processing (NLP)** for text processing  
- **TF-IDF** for feature extraction  
- Machine Learning models for classification

---

##  Features

- Preprocesses resume text (cleaning, stopwords removal)
- Converts text into numerical features using TF-IDF
- Trains and evaluates multiple ML models
- Supports 25 job role categories
- Final model: **SVM** with 99.5% accuracy

---

##  Models Used

- Naive Bayes
- Logistic Regression
- **Support Vector Machine (SVM)** — Best performer

| Model                | Accuracy | F1-Score |
|---------------------|----------|----------|
| Naive Bayes         | 97.93%   | 97.73%   |
| Logistic Regression | 99.48%   | 99.49%   |
| **SVM (Best)**      | **99.5%**| **99.5%**|

---

##  Dataset

- **Source:** [Kaggle - Resume Dataset](https://www.kaggle.com/datasets/gauravduttakiit/resume-dataset)
- **Total resumes:** 962
- **Columns:**
  - `Resume` – Resume content in text format
  - `Category` – Job role label

---

## ▶ How to Run

1. Make sure Python is installed on your system
2. Install required libraries:
   ```bash
   pip install pandas numpy scikit-learn nltk
