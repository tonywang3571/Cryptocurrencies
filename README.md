# Cryptocurrencies

## Overview of Project  

**Purpose:**  
The purpose of this project is to group cryptocurrencies using a clustering algoithm and create a data visualization to share our findings.  

## Resources:  
- Data Source: [Cryptocurrency data](https://min-api.cryptocompare.com/data/all/coinlist)  
- Software: Anaconda 4.10.3, Python 3.9.7, Jupyter Notebook 6.4.5, scikit-learn 0.24.2  

## Analysis and Results  

**Analysis:**  
The first thing I did with the dataset is to clean and transform our data. I first sort our data to currencies that are currently being traded, then dropping any data values that have null values in them. Next, I manipulated the data into binary information, this step allows us to perform unsupervised machine learning analysis. I also standardized our data and reduced our dimensions into three principal components. I perfomed an Elbow Curve to find the best value for "k" which is the number of clusters to group cryptocurrencies. I then created a 3D scatter plot of the cryptocurreny groupings based on the three principal components. As well as creating a 2D scatter plot of "Total Cryptocurrency Coins Mined" vs. "Total Cryptocurrency Coin Supply."  

**Results:**  
The data started with 1252 different cryptocurrencies with 6 different columns of information. After cleaning and transforming the dataset, there was 532 tradable cryptocurrencies to work with and 4 columns of data; number of columns increased to 98 after manipulating the data into binary information for the time being. Looking at our eblow curve graph, I determined that k=4 or 4 cluster groups is what I will use to group our data. The three principal components show

## Summary  

**Conclusion**  
Need to complete  


### Codes Used  

NEED to update
(Please look at specific files for codes used)  
Code for [creating the four tables](https://github.com/tonywang3571/Amanzon_Vine_Analysis/blob/master/Amazon_Reviews_ETL.ipynb)  
(NOTE: Error did occur when creating review_id_table due to data already loaded into SQL database)  
Code for [vine_review calculations](https://github.com/tonywang3571/Amanzon_Vine_Analysis/blob/master/Vine_Review_Analysis.ipynb)  
