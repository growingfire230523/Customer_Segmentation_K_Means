# Customer_Segmentation_K_Means
K-means unsupervised learning application - Customer Segmentation

Path to follow : 

Initialize k using WCSS - Within Cluster Sum Of Squares, plot wcss with k and see the k value after which the wcss saturates
Randomly initialize k centroids amongst all given data points
1-(For all points color each point with the color of centroid closest to them
For each color category take mean and update the centroids)
Repeat 1 until convergence or max_iterations
