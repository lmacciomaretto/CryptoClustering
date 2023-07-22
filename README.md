# CryptoClustering
This is the repository for Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

In this repo:
* Crypto_Clustering: a Jupyter Notebook with code and analysis
* Resources Folder: contains csv file used for the analysis and an Images folder containing the images output.

Steps:
* Load the crypto_market_data.csv into a DataFrame.

* Summary statistics and plot 

* Use StandardScaler() module from scikit-learn to normalize the data
![market_lineplot](https://github.com/lmacciomaretto/CryptoClustering/assets/126762600/69eaadce-8023-4103-ac74-47ddd9ea864a)

* Find the Best Value for k Using the Original Scaled DataFrame. Elbow method: inertia values computed with the different values of k to visually identify the optimal value for k.

* Cluster Cryptocurrencies with K-means Using the Original Scaled Data

* Optimize Clusters with Principal Component Analysis: reduce the features to three principal components.

* Retrieve the explained variance to determine how much information can be attributed to each principal component.

* Find the Best Value for k Using the PCA Data. Elbow method on the PCA data.

* Cluster Cryptocurrencies with K-means Using the PCA Data

![elbow_curve](https://github.com/lmacciomaretto/CryptoClustering/assets/126762600/a328dcd3-0e51-4f4f-a360-e7f0d033c325)

![elbow_pca](https://github.com/lmacciomaretto/CryptoClustering/assets/126762600/a587334f-4b06-4561-aa35-95e13e3583fb)

![scatter_plot](https://github.com/lmacciomaretto/CryptoClustering/assets/126762600/2c1b67e0-3f8f-4997-a135-517cbe35df15)

![scatter_pca](https://github.com/lmacciomaretto/CryptoClustering/assets/126762600/bd4f6a80-9c7e-481f-b23c-d88ad78c485b)
