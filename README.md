# Predicting Antenatal Care Utilization Using Machine Learning

## Project Overview

This project applies supervised machine learning to predict antenatal care (ANC) utilization. It compares six classification algorithms using a Somali DHS dataset and explores predictive analytics in maternal healthcare research.

**Researchers:** Abdillahi Mohamed Abdillahi, Hawa Abdilahi Yusuf, Rahma Abdirizak Muhumed, Sainab Mohamed Saed, and Omran Salih 
**Institution:** Amoud University  
**Programming language:** Python  
**Research field:** Maternal health, medical statistics, and machine learning

## Research Objective

To develop and compare machine learning models for predicting complete and incomplete antenatal care utilization.

## Dataset and Outcome

The dataset was 8,179 records before preprocessing and a binary ANC utilization outcome.

**Outcome:** Complete versus incomplete antenatal care utilization.

## Machine Learning Algorithms

1. Logistic Regression
2. Decision Tree
3. Random Forest
4. K-Nearest Neighbors
5. Gradient Boosting
6. Support Vector Machine

## Analytical Workflow
## Model Evaluation

The notebook reports the following ROC-AUC values:

| Model | Reported ROC-AUC |
|---|---:|
| Logistic Regression | 0.810 |
| Gradient Boosting | 0.795 |
| Decision Tree | 0.663 |
| K-Nearest Neighbors | 0.649 |
| Random Forest | 0.605 |
| Support Vector Machine | 0.465 |

## Methodological Considerations

The dataset has substantial class imbalance. Accuracy alone is therefore insufficient for evaluating predictive performance.

## Software

- Python and Jupyter Notebook
- pandas and NumPy
- scikit-learn
- matplotlib and related visualization packages

## Repository Contents

- `Internship Project - ANC Utilization.ipynb` — Original analysis notebook
- `README.md` — Project documentation
- `.gitignore` — Python exclusions

## Reproducibility and Data Access

The notebook references `ANCinternship.csv`, which is not included in this repository.

The analysis cannot currently be reproduced independently without access to the dataset and confirmed dependencies.

Restricted or identifiable patient data must not be uploaded publicly without appropriate authorization.

## Research Relevance

This project demonstrates experience in supervised machine learning, statistical prediction, algorithm comparison, and computational health research, providing a foundation for advanced epidemiological modeling.

## Author

**Abdillahi Mohamed Abdillahi**  
Amoud University, Somaliland  
GitHub: https://github.com/Darik-ai

