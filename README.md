# Symptom-Based Disease Classification Using ML Algorithms

This GitHub repository focuses on health diagnosis prediction using machine learning. The project leverages a dataset containing symptoms and corresponding disease prognoses based on symptoms using a dataset of 4920 entries. The primary objective is to build accurate and interpretable models for predicting health diagnoses based on observed symptoms. Key models include Logistic Regression, Random Forest, Decision Tree, Naive Bayes, Support Vector Machine, K-Nearest Neighbors and a Voting Classifier (an ensemble of numerous models). The dataset can be obtained from [here](https://www.kaggle.com/datasets/kaushil268/disease-prediction-using-machine-learning).

## Dataset Characteristics:
- **Size:** 4920 entries, 132 features.
- **Format:** Binary (0s, 1s) indicating symptom presence.
- **Target:** 'prognosis' column for diagnosed diseases.

The dataset is balanced and straightforward.

## Contents
### Exploratory Data Analysis and Visualization:
- Detailed insights into the dataset's structure, characteristics and an EDA highlighting patterns among symptoms and diseases using visualizations.

## Data Preprocessing:
- Steps taken to clean the data, dropping irrelevant features and feature selection using chi-squared test to make the dataset suitable for applying machine learning algorithms.

## Machine Learning Models:
- Implementing and training various machine learning models, including Logistic Regression, Random Forest, Decision Tree, Naive Bayes, SVM, KNN and a Voting Classifier using Decision Tree and KNN.

## Performance Evaluation and Model Explainability:
- Evaluating model performance using metrics like accuracy, precision, recall and F1 score.
- Visualizing the decision trees for the Random Forest and Decision Tree, along with feature importance for Decision Tree.
- Employing SHAP (SHapley Additive exPlanations) for model explainability.

## Key Features
**Symptoms-Disease Network**
![Symptoms-Disease Network](Symptoms_Disease_Network.png)
The graph visualizes the Symptoms-Disease Network, where diseases and symptoms are represented as nodes, and the edges indicate the relationship between symptoms and the diseases they are associated with. The network aids in understanding symptom co-occurrences.