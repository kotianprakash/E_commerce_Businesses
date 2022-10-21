
# E-Commerce Businesses Analyze

A key challenge for e-commerce businesses is to analyze the trend in the market to increase their sales. The trend can be easily observed if the companies can group the customers; based on their activity on the e-commerce site. This grouping can be done by applying different criteria like previous orders, mostly searched brands and so on. The machine learning clustering algorithms can provide an analytical method to cluster customers with similar interests.


# Data Definitian:
Input variables:

1) Cust_ID Unique numbering for customers

2) Gender: Gender of the customer

3) Orders: Number of orders placed by each customer in the past

Remaining 35 features contains the number of times customers have searched them


# Conclusion 
In this case study, we have grouped the customers' dataset into 4 clusters based on the brands they have searched on e-commerce sites. We have used the silhouette score method to find the optimum number of clusters and decided k = 4 as the best pick after analyzing the silhouette score.
After applying the K-means algorithm with an optimized number of clusters, we segment the customers under 'Grocery', 'Apparels', 'Electronics', and 'Basket class' categories. These clusters give information about the interest of the customer in the different brands. This type of segmentation can help the e-commerce companies, to know the customer's choices and they can provide more accurate recommendations to the customers