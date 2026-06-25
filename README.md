# 🛒 SmartCart Clustering System

An AI-powered Customer Segmentation System that uses Machine Learning clustering techniques to identify distinct groups of e-commerce customers based on demographics, purchasing behavior, income, engagement, and spending patterns.

## 📌 Project Overview

Businesses often treat all customers the same, resulting in ineffective marketing campaigns and lower customer retention.

The SmartCart Clustering System solves this problem by analyzing customer data and automatically grouping similar customers into meaningful segments. These segments can then be used for:

- Personalized Marketing
- Customer Retention
- Targeted Promotions
- Customer Lifetime Value Analysis
- Business Decision Making

---

## 🎯 Objectives

- Clean and preprocess customer data
- Perform feature engineering
- Analyze customer purchasing behavior
- Reduce dimensionality using PCA
- Identify optimal customer segments
- Apply clustering algorithms
- Visualize and interpret customer groups
- Generate actionable business insights

---

## 📊 Dataset Features

### Demographic Features
- Year of Birth
- Education
- Marital Status
- Income

### Household Features
- Number of Kids
- Number of Teenagers

### Purchase Behavior
- Wine Spending
- Fruit Spending
- Meat Spending
- Fish Spending
- Sweet Spending
- Gold Spending

### Customer Activity
- Web Purchases
- Catalog Purchases
- Store Purchases
- Website Visits
- Recency

---

## ⚙️ Workflow

### 1. Data Preprocessing
- Handle missing values
- Remove inconsistencies
- Prepare data for analysis

### 2. Feature Engineering
Created new features such as:

- Age
- Customer Tenure
- Total Spending
- Total Children

### 3. Exploratory Data Analysis (EDA)
- Distribution Analysis
- Correlation Heatmaps
- Customer Behavior Insights

### 4. Feature Scaling
Standardized numerical features using:

```python
StandardScaler()
```

### 5. Dimensionality Reduction
Applied Principal Component Analysis (PCA) to reduce high-dimensional data into 2D/3D space for visualization.

```python
PCA(n_components=3)
```

### 6. Cluster Optimization

Used:

- Elbow Method (WCSS)
- Silhouette Score

to determine the optimal number of clusters.

### 7. Customer Segmentation

Implemented:

#### K-Means Clustering

```python
KMeans()
```

#### Agglomerative Clustering

```python
AgglomerativeClustering()
```

### 8. Cluster Characterization

Analyzed clusters based on:

- Income
- Spending
- Purchase Frequency
- Customer Behavior

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- KMeans
- Agglomerative Clustering
- PCA
- Jupyter Notebook

---

## 📈 Machine Learning Techniques

| Technique | Purpose |
|------------|----------|
| StandardScaler | Feature Scaling |
| PCA | Dimensionality Reduction |
| K-Means | Customer Segmentation |
| Agglomerative Clustering | Hierarchical Segmentation |
| Elbow Method | Optimal Cluster Selection |
| Silhouette Score | Cluster Evaluation |

---

## 📊 Results

The model successfully segmented customers into **4 distinct customer groups** based on their spending and income behavior.

### Example Segments

#### Cluster 0
- Low/Moderate Income
- Low/Moderate Spending

#### Cluster 1
- High Income
- High Spending
- Premium Customers

#### Cluster 2
- moderate Income
- high Spending

#### Cluster 3
- Low Income
- low Spending

---

## 💡 Business Insights

The identified customer segments can help businesses:

- Launch personalized campaigns
- Improve customer engagement
- Increase conversion rates
- Reduce churn
- Optimize marketing budgets
- Identify high-value customers

---

## 🚀 Future Improvements

- Deploy using Streamlit
- Real-time customer segmentation
- Recommendation Engine Integration
- Customer Churn Prediction
- RFM Analysis
- Interactive Dashboard

---

## 📂 Project Structure

```text
SmartCart-Clustering-System/
│
├── smartcart.ipynb
├── smartcart_customers.csv
├── README.md
```

---

## ▶️ Run Locally

Clone the repository:

```bash
git clone https://github.com/Yash-sahh/SmartCart---E-commmerse-Customer-Segementation-System
```

Navigate to project folder:

```bash
cd SmartCart-Clustering-System
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

---

## 👨‍💻 Author

**Yash Sahu**

Machine Learning | Data Science | AI Enthusiast

---

## ⭐ If you found this project useful, don't forget to star the repository!
