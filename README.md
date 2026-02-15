**🏥 Multiple Disease Classification Model**

**Overview**
This project focuses on building a multi-class machine learning model to predict diseases based on reported symptoms.
The dataset consists of 4,920 patient records with 132 symptom features mapped to 41 different diseases. The objective was to train a classification model capable of identifying the correct disease from a given symptom combination.

**Problem Statement:**

Given a set of binary symptom indicators (0 = No, 1 = Yes), predict the most probable disease (prognosis).
Dataset Details
Total Records: 4,920
Total Features: 132 (Symptom-based features)
Target Variable: prognosis
Total Disease Classes: 41
The dataset is unstructured and clean with missing values.

**Approach**
Imported and validated the dataset
Separated features and target variable
Performed train-test split
Trained a Random Forest Classifier
Evaluated model performance using:
Accuracy Score
Confusion Matrix
Classification Report

**Model Used:**
RandomForestClassifier (Scikit-learn)
Random Forest was chosen due to its ability to handle high-dimensional feature spaces and multi-class classification effectively.

**Results:**
The model achieved high classification accuracy on the test dataset.
Performance metrics indicate strong precision and recall across all disease classes.

**Tech Stack:**
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn

**Project Structure:**
Multiple-Disease-Classification-Model/
│
├── Multiple_Disease_Prediction.ipynb
├── README.md
├── requirements.txt

**Future Improvements:**
1. Cross-validation for more robust evaluation
2. Feature importance analysis
3. Comparison with other classification models
4.Deployment using a lightweight web interface

**Somesh Ashok Bagal
Data Analyst**

This looks clean, professional, and natural — not AI-heavy.

If you want, I can also slightly tune it depending on whether you want it to look more ML-focused or more Data Analyst portfolio-oriented.
