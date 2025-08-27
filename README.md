# DiseasePredictor
Disease Predictor 🩺

This project demonstrates how to build a Disease Prediction System using Google Colab with the Kaggle heart_disease_uci dataset. It applies machine learning techniques to classify whether a patient is likely to have heart disease, based on medical attributes.

***📂 Dataset***

Source: Kaggle - Heart Disease UCI Dataset

Features: Patient health indicators (age, sex, chest pain type, blood pressure, cholesterol, etc.)

Target: Presence or absence of heart disease

***🔧 Steps Performed***

Setup & Data Loading

Used Google Colab for development.

Loaded dataset from Kaggle into Colab environment.

Preprocessing

Handle Missing Values: Imputed or dropped missing records.

Encode Categorical Features: Applied one-hot encoding and label encoding where required.

Scale Data: Standardized features using StandardScaler for consistent model performance.

***Model Training***
Implemented machine learning models using scikit-learn:

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

***Model Evaluation***
Evaluated models with the following metrics:

Accuracy

Precision

Recall

F1-Score

ROC-AUC

Visualization

Confusion Matrix for each model

ROC Curve comparison

Performance metric plots

***📊 Results Summary***
Model	Accuracy	Precision	Recall	F1-Score	ROC-AUC
Logistic Regression	xx%	xx%	xx%	xx%	xx%
Decision Tree	xx%	xx%	xx%	xx%	xx%
Random Forest	xx%	xx%	xx%	xx%	xx%

(Replace xx% with actual results after running code.)

***📌 Requirements***

Python 3.x

Google Colab / Jupyter Notebook

scikit-learn

pandas

numpy

matplotlib

seaborn

Install dependencies if running locally:

pip install scikit-learn pandas numpy matplotlib seaborn

***🚀 How to Run***

Open project in Google Colab.

Mount Kaggle dataset into Colab.

Run all notebook cells sequentially:

Data preprocessing

Model training

Evaluation and visualization

Review results and compare model performance.

***📈 Key Learnings***

Data preprocessing (missing values, encoding, scaling) significantly affects model performance.

Ensemble methods like Random Forest generally outperform single models.

Evaluation with multiple metrics provides a more complete performance picture.

Ensemble methods like Random Forest generally outperform single models.

Evaluation with multiple metrics provides a more complete performance picture.
