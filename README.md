# Facebook-comment-traction

# Predicting whether facebook posts can attract atleast 5 comments

# Facebook Traction

## Data Preparation

*Read data from 'Features_Variant_1.csv' and 'Final_Testset.xlsx'

*Create bin variable that tells us whether post attracted atleast 5 comments

*Perform test-train split and append test sample(Final_Testset) to test

*Perform scaling on test and train data

## Classification

*Constructed SVC models with linear kernel, polynomial kernel, sigmoid kernel. Created decision tree and Ada-boost models aswell.

*Plotted train and cross-val accuracy against appropriate parameters and created confusion matrixes for all the models

*Constructed learning curves and ROC for all the models

*The Decision tree was the best model with test accuracy of 0.86 (86%) and an AUC of 0.80 and test accuracy of 86.6%
