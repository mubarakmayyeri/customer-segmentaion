# Customer Segmentation using K-Means Clustering

This project aims to perform customer segmentation for a mall using the K-Means Clustering algorithm. The dataset used contains customer information such as their age, gender, annual income, and spending score. The segmentation helps to group customers based on their similarities and differences, which can help in creating targeted marketing strategies.

## Dataset

The dataset used in this project contains the following columns:
- CustomerID: Unique ID assigned to each customer
- Gender: Gender of the customer (Male/Female)
- Age: Age of the customer
- Annual Income (k$): Annual income of the customer
- Spending Score (1-100): Score assigned to the customer based on their spending habits

## EDA

Exploratory data analysis was performed on the dataset to get insights and clean the data. The dataset contained balanced records from genders male and female. Some outliers were removed with the help of the interquartile range (IQR) and boxplot. 

## K-Means Clustering

The K-Means Clustering algorithm was used to perform customer segmentation. The elbow method was used to determine the optimal number of clusters, and it was found that the best value for k was 4. The trained algorithm has a Silhouette score of 0.35.

## Segmentation Results

Further analysis was performed on the four groups created by the algorithm, and it was found that the model grouped the customers into the following four groups:
1. Younger females  who spend more with credit card
2. Younger  males who spend more with credit card
3. Older males  who spend less
4. Older females who spend less

## Marketing Strategies

Based on the segmentation results, specific marketing strategies can be used for each group to increase sales. For example, offers can be given to the group who are spending less, and the credit limits of higher spending customers can be increased.

## Repository Contents

- `customer_segmentation.ipynb`: Jupyter Notebook containing the code and documentation of the project
- `customer_data.csv`: CSV file containing the dataset used in the project
- `README.md`: Readme file containing information about the project and repository

## Dependencies

This project requires the following Python libraries:
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Acknowledgements

The dataset used in this project is from Kaggle's Mall Customer Segmentation Data competition.

