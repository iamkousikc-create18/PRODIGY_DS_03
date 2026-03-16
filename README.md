PRODIGY_DS_03

Task 3: Decision Tree Classifier for Customer Purchase Prediction

- - - 
Objective

The objective of this task is to build a Decision Tree Classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data. The model is trained using the Bank Marketing Dataset.

- - -
Dataset

The dataset used in this project is the Bank Marketing Dataset, which contains information about customers and their interactions with a bank marketing campaign.
The dataset includes features such as:
Age
Job
Marital Status
Education
Balance
Housing Loan
Personal Loan
Contact Type
Campaign Information
Previous Campaign Outcome
The target variable is:
y → Indicates whether the customer subscribed to the term deposit (Yes/No).

- - -
Tools and Libraries Used

Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

- - - 
Steps Performed

Imported the required Python libraries.
Loaded the dataset using Pandas.
Explored the dataset and checked for missing values.
Converted categorical variables into numerical values using encoding.
Split the dataset into training and testing sets.
Built a Decision Tree Classifier model.
Predicted customer purchase behavior using the trained model.
Evaluated the model using accuracy, confusion matrix, and classification report.

- - - 
Model Used

Decision Tree Classifier
Decision Trees are supervised machine learning algorithms used for classification and prediction by splitting data into different branches based on feature values.

- - - 
Results

The model was trained to predict whether a customer would subscribe to a bank term deposit based on various demographic and behavioral attributes.

- - -
Project Structure

PRODIGY_DS_03
│
├── bank.csv
├── task 3.ipynb
└── README.md
Conclusion
This project demonstrates how machine learning models like Decision Trees can be used to predict customer behavior. Such models help organizations understand customer preferences and improve marketing strategies.
