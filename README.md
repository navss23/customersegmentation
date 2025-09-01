# 🧠 Customer Segmentation Using Unsupervised Learning

This project explores **customer segmentation** by analyzing credit card transaction data. It applies various unsupervised machine learning algorithms to cluster users into meaningful groups based on their financial behavior.

---

## 📊 Objective

To identify distinct customer segments for better **targeted marketing**, **risk profiling**, and **service personalization** using clustering techniques like K-Means.

---

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
