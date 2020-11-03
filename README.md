# Loan-risk-Analysis-using-Decision-Tree-from-Scratch
This is an implementation of a Decision Tree for Loan risk analysis without using predefined decision tree libraries.

***Dataset***

The dataset is from Lending Club. The dataset has 68 features (columns). But for the purpose of this project we only use 4 of them namely, grade,term,home ownership type and number of years of employment.

# Description
* To tackle imbalance in dataset we apply under-sampling of the cardinally greater class.
* As a measure of impurity for the nodes, ENTROPY is chosen.
* Fitting of the Decision Tree occurs recursively.
* For classification error we test the data on validation set.
# Conclusion
Other impurtiy measures such as Gini Index and Misclassification Error could also be used. Other methods for imbalanced dataset handling can also be implemnted.
This program shows how to implement a Decision Tree from scratch and the working behind it.
