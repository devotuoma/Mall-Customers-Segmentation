iOverview
 
 Custom is one of the most important applications of unsupervised learning. Using clustering techniques, companies can identify several segments of customers allowing them to target the potential user base. In this machine learning project, we will make use of K-means clustering which is the essential algorithm for clustering unlabeled datasets. Before ahead in this project, learn what actually customer segmentation is.

![Customers](https://github.com/devotuoma/Mall-Customers-Segmentation/assets/94548340/82b1d968-06e4-4a1f-b44d-6cc8c3daf92a)

What is Customer Segmentation


Customer Segmentation is the process of division of the customer base into several groups of individuals that share a similarity in different ways that are relevant to marketing such as gender, age, interests, and miscellaneous spending habits.


Companies that deploy customer segmentation are under the notion that every customer has different requirements and requires a specific marketing effort to address them appropriately. Companies aim to gain a deeper approach to the customer they are targeting. Therefore, their aim has to be specific and should be tailored to address the requirements of each and every individual customer. Furthermore, through the data collected, companies can gain a deeper understanding of customer preferences as well as the requirements for discovering valuable segments that would reap them maximum profit. This way, they can strategize their marketing techniques more efficiently and minimize the possibility of risk to their investment.



The technique of customer segmentation is dependent on several key differentiators that divide customers into groups to be targeted. Data related to demographics, geography, economic status as well as behavioral patterns play a crucial role in determining the company's direction toward addressing the various segments.


What is K-Means Algorithm


While using the k-means clustering algorithm, the first step is to indicate the number of clusters (k) that we wish to produce in the final output. The algorithm starts by selecting k objects from the dataset randomly that will serve as the initial centers for our clusters. These selected objects are the cluster means, also known as centroids. Then, the remaining objects have an assignment of the closest centroid. This centroid is defined by the Euclidean Distance present between the object and the cluster mean. We refer to this step as “cluster assignment”. When the assignment is complete, the algorithm proceeds to calculate the new mean value of each cluster present in the data. After the recalculation of the centers, the observations are checked if they are closer to a different cluster. Using the updated cluster mean, the objects undergo reassignment. This goes on repeatedly through several iterations until the cluster assignments stop altering. The clusters that are present in the current iteration are the same as the ones obtained in the previous iteration.



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


