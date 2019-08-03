# Dimensionality-Reduction

Case Study-1

Questions:
1. Scikit learn comes with pre-loaded dataset, load the digits dataset from that collection and write a helper function to plot the image using matplotlib.
[Hint: Explore datasets module from scikit learn]

2. Make a train -test split with 20% of the data set aside for testing. Fit a logistic regression model and observe the accuracy.

3. Using scikit learn perform a PCA transformation such that the transformed dataset can explain 95% of the variance in the original dataset. Find out the number of components in the projected subspace.
[Hint: Refer to decomposition module of scikit learn]

4. Transform the dataset and fit a logistic regression and observe the accuracy. Compare it with the previous model and comment on the accuracy.
[Hint: Project both the train and test samples to the new subspace]

5. Compute the confusion matrix and count the number of instances that has gone wrong. For each of the wrong sample, plot the digit along with predicted and original label.

Case Study-2

1. We shall use the same dataset used in previous assignment - digits. Make a 80-20 train/test split.
[Hint: Explore datasets module from scikit learn]

2. Using scikit learn perform a LDA on the dataset. Find out the number of components in the projected subspace.
[Hint: Refer to discriminant analysis module of scikit learn]

3. Transform the dataset and fit a logistic regression and observe the accuracy. Compare it with the previous model based on PCA in terms of accuracy and model complexity.
[Hint: Project both the train and test samples to the new subspace]

Case Study-3

Domain – Health Care
focus – Cancer detection
Business challenge/requirement
John Cancer Hospital (JCH) is a leading cancer hospital in USA. It specializes in preventing breast cancer.
Over the period of the last few years, JCH has collected breast cancer data from patients who came for screening/treatment.
However, this data has almost 30 attributes and is difficult to run and interpret the result. You as ML expert has to reduce the no. of attributes (Dimensionality Reduction) so that results are meaningful and accurate.

Key issues
Reduce the no. of attributes/features in data to make the results and analysis comprehensible by doctors
