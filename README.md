Customer Segmentation Mini Project

A beginner-friendly machine learning project using K-Means Clustering to segment mall customers.

Project Structure

```
customer_segmentation/
│
├── Customer_Segmentation.ipynb   ← Main notebook (run this!)
├── Mall_Customers.csv            ← Dataset (200 customers)
├── requirements.txt              ← Python dependencies
└── README.md                     ← This file
```

How to Run

### 1. Install dependencies
```bash
pip install -r requirements.txt
```

### 2. Launch Jupyter Notebook
```bash
jupyter notebook Customer_Segmentation.ipynb
```

### 3. Run all cells in order (Cell → Run All)

---
What the Notebook Covers

| Step | Topic |
|------|-------|
| 1 | Import Libraries |
| 2 | Load & Explore Dataset |
| 3 | Exploratory Data Analysis (EDA) |
| 4 | Feature Scaling |
| 5 | Elbow Method + Silhouette Score |
| 6 | K-Means Clustering (k=5) |
| 7 | Cluster Visualization |
| 8 | Business Insights per Segment |
| 9 | Export Results to CSV |

---

Techniques Used

- **K-Means Clustering** — unsupervised ML algorithm
- **Elbow Method** — finds optimal number of clusters (k)
- **Silhouette Score** — validates cluster quality
- **StandardScaler** — normalizes features before clustering
- **Seaborn & Matplotlib** — data visualization

---

5 Customer Segments

| Cluster | Name | Income | Spending |
|---------|------|--------|---------|
| 0 | Careful Spenders | High | Low |
| 1 | High Value Targets | High | High |
| 2 | Standard Customers | Medium | Medium |
| 3 | Budget Shoppers | Low | High |
| 4 | Low Engagers | Low | Low |

---

Requirements

- Python 3.7+
- pandas, numpy, matplotlib, seaborn, scikit-learn

---

*Made for internship — Customer Segmentation using Machine Learning*
