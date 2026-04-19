## RTA-Accident-Severity-Prediction

## 📌 Project Overview
This project predicts road accident severity using a Multi-Layer Perceptron (MLP) model and explains predictions using SHAP.

## ⚙️ Tech Stack
- Python
- TensorFlow / Keras
- Scikit-learn
- SHAP
- Matplotlib / Seaborn

## 📊 Dataset
RTA Dataset (Road Traffic Accident Data)

## 🔍 Features Used
Includes:
- Driver details
- Vehicle information
- Road conditions
- Weather conditions
- Accident cause

## 🧠 Model
- MLP (Neural Network)
- SMOTE used to handle class imbalance

## 📈 Results
- Accuracy: ~75–85%
- Balanced classification across 3 severity levels

## 🔎 Explainability
SHAP used for:
- Feature importance
- Prediction explanation
- Model transparency

## 📁 Outputs
Saved in `/outputs`:
- Distribution plot
- Training curves
- Confusion matrix
- SHAP plots

## ▶️ How to Run
1. Install dependencies:
   pip install -r requirements.txt

2. Run notebook:
   notebook/rta_severity_model.ipynb
