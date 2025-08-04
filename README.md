# 🛍️ Mall Customer Segmentation (K-Means + DBSCAN)

Welcome to the **Customer Segmentation** notebook! In this notebook, we perform clustering on a shopping mall dataset using **K-Means** and **DBSCAN** to segment customers based on their spending behavior and annual income.

---

## 📌 Objective

The goal of this project is to:

- Segment customers into meaningful groups using clustering techniques.
- Understand customer behavior based on income and spending.
- Visualize the customer segments to derive business insights.
- Compare K-Means with DBSCAN clustering algorithms.

---

## 📁 Dataset Description

We are using the `Mall_Customers.csv` dataset. The features include:

| Column                     | Description                             |
|---------------------------|-----------------------------------------|
| CustomerID                | Unique ID for each customer             |
| Gender                    | Gender of the customer (Male/Female)    |
| Age                       | Age of the customer                     |
| Annual Income (k$)        | Customer's yearly income in thousands   |
| Spending Score (1-100)    | Score assigned by the mall based on behavior and spending nature |

---

## 🔧 Libraries Required

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

from sklearn.preprocessing import StandardScaler
from sklearn.cluster import KMeans, DBSCAN
from sklearn.metrics import silhouette_score

## 🛠️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/mall-customer-segmentation.git
   cd mall-customer-segmentation

## ▶️ Usage

- To run the analysis:
  ```bash
  jupyter notebook Mall_Customer_Segmentation.ipynb


---

#### 3. **Project Workflow / Methodology**
A simplified overview of the steps (or you can add a Mermaid diagram if desired).

```markdown
## 🔄 Workflow

1. Load and explore dataset
2. Preprocess and scale features
3. Visualize feature relationships
4. Apply K-Means and use Elbow method
5. Visualize clusters
6. Compare with DBSCAN clustering
7. Analyze business insights

## 💡 Key Insights

- Cluster 1: High-income high spenders — ideal premium customers.
- Cluster 2: Low-income but high spenders — budget targeting group.
- DBSCAN detected outliers and sparse points missed by K-Means.


