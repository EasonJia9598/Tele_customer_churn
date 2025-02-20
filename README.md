# Tele_customer_churn
 

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/EasonJia9598/Tele_customer_churn/blob/main/A2_EasonJia.ipynb)

# Telecom Customer Churn Prediction

## Overview
This project focuses on predicting customer churn in the telecommunications sector using machine learning techniques. The dataset is preprocessed to handle missing values and irrelevant features before training classification models to predict customer retention. A deep learning model is also implemented to improve prediction accuracy. Additionally, concept drift detection is incorporated to monitor changes in customer behavior over time.

## Dataset
The dataset used in this project contains customer demographic information, service subscription details, and billing data. It includes features such as contract type, monthly charges, tenure, and internet service type, which are critical for identifying churn patterns.

## Methodology
1. **Data Preprocessing**:  
   - Handled missing values  
   - Categorical variable encoding  
   - Feature selection and normalization  
   - Splitting into training, validation, and test sets  

2. **Model Training**:  
   - **Baseline Model**: Random Forest Classifier  
   - **Deep Learning Model**: Neural Network using PyTorch  

3. **Evaluation Metrics**:  
   - Accuracy, Precision, Recall, and F1-score  
   - Confusion Matrix and ROC-AUC Score  

4. **Concept Drift Detection**:  
   - Monitored drift in feature distributions using statistical tests  
   - Performance monitoring for accuracy degradation over time  

## Results
- The **Random Forest model** achieved an accuracy of ~85%.  
- The **Neural Network model** improved upon the baseline with ~88% accuracy.  
- Feature importance analysis indicated that **contract type** and **monthly charges** significantly impact churn probability.  

## Conclusion
This project demonstrates the effectiveness of machine learning in predicting customer churn. The use of deep learning provides an improvement over traditional models, and concept drift detection ensures long-term model reliability. The insights gained can help telecom companies proactively retain customers by identifying key churn factors.  
