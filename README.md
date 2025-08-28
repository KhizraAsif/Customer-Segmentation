# Customer-Segmentation

*Objective:
         The objective of this task is to segment mall customers into distinct groups based on their demographic details and spending habits. By applying unsupervised learning (K-Means clustering), we aim to identify different types of customers and propose targeted marketing strategies tailored to each segment.

*Problem Statement:
                 In a competitive retail environment, businesses often struggle to design marketing strategies that appeal to all customers equally. Since customers have different incomes, spending behaviors, and age groups, a one-size-fits-all approach is ineffective.
The challenge is to analyze customer data, identify natural groupings of customers, and suggest personalized marketing strategies for each group, which can improve customer engagement, satisfaction, and sales.

**Results and Findings:

1)Data Exploration
Dataset has 200 rows and 5 columns.
Columns include CustomerID, Gender, Age, Annual Income, Spending Score.
No missing values found.

2)Descriptive Statistics
Average customer age is around 38 years.
Annual income ranges between 15k–137k USD.
Spending score (1–100) shows variation in how much people spend.

3)K-Means Clustering (Elbow Method)
The Elbow curve suggested 5 clusters as the best choice.

4)Customer Segments Identified
.Cluster 1: High income, high spending → Target customers (luxury buyers).
.Cluster 2: Low income, low spending → Less important for promotions.
.Cluster 3: Medium income, medium spending → Potential growth customers.
.Cluster 4: High income, low spending → Can be converted with offers.
.Cluster 5: Low income, high spending → Budget-conscious but loyal buyers.

5)PCA Visualization
Reduced data to 2D for plotting clusters.
Clear separation seen among 5 customer groups.

**Final Insights
Mall should focus marketing on Cluster 1 (big spenders) and Cluster 4 (high income but low spending).
Special discounts or offers can encourage Cluster 3 to spend more.
Cluster 2 customers are not very profitable, so minimal resources should be spent on them.
