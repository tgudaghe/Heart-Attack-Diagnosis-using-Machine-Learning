# Heart-Attack-Diagnosis-using-Machine-Learning

Heart disease remains one of the most significant causes of death worldwide. Early identification of high-risk individuals can reduce mortality rates by enabling timely medical intervention. Traditional methods rely on clinical judgment, which can be subjective and inefficient. This project aims to develop a machine learning model that predicts heart disease risk based on patient attributes.


## 📌 Project Overview

This project demonstrates the application of advanced data science or Generative AI techniques to solve a real-world problem. The notebook showcases the full workflow—from data loading and exploration to model implementation and insights.

## 🎯 Objective

- Apply advanced machine learning alogorithm.
- Demonstrate ability to process, analyze, and visualize data.
- Deliver a functional and interpretable solution with business relevance.

## 🧠 Key Features

- Data cleaning and transformation
- Exploratory Data Analysis (EDA)
- Model training and evaluation
- Results visualization and interpretation
- Conclusions and recommendations

## 📊 Dataset

- **Source:**
   The dataset used for this study was derived from multiple sources and combined into a single dataset, 'heart.csv.'
- **Features:** It contains 13 independent variables like age, chol, thalach, oldpeak etc and 1 target variable (outcome), indicating the presence or absence of heart disease. 

## 🧪 Methods Used

- Pandas & Numpy for preprocessing
- Matplotlib / Seaborn for visualization
- Scikit-learn for ML modeling

### 🧮 Modeling Techniques

The following machine learning models were applied:

- Logistic Regression  
- Decision Tree  
- Random Forest  
- K-Nearest Neighbors (KNN)  
- Naive Bayes  
- Support Vector Machine (SVM)  
- Gradient Boosting Classifier

To address class imbalance in the dataset, **SMOTE (Synthetic Minority Over-sampling Technique)** was used on the training set. Model performance was evaluated using:

- Confusion Matrix  
- Classification Report (Precision, Recall, F1-Score)  
- ROC-AUC Score

## 📈 Results Summary

The models built for this study effectively classified individuals based on heart disease risk. Among all, the **Gradient Boosting Classifier** and **Random Forest** models showed the highest performance, each achieving approximately **90% accuracy**. These results indicate strong potential for deployment in clinical decision-support tools aimed at early detection and prevention of heart disease.

## ✅ Conclusion

Integrating machine learning models into healthcare systems can augment clinical decision-making, reduce diagnostic errors, and enable proactive care. The success of this project demonstrates how data-driven methods can enhance early diagnosis and potentially save lives.
