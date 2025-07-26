# Breast Cancer Prediction using Machine Learning

This project uses supervised machine learning models to predict whether a tumor is benign or malignant based on features from the **Wisconsin Diagnostic Breast Cancer dataset**.

##  Problem Statement

Early detection of breast cancer significantly increases the chances of survival. This project builds classification models that can help predict the presence of cancer based on features like radius, texture, smoothness, symmetry, etc., extracted from digitized images of a breast mass.

##  Models Used
- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree Classifier

##  Dataset
- **Source**: [UCI Machine Learning Repository - Breast Cancer Wisconsin (Diagnostic)](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))
- The dataset contains 569 instances and 30 numerical features.

##  Libraries and Tools
- Python
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn

## Project Highlights
- Data preprocessing (handling null values, scaling, encoding)
- Exploratory Data Analysis (EDA)
- Model training, evaluation, and comparison using accuracy and classification report
- Confusion matrix visualization

## Accuracy Achieved
- Logistic Regression: ~96%
- SVM: ~98%
- Decision Tree: ~92%

##  How to Run
1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Open the notebook `BreastCancer_Prediction.ipynb` and run all cells.

---

##  Acknowledgments
Dataset provided by the UCI Machine Learning Repository. This project is built for educational purposes and aims to demonstrate how ML can assist in healthcare diagnostics.


