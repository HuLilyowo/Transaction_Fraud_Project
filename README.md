# Transaction Fraud Project

This project aims to capture credit card transaction fraud with a supervised model. The final model can detect about 55% of all frauds in 3% of the population. Based on the assumption — on average, $400 gain from every caught fraud and $20 loss on every false positive detection — the overall saving is over $20 million with a 3% cutoff.

##### Data overview:


### Section 1. Data Quality Report
\[File: DQR - Transaction Fraud.ipynb\]

There are 10 fields (2 numerical and 8 categorical) and 96,753 records. Among those, there are 3 fields with missing values or frivolous values. The overall fraudulent rate is 1.095%, which indicates the dataset is imbalanced. 

### Section 2. Data Cleansing and Feature Engineering 
\[File: Feature Engineering - Transaction.ipynb & DQR - Transaction Fraud.ipynb\]

Excluded outliers and filled the missing/ frivolous values with the population mean or mode after detailed matching. Created 2,981 variables 



