# Data-Science-Hackathon
Loan Repayment Assessment in Banking
Overview
Welcome to the Loan Repayment Assessment in Banking project! This project aims to build and train a machine learning model to predict whether a customer will repay or default on a loan based on various financial attributes. By accurately classifying loan applicants into 'Paid' or 'Defaulted' categories, this model will help banks assess the creditworthiness of loan applicants and mitigate the risk of default.

Dataset
The dataset used in this project contains 80,000 records and 28 features. These features include:

annual_inc: Annual income reported by the borrower during registration.
fico_range_high and fico_range_low: Upper and lower boundary range of the borrower's FICO score at loan origination.
int_rate: Interest rate on the loan.
loan_amnt: Listed amount of the loan applied for by the borrower.
emp_length: Employment length in years.
home_ownership: Home ownership status provided by the borrower during registration.
open_acc: Number of open credit lines in the borrower's credit file.
pub_rec: Number of derogatory public records.
revol_bal: Total credit revolving balance.
total_acc: Total number of credit lines currently in the borrower's credit file.
And more.
The target variable is loan_status, indicating whether the loan was fully paid or defaulted.

Problem Statement
The primary objective of this project is to develop a predictive model using machine learning techniques that accurately classify loan applicants into 'Paid' or 'Defaulted' categories. This model will assist financial institutions in making informed decisions when approving or denying loan applications, thereby minimizing the risk of financial loss due to default.

Project Structure
The project is organized into the following directories:

Data: Contains the dataset files used for training and evaluation.
Notebooks: Jupyter notebooks for data exploration, preprocessing, model training, and evaluation.
Scripts: Python scripts for data preprocessing and model training.
Models: Saved trained models for future use.
Results: Evaluation metrics and model performance summaries.
README.md: Overview of the project, instructions, and guidelines.
Setup
To run the code and reproduce the results, follow these steps:

Clone this repository to your local machine.
Install the required dependencies listed in requirements.txt using pip install -r requirements.txt.
Navigate to the Notebooks directory and run the Jupyter notebooks in sequential order.
Technologies Used
This project is implemented using the following technologies and libraries:

Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
Jupyter Notebook
Contributors
Mohammad Nayab
License
This project is licensed under the MIT License.

Feel free to customize this README file according to your project's specifics and requirements.
