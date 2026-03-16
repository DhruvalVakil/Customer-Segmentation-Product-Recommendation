# Customer-Segmentation-Product-Recommendation

## 📌 Project Overview:

This project focuses on transforming raw e-commerce transaction data into actionable business intelligence. By leveraging unsupervised machine learning, I developed a dual-layered system that first categorizes customers into distinct behavioral segments and then provides personalized product recommendations to drive engagement.
I have implemented segmentation using K-Means, Isolation Forest, and RFM, 91.64% accuracy. Also built Neural Collaborative Filtering-based recommendations to improve user engagement.

## 🛠️ Technical Stack & Workflow:

1. Feature Engineering: Calculated RFM scores to quantify customer value and used log transformations to handle skewed distributions.

2. Clustering Logic: Applied the Elbow Method and Silhouette Analysis to determine the optimal number of clusters for K-Means.

3. Recommendation Logic: Utilized Cosine Similarity / Singular Value Decomposition (SVD) to map user-item interactions and predict high-probability purchases.

4. Optimization: Scaled features using StandardScaler to ensure the clustering algorithm wasn't biased by varying units (e.g., days vs. dollars).

## 🔑 Key Achievements:

1. Customer Segmentation: Implemented K-Means clustering and RFM (Recency, Frequency, Monetary) analysis to identify high-value "Champions" vs. "At-Risk" customers.

2. Personalization Engine: Built a recommendation system using Collaborative Filtering to suggest products based on similar user behavior.

3. Data-Driven Insights: Visualized segment-specific trends to help marketing teams tailor their outreach strategies.
