# unsupervised-machine-learning-challenge

Instructor Do: Speeding up ML algorithms with PCA
Overview
In this activity, students will learn how to improve the performance of machine learning algorithms by using PCA to reduce the dimensionality of the data. They will also use t-SNE to visualize high-dimensional data in two dimensions.

Class Setup
Clone the starter files to the students' VMs.
Dependencies
matplotlib
pandas
sklearn
Dataset
This activity uses the myopia.csv dataset in the Resources folder. The dataset contains measurements of several ocular parameters for 618 children between the ages of 5 and 14, as well as a binary indicator variable indicating whether or not each child is myopic.

Walkthrough
Start by importing the necessary libraries and reading the myopia.csv file into a pandas DataFrame.
Print the number of unique values in the MYOPIC column and the number of unique values in its value counts.
Print the shape of the DataFrame, its column names, and the number of null values in each column.
Print any duplicated rows in the DataFrame and use the describe() method to get basic statistics about each column.
Separate the MYOPIC column from the rest of the DataFrame and use the StandardScaler class to standardize the features. Then, use the PCA class to reduce the dimensionality of the data to two dimensions.
Use the t-SNE algorithm to reduce the dimensionality of the standardized data to two dimensions, and plot the resulting data points using a scatter plot.
Finally, use the KMeans algorithm to cluster the original data into two clusters, and compare the results to the true labels.
Summary
In this activity, students learned how to improve the performance of machine learning algorithms by using PCA to reduce the dimensionality of the data. They also learned how to use t-SNE to visualize high-dimensional data in two dimensions, and how to cluster the data using the KMeans algorithm.
