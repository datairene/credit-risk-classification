This project used supervised learning to train and evaluate a model based on loan risk. The purpose of this analysis is to predict if someone will default on their loans based on income, debt to income ratio, number of accounts, derogatory marks, total debt and loan status. 

Using Python, numpy, pandas, pathlib and sklearn.metrics I split the data into training and testing sets and created a logistic regression model with the original data.

Results:
- accuracy score: 0.99

Model 1 (healthy loan):
- precision score: 1.00
- recall score: 0.99

Model 2 (high-risk loan):
- precision score: 0.84
- recall score: 0.99

Overall, the logistic regression model performs exceptionally well in predicting both healthy and high-risk loans. It exhibits high precision, recall, and F1-score for both classes, indicating strong predictive performance across the board. It is important to still consider the specific business risks of a false positive or false negative. It is also essential to take a look at the ethics of individual cases and be aware of how a false negative could impact individuals applying for loans. One way to midigate this risk is by creating a system for applicants who are denined loans to work directly with staff.
