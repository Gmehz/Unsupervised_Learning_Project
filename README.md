# machine_learning_project-unsupervised-learning

## Project Goals
 The goal of this project is to perform unsupervised learning techniques on a wholesale data dataset. The main objective is to segment the customers in such a way that the distributor can devise targeted marketing and service strategies for each segment, thus improving business performance and customer satisfaction. This is achieved by applying unsupervised learning techniques (like KMeans clustering, Hierarchical clustering) and Dimensionality Reduction (Principal Component Analysis) on the spending data.
 
 ## Project Steps
 The project involves four main steps: 

 1.Exploratory data analysis and pre-processing

 2.KMeans clustering

 3.Hierarchical clustering

 4.PCA.

### Project Description:
In this project, I have applied unsupervised learning techniques to a real-world data set and I have used data visualization tools so that I can communicate the insights gained from the analysis.


-	Exploratory data analysis and pre-processing: I have imported and cleaned the dataset, analyzed and visualized the relationships between the different variables. There were no missing values. I have dealt with outliers, and hot-encoded the Region and Channel columns which are categorical columns.
-	Unsupervised learning: I have performed kMeans clustering, Hierarchical clustering, and Principal component Analysis (PCA) to identify patterns and group similar data points together. After doing the KMeans and Hierarchical clustering, I have calculated and plotted the silhouette scores for the probable number of clusters. These scores help us determine the optimal number of clusters. For KMeans 3 seems a reasonable cluster, while 5 clusters also seem appropriate. As for Hierarchical clustering, 5 clusters seem to have the highest silhouette score. The PCA step makes clustering easier. PCA led to the fact that 'Channel', 'Grocery', 'Detergents_Paper', and 'Milk' are the main contributors to the first principal component. This can help us determine key factors differentiating customer groups.

## Conclusion
To cater for Tailored Marketing Strategies, with an understanding of the different distinct customer segments and their purchasing patterns, businesses can develop a tailored marketting strategies to better target these customers.






