---

# **Customer Segmentation Using Clustering**  

## **Introduction**  
This project aims to **segment credit card customers based on their transaction patterns** using **K-Means Clustering**. With more accurate segmentation, Bank ABC can **develop more effective marketing strategies, enhance customer loyalty, and optimize product offerings**.  

## **Project Objectives**  
- **Identify customer credit card usage patterns**  
- **Assist in designing more targeted marketing strategies**  
- **Improve customer satisfaction and loyalty through personalized offers**  

## **Project Stages**  
1. **Data Collection** → Retrieve transaction data from **Google BigQuery**  
2. **Data Preprocessing** → Clean data, handle missing values, normalize (scaling), and reduce dimensions using PCA  
3. **Feature Engineering** → Select key variables based on customer transaction patterns  
4. **Modeling** → Apply **K-Means Clustering** to segment customers  
5. **Model Evaluation** → Determine the optimal number of clusters using **Elbow Method & Silhouette Score**  
6. **Result Visualization** → Display clustering results with **Matplotlib & Seaborn**  

## **Technologies Used**  
- **Database**: Google BigQuery  
- **Programming & Machine Learning**: SQL, Python, Scikit-learn, Pandas, NumPy  
- **Data Visualization**: Matplotlib, Seaborn  
- **Notebook**: Google Colab / Jupyter Notebook  

## **Customer Segmentation Results**  
The segmentation results classified customers into **5 clusters** with distinct characteristics:  

1. **Cluster 0** → Active customers with high balances, large credit limits, and frequent cash advance usage  
2. **Cluster 1** → Conservative customers with low transactions, small balances, and low credit limits  
3. **Cluster 2** → Moderate usage customers with varying balances and credit limits, and infrequent cash advance usage  
4. **Cluster 3** → Customers with high balances, large payments, high credit limits, but minimal cash advance usage  
5. **Cluster 4** → Customers with low balances, small payments, and rare credit card usage  

## **Business Recommendations**  
Based on the customer segmentation, **Bank ABC** can develop more targeted marketing strategies:  

- **Cluster 0** → Offer **premium products & exclusive services** to enhance loyalty among high-spending customers  
- **Cluster 1** → Educate customers on **credit card benefits** and offer credit limit increases  
- **Cluster 2** → Provide **cashback or rewards programs** to boost credit card usage  
- **Cluster 3** → Develop **special offers and exclusive services** for customers with high financial potential  
- **Cluster 4** → Promote offers to encourage more active credit card usage  

## **Suggestions for Further Analysis**  
- **Conduct additional exploratory data analysis (EDA)** → Analyze spending patterns based on transaction categories and credit card usage time  
- **Identify under-targeted customer groups** → Ensure all segments receive appropriate product offers  
- **Analyze peak transaction times** → Optimize promotions and marketing campaigns during the most active transaction periods  
- **Understand customer preferences** → Develop products that better meet customer needs  

## **Business Impact**  
- **Optimize marketing strategies** → Target customers with more relevant promotions based on their segments  
- **Enhance customer loyalty** → Provide more personalized offers to improve customer retention  
- **Maximize credit card usage** → Encourage customers to use their credit cards more actively and increase transactions per customer  

## **How to Run the Project**  
1. Clone this repository  
2. Install dependencies with `pip install -r requirements.txt`  
3. Connect to **Google BigQuery** to retrieve data  
4. Run the analysis and clustering model scripts in **Jupyter Notebook**  

## **Contact**  
For any questions or suggestions, please contact:  
**Email**: yinkasinulingga@gmail.com  

---
