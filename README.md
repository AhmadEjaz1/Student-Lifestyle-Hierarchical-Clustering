# Student-Lifestyle-Hierarchical-Clustering
Hierarchical Clustering is an unsupervised machine learning technique used to group similar data points into clusters based on their characteristics. In the context of student lifestyle analysis, it can help identify distinct groups of students with similar habits (e.g., study patterns, sleep schedules, social activities).

# For Data Set
visit:https://www.kaggle.com/datasets/charlottebennett1234/lifestyle-factors-and-their-impact-on-students
# Key Concepts
1. How Hierarchical Clustering Works
Agglomerative (Bottom-Up) Approach:

Starts by treating each student as a separate cluster.

Iteratively merges the closest clusters until all students are in one big cluster.

Divisive (Top-Down) Approach:

Starts with all students in one cluster and splits them recursively.

2. Key Steps in Hierarchical Clustering
Data Preprocessing

Standardize features (e.g., StudyHours, SleepHours, SocialMediaUsage) to ensure equal weighting.

Handle missing values (if any).

Distance Metric Selection

Common choices:

Euclidean Distance (for numerical data).

Manhattan Distance (less sensitive to outliers).

Cosine Similarity (if analyzing patterns rather than magnitudes).

Linkage Method

Determines how distances between clusters are calculated:

Single Linkage: Uses the smallest distance between clusters (can lead to "chaining").

Complete Linkage: Uses the largest distance (creates compact clusters).

Average Linkage: Uses the average distance (balanced approach).

Ward’s Method: Minimizes variance within clusters (popular for lifestyle segmentation).

Dendrogram Visualization

A tree-like diagram that shows how clusters merge.

Helps decide the optimal number of clusters by cutting at a certain height.

Cluster Interpretation

Analyze the lifestyle patterns of each group (e.g., "High Study-Low Sleep," "Balanced Lifestyle," "Social Media Heavy Users").

# Results
# Correlation Matrix of Student Lifestyle Factors
![image](https://github.com/user-attachments/assets/7638b40d-c008-489e-8fd5-321e15ac6d67)
# Study Efficiency vs. Study Hours
![image](https://github.com/user-attachments/assets/05d1f173-920c-49df-bd92-3aefefa0ce8e)
# Grades vs. Total Daily Activity Hours
![image](https://github.com/user-attachments/assets/3b3cc1c3-7f96-458a-b565-9b84b96c988a)
# Hierarchical Clustering
![image](https://github.com/user-attachments/assets/38a4d38d-2a8f-4b03-8ad1-0f0f01d57af7)
![image](https://github.com/user-attachments/assets/35bcf9d3-9f8a-4ef6-ab99-e47b203beca1)



