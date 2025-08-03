# Customer-Segmentation-Using-KMeans
This project performs customer segmentation using K-Means clustering on a dataset of customer demographics and spending behavior. It aims to identify distinct groups for targeted marketing.
 Process Steps/=
1. **Data Cleaning** – Removed unnecessary columns and handled missing values.
2. **Feature Selection** – Chose the most relevant numeric columns.
3. **Feature Scaling** – Used StandardScaler for normalization.
4. **Choosing K** – Applied the Elbow Method to determine the best number of clusters.
5. **Clustering** – Performed K-Means clustering.
6. **Visualization** – Used pairplots and cluster plots to analyze group differences.

7. Cluster Profiles
Cluster 0 – 🎯 Young & Active
Younger customers (age ~39), short tenure, but high transactions and high credit utilization.
Likely new but engaged customers with growing usage.

Cluster 1 – 💤 Older & Inactive
Older customers (age ~48), long tenure, low spending and usage.
Likely at-risk or dormant customers.

Cluster 2 – 🧱 Stable & Engaged
Oldest customers, longest tenure, consistent usage & loyalty, moderate utilization.
Likely mature, loyal customers.

Cluster 3 – 💰 High Rollers
Mid-aged, fewer relationships, but huge spending and very high activity.
Likely premium or high-value customers.
