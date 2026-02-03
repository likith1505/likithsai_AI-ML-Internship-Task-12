# Task 12: KMeans Customer Segmentation

##  Project Overview
This project implements **KMeans Clustering** to perform **customer segmentation** using the Mall Customer Segmentation dataset.  
The goal is to group customers based on their **Annual Income** and **Spending Score** to derive meaningful business insights.

This task is part of the **AI & ML Internship – Task 12**.

---

##  Tools & Technologies Used
- Python
- Google Colab
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

##  Dataset
**Dataset Name:** Mall Customer Segmentation Dataset  
**Source:** Kaggle  

### Key Features Used:
- Annual Income (k$)
- Spending Score (1–100)

The `CustomerID` column was removed as it does not contribute to clustering.

---

##  Steps Followed

1. Uploaded dataset to Google Colab  
2. Imported required Python libraries  
3. Loaded and explored the dataset  
4. Dropped unnecessary columns  
5. Applied **StandardScaler** to normalize features  
6. Used **Elbow Method** to determine optimal number of clusters  
7. Trained KMeans model with optimal K  
8. Assigned cluster labels to customers  
9. Visualized clusters using scatter plots  
10. Exported segmented dataset as CSV  

---

##  Results & Visualizations

### Elbow Method
- Used to determine the optimal number of clusters
- Optimal **K = 5**

### Cluster Visualization
- Customers are clearly grouped based on income and spending behavior

### Cluster Interpretation
- **Cluster 0:** High income, high spending (Premium Customers)
- **Cluster 1:** Low income, low spending (Budget Customers)
- **Cluster 2:** High income, low spending (Careful Customers)
- **Cluster 3:** Low income, high spending (Impulsive Buyers)
- **Cluster 4:** Average income & spending (Regular Customers)


## Output
<img width="985" height="672" alt="Image" src="https://github.com/user-attachments/assets/f952c9a0-baa4-4e9f-b7ec-562eb53ba7a2" />
<img width="918" height="373" alt="Image" src="https://github.com/user-attachments/assets/4076bce4-8dfc-44c9-b5a1-5b5721b0b7c4" />
<img width="954" height="602" alt="Image" src="https://github.com/user-attachments/assets/ef0becff-466d-435b-9f72-497fd2f0303b" />
<img width="970" height="644" alt="Image" src="https://github.com/user-attachments/assets/9912bca8-855e-4a3e-8863-c4b55d6f4a44" />