# Customer-Segmentation-Using-Hierarchical-Clustering

📌 Project Overview

This project applies Hierarchical Clustering (Agglomerative Clustering) to the Mall Customers dataset to identify distinct customer segments based on purchasing behavior.
The goal is to group customers with similar characteristics to support data-driven marketing strategies and business decision-making.

-----------------------------------------------------------------
🎯 Objectives

Perform Exploratory Data Analysis (EDA) to understand customer behavior

Preprocess and clean the dataset

Apply Hierarchical Clustering

Visualize clusters using dendrograms

Interpret customer segments for business insights
-----------------------------------------------------------------
📂 Dataset

Mall Customers Dataset
Common features include:

CustomerID

Gender

Age

Annual Income (k$)

Spending Score (1–100)

This dataset is widely used for unsupervised learning and clustering demonstrations.
-----------------------------------------------------------------
🧪 Methodology

1️⃣ Data Preprocessing

Checked missing values

Encoded categorical variables (if required)

Scaled numerical features for distance-based clustering

2️⃣ Exploratory Data Analysis

Distribution of age, income, and spending score

Relationship analysis between income and spending

Outlier inspection

3️⃣ Hierarchical Clustering

Used Agglomerative Clustering

Distance metric: Euclidean

Linkage method: Ward

Optimal number of clusters selected using dendrogram

4️⃣ Visualization

Dendrogram to choose cluster count

Scatter plots to visualize customer segments

-----------------------------------------------------------------
📊 Results

The model successfully grouped customers into meaningful segments such as:

High income – high spending customers

High income – low spending customers

Low income – high spending customers

Budget-conscious customers

These segments can be used for targeted marketing and personalization.
-----------------------------------------------------------------
🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib / Seaborn

Scikit-learn

SciPy (for dendrogram)

-----------------------------------------------------------------
🚀 How to Run
pip install pandas numpy matplotlib seaborn scikit-learn scipy

jupyter notebook


Open hierarchical_clustering.ipynb and run all cells.

-----------------------------------------------------------------
📌 Key Learnings

Importance of feature scaling in distance-based algorithms

How dendrograms help determine optimal clusters

Interpreting clusters for real-world business use

Difference between K-Means and Hierarchical Clustering

------------------------------------------------------------------
🔮 Future Improvements

Compare results with K-Means clustering

Try different linkage methods

Apply PCA for better visualization

Use silhouette score for validation

-----------------------------------------------------------------
👤 Author

Rudresh
Student | Data Science & Machine Learning Enthusiast

-----------------------------------------------------------------
