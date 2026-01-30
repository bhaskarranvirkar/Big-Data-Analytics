# Big-Data-Analytics
Unsupervised Clustering &amp; Country Segmentation using RapidMiner

# Unsupervised Clustering of Countries Using Economic & Business Indicators

## Project Overview
This project applies **unsupervised machine learning (clustering)** to group
countries based on 25 indicators related to transportation capacity, business
environment, financial development, and socioeconomic status.

The objective is to identify **homogeneous groups of countries** and determine
the optimal number of clusters using statistical performance metrics.

---

## Dataset Description
- 25 country-level attributes
- Covers:
  - Transportation & logistics capacity
  - Business environment & entrepreneurship
  - Financial and economic indicators
  - Socioeconomic development metrics
- Countries include developed, developing, and least developed economies

---

## Methodology
- Data standardization
- K-Means clustering
- Evaluation using:
  - **Silhouette Score**
  - **Davies–Bouldin Index (DBI)**
- Models tested with:
  - K = 2 clusters
  - K = 3 clusters

---

## Key Findings (Business Interpretation)

### 1. Natural Segmentation of Countries
The clustering exercise clearly grouped countries into:
- High-capacity / developed economies
- Lower-capacity / developing & least-developed economies

This confirms that the dataset captures meaningful global economic differences.

---

### 2. Transportation Capacity as a Major Driver
Indicators such as:
- Air freight movement
- Air passenger traffic
- Container port volume

were among the strongest contributors to cluster separation, highlighting the
importance of logistics infrastructure in economic development.

---

### 3. Business Environment Matters
Variables such as:
- Cost & time to start a business
- Startup density
- Number of procedures

helped separate business-friendly economies from restrictive ones.

---

### 4. USA and China in Same Cluster (K = 2)
In the 2-cluster solution, **USA and China** appeared in the same high-capacity
cluster due to:
- Large-scale economic output
- Strong transportation networks
- High business activity levels

This shows clustering captures **capacity**, not income level alone.

---

## Clustering Performance Evaluation

### K = 2 Clusters
- **Silhouette Score:** 0.639 (high separation)
- **Davies–Bouldin Index:** 0.717 (compact clusters)

➡️ Indicates strong, well-separated clustering.

---

### K = 3 Clusters
- **Silhouette Score:** 0.300 (weak separation)
- **Davies–Bouldin Index:** 1.101 (overlapping clusters)

➡️ Clusters are less distinct and statistically weaker.

---

## Final Conclusion
Although K = 3 produces intuitive labels (developed, developing, least-developed),
**K = 2 is statistically optimal** for this dataset.

The performance indicators clearly support a **two-cluster structure** as the
most meaningful and robust segmentation.

---

## Tools & Skills Demonstrated
- Unsupervised Machine Learning (K-Means)
- Cluster evaluation metrics
- High-dimensional data analysis
- Business & economic interpretation
- Excel-based analytical modeling

---

## Business Relevance
Such clustering can be used for:
- Market entry strategy
- Global investment prioritization
- Infrastructure planning
- Policy & development analysis
