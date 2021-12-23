# Cryptocurrencies

## Overview

The purpose of this project is to use unsupervised machine learning to analyze a database of cryptocurrencies and create a report including the traded cryptocurrencies classified by group according to their features.
This classification report could be used by an investment bank to propose a new cryptocurrency investment portfolio to its clients.
We have used the following methods for the analysis:

1. Preprocessing the database.
2. Reducing the data dimension using Principal Component Analysis (PCA).
3. Clustering cryptocurrencies using K-Means.
4. Visualizing classification results with 2D and 3D scatter plots.

## Results

Following the preprocessing and cleaning phase with cryptocurrencies that are actively trading, have a defined algorithm, and have a complete set of data, we have a total of 532 tradable cryptocurrencies.

<img width="514" alt="1" src="https://user-images.githubusercontent.com/88418201/147299763-2cf105c9-9802-40b2-8d96-2bf22319f6a8.png">

## Clustering Cryptocurrencies using K-Means - Elbow Curve

We do not know what would be the output of the analysis so we are using unsupervised machine learning to identify clusters of the cryptocurrencies. We have created the elbow curve using the K-Means method iterating on k values from 1 to 10.

<img width="685" alt="elbow curev" src="https://user-images.githubusercontent.com/88418201/147299932-a8ea6c06-dee9-4c02-9aa1-593375dce2ea.png">

The best k value appears to be 4 so we would conclude on an output of 4 clusters to categorize the crytocurrencies.

## Visualizing Cryptocurrencies Results

### 3D-Scatter plot with clusters

<img width="746" alt="scatterplot" src="https://user-images.githubusercontent.com/88418201/147300087-65ff929d-147c-4437-9569-366e9c9325f2.png">

This 3-D scatter plot was obtained using the PCA algorithm to reduce the crytocurrencies dimensions to three principal components.

## Number of Tradable Cryptocurrencies

<img width="727" alt="3" src="https://user-images.githubusercontent.com/88418201/147300204-4a90638c-7a62-46d6-96d3-cbef9a4c2c4f.png">

## Tradable Cryptocurrencies Table

<img width="753" alt="6" src="https://user-images.githubusercontent.com/88418201/147300532-9f9e6829-8de8-4822-92c5-d42f672ef4e8.png">


## 2D-Scatter plot with TotalCoinsMined vs TotalCoinSupply

<img width="695" alt="5" src="https://user-images.githubusercontent.com/88418201/147300293-e7888263-09bd-4948-9572-17beea7f57bb.png">





