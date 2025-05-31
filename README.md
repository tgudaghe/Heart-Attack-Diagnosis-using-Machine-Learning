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

### Modelling
- Several machine learning models are applied to the preprocessed data, including Logistic Regression, Decision Tree, Random Forest, K-Nearest Neighbors (KNN), Naive Bayes, and Support Vector Machine (SVM). To address class imbalance, SMOTE (Synthetic Minority Over-sampling Technique) was applied to the training data. Models were evaluated using confusion matrices, classification reports, and ROC-AUC scores to assess the performance.

## Result Summary
The models developed during this study effectively classify individuals based on heart disease risk, with Gradient Boosting Classifier and Random Forest showing the highest potential for deployment in a clinical setting. Both model achieved 90% accuracy. The results suggest that integrating the model into clinical decision support systems could enhance early detection and treatment of heart disease.


  
