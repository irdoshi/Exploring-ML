# Exploring-ML

This repository contains code snippets for applying K-Means Clustering, Hierarchical Clustering, Decision Trees, and Naive Bayes on different datasets. Below you will find a description of each part and the corresponding code.

Part I - Applying K-Means Clustering and Hierarchical Clustering on Wine Data
This section applies K-Means Clustering and Hierarchical Clustering algorithms on a wine dataset. It includes the following steps:

- Generating synthetic data using numpy.
- Visualizing the data using scatter plots.
- Applying K-Means Clustering and visualizing the clustering results.
- Plotting an elbow plot to determine the optimal number of clusters using the sum of squares.
- Applying Hierarchical Clustering using complete, average, and single linkage methods.
- Visualizing the dendrograms for each linkage method.
- Comparing the clustering results of Hierarchical Clustering with the K-Means clustering labels.
- Calculating and printing the differences between the clustering results.

Part 2: Decision Trees
This part focuses on applying Decision Trees on the Diabetes dataset. It includes the following steps:

- Loading the Diabetes dataset.
- Selecting the relevant features for training.
- Splitting the dataset into training and test sets.
- Creating a Decision Tree classifier object and training it.
- Making predictions on the test dataset.
- Evaluating the performance of the classifier using classification metrics and confusion matrix.
- Visualizing the Decision Tree using tree.plot_tree.
- Discussing the root node and top three features.


Part 3: Fake News and Naive Bayes
In this part, Naive Bayes is applied to a dataset that classifies news stories as fake or true. The steps are as follows:

- Reading the training data from a CSV file.
- Extracting the relevant features for classification.
- Creating a pipeline that vectorizes the text data and trains a Naive Bayes classifier.
- Evaluating the pipeline using cross-validation and reporting accuracy.
- Reading and preparing the test data.
- Making predictions on the test data using the trained pipeline.
- Discussing ways to improve accuracy, such as using a better tokenizer, removing stop words, stemming and lemmatization, document preprocessing, and IDF smoothing.
- Implementing one improvement by removing stop words and evaluating the accuracy using cross-validation.
