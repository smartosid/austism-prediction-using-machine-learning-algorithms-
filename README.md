# 🧠 Autism Spectrum Disorder (ASD) Prediction using Machine Learning

This project focuses on early prediction of **Autism Spectrum Disorder (ASD)** using machine learning models trained on behavioral screening data. The goal is to support early screening and diagnosis using simple, structured data inputs.

## 📊 Dataset

The dataset used is sourced from publicly available autism screening data, which typically includes:

- Responses to behavioral screening questions (Yes/No)
- Demographic attributes (Age, Gender, Ethnicity, etc.)
- Family history
- Result from standard autism screening tools

> Dataset format: `.csv`  
> Target column: `Class/ASD_Traits`

## 🧪 Machine Learning Models Used

- **Logistic Regression**
- **Support Vector Machine (SVM)**
- **Random Forest Classifier**
- **XGBoost Classifier**

Each model is evaluated using:
- Accuracy
- Confusion Matrix
- Classification Report (Precision, Recall, F1-Score)

## ⚙️ Technologies

- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib, Seaborn (for visualization)
- Jupyter Notebook / Google Colab

## 📁 Project Structure

autism-ml-prediction/
│
├── data/
│ └── autism_data.csv
├── notebooks/
│ └── autism_model_training.ipynb
├── results/
│ ├── confusion_matrix_svm.png
│ ├── confusion_matrix_rf.png
│ ├── confusion_matrix_xgb.png
│ └── classification_report.txt
├── autism_model.pkl
├── README.md
└── requirements.txt
