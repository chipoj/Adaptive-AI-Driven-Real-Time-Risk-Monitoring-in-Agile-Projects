# Adaptive AI-Driven Real-Time Risk Monitoring in Agile Projects

## Overview
This repository contains the implementation of a research project focused on applying adaptive artificial intelligence techniques to real-time risk monitoring in Agile software development environments.

The project evaluates and compares traditional machine learning models, ensemble learning methods, and adaptive streaming algorithms using multiple public Agile project datasets. It also includes a simulation layer using Jira-style workflows and a dashboard for visualising risk insights.

---

## Research Objective
The objective of this study is to identify and evaluate machine learning approaches capable of supporting real-time risk identification, prediction, and monitoring in Agile projects, where risks evolve dynamically across iterations.

---

## Key Features
- Multi-dataset Agile risk prediction pipeline
- Standardised data preprocessing and feature engineering
- Comparative analysis of:
  - Traditional machine learning models
  - Ensemble learning models
  - Adaptive/streaming models
- Cost-sensitive risk evaluation (False Positives vs False Negatives)
- Jira-based simulation of Agile project workflows
- Interactive dashboard for risk monitoring and insights

---

## Datasets
The project uses the following publicly available datasets:

- TAWOS Dataset  
- Jira Social Repository Dataset  
- User Story NeoDataset  
- Agile Scrum Sprint Velocity Dataset  

> Note: Due to size or licensing restrictions, datasets are not included in this repository. Please download them separately and place them in the `data/raw/` directory.

---

## Model Categories

### 1. Traditional Machine Learning
- Logistic Regression  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)  
- Decision Tree  

### 2. Ensemble Learning
- Random Forest  
- Extra Trees  
- Gradient Boosting  
- AdaBoost  

### 3. Adaptive / Streaming Models
- Hoeffding Adaptive Tree  
- Online Bagging / Adaptive methods (e.g., ADWIN-based approaches)  

---

## Evaluation Metrics
Models are evaluated using:

- Accuracy  
- Precision  
- Recall  
- F1-score  
- ROC-AUC  
- Confusion Matrix  
- Cost-sensitive analysis (impact of False Negatives vs False Positives)

---

## Project Structure
