# cryptoclustering-challenge
Module 19 challenge for U of T's SCS Data Analytics Boot Camp

The purpose of this challenge is to utilize Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

The challenge entails clustering cryptocurrencies with K-means using original scaled data. It then optimizes clusters with principal component analysis and reduces the features to three principal components.  To find the best value for k using PCA data, an elbow curve of the inertia of each possible value of k.  The scatter plot for the clusters created using all seven features was compared with the scatter plot using the PCA data, which reduced the number of features to three.  It became more visually apparent why the optimal number of clusters was four. 
