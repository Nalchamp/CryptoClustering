# CryptoClustering

# Project
The Crypto Clustering project aims to predict if cryptocurrencies are affected by 24-hour or 7-day price changes using unsupervised learning techniques, specifically K-means clustering. Additionally, the project explores the impact of dimensionality reduction using Principal Component Analysis (PCA) on clustering.

# Steps
  Load and preprocess the data.
  Scale the data using StandardScaler.
  Find the best value for k using the elbow method.
  Cluster cryptocurrencies with K-means using the original scaled data.
  Perform PCA to reduce the features to three principal components.
  Find the best value for k using the PCA data.
  Cluster cryptocurrencies with K-means using the PCA data.
  Visualize and compare the results using hvPlot.
  
# Results

Eblow curve for original data

<img width="672" alt="Screenshot 2024-03-23 at 7 08 08 PM" src="https://github.com/Nalchamp/CryptoClustering/assets/145158606/cd1006ab-95b0-42e6-900e-9aae7156b6c6">

Elbow curve for PCA data

<img width="687" alt="Screenshot 2024-03-23 at 7 10 10 PM" src="https://github.com/Nalchamp/CryptoClustering/assets/145158606/8c92eec1-f1cd-4b18-b39a-620a2125e037">

Scatter plot of cryptocurrency clusters based on the original data.

<img width="652" alt="Screenshot 2024-03-23 at 7 12 18 PM" src="https://github.com/Nalchamp/CryptoClustering/assets/145158606/59dc4840-c64e-428f-8e30-a8eeb07502dd">

Scatter plot of cryptocurrency clusters based on the PCA data.

<img width="660" alt="Screenshot 2024-03-23 at 7 13 13 PM" src="https://github.com/Nalchamp/CryptoClustering/assets/145158606/19f94491-89a8-4884-954e-994b7ac2ca0f">

# Dependencies
  Python
  Panda
  hvPlot
  scikit-learn


