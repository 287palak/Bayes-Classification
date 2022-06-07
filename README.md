# Bayes-Classification
Implementation of Gaussian Naive Bayes Classifier from scratch.

## Question 01:
Naive Bayes classifiers are a collection of classification algorithms based on Bayes’ Theorem. It is not a single algorithm but a family of algorithms where all of them share a common principle, i.e. every pair of features being classified is independent of each other. This question is meant to help you comprehend how a naive bayes classifier works. Download the Titanic Dataset and implementation includes the following tasks:-
  
1. Perform pre-processing and visualization of the dataset. Split the data into train
and test sets. Also identify the useful columns and drop the unnecessary ones

2. Identify the best possible variant of naive bayes classifier for the given dataset.
Justify your reason for the same

3. Implement the identified variant of Naive Bayes Classifier from scratch. [you may
not use any 3rd-party library's classifier function, such as scikit-learn. However,
Built-in functions, such as train/test split, can be used for supplementary tasks.] 

4. Perform 5-fold cross-validation using the entire training feature set 

5. Visualize and summarize the results across the cross-validation sets. Compute the probability of the top class for each row in the testing dataset.

6. Compare your scratch implementation with scikit-learn in terms of the performance

7. Implement any other model of your choice [not necessarily from scratch] and perform 5-fold cross-validation and summarize the results. Compare it with the Naive Bayes Classifier you have implemented and justify your results


## Question 02: 
Only Numpy, Pandas, Seaborn and Matplotlib are allowed.
There are 210 rows with 7 input variables and 1 output variable. The variable names are as given:
1. Area.
2. Perimeter.
3. Compactness
4. Length of kernel.
5. Width of kernel.
6. Asymmetry coefficient.
7. Length of kernel groove.
8. Class (1, 2, 3).

a. Use histogram to plot the distribution of samples
b. Determine the prior probability for all the classes.
c. Discretize the features into bins from scratch. Use of pandas, scikit learn and scipy is not allowed for this subpart.
d. Determine the likelihood/class conditional probabilities for all the classes. 
e. Plot the count of each unique element for each class. Compare the plot with the plot of distribution.
f. Calculate the posterior probabilities and plot them in a single graph. Analyse the plot.
