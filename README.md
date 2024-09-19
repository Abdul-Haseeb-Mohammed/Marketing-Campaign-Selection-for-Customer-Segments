# CampaignOptiSales - Data Cleaning & Customer Segmentation Analysis

This project involved analyzing three years of sales data from customers who participated in marketing campaigns. The focus was on data cleaning, customer segmentation, and analyzing demographic data to optimize marketing efforts and boost sales. A combination of Python, machine learning algorithms, and Power BI was used to visualize and derive insights from the data.

## Key Objectives

1. **Data Cleaning**: Cleaning and preparing the raw sales and customer data for further analysis.
2. **RFM Analysis**: Performing **Recency, Frequency, and Monetary (RFM)** analysis to score customers, helping to segment them based on their purchase behavior.
3. **Customer Demographic Analysis**: Leveraging customer demographics (such as marital status, number of children, education level) to understand spending habits.
4. **Customer Segmentation with K-Means**: Applying **K-Means clustering** to segment customers and compare those results with RFM analysis.
5. **Apriori Algorithm Experiment**: Attempting **Apriori algorithm** for association rule learning, which couldn't be fully applied due to data aggregation.

## Project Workflow

### 1. Data Cleaning
- Dealt with missing values, duplicates, and inconsistent formats.
- Standardized data for better usability and analysis.
- Prepared the data for machine learning models and further analysis.

### 2. RFM Analysis
- **Recency**: The last time a customer made a purchase.
- **Frequency**: How often a customer made purchases.
- **Monetary**: The total spending of the customer.
- Segmented customers based on their scores for better campaign targeting.

### 3. Demographics and Spending Habits
- Analyzed how demographic factors such as marital status, education, and number of children impacted spending behavior.
- Visualized the findings using **Power BI**, which helped to create interactive dashboards and deeper insights into the customer base.

### 4. K-Means Clustering
- Performed K-Means clustering to further segment the customer base.
- Compared clusters generated using K-Means with those from RFM analysis to identify patterns in customer behavior.

### 5. Apriori Algorithm (Association Rule Mining)
- Attempted to use **Apriori algorithm** to find relationships between different products bought by customers.
- The aggregated nature of the data limited the effectiveness of this method, but it was a valuable learning experience in understanding the requirements for association rule mining.

## Tools & Technologies Used
- **Python**: For data cleaning, manipulation, and running machine learning algorithms.
- **Pandas**: For data manipulation and analysis.
- **Scikit-Learn**: For K-Means clustering and machine learning models.
- **Power BI**: For creating interactive visualizations and dashboards to better understand the data.
- **Matplotlib & Seaborn**: For data visualization in Python.
- **Apriori**: Initial experiment for association rule mining.

## Key Insights
- **RFM analysis** effectively helped in segmenting customers based on their past purchasing behaviors, which can be leveraged for future marketing campaigns.
- **Customer demographic analysis** provided a better understanding of the core customer base, revealing spending patterns influenced by family and education factors.
- **K-Means clustering** enhanced customer segmentation by grouping customers into distinct categories, allowing targeted marketing approaches.
- **Apriori experiment** highlighted the importance of transaction granularity for association rule mining, a key takeaway for future data projects.

## Conclusion
This project successfully demonstrated the power of using multiple methods like RFM analysis, and customer segmentation for improving marketing strategies. Using Power BI alongside Python allowed for quick and interactive understanding of customer behaviors, enabling data-driven decisions for marketing and sales optimization.
