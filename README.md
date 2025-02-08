# Spam_Email_Classification

# **Spam Classification Using Machine Learning**  

## **Overview**  
I was particularly interested in this assignment I completed in my Machine Learning course in grad school, because it tested my knowledge of key machine learning classification techniques to solve a practical real-world issue (spam filtration in email inboxes). This project applies various classification techniques to build an effective spam detection model.  

## **What This Project Covers**  

- **Machine Learning Models**:  
  - **Logistic Regression**  
  - **K-Nearest Neighbors (KNN)**  
  - **Random Forest Classifier**  
  - **Support Vector Machines (SVM)**  

- **Model Evaluation & Optimization**: Cross-validation, hyperparameter tuning, and performance metrics (F1-scores).  

## **What I Found**  

The **Random Forest Classifier** model with six total features included (frequency of the word "free", frequency of exclamation marks, average run length of capital letters, frequency of the word "money", frequency of "000" and frequency of "$") performed the best, with a test set F1 score of 0.855. This indicates the model achieved a strong balance between precision and recall (considering both false positives and false negatives), with an overall performance of 85.5% on the unseen test data.

