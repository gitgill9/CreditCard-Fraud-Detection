# CreditCard-Fraud-Detection

This project was done as a part of hackathon organised by MasterCard and BrainStation. 
We were provided with a dataset of thousands of transactions where around 2% transactions are flagged as fraud.

## Data Source
Dataset for this project can be found in following link: 
https://drive.google.com/file/d/1sI1y_PBGnqBYGIQugfXiSFIQ9FUhHi70/view?usp=sharing

## EDA (Exploratory Data Analysis) 
- All the duplicates and null values checked first
- Dataset has total of around 1.2 million transactions 
- Each transaction has 22 columns showing a specific information regarding that transaction

Columns in the dataset:

- index - Unique Identifier for each row
- transdatetrans_time - Transaction DateTime
- cc_num - Credit Card Number of Customer
- merchant - Merchant Name
- category - Category of Merchant
- amt - Amount of Transaction
- first - First Name of Credit Card Holder
- last - Last Name of Credit Card Holder
- gender - Gender of Credit Card Holder
- street - Street Address of Credit Card Holder
- city - City of Credit Card Holder
- state - State of Credit Card Holder
- zip - Zip of Credit Card Holder
- lat - Latitude Location of Credit Card Holder
- long - Longitude Location of Credit Card Holder
- city_pop - Credit Card Holder's City Population
- job - Job of Credit Card Holder
- dob - Date of Birth of Credit Card Holder
- trans_num - Transaction Number
- unix_time - UNIX Time of transaction
- merch_lat - Latitude Location of Merchant
- merch_long - Longitude Location of Merchant
- is_fraud - Fraud Flag
