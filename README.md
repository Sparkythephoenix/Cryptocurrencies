# Cryptocurrencies



**Purpose**
The purpose of this project was to search for unknown patterns in data using unsupervised machine learning and create 3D visualisations and scatterplots with plotly.explress and hvplot.

The data set was provided for this project.

The whole process was broken down to several steps:

The data was preprocessed for principal component analysis (PCA), unnecessary columns removed, null values dropped, StandardCScaller was used to standardize the features in DataFrame
Data Dimensions reduced using PCA
Data clustered using K-means algorithm, number of centroids for K-means determined using the elbow curve
