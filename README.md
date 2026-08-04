# synent-task6-CustomerSegmentation-MahewishSaudagar

# Customer Segmentation using K-Means Clustering

## Problem Statement

The objective of this project is to segment customers into different groups based on their purchasing behavior using the K-Means Clustering algorithm. Customer segmentation helps businesses understand customer behavior and improve marketing strategies.


## Dataset Details

* **Dataset:** Mall Customer Dataset
* **Source:** Kaggle
* **Format:** CSV

### Dataset Columns

* CustomerID
* Gender
* Age
* Annual Income (k$)
* Spending Score (1–100)


## Approach

### 1. Data Loading

* Loaded the dataset using Pandas.

### 2. Data Exploration

* Displayed the first few records using head().
* Generated summary statistics using describe().
* Checked the dataset shape using `shape`.
* Checked data types using dtypes

### 3. Data Preprocessing

Performed the following preprocessing steps:
* Checked for missing values using `isnull()`.
* Checked for duplicate records using `duplicated()`.

### 4. Feature Selection

* Selected **Annual Income (k$)** and **Spending Score (1–100)** as the features for clustering.

### 5. Finding the Optimal Number of Clusters

* Applied the Elbow Method.
* Calculated WCSS (Within Cluster Sum of Squares).
* Determined the optimal number of clusters from the Elbow Curve.

### 6. K-Means Clustering

* Trained the K-Means model.
* Assigned cluster labels to each customer using `fit_predict()`.

### 7. Data Visualization

Created the following visualizations:

* Elbow Method (WCSS vs Number of Clusters)
* Scatter Plot of Customer Segments


## Results

The analysis provided the following insights:

* The Elbow Method helped identify the optimal number of customer clusters.
* Customers were grouped into distinct segments based on Annual Income and Spending Score.
* The scatter plot clearly visualized different customer groups.
* These customer segments can be used to design targeted marketing strategies.


## Technologies Used

* Python
* Pandas
* Matplotlib
* Scikit-learn
* Jupyter Notebook


## Output

Successfully implemented customer segmentation using the K-Means Clustering algorithm. The project identified customer groups based on purchasing behavior and visualized them using the Elbow Method and scatter plot. This analysis can help businesses better understand their customers and support data-driven decision-making.

