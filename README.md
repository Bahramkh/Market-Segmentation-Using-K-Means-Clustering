# Market-Segmentation-Using-K-Means-Clustering
This project focuses on implementing K-Means clustering to perform market segmentation on a dataset containing customer satisfaction and loyalty metrics. The goal is to identify distinct customer segments based on their behaviors and preferences, enabling more targeted marketing strategies.
Market Segmentation Using K-Means Clustering
This project focuses on implementing K-Means clustering to perform market segmentation on a dataset containing customer satisfaction and loyalty metrics. The goal is to identify distinct customer segments based on their behaviors and preferences, enabling more targeted marketing strategies.
Key steps in this project include:
1.	Data Standardization: To ensure fair clustering, the data was standardized to eliminate biases arising from differences in scales.
2.	Optimal Cluster Selection: The Elbow Method was employed to determine the optimal number of clusters by analyzing the within-cluster sum of squares (WCSS) and identifying the point where adding more clusters provided diminishing returns.
3.	Clustering Analysis: The K-Means algorithm was applied to group customers into clusters based on their satisfaction and loyalty measures.
The results offer valuable insights into customer segmentation, providing actionable recommendations for improving customer experience and tailoring marketing strategies to specific segments.

you will see that I have used inertia_ in Elbow method, In K-Means clustering, inertia_ is a metric that measures how well the data points are clustered within their respective clusters. It represents the sum of squared distances of each data point to the centroid of the cluster it belongs to.

Key Characteristics
Lower Inertia: Indicates tighter clusters with points closer to their centroids, suggesting better clustering.
Higher Inertia: Indicates more dispersed clusters, which might suggest suboptimal clustering.
Use in the Elbow Method
inertia_ is commonly used with the Elbow Method to determine the optimal number of clusters:

Plot the inertia values for different numbers of clusters (k).
Look for the "elbow point," where the rate of decrease in inertia slows down. This is typically considered the optimal number of clusters.
Limitations
Inertia is sensitive to the scale of data. Standardizing or normalizing the data is crucial before using K-Means.
It doesn't account for the density or shape of clusters, so it may not work well with non-spherical clusters.
![image](https://github.com/user-attachments/assets/42bc8c41-ae5e-48e8-bf96-b084d37b1fc3)
