Overview
This project focuses on analyzing customer and transaction data to extract valuable insights and segment customers into meaningful clusters. The tasks include identifying top products, analyzing regional performance, and performing customer segmentation using clustering techniques.

Tasks
Task 1: Top 5 Products by Total Transactions
Objective: Identify the top 5 products based on total transactions and visualize them.
Steps:
Aggregate transaction data by product to compute the total quantity sold.
Merge the aggregated data with product details.
Plot the top 5 products using a bar chart.
Output: A bar chart showing the top 5 products based on the quantity sold.
Task 2: Regional Performance Analysis
Objective: Analyze the regional performance of customer transactions.
Steps:
Aggregate transaction data to calculate total spending per region.
Merge the aggregated data with customer details.
Visualize regional spending using a pie chart.
Output: A pie chart showing the distribution of total spending across regions.
Task 3: Customer Segmentation
Objective: Perform customer segmentation using clustering techniques to identify customer groups with similar behavior.
Steps:
Aggregate transaction data to calculate total transactions and spending for each customer.
Merge the data with customer profiles and encode categorical variables (e.g., region).
Scale features and use KMeans clustering to segment customers.
Optimize the number of clusters using the Davies-Bouldin Index.
Visualize the clusters using PCA (Principal Component Analysis).
Output:
A scatter plot showing customer clusters.
A CSV file (FirstName_LastName_Clustering.csv) with cluster assignments for each customer.
How to Run
Environment Setup:

Use Google Colab or any Python environment.
Install the required libraries:
bash
Copy
Edit
pip install pandas numpy matplotlib seaborn scikit-learn
Upload the following datasets:
Customers.csv
Transactions.csv
Products.csv
Execute the Tasks:

Run the provided Python code for each task sequentially.
Ensure the required datasets are loaded into the environment.
Outputs:

Task 1: Bar chart for top 5 products.
Task 2: Pie chart for regional spending.
Task 3:
Scatter plot visualizing customer clusters.
CSV file with cluster assignments.
Dependencies
Python Libraries:
pandas: Data manipulation.
numpy: Numerical operations.
matplotlib and seaborn: Data visualization.
scikit-learn: Clustering and feature scaling.
Results and Insights
Task 1: Identified the top 5 products driving transactions.
Task 2: Highlighted regions contributing to the majority of total spending.
Task 3: Segmented customers into meaningful groups for targeted marketing strategies.
