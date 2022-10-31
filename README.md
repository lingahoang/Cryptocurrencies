# Cryptocurrencies

## Project Overview 

After learning about unsupervised machine learning model, the client requested us to process the provided data and used all the skills to create an analysis to prepare the client to enter the cryptocurrency market. In this case, we will help to create a report that included what cryptocurrencies are on trading market and how it could be grouped to create a classification system for the new investment. 

In this project, we will used unsupervided learning, applying a clustering algorithm and will use data visualizations to share what we find with the client. 

### Data Sources

The dataset in this project is not ideal, but here is what provided: 

  * [cryto_data.csv](https://github.com/lingahoang/Cryptocurrencies/blob/main/Resources/crypto_data.csv)

### Results

## Deliverable 1 and 2: Preprocessing and Reducing the Data for PCA##

| ![Data Before Cleaning](https://github.com/lingahoang/Cryptocurrencies/blob/main/Screenshots/Data_Before_Cleaning%20.png)         | 
|:-------------:| 
| __Crypto_df before cleaning__     |  

| ![IsTrading](https://github.com/lingahoang/Cryptocurrencies/blob/main/Screenshots/IsTrading.png)          | 
|:-------------:| 
| __Cryptocurrencies that is currently trading__     |  

| ![Null Values](https://github.com/lingahoang/Cryptocurrencies/blob/main/Screenshots/Check_null_values.png)       | 
|:-------------:| 
| __Null Values that will be dropped__  |  

| ![Data After Cleaning](https://github.com/lingahoang/Cryptocurrencies/blob/main/Screenshots/DF_afer_cleaning%20.png)          | 
|:-------------:| 
| __Data After Cleaning__    |  

## Deliverable 3: Clustering Crytocurrencies Using K-Means ##

| ![ELbow Curve](https://github.com/lingahoang/Cryptocurrencies/blob/main/Screenshots/Elbow_Curve.png)           | 
|:-------------:| 
| __Elbow Curve cornfirms K-means=4 (4 clusters)__      |  

| ![Crypto 4 class](https://github.com/lingahoang/Cryptocurrencies/blob/main/Screenshots/Crypto_4_class.png)           | 
|:-------------:| 
| __Cryptocurrencies grouped by 4 classes__     |  

## Deliverable 4: Visualizing Cryptocurrencies Results ##

| ![Scatter Plot](https://github.com/lingahoang/Cryptocurrencies/blob/main/Screenshots/Scatter_Plot_w_Clusters.png)           | 
|:-------------:| 
| __3D-Scatter with Clusters__     |  

| ![Tradable Crypto](https://github.com/lingahoang/Cryptocurrencies/blob/main/Screenshots/Tradable_Crypto.png)           | 
|:-------------:| 
| __Tradable Cryptocurrencies__     |  

| ![hvplot scatter](https://github.com/lingahoang/Cryptocurrencies/blob/main/Screenshots/hvplot_Scatter_plot.png)           | 
|:-------------:| 
| __hvplot Scatter Plot__      | 


