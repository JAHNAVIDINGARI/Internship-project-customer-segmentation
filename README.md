#Customer Segmentation Using K-Means Clustering

This project demonstrates customer segmentation using the K-Means clustering algorithm. Customer segmentation is a key marketing technique used to divide customers into groups based on shared characteristics. In this project, customers are grouped based on their Annual Income and Spending Score to help businesses better understand customer behavior and make data-driven decisions. This project was developed during my Virtual Internship at Prodigy Infotech as part of a task focused on unsupervised learning and consumer behavior analysis.

##Project Overview

The objective of this project is to analyze customer purchasing patterns and identify distinct customer groups. Using the Mall_Customers.csv dataset, the project applies K-Means clustering to form meaningful customer segments. These segments help businesses understand different spending patterns, allowing them to develop targeted marketing strategies and improve customer engagement.

##Why I Chose This Project?

Customer segmentation is widely used across industries such as retail, banking, e-commerce, and marketing analytics. I chose this project because it introduces real-world problem solving through unsupervised learning. Working on this helped me understand clustering algorithms, evaluation methods, and data visualization. It also strengthened my ability to translate raw data into actionable insights.

##Problem This Project Solves!

Businesses often struggle to interpret diverse customer behaviors. Without segmentation, marketing strategies become generic and inefficient. This project identifies clear customer groups, such as high-income buyers, budget-conscious customers, and impulsive spenders, enabling businesses to personalize their marketing efforts and improve customer satisfaction.

##Dataset

The dataset used is Mall_Customers.csv, which contains the following features:

CustomerID: Unique identifier for each customer

Gender: Male or Female

Age: Age of the customer


Annual Income (k$): Annual income in thousands

Spending Score (1–100): Score assigned based on customer purchasing behavior

For clustering, the project focuses specifically on Annual Income and Spending Score, as these two features strongly influence customer purchasing patterns.

##Flow of the Project

The project begins with loading the dataset and performing exploratory data analysis to understand the structure, summary statistics, and customer attributes. Annual Income and Spending Score are selected as the primary features for clustering. The data is then split into training and testing subsets to visualize cluster behavior across different portions of the data.
K-Means clustering is applied with five clusters using the k-means++ initialization technique. After training the model, scatter plots are generated to visualize clusters for both training and testing datasets, with centroids clearly marked. To evaluate cluster quality, the Silhouette Score is computed, and the Elbow Method is used to validate the selection of the optimal number of clusters. The project concludes with silhouette distribution plots and final cluster visualizations, showing clear customer segments based on income and spending behavior.

##Files in This Repository

customer_segmentation.ipynb – Jupyter Notebook containing the complete implementation.

Mall_Customers.csv – Dataset used for clustering.

requirements.txt – List of dependencies for the project.

README.md – Project documentation.

##Tech Stack Used and Why?

Python: Core programming language used

Pandas: Data loading, cleaning, and manipulation


NumPy: Numerical computations

Matplotlib & Seaborn: Visualizations of clusters and evaluation metrics

Scikit-learn: K-Means algorithm, silhouette score, train-test split

These tools provide a powerful and flexible environment for machine learning and data analysis.

##Usage Instructions

1.	Clone the repository
git clone https://github.com/JAHNAVIDINGARI/Internship-project-customer-segmentation
2.	Navigate to the project directory
cd customer-segmentation
3.	Install dependencies
pip install -r requirements.txt
4.	Run the notebook
Open  customer_segmentation.ipynb  and in the  file make sure to update the dataset file path in the notebook according to your local system and execute to view clustering results and visualizations.

##Results and Insights

The model successfully identifies five customer segments. These clusters represent distinct purchasing behaviors such as:


High-income, high-spending customers

High-income, low-spending potential customers

Low-income, high-spending impulsive buyers

Moderate-income, moderate-spending regular customers

Low-income, low-spending budget-conscious customers

Such segmentation allows businesses to design targeted marketing strategies, optimize product placement, and improve customer retention.

##Author

Jahnavi Dingari

##Contact

For queries, collaboration, or further discussion regarding this project, please reach out via LinkedIn:
LinkedIn: https://www.linkedin.com/in/jahnavi-dingari

