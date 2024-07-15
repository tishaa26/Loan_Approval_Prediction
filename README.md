# Loan_Approval_Prediction

This project aims to build a predictive model that predicts loan approval status based on specified columns such as 'Dependents', 'ApplicantIncome', 'CoapplicantIncome', 'LoanAmount', 'Loan_Amount_Term', 'Credit_History', and 'Property_Area'.

**Dataset**
The dataset used for training the model is stored in a CSV file named train_data.csv. It contains information about loan applicants including the specified columns and the target variable 'Loan_Status'.

**Model Building**
Preprocessing: The dataset is preprocessed by handling missing values, encoding categorical variables (e.g., 'Property_Area'), and splitting into features and target variable.
Model Selection: A Random Forest and NaiveBayes classifiera are chosen to predict the 'Loan_Status' based on the input features.
Training: The model is trained on the preprocessed data after splitting it into training and testing sets.

**Usage**
Clone the repository to your local machine.
Ensure you have the required libraries installed (pandas, scikit-learn, etc.).
Run the script to generate predictions for loan approval status based on the specified columns.

**Files**
train_data.csv: CSV file containing the loan applicant data.
Loan_Approval_Prediction.ipynb: Python script for building and using the loan approval prediction model.

**Dependencies**
pandas
scikit-learn

**Acknowledgements**
This project is inspired by the need to automate loan approval predictions based on specific applicant information. The model aims to assist in the decision-making process for loan approvals.
Feel free to contribute to this project by adding more features, improving the model's accuracy, or enhancing the user experience.
Thank you for checking out this loan approval prediction model project!
