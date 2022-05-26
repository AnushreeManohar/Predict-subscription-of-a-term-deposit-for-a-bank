# Term deposit subscription prediction for a bank

### Overview

- Predicted whether a client subscribed to a term deposit by developing a python code with the implementation of various
machine learning models like Decision Tree, Random Forest, KNN, Gaussian Naive Bayes	and Multinomial Naive Bayes models.
- Above models were compared based on their accuracies in addition to comparing each of the model's accuracy using 10 fold cross validation.
- Random forest was identified as the best model with an accuracy of 90%. 

### Pre-processing and Exploratory Data Analysis

- To begin with, checked for the null values.
- Exploratory data analysis was performed by plotting a few bar graphs and boxplots.
- All the cetegorical data were mapped to numeric using map() function.
- After mapping, a heatmap was plotted to find the correlation among the different variables.
- The attributes pdays, poutcome and previous were identified to be highly correlated. 
- An attribute, 'housing', that was least correlated was dropped.
- The data was then at its best form for splitting into different sets and fitting into models.

### Models and accuracies

- The data was split into training and testing sets with a test set size of 0.25.
- Different models were built and accuracies measured along with a 10 fold cross validation for each of them.
- Below are the accuracies recorded for each of the models.

 Model  | Accuracy| 10-fold-cross-validation_accuracy  | 
  :---: | :---:   | :---:                              | 
Decision Tree  | 85.86 | 86.20  | 
Random Forest  | 90.27 | 90.07  | 
KNN   | 88.86 | 88.08  | 
GaussianNB  | 85.76 | 84.23  | 
MultinomialNB  | 88.50 | 88.48  | 

