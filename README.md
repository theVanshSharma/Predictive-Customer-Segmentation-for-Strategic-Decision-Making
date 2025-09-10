# Predictive-Customer-Segmentation-for-Strategic-Decision-Making

## Project Overview
This project leverages **data-driven customer segmentation** and **predictive modeling** to identify distinct customer groups and forecast segment membership for new or existing customers. The goal is to provide actionable insights for **customer retention, engagement, and revenue growth**.

**Key Objectives:**
- Segment customers into meaningful groups based on behavior and demographics.
- Predict segment membership for new customers using a classification model.

---

## Dataset
The dataset includes the following features for each customer:

| Feature             | Description |
|--------------------|-------------|
| Age                 | Customer age in years |
| Tenure              | Duration as a customer (months) |
| Usage Frequency     | Number of times customer uses the service |
| Support Calls       | Number of customer support interactions |
| Payment Delay       | Average days of delayed payments |
| Total Spend         | Total revenue from customer |
| Last Interaction    | Days since last interaction |


## Approach

### 1. Data Preparation
- Data cleaning and handling missing values.
- Feature selection and scaling where necessary.

### 2. Customer Segmentation
- Applied **KMeans clustering** to segment customers.
- Used **Elbow Method and Silhouette Score** to determine optimal number of clusters.
- Generated cluster centroids for analysis.

### 3. Cluster Profiling
- Analyzed centroids to understand characteristics of each cluster.
- Visualized clusters using Heatmaps (centroid comparison)

### 4. Predictive Modeling
- Built a **multi-class classification model** to predict customer segment.
- Evaluated using **accuracy, precision, recall, and F1-score**.
- Enabled predictions for new customers.

---

## Tools & Technologies
- Python: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`  
- Jupyter Notebook 

---

## Business Insights
- **Cluster 0:** Target for **loyalty programs and upselling**.  
- **Cluster 1:** Focus on **engagement campaigns and payment reminders**.  
- **Cluster 2:** Proactive **customer success initiatives** to increase engagement.  
- **Cluster 3:** Encourage **higher usage while maintaining excellent payment behavior**.  

