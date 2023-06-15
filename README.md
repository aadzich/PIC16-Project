## PIC16-Project: Predicting Delinquent Mortgage Loans
# Overview
  This project works with HELOC (Home Equity Line of Credit) loans and aims to predict borrower delinquency behavior based on features such as property type or FICO credit score. As a lender, two of the greatest potential risks when issuing a loan are prepayment and delinquency. After analyzing our given data, we decided to focus on predicting delinquency. Delinquent loans occur when a payment is not made by a specified date, and can turn into a default, when the payment is late past a certain amount of days and converts to debt. 
	This github includes Python code for importing loan data and creating a local SQL database to then perform meaningful analysis on predicting delinquency, including machine learning models and visualizations.

# How to Use
  Importing the functs.py and delinquent_loan_machine_learning.ipynb files onto your local computer, a user can then adapt the given notebook code to import the required files from the correct storage location. The user can also upload all of the mortgage loan data they have, and run the code that creates a locally stored SQL database to ensure more efficient runtime. 
  Once all of the necessary imports are in, a user can then utilize our written functions for cleaning the data as well as resampling, where oversampling or undersampling may be more advantageous depending on the data.
  Finally, a user can run or modify our established Keras sequential models and perform feature training, and reach final conclusions on their model's ability to accurately predict delinquent loans.

# Files Descriptions
*functs.py* (function package, imported in our main notebook) \
*delq_loan_ machine_learning.ipynb* (primary notebook file modeling over/undersampling) \
*preliminary_data_exploration.ipynb* (initial code exploring correlations and resampling methods)
