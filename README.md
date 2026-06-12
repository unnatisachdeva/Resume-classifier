# Resume Classifier using NLP and Machine Learning

## Overview

This project is a Resume Classification System that automatically predicts the job category of a resume based on its textual content. The objective is to automate the resume screening process by classifying resumes into relevant job roles using Natural Language Processing (NLP) and Machine Learning techniques.

The project follows a complete machine learning workflow, including data preprocessing, feature extraction, model training, evaluation, and comparison of multiple classification algorithms.

---

## Problem Statement

Recruiters often receive hundreds of resumes for various job openings. Manually reviewing and categorizing these resumes is time-consuming and inefficient.

This project aims to automate that process by analyzing resume text and predicting the most suitable job category.

---

## Dataset

**Dataset:** Updated Resume Dataset

### Categories Included

- Data Science
- HR
- Java Developer
- Testing
- DevOps Engineer
- Mechanical Engineer
- Civil Engineer
- Advocate
- Sales
- Operations Manager
- Business Analyst
- ETL Developer
- SAP Developer
- Network Security Engineer
- And more...

**Total Categories:** 25

---

## Project Workflow

### 1. Data Cleaning & Preprocessing

- Removed duplicate records
- Converted text to lowercase
- Removed special characters and punctuation
- Removed newline characters and extra spaces
- Cleaned noisy resume text using Regular Expressions (Regex)

### 2. Label Encoding

The target variable (`Category`) was converted into numerical labels using `LabelEncoder`.

### 3. Feature Extraction

Applied **TF-IDF Vectorization** to convert resume text into numerical feature vectors suitable for machine learning models.

### 4. Train-Test Split

- Training Data: 80%
- Testing Data: 20%

### 5. Model Training

The following machine learning models were trained and evaluated:

- Logistic Regression
- Multinomial Naive Bayes
- Random Forest Classifier
- Linear Support Vector Machine (SVM)

### 6. Model Evaluation

Models were evaluated using:

- Accuracy Score
- Classification Report
- Confusion Matrix

---

## Results

| Model | Accuracy |
|---------|---------|
| Logistic Regression | 64.71% |
| Multinomial Naive Bayes | 26.47% |
| Random Forest | 76.47% |
| **Linear SVM** | **94.12%** |

### Best Model

Linear SVM achieved the highest accuracy of **94.12%** and was selected as the final model for resume classification.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Regular Expressions (Regex)
- Matplotlib
- Google Colab

---

## Project Structure

```text
Resume-Classifier/
│
├── Resume_Classifier.ipynb
├── UpdatedResumeDataSet.csv
├── README.md
└── svm_model.pkl
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Resume-Classifier.git
```

Navigate to the project directory:

```bash
cd Resume-Classifier
```

Install dependencies:

```bash
pip install pandas numpy scikit-learn matplotlib
```

---

## Running the Project

Open the notebook:

```text
Resume_Classifier.ipynb
```

Run all cells sequentially in:

- Google Colab
- Jupyter Notebook

---

## Sample Prediction

### Input Resume

```text
Python
Machine Learning
SQL
TensorFlow
Deep Learning
Data Analysis
Pandas
NumPy
```

### Predicted Category

```text
Data Science
```

---

## Key Learnings

Through this project, I learned:

- Text preprocessing for NLP applications
- TF-IDF feature extraction
- Multiclass classification
- Model evaluation and comparison
- Building an end-to-end machine learning pipeline
- Selecting the best model based on performance metrics

---

## Future Enhancements

- PDF Resume Upload
- Resume Parsing
- Skill Extraction using NLP
- Streamlit Web Application
- Top-3 Job Role Recommendations
- Confidence Score Display
- Deep Learning Models (LSTM, BERT)

---

## Author

**Unnati Sachdeva**

Computer Science Engineering Student  
Machine Learning & NLP Enthusiast

