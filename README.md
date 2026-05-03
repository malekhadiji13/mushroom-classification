# mushroom-classification
# Comparative Analysis of ML & Deep Learning Models for Mushroom Binary Classification

A fully explainable comparative study of 5 Machine Learning and 3 Deep Learning 
models for mushroom binary classification — covering EDA, data preprocessing, model 
evaluation, and interpreted results with a detailed written report.

Developed as part of MBA 523: Neural Networks & Deep Learning  
Master's in Business Analytics — Tunis Business School, 2024/2025

---

## About This Project

This project goes beyond running models — every step is fully explained and 
interpreted, from exploratory data analysis and preprocessing decisions to model 
selection rationale and result analysis.

The report documents all findings in detail, making this a complete 
end-to-end explainable AI study.

---

## Problem Statement

Classifying mushrooms as edible or poisonous is a critical task with direct health 
implications. This project explores and compares multiple ML and DL approaches to 
solve this binary classification problem using structured mushroom feature data.

---

## Dataset

- 54,035 rows × 9 features
- Features: Cap Diameter, Cap Shape, Gill Attachment, Gill Color, Stem Height, 
  Stem Width, Stem Color, Season, Class (target)
- Target: 0 = Edible, 1 = Poisonous (55% / 45% — relatively balanced)
- No missing values
- Source: [Kaggle — Mushroom Dataset](https://www.kaggle.com/datasets/uciml/mushroom-classification)

---

## Models Compared

**Machine Learning**
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes
- Logistic Regression
- Decision Tree
- Random Forest

**Deep Learning**
- Artificial Neural Network (ANN)
- Convolutional Neural Network (CNN)
- Recurrent Neural Network (RNN)

---

## Results

| Model | Accuracy |
|-------|----------|
| Random Forest | 99.1% |
| KNN | 99.1% |
| Decision Tree | 97.8% |
| CNN | 98.2% | 
| ANN | 97.7% | 
| RNN | 87.1% | 
| Logistic Regression | 63.7% | 
| Gaussian Naive Bayes | 63.3% | 

**Key finding:** Random Forest and KNN were the top performers overall. Among deep 
learning models, CNN achieved the best recall and F1-score. RNN, Logistic Regression, 
and Naive Bayes were the weakest fits for this dataset.

---

## Tech Stack

- Python, Jupyter Notebook
- scikit-learn, TensorFlow / Keras
- pandas, NumPy, Matplotlib, Seaborn

---

## Project Structure

- `mushroom_classification.ipynb` — Full explainable analysis and model code
- `mushroom_classification_report.pdf` — Detailed report
- `mushroom_cleaned.csv` — Dataset
- `requirements.txt` — Python dependencies
