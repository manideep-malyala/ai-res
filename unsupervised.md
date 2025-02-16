# **Unsupervised Machine Learning**

Unsupervised Machine Learning identifies patterns and relationships within **unlabeled data** without predefined outcomes. It is widely used for **clustering, anomaly detection, dimensionality reduction, and association rule learning**, enabling businesses and researchers to extract valuable insights.

## **Types of Unsupervised Learning**

| **Type**                     | **Definition**                                                                                          | **Common Use Cases**                                                                 |
|------------------------------|------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------|
| **Clustering**               | Groups similar data points based on shared characteristics.                                         | Customer segmentation, document clustering, image categorization.                   |
| **Dimensionality Reduction**  | Reduces the number of variables while preserving key data patterns.                               | Feature selection, data visualization, noise reduction in datasets.                |
| **Anomaly Detection**         | Identifies rare or unusual data points that significantly differ from the norm.                  | Fraud detection, cybersecurity threat detection, fault detection in manufacturing. |
| **Association Rule Learning** | Finds relationships between items in large datasets, often used for market analysis.             | Product recommendations, basket analysis, cross-selling strategies.                |

---

## **Comparison of Clustering, Dimensionality Reduction, Anomaly Detection, and Association Rule Learning**

| **Feature**               | **Clustering**                                      | **Dimensionality Reduction**                     | **Anomaly Detection**                          | **Association Rule Learning**                  |
|--------------------------|------------------------------------------------|----------------------------------------------|--------------------------------------------|-------------------------------------------|
| **General Definition**   | Groups data into meaningful clusters.          | Compresses high-dimensional data.           | Detects unusual data points.               | Finds relationships between data points.  |
| **In Machine Learning**  | Identifies patterns in unstructured data.      | Extracts key features from complex data.    | Flags deviations from normal patterns.     | Discovers associations between elements.  |
| **Goal**                 | Identify hidden group structures in data.      | Reduce feature space while preserving key patterns. | Identify rare or unexpected patterns. | Discover co-occurrence relationships in data.  |
| **Input**                | Unlabeled data with multiple features.         | High-dimensional dataset.                   | Normal & abnormal data points.             | Large datasets with frequently occurring transactions. |
| **Output**               | Cluster labels (e.g., customer groups).        | Lower-dimensional representation of data.   | Anomaly or normal classification.          | Frequent item sets or association rules.  |
| **Popular Algorithms**   | K-Means, DBSCAN, Hierarchical Clustering.      | PCA, t-SNE, Autoencoders.                   | Isolation Forest, One-Class SVM, LOF.      | Apriori, Eclat, FP-Growth.               |

---

## Real-World Use Cases of Unsupervised Learning**

| **Application** | **Problem Statement** | **Type** | **Detailed Explanation (Inputs & Output)** |
|---------------|----------------------|------------|----------------------------------------------------------------------------------------------------------------------------|
| **Amazon** | **Customer Segmentation for Targeted Marketing** | Clustering | **Inputs:** Purchase history, browsing behavior, demographic details. <br> **Output:** Groups of customers with similar buying behaviors. <br> **Explanation:** Amazon clusters customers into segments (e.g., tech enthusiasts, frequent buyers) to offer personalized recommendations and marketing strategies. |
| **Google Photos** | **Automatic Photo Organization by Faces** | Clustering | **Inputs:** Facial features in images. <br> **Output:** Grouped photos based on individual faces. <br> **Explanation:** Google Photos clusters images of the same person, allowing users to efficiently search and manage their albums. |
| **Netflix** | **Improving Personalized Content Recommendations** | Dimensionality Reduction | **Inputs:** User viewing history, genre preferences, interaction patterns. <br> **Output:** Compressed user preference data used in a recommendation model. <br> **Explanation:** Netflix applies **Singular Value Decomposition (SVD)** and **Principal Component Analysis (PCA)** to reduce dimensionality in user preference data, improving recommendation accuracy. |
| **Tesla** | **Detecting Unusual Driving Behavior for Safety Alerts** | Anomaly Detection | **Inputs:** Speed, acceleration, braking patterns, GPS data. <br> **Output:** Flags for risky or abnormal driving behaviors. <br> **Explanation:** Tesla’s AI detects erratic driving patterns, enabling proactive safety measures such as driver alerts and autonomous interventions. |
| **Mastercard** | **Detecting Credit Card Fraud in Transactions** | Anomaly Detection | **Inputs:** Transaction amount, location, time, spending history. <br> **Output:** Flags suspicious transactions for review. <br> **Explanation:** The AI detects unusual spending patterns that deviate from a user’s normal behavior, helping prevent fraudulent transactions. |
| **Walmart** | **Product Recommendation & Basket Analysis** | Association Rule Learning | **Inputs:** Customer purchase history, frequently bought-together items. <br> **Output:** Recommendations for frequently co-purchased products. <br> **Explanation:** Using the **Apriori** and **FP-Growth** algorithms, Walmart identifies patterns in shopping behavior (e.g., "Customers who buy bread often buy butter") to enhance cross-selling strategies. |

---
