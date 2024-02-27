# Churn Modelling with Bank Customer Prediction using ANN

This repository contains a machine learning project aimed at predicting whether a bank customer will leave the bank or not using churn modelling techniques based on an Artificial Neural Network (ANN). The dataset includes 13 features, out of which 12 are independent variables and 1 is the dependent variable.

## Dataset
The dataset used for this project is churn_modelling.csv, which includes the following features:

1. **RowNumber**: A unique identifier for each row.
2. **CustomerId**: Unique identifier for each customer.
3. **Surname**: Customer's surname.
4. **CreditScore**: Credit score of the customer.
5. **Geography**: Customer's country.
6. **Gender**: Customer's gender.
7. **Age**: Age of the customer.
8. **Tenure**: Number of years the customer has been with the bank.
9. **Balance**: Account balance of the customer.
10. **NumOfProducts**: Number of bank products the customer uses.
11. **HasCrCard**: Whether the customer has a credit card (1 for yes, 0 for no).
12. **IsActiveMember**: Whether the customer is an active member (1 for yes, 0 for no).
13. **EstimatedSalary**: Estimated salary of the customer.
14. **Exited**: Whether the customer exited the bank (1 for yes, 0 for no).

## Objective
The main objective of this project is to build an Artificial Neural Network model that can predict whether a bank customer will churn (leave) based on the provided features.

## Methodology
1. **Data Preprocessing**: 
   - Handling missing values.
   - Encoding categorical variables (One-Hot Encoding for Geography and Gender).
   - Feature scaling if necessary.
2. **Exploratory Data Analysis (EDA)**: 
   - Understanding the distribution of variables.
   - Detecting outliers.
   - Visualizing relationships between variables.
3. **Model Building**:
   - Splitting the dataset into training and testing sets.
   - Designing and training an Artificial Neural Network model.
   - Evaluating model performance using appropriate metrics (e.g., accuracy, precision, recall, F1-score).
4. **Model Selection**:
   - Tuning hyperparameters if necessary.
   - Choosing the best performing ANN model based on evaluation metrics.
5. **Model Deployment**:
   - Deploying the chosen ANN model for real-time predictions.

## Usage
To replicate the analysis, follow these steps:

1. Clone this repository to your local machine.
2. Install the required dependencies listed in `requirements.txt`.
3. Run the Jupyter notebook `Churn_Modelling_Prediction.ipynb` to execute the code and follow the step-by-step analysis.
4. To install all the necessary files and libraries required to run this script, please execute the following command : pip install -r requirements.txt 


## Results
The results of the analysis, including model performance metrics and insights gained from EDA, can be found within the Jupyter notebook.
