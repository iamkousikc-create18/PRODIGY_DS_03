PRODIGY_DS_03

Task 3: Decision Tree Classifier with SMOTE for Customer Purchase Prediction

Objective

The objective of this task is to build a Decision Tree Classifier to predict whether a customer will subscribe to a term deposit based on their demographic and behavioral data. Additionally, SMOTE (Synthetic Minority Oversampling Technique) is applied to handle class imbalance and improve model performance.

Dataset

The dataset used is the Bank Marketing Dataset, which contains customer information collected during a marketing campaign.

Features
Numerical Features:
 - age
 - balance
 - day
 - duration
 - campaign
 - pdays
 - previous
Categorical Features:
 - job
 - marital
 - education
 - default
 - housing
 - loan
 - contact
 - month
 - poutcome
Target Variable:
 - y → Indicates whether the customer subscribed to the term deposit (Yes/No)
   
Tools and Libraries Used
 - Python
 - Pandas
 - NumPy
 - Matplotlib
 - Seaborn
 - Scikit-learn
 - Imbalanced-learn (SMOTE)
   
Steps Performed
1. Imported required libraries.
2. Loaded and explored the dataset.
3. Checked for missing values and data types.
4. Encoded categorical variables into numerical format.
5. Split the dataset into training and testing sets.
6. Applied SMOTE to balance the training data.
7. Trained a Decision Tree Classifier model.
8. Made predictions on the test dataset.
9. Evaluated the model using:
 - Accuracy Score
 - Confusion Matrix
 - Classification Report

Model Used

Decision Tree Classifier

A Decision Tree is a supervised learning algorithm that splits the dataset into branches based on feature values to make predictions.

Handling Imbalanced Data

The dataset had class imbalance, so SMOTE (Synthetic Minority Oversampling Technique) was used to generate synthetic samples for the minority class, improving model performance.

Results
 - The model achieved an accuracy of approximately 81%.
 - SMOTE helped improve the model’s ability to correctly predict the minority class.
 - Evaluation metrics such as confusion matrix and classification report were used to assess performance.

Project Structure

PRODIGY_DS_03

├── bank.csv
├── task 3.ipynb
└── README.md

Conclusion

This project demonstrates how machine learning models like Decision Trees can be used to predict customer behavior. Handling imbalanced data using techniques like SMOTE significantly improves model performance and reliability.
