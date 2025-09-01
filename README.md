# 🧠 Customer Segmentation Using Unsupervised Learning

The project aims to group customers of a bank based on their transactional and behavioral patterns to better understand their needs and design targeted services. Due to the sensitivity of customer data and its unavailability in the public domain, this project begins by generating a synthetic dataset that simulates real-world customer profiles using the SDV (Synthetic Data Vault) library.
The project workflow includes the following key steps:
1.	Data Generation:
o	A cleaned version of an open-source credit card dataset was used as a base.
o	Using SDV's GaussianCopula model, realistic synthetic data was generated.
o	The quality of the synthetic data was validated using SDMetrics, yielding an overall score of 81.74%, ensuring reliability for downstream tasks.
2.	Data Preprocessing:
o	Handled missing values, outliers, and irrelevant features.
o	Standardized the dataset using MinMaxScaler to prepare it for clustering algorithms.
3.	Feature Engineering:
o	Selected relevant features such as BALANCE, PURCHASES, CREDIT_LIMIT, and PAYMENTS.
o	Created derived features like Average Purchase per Transaction and Credit Utilization Ratio for deeper insights.
4.	Clustering:
o	Applied K-Means Clustering, choosing the optimal number of clusters (k=3) using the elbow method.
o	Reduced dimensions with PCA for visualization.
o	Assigned descriptive labels to each cluster based on behavioral patterns.
5.	Interpretation and Use Case Mapping:
o	Mapped each customer group to suitable banking products or strategies:
-	Cluster 0: Budget-Conscious Users → Offered basic savings and budget planning tools.


-	Cluster 1: High-Spending Users → Targeted for premium cards, investment opportunities.
-	Cluster 2: Revolvers (High balance, low payment) → Recommended credit advisory or risk monitoring.
This project demonstrates how clustering combined with synthetic data generation can help banks gain deeper insights into customer behavior while preserving privacy. The approach is scalable and applicable to a wide range of domains, including marketing, fraud detection, and credit risk modeling.



## 🛠️ Techniques Used

- Data Cleaning & Preprocessing  
- Feature Engineering (e.g. Payment Ratio, Balance Limit Ratio)
- Standardization (StandardScaler)
- Dimensionality Reduction (PCA)
- Clustering:
  - **K-Means** (with Elbow & Silhouette Score)
 
- Cluster Profiling (Cluster Centers + EDA)
- Visualization (Seaborn, Matplotlib)

---

## 📈 Results

- **K-Means** was found to be the most balanced and interpretable model based on Silhouette Score  and PCA visualization.
- Four distinct customer groups were identified and profiled.
- Boxplots and cluster center analysis revealed unique purchasing and credit behaviors across clusters.


## 📚 Dataset

- Source: [UCI Credit Card Dataset](https://www.kaggle.com/datasets/arjunbhasin2013/ccdata)
- Attributes: 18+ customer metrics including balance, purchases, payments, etc.

---

## 🚀 Future Work

- Use **t-SNE** or **UMAP** for deeper visualization  
- Apply **autoencoders** for feature compression  
- Integrate business feedback to fine-tune clusters  
- Build a **recommendation engine** on top of clusters

---

## 👩‍💻 Author

**Navya Mehta**  
Final-year IT Engineering student  
Passionate about Data Science, Business Intelligence & AI

---
