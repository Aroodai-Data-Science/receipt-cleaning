# Data cleaning on POS Flags Data

## Context

Data cleaning is a critical operation in any data science project. Before trying to make use of data for exploratory analysis, modeling, or otherwise, it is important that the data to be used is cleaned. This includes removing or "sanitizing" any invalid inputs and missing data, and normalizing the data to match the requirements of the model or software with which it will be used.

In this notebook, we demonstrate our cleaning operation on two separate excel files. Both excel files contain information coming from Point-Of-Sales (POS) transactions recorded at the Havaiianas ION Orchard branch in Singapore. The first file [Sales Report by Receipt with Item Details with notes.xlsx](https://github.com/aroodai/receipt-cleaning/tree/main/unclean) contains individual transactions identified with a receipt-number and the items purchased, any discount or promo availed, and the transaction amount; meanwhile, the second file [POS Flags with Purchase Item Details with notes.xlsx](https://github.com/aroodai/receipt-cleaning/tree/main/unclean) contains more or less the same information but with added information on the customer as inputted by the assigned cashier during the time of purchase.

The notebook demonstrating the cleaning steps is `receipt-cleaning.ipynb` but you can easily jump to the file by [clicking here](https://github.com/aroodai/receipt-cleaning/blob/main/receipt-cleaning.ipynb).

The output of the data cleaning operation is saved in the `cleaned` [folder](https://github.com/aroodai/receipt-cleaning/tree/main/cleaned).

## Cleaned Data

The cleaned and pre-cleaned data files have been included in the repository for easy access. The cleaned data output is best accessed through our [Kaggle datasets](https://www.kaggle.com/datasets/aroodai/havaiianas-ion-orchard-singapore-pos-records).

## Licensing

Code found in this repository is licensed under the MIT License, which gives users the right to use, download, or modify the content conditional on proper and ethical attribution. Licensing of our dataset is separate and can be found on its counterpart Kaggle page.
