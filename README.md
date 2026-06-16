# Mall Customers Segmentation using K-Means Clustering

## Project Overview

Customer segmentation is a crucial marketing strategy that helps businesses understand different groups of customers and target them effectively. This project uses **K-Means Clustering**, an unsupervised machine learning algorithm, to segment mall customers based on their purchasing behavior and annual income.

The goal is to identify distinct customer groups and generate insights that can help businesses improve marketing campaigns, customer retention, and sales strategies.

---

## Dataset

The dataset contains information about mall customers, including:

| Feature                | Description                                        |
| ---------------------- | -------------------------------------------------- |
| CustomerID             | Unique customer identifier                         |
| Gender                 | Customer gender                                    |
| Age                    | Customer age                                       |
| Annual Income (k$)     | Annual income in thousands of dollars              |
| Spending Score (1-100) | Score assigned based on customer spending behavior |

### Dataset Size

* 200 Customers
* 5 Features

---

## Objectives

* Perform Exploratory Data Analysis (EDA)
* Understand customer demographics and spending patterns
* Determine the optimal number of clusters
* Apply K-Means Clustering
* Evaluate clustering performance using Silhouette Score
* Profile customer segments and generate business insights

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Project Workflow

### 1. Data Exploration

* Checked dataset structure and missing values
* Analyzed distributions of age, income, and spending score
* Visualized customer characteristics

### 2. Feature Selection

Selected the following features for clustering:

* Annual Income (k$)
* Spending Score (1-100)

These features best capture purchasing behavior and customer value.

### 3. Finding the Optimal Number of Clusters

#### Elbow Method

The Elbow Method was used to identify the optimal number of clusters by plotting:

* Number of Clusters (K)
* Within-Cluster Sum of Squares (WCSS)

The elbow point suggested the optimal K value.

#### Silhouette Score

Silhouette Analysis was performed to evaluate cluster quality.

The clustering solution with the highest silhouette score was selected.

### 4. K-Means Clustering

Applied K-Means clustering using the optimal number of clusters and assigned each customer to a cluster.

### 5. Cluster Visualization

Visualized customer segments using scatter plots to understand cluster separation and customer behavior.

---

## Results

The analysis identified distinct customer groups with different income and spending characteristics.

### Example Customer Segments

| Cluster   | Description                          |
| --------- | ------------------------------------ |
| Cluster 0 | High Income, High Spending Customers |
| Cluster 1 | High Income, Low Spending Customers  |
| Cluster 2 | Average Customers                    |
| Cluster 3 | Low Income, High Spending Customers  |
| Cluster 4 | Low Income, Low Spending Customers   |

---

## Business Insights

### High Income, High Spending Customers

* Most valuable customer segment
* Suitable for premium products and loyalty programs

### High Income, Low Spending Customers

* Strong purchasing potential
* Can be targeted through personalized marketing campaigns

### Low Income, High Spending Customers

* Frequent buyers despite lower income
* Respond well to discounts and promotional offers

### Low Income, Low Spending Customers

* Lower priority segment
* Cost-effective marketing strategies recommended

---

## Model Evaluation

### Elbow Method

Used to determine the optimal number of clusters.

### Silhouette Score

Used to measure cluster cohesion and separation.

Higher silhouette scores indicate better-defined clusters.

---

## Visualizations

The project includes:

* Customer Age Distribution
* Gender Distribution
* Annual Income Distribution
* Spending Score Distribution
* Correlation Analysis
* Elbow Curve
* Silhouette Score Analysis
* K-Means Cluster Scatter Plot
* Cluster Profile Analysis

---

## How to Run the Project

### Clone the Repository

```bash
git clone https://github.com/Arpita7007/Mall_Customers---Clustering.git
```

### Navigate to Project Directory

```bash
cd Mall_Customers---Clustering
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook and run all cells.

---

## Future Improvements

* Hierarchical Clustering
* DBSCAN Clustering
* Gaussian Mixture Models
* PCA for Dimensionality Reduction
* Interactive Dashboards using Plotly
* Customer Lifetime Value Analysis

---

## Learning Outcomes

Through this project, I gained hands-on experience in:

* Data Preprocessing
* Exploratory Data Analysis
* Feature Selection
* Unsupervised Machine Learning
* K-Means Clustering
* Cluster Evaluation
* Business Insight Generation
* Data Visualization

---

## Author

**Arpita Sharma**

Feel free to connect and share feedback on the project.
