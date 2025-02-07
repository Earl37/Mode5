To implement Principal Component Analysis (PCA), we start by importing the necessary library packages that will assist in manipulating the numerical data and summarizing the results with visual illustrations.

Thereafter, we import PCA, the preprocessing tool and our dataset, which we then load and understand its scope e.g., number of variables (columns), number of entries (rows) etc.

We then standardize our data by scaling it to have a zero mean and a unit variance. This is then followed up by applying PCA now that we have ‘clean data’ to reduce the dimensionality of the dataset.

As a result of performing PCA, we realise that ten variables explain 95 percent of the variance, leaving the rest of the components contributing only 5 percent.

Next, we apply PCA to reduce our dataset to representation in terms of only the first two principal components which are then visualized using a scatter plot to help show how well these components separate the malignant and benign cases. The resulting explained variance ratio indicates that 63 percent of the essential variables are captured by the reduction to just these two components. 

Finally, we implement logistic regression for prediction. In this scenario, it returns an accuracy of 97 percent which indicates that only 3 percent of the model outturns were wrongly classified since we had 106 True Positives, 60 True Negatives, 3 False Positives and 2 False Negatives. 

The above outcome suggests that our model performs well and would be 97 percent accurate in predicting the next course of action to manage the growing number of referrals at the Anderson Cancer Center. 
