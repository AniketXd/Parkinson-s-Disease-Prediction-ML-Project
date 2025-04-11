# 🧠 Parkinson's Disease Detection using Machine Learning

This repository contains a complete machine learning pipeline for detecting Parkinson's Disease using biomedical voice measurements. The models applied in this project include Random Forest, Support Vector Machine, Voting Classifier, and Stacking Classifier — each evaluated on accuracy, F1 Score, and AUC-ROC metrics.

---

## 📊 Dataset

- **Source**: UCI Machine Learning Repository  
- **Created by**: Max Little (University of Oxford) in collaboration with the National Centre for Voice and Speech, Denver, Colorado  
- **Features**: 22 biomedical voice features + 1 target variable  
- **Target**: `status` (1 = Parkinson’s, 0 = Healthy)

---

## ⚙️ Preprocessing

- Unused columns (like `name`) were removed.
- Features were normalized using **MinMaxScaler** to scale all input features to a [0, 1] range.
- The dataset was split into training and testing sets using an 80:20 ratio.

---

## 🤖 Models Implemented

| Model                | Accuracy | F1 Score | AUC  |
|---------------------|----------|----------|------|
| Random Forest        | 0.9324   | 0.9351   | 0.98 |
| SVM                  | 0.9054   | 0.9067   | 0.95 |
| Voting Classifier    | 0.9324   | 0.9351   | 0.98 |
| Stacking Classifier  | 0.9324   | 0.9351   | 0.99 |

---

## 📈 Visualizations

- 📌 Correlation Heatmap (feature relationship analysis)
- 📊 Accuracy Comparison Bar Graph
- 🔁 AUC-ROC Curves for all models in a single plot

---

## 🧪 Evaluation Metrics

- **Accuracy**: Correct predictions / total predictions  
- **F1 Score**: Harmonic mean of precision and recall  
- **AUC-ROC**: Measures true positive rate vs. false positive rate

---


