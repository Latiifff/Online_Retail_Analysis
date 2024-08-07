# Online Retail Data Mastery: In-Depth Analysis with Dashboard for RFM Segmentation, Clustering, Cohorts, and Predictive Forecasting
This project utilizes advanced data analytics to enhance retail business performance through a comprehensive dashboard featuring RFM Segmentation, Clustering, Cohort Analysis, and Predictive Forecasting. The dashboard aims to address key business problems such as improving customer retention by categorizing customers with RFM analysis, enhancing customer segmentation using clustering techniques, gaining insights into customer behavior over time with cohort analysis, and optimizing sales by predicting future product demand through forecasting. Additional KPIs, including Total Customers, Total Product Sold, Total Revenue, and Average Order Value (AOV), are monitored to assess performance and guide strategic decision-making.

## 🧩 Business Problem & Objectives 

1. **Improving Customer Retention** 🔄
   - **Problem:** How can companies improve customer retention with RFM (Recency, Frequency, Monetary) analysis?
   - **Objective:** Use RFM analysis to categorize customers and develop more effective retention strategies.
2. **Enhancing Customer Segmentation** 📊
   - **Problem:** How can a company divide its customers into more meaningful segments using clustering techniques?
   - **Objective:** Apply clustering techniques to identify groups of customers with similar characteristics and develop more targeted marketing campaigns.
3. **Gaining Sales and Customer Behavior Insights** 📈
   - **Problem:** How can cohort analysis help companies track and analyze customer behavior over time?
   - **Objective:** Use cohort analysis to monitor and analyze customer behavior by time of registration or purchase.
4. **Optimizing Sales and Forecasting Demand** 🔮
   - **Problem:** How can companies increase sales by predicting future product demand using predictive forecasting?
   - **Objective:** Use predictive forecasting techniques to project future product demand and optimize inventory and sales strategies.
5. **Additional KPIs** 📋
   * **Total Customers:** Monitor the total number of customers.
   * **Total Product Sold:** Measures the total number of products sold.
   * **Total Revenue:** Calculates the total revenue generated.
   * **Average Order Value (AOV):** Finds out the average value per order.
     
## 🔑 Key Insights
1. **Additional KPIs:**
   - Total Customer Acquisition: 4,34K
   - Total Product Sold: 5,17M
   - Total Revenue: £ 8,9M
   - Average Order Value: 3,126
2. **Segmentation Analysis by Customer Acquisition:**
   - Others/Recent Shopper has the highest number of customers (1669) and generates the highest revenue (£6710K), but also has the lowest average order value (896.13K).
   - Best Customer has the least number of customers (69) but the largest revenue contribution per customer (£214K).
3. **Segmentation Analysis by Revenue:**
   - Others/Recent Shopper is the segment with the highest revenue contribution (£6710K), indicating that this segment has a high transaction volume.
   - Best Customer contributes low revenue (£12K) but has a very high average order value (1.87K).
4. **Segmentation Analysis by AOV:**
   - Others/Recent Shopper has the highest average order value (896.13K), indicating that this segment makes consistently large purchases.
   - Big Spender and Almost Lost have high average order values, indicating the potential to increase revenue with more strategic targeting.
5. **Customer Clustering:**
   - Cluster 0 is the largest cluster with the highest product and revenue contribution, however its average order value is slightly below average (£3,021).
   - Cluster 1 has the highest AOV (£3,936) and significant revenue contribution despite having few customers.
   - Cluster 2 and Cluster 3 have lower AOV and lower revenue contribution and product volume.

     
## 💡 Actionable Insights
1. **Optimize Retention:** Focus on Others/Recent Shoppers for retention and improved customer experience.
2. **Increase the Value of Best Customers:** Offer exclusive promotions to increase their purchase frequency and value.
3. **Segmentation by Cluster:**
   - Cluster 1: Retain and increase purchases.
   - Cluster 0: Increase AOV with upselling/cross-selling strategies.
   - Cluster 2: Offer incentives and loyalty programs to increase purchase frequency and engagement.
   - Cluster 3: Conduct in-depth analysis to understand their specific needs and customize products or services to make them more relevant.
4. **Loyalty Program:** Develop programs to encourage Almost Lost and Recent Shoppers to increase purchase frequency and transaction value.

## ✅ Recommendations
1. **Product Development:** Analyze best-selling products in Others/Recent Shopper and Cluster 0 to expand product offerings on demand.
2. **Targeted Marketing Campaigns:** Conduct more personalized marketing campaigns for Best Customers and Cluster 1 to increase loyalty and repeat purchases.
3. **Feedback and Service Adjustments:** Gather feedback from Almost Lost to understand their needs and customize services or products to make them more relevant.
4. **Incentive and Promotion Programs:** Offer special incentives and attractive promotions to Potential Customers to turn them into active and loyal customers.
5. **Strategy for Cluster 2:** Implement incentive and loyalty programs designed to increase purchase frequency and transaction value from customers in Cluster 2.
6. **Strategy for Cluster 3:** Conduct in-depth analysis to understand the specific preferences and needs of customers in Cluster 3, and customize products or services to increase their relevance and engagement.
   
## 🖥️ Dashboard
For detailed visualizations and further exploration of our data, please visit our Tableau dashboard:

🔰 [Online Retail Dashboard in Tableau Public](https://public.tableau.com/views/OnlineRetailDashboard_17228704584530/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

![Dashboard Page 1](Dashboard%201%20-%20Segmentation%20%26%20Clustering.png)
![Dashboard Page 2](Dashboard%202%20-%20Cohort%20%26%20Forecasting.png)

## 🚀 How to Use
To get started with this project:
1. Clone the repository: `git clone https://github.com/Latiifff/Online_Retail_Analysis.git`
2. Open the Tableau Public files included in the repository.
3. Connect the Tableau files to the dataset "Online Retail (clean data).csv".
4. Explore and customize the dashboards as needed.
   
## 📚 References
- Chen,Daqing. (2015). Online Retail. UCI Machine Learning Repository. https://doi.org/10.24432/C5BW33.
- https://medium.com/@dinichandraa/the-look-e-commerce-customer-segmentation-a45de7d44b20
