# Customer Segmentation using K-Means Clustering

## Synent Technologies – Data Science Internship  
### Intermediate Level – Task 6: Customer Segmentation

This project is developed as part of the Synent Technologies Data Science Internship Program. The objective of this task is to group customers based on purchasing behavior using Machine Learning clustering techniques. :contentReference[oaicite:0]{index=0}

---

# Project Objective

The goal of this project is to:

- Perform data preprocessing
- Analyze customer behavior
- Apply K-Means clustering
- Visualize customer segments
- Generate business insights from customer groups

This project demonstrates how businesses can use customer segmentation for targeted marketing and decision-making.

---

# Dataset Information

### Dataset Used
Mall Customer Dataset

### Dataset Source
https://www.kaggle.com/datasets/shwetabh123/mall-customers

### Dataset Features

| Feature | Description |
|---|---|
| CustomerID | Unique customer identifier |
| Gender | Male/Female |
| Age | Customer age |
| Annual Income (k$) | Annual income of customer |
| Spending Score (1-100) | Spending behavior score assigned by mall |

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# Machine Learning Workflow

## 1. Data Preprocessing

Performed:
- Checked missing values
- Removed duplicate records
- Selected important features
- Feature scaling using StandardScaler

### Selected Features
- Annual Income (k$)
- Spending Score (1-100)

These features were selected because they strongly represent customer purchasing behavior.

---

## 2. Exploratory Data Analysis (EDA)

Performed:
- Customer distribution analysis
- Income vs spending analysis
- Pattern visualization

### Key Observation
Customers with similar income levels often show very different spending behavior.

---

# K-Means Clustering

## Why K-Means?

K-Means clustering is an unsupervised Machine Learning algorithm used to group similar data points into clusters.

This helps businesses:
- identify premium customers
- target marketing campaigns
- understand customer behavior
- improve customer retention

---

# Elbow Method

The Elbow Method was used to determine the optimal number of clusters.

### Process
- Calculated WCSS (Within-Cluster Sum of Squares)
- Compared values for multiple cluster counts
- Identified optimal cluster value

### Result
Optimal number of clusters:
```python
k = 5

Project Structure
synent-task6-customersegmentation-aadarsh/
│
├── data/
│   └── Mall_Customers.csv
│
├── notebook/
│   └── customer_segmentation.ipynb
│
├── images/
│   ├── elbow_method.png
│   ├── customer_clusters.png
│   └── cluster_analysis.png
│
├── README.md
└── requirements.txt
How to Run the Project
Step 1 — Clone Repository
git clone <repository-link>
Step 2 — Install Dependencies
pip install -r requirements.txt
Step 3 — Run Notebook

Open:

customer_segmentation.ipynb

Run all cells.

Business Insights
Customers can be grouped into meaningful purchasing segments.
High-income customers do not always spend more.
Premium customers contribute significantly to revenue.
Personalized marketing strategies can improve business performance.
Future Improvements
Add customer recommendation system
Build interactive dashboard using Streamlit
Apply advanced clustering algorithms
Add customer lifetime value prediction
Output
Customer clusters
Cluster visualizations
Business insights
Customer behavior analysis
Internship Task Reference

This project is completed for:

Task 6 — Customer Segmentation

Requirements included:

Data preprocessing
Apply K-Means clustering
Visualize customer clusters
Generate insights from customer behavior
Author

Aadarsh
B.Tech CSE (AI & ML)

License

This project is created for educational and internship purposes.