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

---

## 🔍 Cluster Profiles (Highlights)

- **Cluster 0**: High spenders with large balances and frequent transactions.
- **Cluster 1**: Low engagement users with minimal purchases and low limits.
- **Cluster 2**: Moderate spenders with regular installment use.
- **Cluster 3**: High cash advance users with large balances but low purchase frequency.

---

## 📌 Business Recommendations

- Target **Cluster 0** with premium loyalty programs.
- Offer **Cluster 1** promotions to increase engagement.
- Monitor **Cluster 3** for credit risk due to high cash withdrawals.

---

## 📂 Files

- `customersegmentationproject.ipynb`: Main notebook with complete workflow
- `README.md`: Project overview and guide

---

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
