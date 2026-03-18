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


---

## Technology Stack

- Python  
- pandas, NumPy  
- scikit-learn  
- River (for streaming models)  
- Streamlit  
- Jira REST API  

---

## Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/your-username/adaptive-agile-risk-monitoring.git
cd adaptive-agile-risk-monitoring

###  2. Create virtual environment
python -m venv venv
source venv/bin/activate      # Linux / Mac
venv\Scripts\activate         # Windows

### 3. Install dependencies
pip install -r requirements.txt

###  4. Add datasets

Place all datasets inside:
data/raw/
Running the Project
Run full pipeline

python scripts/run_pipeline.py

Train models
python scripts/train_all_models.py

### Evaluate models
python scripts/evaluate_all_models.py

### Simulate Jira workflow
python scripts/simulate_jira_stream.py

### Launch dashboard
streamlit run src/dashboard/app.py


### Key Findings

- Ensemble models (e.g., Random Forest, Gradient Boosting) achieved the best overall predictive performance.

- Traditional models provided interpretable baselines but struggled with complex patterns.

- Adaptive/streaming models demonstrated potential in handling evolving risks, particularly in dynamic Agile environments.

- Cost-sensitive evaluation highlighted the critical importance of minimizing False Negatives in risk prediction.

## Future Work
- Integration of Large Language Models (LLMs) for risk identification from textual data

- Reinforcement learning for automated risk mitigation strategies

- Real-time deployment in production Agile environments

- Multi-agent AI systems for collaborative risk monitoring

### Author
## Chipo Jokonya
MSc Applied Data Science
Group IT Manager | Data & AI Enthusiast

## License

This project is licensed under the MIT License.

## cknowledgements

This work was conducted as part of a postgraduate research study in applied data science, focusing on AI-driven risk management in Agile software projects.

---
