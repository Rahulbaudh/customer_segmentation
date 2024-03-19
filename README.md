# Customer Segmentation Analysis using Machine Learning Algorithms
In this project, I performed customer segmentation analysis on a mall customer dataset using various machine learning algorithms. Customer segmentation is a crucial task for businesses as it helps in understanding customer behavior, preferences, and target marketing strategies.

# Dataset Overview
The dataset contains information about customers including their age, gender, annual income, and spending score. Here are some key steps and insights gained from the analysis:

# Data Preprocessing
Loaded the dataset using Pandas and dropped the unnecessary 'CustomerID' column.
Checked for missing values and duplicates in the dataset (No missing values were found, but there were duplicate entries).
Explored the distribution of features such as age, annual income, and spending score using histograms and violin plots.

# Exploratory Data Analysis (EDA)
Analyzed the distribution of customers based on age groups and plotted a bar chart to visualize the number of customers per age group.
Explored the relationship between annual income and spending score using a scatter plot.
Divided the customers into spending score groups and plotted a bar chart to show the number of customers in each spending score group.
Categorized customers based on annual income groups and visualized the distribution using a bar plot.

# Clustering Algorithms
K-Means Clustering
Utilized the K-Means clustering algorithm to segment customers based on age and spending score, annual income and spending score, and all available features.
Used the Elbow method to determine the optimal number of clusters for each clustering task.
Visualized the clusters using scatter plots and highlighted the cluster centers.

# Agglomerative Clustering
Implemented Agglomerative Clustering to group customers based on annual income and spending score.
Visualized the clusters using a scatter plot and labeled each cluster for better interpretation.
DBSCAN (Density-Based Spatial Clustering of Applications with Noise)
Employed DBSCAN algorithm to cluster customers based on their spending score and annual income.
Calculated the estimated number of clusters and noise points and evaluated the clustering performance using homogeneity metric.

# Conclusion
Customer segmentation analysis using machine learning algorithms provides valuable insights into customer behavior and preferences. By understanding distinct customer segments, businesses can tailor their marketing strategies, improve customer satisfaction, and optimize resource allocation.

