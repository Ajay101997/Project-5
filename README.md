# Project-5
# 📊 Telecom Data Analysis & User Clustering

## 📌 Project Overview
This project focuses on analyzing telecom user data to understand user behavior and segment users based on their engagement and experience. Machine Learning techniques and SQL Server are used for analysis, storage, and tracking.

---

## 🎯 Objectives
- Perform Exploratory Data Analysis (EDA)
- Create meaningful features (Engagement, Experience, Satisfaction)
- Segment users using KMeans Clustering
- Store processed data in SQL Server
- Track model performance

---

## 📂 Dataset
The dataset contains telecom user activity data including:
- Data usage (Download & Upload)
- Session duration
- Device details
- Application usage (YouTube, Netflix, Gaming)

---

## ⚙️ Technologies Used
- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- SQL Server
- Jupyter Notebook

---

## 🔍 Exploratory Data Analysis (EDA)
- Univariate Analysis (distribution of features)
- Bivariate Analysis (relationship between variables)
- Multivariate Analysis
- Correlation Analysis (heatmap)

---

## 🛠️ Feature Engineering
- Engagement Score → Total Data Usage
- Experience Score → Session Duration
- Satisfaction Score → Average of both

---

## 🤖 Model Building
- Algorithm: KMeans Clustering
- Optimal Clusters: K = 3 (Elbow Method)

---

## 📊 Results
- Users segmented into 3 clusters:
  - High usage users
  - Medium usage users
  - Low usage users
- Identified user behavior patterns

---

## 🗄️ SQL Integration
- Exported processed data to SQL Server
- Table Name: `user_scores`
- Verified using SELECT query

---

## 📈 Model Tracking
- Recorded parameters, execution time, and metrics
- Stored tracking data in CSV file

---

## 💾 Model Artifact
- Saved trained model as `kmeans_model.pkl`
- Enables reuse without retraining

---

## 💡 Business Insights
- Identifies high-value users
- Helps improve low-engagement users
- Supports targeted marketing
- Improves customer satisfaction

---

## ✅ Conclusion
The project successfully analyzed telecom data, segmented users, stored results in SQL Server, and implemented model tracking. It provides valuable insights for business decision-making.

---

## 📸 Screenshots

Univariate Analysis:

<img width="778" height="303" alt="image" src="https://github.com/user-attachments/assets/16f72a22-a413-44f7-9e86-7442c7361643" />

<img width="778" height="345" alt="image" src="https://github.com/user-attachments/assets/5d291aa4-c68c-4a55-9e9d-634ca8fa275f" />

Bivariate Analysis:

<img width="778" height="303" alt="image" src="https://github.com/user-attachments/assets/7531ed03-32e6-486e-86cf-84fc323c034e" />

<img width="778" height="345" alt="image" src="https://github.com/user-attachments/assets/1bc7e887-f327-498d-998d-9630a5e341e5" />

Correlation Heatmap:

<img width="759" height="690" alt="image" src="https://github.com/user-attachments/assets/a7a87319-07d1-437d-bd7f-b02c353ddfe3" />

Elbow graph:

<img width="683" height="511" alt="image" src="https://github.com/user-attachments/assets/86aa8233-3311-4d35-979a-1dadfd0c88ca" />

SQL output:

<img width="683" height="526" alt="image" src="https://github.com/user-attachments/assets/d06a95ae-9d59-4806-830f-bd8af2530721" />

<img width="583" height="511" alt="image" src="https://github.com/user-attachments/assets/80164461-3f31-4000-bcd2-9e02b817a627" />

---

## 🙌 Acknowledgement
This project was completed as part of a data analytics/machine learning assignment.

---

## 📧 Contact
Mr. Ajay Kumar Sahu  
(ajaykumarsahu2017.1997@gmail.com)
