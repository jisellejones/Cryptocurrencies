# Cryptocurrencies

*Repo Image by [Art Rachen](https://unsplash.com/@artrachen?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on Unsplash*

## Overview

The purpose of this project was to use unsupervised learning on a cryptocurrency dataset to determine how cryptocurrencies could be grouped to create a classification system for a new investment group.

## Data Source
- [CryptoCompare](https://min-api.cryptocompare.com/data/all/coinlist)

## Software
- sklearn
- Plotly
- Python
- hvPlot
- Jupyter Notebook

## Results

### Standardize Data

Once the data was cleaned, we used StandardScaler() to scale the data.
![image of code and scaled data]()

### Principal Component Analysis (PCA)

The crypotcurrency dataset had a large number of input features. We reduced the number of dimensions using PCA. We chose to group the dimensions into 3 components.

![image of dimensions grouped into 3 components]()

### Clustering Cryptocurrency using K-means

We found an elbow curve to determine the best number of cryptocurrency clusters would be a cluster of 4.

![image of elbow curve]()

The algorithm placed the cryptocurrencies in 4 different clusters based on the input features.

![3D image ofcryptocurrency clusters]()

Finally, we related these clusters or "classes" back to the tradable cryptocurrencies and visualize the classes based on total coin supply and total coins mined.

![scatterplot of total coin supply, total coins mined, and class]()


