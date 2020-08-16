# Bank Loan Default Predicition Using Logistic Regression

Model for predicting whether a bank customer is likely to default on a loan or not, based on the customer profile. Model can aid banks in giving out loans

## Getting started 

Run Jupiter notebook to generate model
In block 48 (under single case use), enter the values for the variables to run the model
`Salary:  [x]` - in 1000s i.e 10 = 10 000 ~ customer salary
`Late_on_2: [x]` - takes 0 or 1,  0 if customer is not late on 2 and 1 otherwise (assume the variable “late on 2” has some significance to the bank)
`Location: [x]`, - takes 0 or 1, 0 if customer is not in a specific location and 1 otherwise ( assume the variable location has some significance to the bank)
`Single: [x]` - takes 0 or 1, 0 if customer is single and 1 if married
 
Once the values have been provided, run the block to get the prediction on weather the customer will default or not 


## Prerequisites 
* Jupyter notebook

## Python libraries required: 
* pandas 
* numpy
* matplotlib.pyplot
* seaborn 
sklearn
statsmodels