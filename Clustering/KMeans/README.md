# 🛒 Customer Segmentation with K-Means

## 📌 Context
This dataset is created only for the **learning purpose** of customer segmentation concepts, also known as **market basket analysis**.  
I will demonstrate this using the **K-Means clustering algorithm** in its simplest form.

---

## 📊 Content
Imagine you own a **supermarket mall** and, through membership cards, you collect some basic data about your customers:
- Customer ID  
- Age  
- Gender  
- Annual Income (k$)  
- Spending Score (1–100)  

**Spending Score** is something you assign to the customer based on defined parameters like customer behavior and purchasing history.

---

## ❓ Problem Statement
As the mall owner, you want to **understand your customers** — especially those who can be easily converted into loyal buyers (target customers).  
This knowledge can then be passed to the **marketing team** to plan effective strategies.

---

## 🙏 Acknowledgements
This dataset comes from **Udemy's Machine Learning A-Z course**.  
Original dataset: [Mall_Customers.csv](https://github.com/SteffiPeTaffy/machineLearningAZ/blob/master/Machine%20Learning%20A-Z%20Template%20Folder/Part%204%20-%20Clustering/Section%2025%20-%20Hierarchical%20Clustering/Mall_Customers.csv)

I am new to the Data Science field and want to share my knowledge with others through this simple case study.

---

## 🎯 Inspiration
By the end of this project, you will be able to answer:
1. How to achieve **customer segmentation** using K-Means clustering in Python (step by step).  
2. Who are the **target customers** with whom you can start a marketing strategy.  
3. How such segmentation insights can drive **real-world marketing** strategies.  

---

## 🛠️ Tech Stack
- Python  
- pandas, numpy  
- scikit-learn  
- matplotlib, seaborn  

---

## 🚀 Workflow
1. **Data Preprocessing**  
   - Handle missing values  
   - Encode categorical features (Gender → One-Hot)  
   - Scale numeric features (StandardScaler)  

2. **Modeling (K-Means)**  
   - Use Elbow Method & Silhouette Score to choose `k`  
   - Train final K-Means with optimal clusters  

3. **Visualization**  
   - 2D scatter plots for feature pairs  
   - PCA for 2D/3D projection  
   - Silhouette plots for cluster quality  

4. **Interpretation**  
   - Centroids converted back to original units  
   - Cluster personas (age, income, spending habits, gender mix)  

---

## 📂 Files
- `Mall_Customers.csv` → dataset  
- `KMeans_Customer_Segmentation.ipynb` → notebook with step-by-step implementation  
- `README.md` → this file  

---

## 📈 Example Output
- Elbow curve showing optimal `k`  
- Silhouette scores printed for each k  
- Cluster scatter plots (`Age` vs `Spending`, `Income` vs `Spending`, etc.)  
- PCA projection with centroids  
- Human-readable cluster profiles (e.g., *young high spenders*, *older low spenders*)  

---

## ✅ Conclusion
Customer segmentation is a powerful way to:
- Identify **profitable customer groups**  
- Optimize **marketing strategy**  
- Increase **engagement and revenue**  

This simple case study shows how **unsupervised learning (K-Means)** can provide actionable insights for business decision-making.
