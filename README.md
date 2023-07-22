# CryptoClustering
This is the repository for Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

In this repo:
* Crypto_Clustering: a Jupyter Notebook with code and analysis
* Resources Folder: contains csv file used for the analysis and an Images folder containing the images output.

Steps:
* Load the crypto_market_data.csv into a DataFrame.

* Summary statistics and plot 

* Use StandardScaler() module from scikit-learn to normalize the data

* Find the Best Value for k Using the Original Scaled DataFrame. Elbow method: inertia values computed with the different values of k to visually identify the optimal value for k.

* Cluster Cryptocurrencies with K-means Using the Original Scaled Data

* Optimize Clusters with Principal Component Analysis: reduce the features to three principal components.

* Retrieve the explained variance to determine how much information can be attributed to each principal component.

* Find the Best Value for k Using the PCA Data. Elbow method on the PCA data.

* Cluster Cryptocurrencies with K-means Using the PCA Data
