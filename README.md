This project used supervised learning to train and evaluate a model based on loan risk. The purpose of this analysis is to predict if someone will default on their loans based on income, debt to income ratio, number of accounts, derogatory marks, total debt and loan status. 

Using Python, numpy, pandas, pathlib and sklearn.metrics I split the data into training and testing sets and created a logistic regression model with the original data.

Results:
- accuracy score: 0.99
- precision score: 0.85
- recall score: 0.91

I would recommend this model to be used by the company. With high accuracy, recall and precision the model is very good at predicting credit worthiness. It is important to still consider the specific business risks of a false positive or false negative. It is also essential to take a look at the ethics of individual cases and be aware of how a false negative could impact individuals applying for loans. One way to midigate this risk is by creating a system for applicants who are denined loans to work directly with staff.
