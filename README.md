Abstract
Customer segmentation is essential for enhancing marketing strategies and improving customer engagement. This project employs RFM (Recency, Frequency, Monetary) analysis to segment customers using an eCommerce dataset. We categorize customers based on their purchasing behavior to provide insights for targeted marketing and retention strategies. The methodology includes data preprocessing, RFM metric calculation, segmentation using quartiles, K-Means clustering, segment profiling, and formulating marketing recommendations. Our analysis aims to optimize marketing efforts, enhancing customer satisfaction and revenue.

Introduction
Understanding and catering to diverse customer needs is vital in today's competitive business environment. Customer segmentation categorizes customers into distinct groups based on shared characteristics, aiding in tailored marketing efforts. This project focuses on RFM Analysis, a popular method in eCommerce, evaluating customer behavior through three dimensions: Recency, Frequency, and Monetary value. By analyzing these metrics, businesses can develop targeted marketing strategies and personalized experiences.

The project involves several phases, starting with data preprocessing to ensure data quality. RFM metrics are calculated, followed by customer segmentation using quartiles or custom bins. Clustering techniques, such as K-Means, group customers with similar purchasing profiles. Segment profiling involves analyzing characteristics of each segment, including RFM scores and other relevant attributes, to develop actionable marketing recommendations.

Visualizations such as bar charts and scatter plots effectively communicate RFM scores and clusters. These visual tools provide a clear overview of customer segments, aiding decision-makers in strategy formulation. This research offers a roadmap for implementing RFM analysis, understanding customer segments, and refining marketing strategies for improved customer satisfaction and revenue.

Data Sources
The primary data source is an eCommerce dataset from Kaggle, which includes customer transactions with details such as customer IDs, purchase dates, order quantities, and unit prices. This dataset provides a foundation for RFM analysis, enabling businesses to tailor marketing and engagement strategies based on customer segments.

Summary
Data preprocessing was crucial to ensure dataset quality. Steps included exploring data types, handling missing values, and addressing outliers. The 'InvoiceDate' column was converted to datetime format, and additional dimensions such as month names and times of the day were extracted. A new 'TotalCost' column was introduced to enhance the Monetary metric. This thorough preprocessing ensured a robust dataset for RFM analysis and customer segmentation.

Identifying the correct number of segments was vital. We explored various clustering algorithms to understand the relationship between profitability and generated segments. The focus was not only on segmentation but also on how these segments correlate with profitability.

Observations
Segment 0: Most valuable, highest RFM scores, frequent buyers recently ceased purchasing.
Segment 1: Weakest, lowest performance across all metrics, recent customers not spending significantly.
Segments 2 and 3: Promising potential for increasing sales with strategic interventions.
Segment 4: Potential liabilities, lackluster performance, requiring further engagement strategies.
Limitations
Feature Reliance: Effectiveness of segmentation depends on chosen RFM metrics, which may not capture all customer behavior aspects.
Data Quality: Missing or incomplete information could influence analysis accuracy.
Algorithm Sensitivity: Clustering algorithms may produce different results with each run, requiring careful interpretation.
External Factors: Economic conditions or external events impacting customer behavior are not considered.
Conclusion
This project successfully applied RFM analysis and K-Means clustering to segment customers based on purchasing behavior. Segment profiling and product analysis provided actionable insights for targeted marketing strategies. Despite limitations, the project demonstrates RFM analysis's potential in guiding marketing and customer retention strategies. The findings offer a foundation for businesses to enhance customer-centric approaches and optimize revenue.

