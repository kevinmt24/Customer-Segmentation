# Customer-Segmentation
Customer Segmentation using K Means Clustering Algorithm.


Specific groups are identified in a Mall Customer Dataset based on their age, annual income and their spendings. 

Number of Clusters is calculated using WCSS (Within Cluster Sum of Squares). Using the "elbow method" as a cutoff point is a 
common method in mathematical optimization to choose a point where diminishing returns are no longer worth the additional cost.
Elbow plot figure shows optimal number of clusters which can be selected is 4. 

![alt text](https://github.com/kevinmt24/Customer-Segmentation/blob/main/elbow.png?raw=true)

4 Cluster centroids are shown in cyan. Trained using sklearn.cluster.KMeans().

![alt text](https://github.com/kevinmt24/Customer-Segmentation/blob/main/plot.png?raw=true)
