Customer Segmentation for Travel Agency

🚀 Project Overview

This project focuses on customer segmentation for a travel agency, utilizing machine learning clustering techniques. The goal is to group customers based on common characteristics to enhance marketing strategies and improve customer engagement.

📊 Dataset

2000 customers from a travel agency

Features: Age, Gender, Annual Income, Marital Status, Education, Occupation, Settlement Size

🔍 Methodology

Exploratory Data Analysis (EDA):

Detecting outliers, missing values, and understanding the data distribution.

Key findings:

Customers' age range: 20 to 76 years (average ~40.8 years)

Income range: $35,832 - $309,364 (average ~$137,000)

Gender split: 60% female, 40% male

Marital status: 50% married, 50% single

Education: 48% graduates, 41.5% postgraduates

Occupation: Largest segment is unemployed/unskilled (~1000 customers)

Settlement: 56.6% rural, 40% urban, 3.6% suburban

Determining Optimal Clusters:

Elbow Method & Silhouette Analysis to identify the ideal number of clusters

Best choice: k=2 clusters (highest silhouette score of 0.60)

Clustering Techniques:

K-means++ & Agglomerative Clustering

Both methods found two distinct customer groups:

Cluster 1: Younger, single females (~33 years old, $103K income, rural areas, mid-level education, lower-tier jobs)

Cluster 2: Older, married males (~48 years old, $171K income, large cities, high education, professional roles)

🎯 Recommendations

🔹 For younger, moderate-income customers:

Offer budget-friendly travel deals (weekend getaways, adventure trips, seasonal discounts)

Promote via Instagram, TikTok, Facebook using engaging content

Implement group discounts & referral programs

🔹 For older, high-income customers:

Provide luxury tours, cruises, and exclusive travel packages

Leverage email marketing, loyalty rewards, business publications

Create premium membership programs for VIP deals and private tours

🔮 Conclusion

This project successfully segmented customers into two meaningful groups, allowing for targeted marketing strategies. Future work can involve more granular segmentation and advanced machine learning techniques for personalized recommendations.

📌 Tech Stack

Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)

Machine Learning (K-means++, Agglomerative Clustering)

📫 Contact

For any questions or collaboration opportunities, reach out to Minh Anh (Jane) Tran via LinkedIn or email minnhanh.tran@students.mq.edu.au.

