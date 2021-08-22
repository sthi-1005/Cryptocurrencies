# Cryptocurrencies

## Project Objective
Using the cryptocurrency dataset, cleanse the data and perform unsupervised machine learning tot identify any trends in the Total Coins Mined and Total Coin Supply.

## Approach Outline
Cleansing
- `get_dummies()` to transfer all variables from string to numeric values
- StandardScaler `fit_transform()` to standardize machine learning features
- drop all rows to obtain only coins currently being traded

Modelling
- Use Elbow Curve to determine ideal K-means value
- Use the PCA algorithm with 3 factors

## Visualization of Results

Elbow Curve
![bokeh_plot](https://user-images.githubusercontent.com/79720695/130341617-efd97b7e-f680-44f2-a28a-38bdd1be7c2b.png)

3D Scatter - Cluster
![image](https://user-images.githubusercontent.com/79720695/130341668-b3b6656f-13d5-42fc-a91a-6aa44b096da1.png)

Scaled 2D Scatter
![bokeh_plot (1)](https://user-images.githubusercontent.com/79720695/130341648-6cef66a3-513f-42fb-aebc-728ffc098678.png)

