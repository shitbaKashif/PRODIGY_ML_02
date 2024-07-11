# PRODIGY_ML_02
## K-Means Clustering for Retail Store Customers
***Overview***

This project implements a K-Means Clustering algorithm to group customers of a retail store based on their purchase history. The goal is to identify different customer segments to better understand their behavior and tailor marketing strategies accordingly.

***Dataset***

The dataset used is Mall_Customers.csv, which contains the following columns:
  - *CustomerID:* Unique ID for each customer
  - *Gender:* Gender of the customer (Male/Female)
  - *Age:* Age of the customer
  - *Annual Income (k$):* Annual income of the customer in thousands of dollars
  - *Spending Score (1-100):* Spending score assigned to the customer (1-100)

***Files***
  - *Mall_Customers.csv:* The dataset file
  - *kmeans_clustering.py:* The Python script implementing the K-Means Clustering algorithm

***Dependencies***
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  *You can install the required libraries using the following command:*
    - !pip install pandas numpy matplotlib seaborn scikit-learn

***Usage***

Ensure that the Mall_Customers.csv file is in the same directory as the V1.ipynb/V2.ipynb script.
*The script will:*
  - Load and preprocess the dataset
  - Determine the optimal number of clusters using the Elbow Method
  - Apply the K-Means Clustering algorithm
  - Visualize the clusters
  - Save the clustered data to Result.csv

***Conclusion***

This project demonstrates how to use the K-Means Clustering algorithm to segment customers based on their purchase history. By identifying different customer segments, businesses can tailor their marketing strategies and improve customer satisfaction.
