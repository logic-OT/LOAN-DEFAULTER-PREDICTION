# LOAN-DEFAULTER-PREDICTION
**Description**: Banks earn a major revenue from lending loans. But it is often associated with risk. The borrower's may default on the loan. To mitigate this issue, the banks have decided to use Machine Learning to overcome this issue. They have collected past data on the loan borrowers & would like you to develop a strong ML Model to classify if any new borrower is likely to default or not. 

## Datatset
The dataset is enormous & consists of multiple deteministic factors like the borrower's, income, gender, loan purpose etc. It consists of over 10,000 rows of customer information, where each row corresponds to the target value that indicated whether a customer was a defaulter or not. The dataset can be seen in the csv file in the code section, titled, **loan Default.csv**

## Visualisations and EDA
I started off by doing some exploratory data analysis where I discovered some skewness in a few columns and a surprising amount of null values. Here are some images of graphs the graphs plotted:
![download (7)](https://github.com/logic-OT/LOAN-DEFAULTER-PREDICTION/assets/61668807/c9803cb4-4708-4329-8b46-0eb5198922ae)
![download (8)](https://github.com/logic-OT/LOAN-DEFAULTER-PREDICTION/assets/61668807/9463ba32-c0c8-4f16-bc0e-10336f70db42)
![download (9)](https://github.com/logic-OT/LOAN-DEFAULTER-PREDICTION/assets/61668807/a6ac5f4d-e4e1-4302-af67-58f4c2c58612)

## PREPROCESSING
Simple mean and mode imputation helped alleviate the problem of Null values. OneHot encoding and Robust scaling were implemented as the next step during processing. Due to an imbalance in the target column, we rationalised performing undersampling to prevent any biases the final model might develop.

## RESULTS
In the end, we trained 3 models with randomised hyperparameter tuning. Random Forest was our best model with a test accuracy and precision score of 1.0. KNN and Logistic Regression resulted in an accuracy of 0.91 and 0.77 respectively.

## Notebook
The detailed notebook is in the code section, titled, **housing (1).ipynb**
