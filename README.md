# Iris-dataset


## Table of Contents
  - Project Overview

  - Tools

  - Data Cleaning

  - Unsupervised Machine Learning

  - Insights

### Project Overview
This Unsupervised Machine learning data science project aims to generate insights for creating a model that effectively clusters and predicts various plant species. Through an analysis of the Iris dataset, the goal is to identify a model that precisely fits the data and offers a graphical representation of the optimal number of clusters.

### Tools
 - Python - Data Analysis
 - Matplotlib
 - Numpy
 - Pandas
 - Scikit-learn
 - Jupyter notebook - Environment for analysis

### Data Cleaning
In the data preparation phase, i performed the following tasks;

1. Data loading
2. Data Validation
3. Data cleaning

### Unsupervised Machine Learning
Unsupervised machine learning is a type of machine learning where the algorithm is provided with unlabeled data, and its objective is to identify patterns, relationships, or structures within the data without explicit guidance or predefined output labels. The K-Means Clustering is used in finding specified number of clusters in a data set.

Steps carried out:
   1. I created a train and test dataset by randomly taking specified sample size for the train and using the rest dataset as the test data.
   2. I created a  model and fitted it to the train dataset using the KMeans function from the Sklearn package .
   3. I ensured to use different range of values from 1 - 11 for the n_clusters using a for loop to ensure I get the best value of inertia .
   4. I went ahead to evalute the performance of the model , by checking its performance accuracy on the test dataset.
   5. I created a graph to visualize the various clusters using matplotlib package.

### Insights

1.The optimum number of cluster was 3

2.The value of inertia is 61.7


