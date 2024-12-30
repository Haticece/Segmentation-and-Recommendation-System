# Customer Segmentation and Recommendation System

This project aims to perform customer segmentation on an online retail dataset using machine learning techniques and build a simple recommendation system to make product recommendations to customers.

## Dataset

The dataset used in this project is the "Online Retail" dataset, which contains all the transactions occurring for a UK-based and registered, non-store online retail between 01/12/2010 and 09/12/2011. The dataset is available on Kaggle: [https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci](https://www.google.com/url?sa=E&source=gmail&q=https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci)

## Tools

This project is implemented in Python 3 using the following libraries:

  - NumPy
  - Pandas
  - Matplotlib
  - Seaborn
  - Scikit-learn

## Customer Segmentation

Customer segmentation is the process of dividing customers into distinct groups based on their purchasing behavior. This can help businesses to target their marketing efforts to specific groups of customers.

In this project, we use the k-means clustering algorithm to segment customers. K-means clustering is an unsupervised machine learning algorithm that works by assigning each data point to the cluster with the nearest mean.

Before segmenting the customers, the dataset is cleaned and preprocessed. This includes removing duplicate rows and missing values. Also, Recency, Monetary, and Frequency (RFM) values are calculated to remove outliers.

After preprocessing the dataset, we use the elbow method to find the optimal number of clusters. The elbow method works by plotting the within-cluster sum of squares (WCSS) for different values of k. The "elbow" point in the WCSS plot represents the optimal number of clusters.

Once we determine the optimal number of clusters, we use the k-means algorithm to segment the customers. Then, we analyze each segment and assign descriptive names to them. For example, we may find segments such as High-Value Customers, Spenders, Loyal Customers, Low-Value Customers, etc.

## Recommendation System

A recommendation system is a system that predicts items that a user may be interested in. Recommendation systems are used in a variety of applications, from e-commerce to online advertising.

In this project, we build a simple recommendation system using collaborative filtering. Collaborative filtering is a type of recommendation system that works by finding users with similar tastes based on their past behavior and recommending items liked by those users.

In this notebook, we create a rating of 1 when a user buys a product. Then, we recommend similar items using a collaborative filtering technique. We apply item-based collaborative filtering to find similar items.

## Results

The notebook performs exploratory data analysis (EDA) to gain insights into the dataset. Then it applies k-means clustering for customer segmentation and builds a collaborative filtering-based recommendation system. The results of the customer segmentation and the recommendation system are presented with visualizations and explanations.

## Conclusion

This project provides a simple example of how to perform customer segmentation and build a recommendation system using machine learning techniques. The results obtained can be used to improve marketing campaigns, increase customer satisfaction, and boost sales.

## Further Improvements

The project can be further improved by:

  - Trying other clustering algorithms
  - Incorporating other features into the segmentation process
  - Building a more sophisticated recommendation system
  - Evaluating the performance of the recommendation system using appropriate metrics
  - Deploying the recommendation system into a production environment

## Author

Farzad Nekouei

## License

This project is licensed under the MIT License - see the LICENSE file for details.
