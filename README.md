# Unsupervised_Extreme_Learning_Machine
Unsupervised Extreme Learning Machine(ELM) is a non-iterative algorithm used for feature extraction. This method is applied on the IRIS Dataset for non-linear feature extraction, cluster prediction and finally clustering is carried out using k-means.

<h3> Objective </h3>

To perform non-linear feature learning using Unsuoervised Extreme Learning Machine, predicting the number of clusters in the dataset using Bayesian Information Criterion (BIC) and finally clustering using k-means

<h3> Modules </h3>

1.**Unsupervised Extreme Learning Machine** : In this module, feature extraction of the dataset is performed using Unsupervised Extreme Learning Machine. It is a **non-iterative** algorithm with a single hidden layer where the weights between the input layer and the hidden layer are randomly initialized and the weights between the hidden layer and the output layer are computed using the objective function. Hence, it is guaranteed to converge at a global minima.

2.**Bayesian Information Criterion** : Bayesian Information Criterion is a statistical method use dto find out the number of clusters in the dataset. It uses the Expectation Maximization(EM) ALgorithm to find the number of clusters in the dataset. This module is added to automate the process of cluster prediction as for k-means clustering we need to specify priorly the number of clusters.

3. **K-means Clustering** : Linearly clustering where input is the feature learning information from Unsupervised ELM and the number of clusters from BIC. Finally, we display the confusion matrix and clustering accuracy.
