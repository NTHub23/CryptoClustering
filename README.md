# Crypto Clustering


![image](https://github.com/NTHub23/CryptoClustering/assets/138403390/4e6b061c-fda5-4568-890d-8389e7b7f3ae)


# Overview

The Crypto Clustering project aims to predict if cryptocurrencies are affected by 24-hour or 7-day price changes using unsupervised learning techniques, specifically K-means clustering. Additionally, the project explores the impact of dimensionality reduction using Principal Component Analysis (PCA) on clustering.

## Steps

1. Load and preprocess the data.
2. Scale the data using StandardScaler.
3. Find the best value for k using the elbow method.
4. Cluster cryptocurrencies with K-means using the original scaled data.
5. Perform PCA to reduce the features to three principal components.
6. Find the best value for k using the PCA data.
7. Cluster cryptocurrencies with K-means using the PCA data.
8. Visualize and compare the results using hvPlot.

## Results

The project includes the following visualizations:

1. Elbow curve for the original data.

![image](https://github.com/NTHub23/CryptoClustering/assets/138403390/4cb6d873-1143-42b0-bb51-66e6b29ec4c2)


2. Elbow curve for the PCA data.

![image](https://github.com/NTHub23/CryptoClustering/assets/138403390/7fc7279d-cc57-45c1-a052-158f5b6b437d)


3. Scatter plot of cryptocurrency clusters based on the original data.

![image](https://github.com/NTHub23/CryptoClustering/assets/138403390/7dd44c39-06fe-48cb-8555-32f3d62e355e)


4. Scatter plot of cryptocurrency clusters based on the PCA data.
![image](https://github.com/NTHub23/CryptoClustering/assets/138403390/2f10616c-9195-4497-9b75-917ef31ababe)


## Conclusion


* `We can conclude that using less features also gave similar performance as that of original model as the number of clusters remained same that is 4. Also the reduced number of columns makes it easier to visualize the value of the clustering. The trade off is that valuable 10% of data is lost by using PCA model.`
