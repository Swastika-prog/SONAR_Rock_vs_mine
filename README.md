# 🎵 SONAR Rock vs Mine Classification

This project uses machine learning to classify whether an object detected by sonar is a **rock** or a **mine (metal object)**. The dataset consists of sonar signals bounced off different surfaces, and the model predicts the type of object based on the frequency patterns.

## 📂 Project Overview
- Load and preprocess the sonar dataset
- Train a machine learning classifier
- Evaluate model performance
- Predict whether a new input is a rock or a mine

## 🛠 Features
- Data preprocessing and exploration
- Splitting dataset into training and testing sets
- Model training using Logistic Regression (or other classifiers)
- Performance evaluation using accuracy score
- Predictive system for new sonar readings

## 📊 Dataset
The dataset contains **60 features** representing energy values of sonar signals at different frequencies, and a label:
- **R** = Rock
- **M** = Mine

(*Dataset source: UCI Machine Learning Repository - Sonar Dataset*)

## 🧑‍💻 Technologies Used
- Python 3
- Jupyter Notebook
- NumPy
- Pandas
- scikit-learn

## 🚀 Getting Started

### Prerequisites
Install the required libraries:
```bash
pip install numpy pandas scikit-learn
# SONAR_Rock_vs_mine
