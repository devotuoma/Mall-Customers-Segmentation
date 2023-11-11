Mall-Customer-Segmentation using K-Means Clustering

Overview:

Customer segmentation is a crucial application of unsupervised learning, empowering companies to identify distinct customer segments and effectively target potential user bases. In this machine learning project, we leverage the power of the K-means clustering algorithm—an essential tool for clustering unlabeled datasets. Before delving into the details of the project, let's explore the concept of customer segmentation.

![Customers](https://github.com/devotuoma/Mall-Customers-Segmentation/assets/94548340/82b1d968-06e4-4a1f-b44d-6cc8c3daf92a)

What is Customer Segmentation?

Customer segmentation involves dividing the customer base into groups based on shared characteristics, such as gender, age, interests, and spending habits. Companies adopting customer segmentation recognize that each customer has unique requirements, necessitating tailored marketing efforts. 
The goal is to gain a profound understanding of the target audience, enabling companies to create specific and effective marketing strategies. By collecting and analyzing data, companies can uncover valuable customer segments, refine their marketing techniques, and minimize investment risks.
Customer segmentation relies on key differentiators, including demographics, geography, economic status, and behavioral patterns, to categorize customers into targeted groups.

What is the K-Means Algorithm?

The K-means clustering algorithm is a fundamental technique used for grouping unlabeled datasets. The process begins by specifying the desired number of clusters (k) for the final output. The algorithm randomly selects k objects from the dataset to serve as initial cluster centers, known as centroids. Subsequently, each remaining object is assigned to the closest centroid based on Euclidean Distance—a step referred to as "cluster assignment."

After completing the initial assignment, the algorithm calculates new mean values for each cluster. The objects are then reassigned based on proximity to the updated cluster means. This iterative process continues until the cluster assignments stabilize, meaning they no longer change between iterations. The clusters identified in the final iteration are the same as those obtained in the previous one.

By applying the K-means algorithm to customer segmentation, companies can gain valuable insights into distinct customer groups, allowing for more targeted and efficient marketing strategies. This project provides a practical demonstration of how to implement K-means clustering for customer segmentation, offering a deeper understanding of both the algorithm and its application in real-world scenarios.



Dataset


The dataset is acquired from Kaggle and the link is given below :

https://www.kaggle.com/nelakurthisudheer/mall-customer-segmentation

 . The dataset consists of the following five features of 200 customers:

 . CustomerID: Unique ID assigned to the customer

 . Gender: The gender of the customer

 . Age: The age of the customer

 . Annual Income (k$): Annual Income of the customer
 . Spending Score (1-100): A score assigned by the mall based on customer behavior and spending nature.


 ![Screenshot from 2023-08-11 11-49-23](https://github.com/devotuoma/Mall-Customers-Segmentation/assets/94548340/c613eeb1-3195-48ae-82fe-49b86e30a9ab)


 ![Screenshot from 2023-08-11 11-49-55](https://github.com/devotuoma/Mall-Customers-Segmentation/assets/94548340/2b1b6ac4-d41a-413c-b9a6-c6491359eade)

 ![Screenshot from 2023-08-11 11-50-49](https://github.com/devotuoma/Mall-Customers-Segmentation/assets/94548340/10b784e0-6896-451f-bb6d-cc8d79d6a812)




![Screenshot from 2023-08-11 11-50-28](https://github.com/devotuoma/Mall-Customers-Segmentation/assets/94548340/e8737a25-ae20-4109-854e-a7da1b774fe8)



![Screenshot from 2023-08-11 11-51-09](https://github.com/devotuoma/Mall-Customers-Segmentation/assets/94548340/b38f7cd1-5557-4b4d-b456-b87bbf281bd6)


![Screenshot from 2023-08-11 11-51-23](https://github.com/devotuoma/Mall-Customers-Segmentation/assets/94548340/fc2e37a7-8b06-44d7-b6b0-e055b9020960)

![Screenshot from 2023-08-11 11-51-43](https://github.com/devotuoma/Mall-Customers-Segmentation/assets/94548340/16c0aaf8-01d0-4242-834c-718dae41ce63)


