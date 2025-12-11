# Customer Segmentation Using K-Means Clustering

<p align="justify">
This project demonstrates customer segmentation using the K-Means clustering algorithm. Customer segmentation is a key marketing technique used to divide customers into groups based on shared characteristics. In this project, customers are grouped based on their <b>Annual Income</b> and <b>Spending Score</b> to help businesses better understand customer behavior and make data-driven decisions. This project was developed during my  Internship at <b>Prodigy Infotech</b> as part of a task focused on unsupervised learning and consumer behavior analysis.
</p>

##  Table of Contents
- [Project Overview](#project-overview)
- [Why I Chose This Project](#why-i-chose-this-project)
- [Problem This Project Solves](#problem-this-project-solves)
- [Dataset](#dataset)
- [Flow of the Project](#flow-of-the-project)
- [Files in This Repository](#files-in-this-repository)
- [Tech Stack Used and Why](#tech-stack-used-and-why)
- [Usage Instructions](#usage-instructions)
- [Results and Insights](#results-and-insights)
- [Author](#author)
- [Contact](#contact)

## Project Overview
<p align="justify">
The objective of this project is to analyze customer purchasing patterns and identify distinct customer groups. Using the <b>Mall_Customers.csv</b> dataset, the project applies K-Means clustering to form meaningful customer segments. These segments help businesses understand different spending patterns, allowing them to develop targeted marketing strategies and improve customer engagement.
</p>

## Why I Chose This Project
<p align="justify">
Customer segmentation is widely used across industries such as retail, banking, e-commerce, and marketing analytics. I chose this project because it introduces real-world problem solving through unsupervised learning. Working on this helped me understand clustering algorithms, evaluation methods, and data visualization. It also strengthened my ability to translate raw data into actionable insights.
</p>

## Problem This Project Solves
<p align="justify">
Businesses often struggle to interpret diverse customer behaviors. Without segmentation, marketing strategies become generic and inefficient. This project identifies clear customer groups, such as high-income buyers, budget-conscious customers, and impulsive spenders, enabling businesses to personalize their marketing efforts and improve customer satisfaction.
</p>

## Dataset
<p align="justify">
The dataset used is <b>Mall_Customers.csv</b>, which contains the following features:
</p>

- <b>CustomerID</b>: Unique identifier for each customer  
- <b>Gender</b>: Male or Female  
- <b>Age</b>: Age of the customer  
- <b>Annual Income (k$)</b>: Annual income in thousands  
- <b>Spending Score (1–100)</b>: Score assigned based on customer purchasing behavior  

<p align="justify">
For clustering, the project focuses specifically on <b>Annual Income</b> and <b>Spending Score</b>, as these two features strongly influence customer purchasing patterns.
</p>

## Flow of the Project
<p align="justify">
The project begins with loading the dataset and performing exploratory data analysis to understand the structure, summary statistics, and customer attributes. Annual Income and Spending Score are selected as the primary features for clustering. The data is then split into training and testing subsets to visualize cluster behavior across different portions of the data.
</p>

<p align="justify">
K-Means clustering algorithm is applied with <b>five clusters</b> . After training the model, scatter plots are generated to visualize clusters for both training and testing datasets, with <b>centroids clearly marked</b>. To evaluate cluster quality, the <b>Silhouette Score</b> is computed, and the <b>Elbow Method</b> is used to validate the selection of the optimal number of clusters. The project concludes with silhouette distribution plots and final cluster visualizations, showing clear customer segments based on income and spending behavior.
</p>

## Files in This Repository
- <b>customer_segmentation.ipynb</b> – Jupyter Notebook containing the complete implementation  
- <b>Mall_Customers.csv</b> – Dataset used for clustering  
- <b>requirements.txt</b> – List of dependencies for the project  
- <b>README.md</b> – Project documentation

## Tech Stack Used and Why
- <b>Python</b>: Core programming language used  
- <b>Pandas</b>: Data loading, cleaning, and manipulation  
- <b>NumPy</b>: Numerical computations  
- <b>Matplotlib & Seaborn</b>: Visualizations of clusters and evaluation metrics  
- <b>Scikit-learn</b>: K-Means algorithm, silhouette score, train-test split  

<p align="justify">
These tools provide a powerful and flexible environment for machine learning and data analysis.
</p>

## Usage Instructions
<p align="justify">
1. <b>Clone the repository</b><br>
   <code>git clone https://github.com/JAHNAVIDINGARI/Internship-project-customer-segmentation</code>
</p>

<p align="justify">
2. <b>Navigate to the project directory</b><br>
   <code>cd customer-segmentation</code>
</p>

<p align="justify">
3. <b>Install dependencies</b><br>
   <code>pip install -r requirements.txt</code>
</p>

<p align="justify">
4. <b>Run the notebook</b><br>
   Open <b>customer_segmentation.ipynb</b> and make sure to <b>update the dataset file path</b> according to your local system. Then execute the notebook to view clustering results and visualizations.
</p>

## Results and Insights
<p align="justify">
The model successfully identifies <b>five customer segments</b>. These clusters represent distinct purchasing behaviors such as:
</p>

- High-income, high-spending customers  
- High-income, low-spending potential customers  
- Low-income, high-spending impulsive buyers  
- Moderate-income, moderate-spending regular customers  
- Low-income, low-spending budget-conscious customers  

<p align="justify">
Such segmentation allows businesses to design targeted marketing strategies, optimize product placement, and improve customer retention.
</p>

## Author
- <b>Jahnavi Dingari</b>

## Contact
<p align="justify">
For queries, collaboration, or further discussion regarding this project, please reach out via <b>LinkedIn</b> or <b>email</b>: 
  <p align="justify">
- <b>LinkedIn:</b> https://www.linkedin.com/in/jahnavi-dingari 
    <p align="justify">
- <b>Email:</b> <a href="mailto:jahnavidingari04@gmail.com">jahnavidingari04@gmail.com</a>
</p>

