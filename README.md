# Customer_Churn_Prediction
This project was developed as part of my** Celebal Summer Internship** in the Data Science domain. The primary goal is to build a machine learning model that predicts customer churn — whether a customer is likely to stop using a subscription-based service such as telecom, internet, or streaming.

Customer churn is a critical business problem, and predicting it accurately can help companies proactively retain customers through personalized offers or improved service. For this project, I used the Telco Customer Churn dataset from Kaggle, which contains information about 7,000+ customers, including demographic details, service usage, and account-level features.

The project follows a standard machine learning pipeline:

Data Cleaning & Preprocessing: Missing values were handled, TotalCharges was converted from object to numeric, and irrelevant features like customerID were removed.

Feature Engineering: Label encoding and one-hot encoding were applied to categorical variables. The dataset was then scaled using StandardScaler.

Modeling: A Random Forest Classifier was trained to predict the target variable (Churn). The model was evaluated using accuracy, confusion matrix, and classification report.

Evaluation: The model showed reliable accuracy in predicting churn, making it a solid baseline for future enhancement.

Visualization: Key patterns such as churn distribution by gender, contract type, and internet service were visualized using Seaborn and Matplotlib.

This project strengthened my understanding of end-to-end machine learning workflows — from data preparation to model evaluation. It also demonstrated the importance of feature engineering and data visualization in solving real-world business problems.
