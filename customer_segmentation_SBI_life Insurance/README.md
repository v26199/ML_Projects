# Market Segmentation in SBI Life Insurance

### Objective
The goal of this project is to develop a customer segmentation model to provide targeted recommendations for products and services like saving plans, loans, and wealth management to specific customer groups.

### Data Description
The dataset consists of information on approximately 9,000 active credit card holders' usage behaviour over the last 6 months. It includes 18 behavioural attributes for each customer, providing insights into their credit card usage patterns.

### Key Attributes for Market Segmentation
1. **PURCHASES**: Total amount of purchases made from the account. This feature helps identify high-spending customers and their purchasing behaviour patterns.

2. **BALANCE**: Remaining balance amount available for purchases. It provides insights into customers’ financial status and their credit utilization.

3. **CREDITLIMIT**: Credit card limit of the customer. Understanding credit limits allows segmentation based on customers' financial capacity.

4. **PAYMENTS**: Total amount of payments made by the customer. This feature is crucial to identify responsible customers who consistently pay off their credit card balances.

5. **ONEOFFPURCHASES**: Maximum purchase amount made in a single transaction. This helps in segmenting customers based on their tendency to make large, one-time purchases.

6. **PURCHASESFREQUENCY**: Frequency of purchases made by the customer. It indicates the regularity of a customer's spending and helps in understanding purchase behavior.

## Project Details
### Project Title
**Customer Segmentation for SBI Life Insurance** - Using clustering models to provide personalized product and service recommendations.

### Dataset
The dataset contains customer-level information on credit card usage over the last six months. It includes attributes such as balance, purchases, cash advances, payments, and more, which are used to segment customers based on their behaviour.

### Approach
We explored various unsupervised clustering algorithms, including:

- **K-Means Clustering**
- **Hierarchical Clustering**
- **DBSCAN**

#### Hyperparameters Tuning
We fine-tuned clustering models by adjusting parameters such as the number of clusters, distance metrics, and linkage methods.

#### Optimal Cluster Evaluation
- **Elbow Method**: Used to determine the optimal number of clusters by finding the point where adding more clusters does not significantly reduce the sum of squared distances.
- **Silhouette Method**: Used to evaluate cluster cohesion and separation. The silhouette score ranges from -1 to 1, with a higher score indicating better-defined clusters.

## Business Impact
This project can significantly impact the banking sector by enabling targeted marketing strategies. Based on the model’s suggestions, SBI can offer customized products and services to specific customer segments, increasing customer retention and generating additional revenue.

## Future Scope
The model can be further enhanced by incorporating additional data sources, such as customer demographics and transaction histories, to refine segmentation and recommendations. This will help the bank personalize offers even more precisely, leading to better customer engagement and profitability.
