# AWS-SaaS-Sales-Data-Analysis
The main goal is to give insight to AWS (Amazon Web Service) company, which focuses on SaaS features, to understand and optimize their business performance especially if profitability of company are negative because of factors likely based on company`s sales performance, customer segment, and company market

## Background

**AWS (Amazon Web Service)** is a Cloud Computing service from Amazon company. AWS is one of top choices for cloud computing with a series of advantages and features. Cloud Computing allows user for large-scale data storage [(Aws-Amazon, 2023)](https://aws.amazon.com/id/what-is-aws/). This technology is essentially an answer to the needs of modern business players in many industry. In this current state, there have been a series of Cloud Computing names with various classes and types of services, including AWS [(Meilinaeka, 2023)](https://it.telkomuniversity.ac.id/aws-amazon-web-service-cloud-cloud-computing-andalan/).

With its market potential, as a Data Analyst we could identify **patterns and trends** in sales volume and product preferences across different industries and customer segments. Also, we could explore other **companies buying behaviors** including purchase frequency, preferred products, and geographic distribution of customers especially in SaaS sales.

### Business Problem Statements

The AWS (Amazon Web Service) company focusing on SaaS feature is a company that sells sales and marketing software to other companies (B2B). They have collected transactions data from their customer.

1. **Analyze the company’s sales performance.** Identify the key factors that influence sales and profit especially for negative profits. This could include the impact of discounts on sales, the performance of different products, or sales trends over time.

2. **Analyze the company’s customers segment** based on their purchasing behavior, including purchase frequency, preferred products, and geographic distribution of customers.

3. **Analyze the company’s market.** Identify the top-performing regions or subregions, and understand the distribution of customers across different industries.

The company wants to understand the factors that contribute to negative profitability in the sale of SaaS products on AWS, especially in the context of products that generate negative profit. The purpose of this analysis is to identify variables that may affect negative profitability based on sales performance, customer segment, and company market. As a data analyst, we will try to answer the following question:

**“How to analyze the factors that contribute to negative profitability in the sale of SaaS products on AWS and provide recommendations to improve the profitability of these products based on company`s sales performance, customer segment, and company market?”**

### Data


This dataset contains transaction data from SaaS company selling sales and marketing software to other companies (B2B). In the dataset, each row represents a single transaction/order (9,994 transactions), and the columns include:

## **Column Description**

**Here is the Original Dataset:**

| **Columns Name** | **Column Description**                                   |
| ---------------- | -------------------------------------------------------- |
| **Row ID**       | A unique identifier for each transaction.                |
| **Order ID**     | A unique identifier for each order.                      |
| **Order Date**   | The date when the order was placed.                      |
| **Date Key**     | A numerical representation of the order date (YYYYMMDD). |
| **Contact Name** | The name of the person who placed the order.             |
| **Country**      | The country where the order was placed.                  |
| **City**         | The city where the order was placed.                     |
| **Region**       | The region where the order was placed.                   |
| **Subregion**    | The subregion where the order was placed.                |
| **Customer**     | The name of the company that placed the order.           |
| **Customer ID**  | A unique identifier for each customer.                   |
| **Industry**     | The industry the customer belongs to.                    |
| **Segment**      | The customer segment (SMB, Strategic, Enterprise, etc.). |
| **Product**      | The product was ordered.                                 |
| **License**      | The license key for the product                          |
| **Sales**        | The total sales amount for the transaction.              |
| **Quantity**     | The total number of items in the transaction             |
| **Discount**     | The discount applied to the transaction.                 |
| **Profit**       | The profit from the transaction.                         |

## Conclusion

The Marketing Suite product within the AWS SaaS company has consistently exhibited negative profit margins throughout the analyzed period. This product stands as a significant detractor from the overall profitability of the company's product line. The negative trend in profit suggests a need for immediate attention and strategic interventions.

The Marketing Suite product consistently portrays a negative profitability trend across various analysis dimensions. It’s apparent from correlation analysis, regional, sub-regional, country, city, and segment analysis that the Marketing Suite encounters substantial challenges in specific regions, sub-regions, and customer segments.

### Overall Insight for Marketing Suite

1. Discount-Profit Correlation: There's a clear negative correlation between discounts and profitability for the Marketing Suite. Increasing discounts correspond to reduced profitability, implying a need for discount strategy reassessment.

2. Regional Analysis: The Marketing Suite performs well in certain regions like AMER but struggles in regions like EMEA and APJ, reflecting the need for tailored strategies in underperforming regions.

3. Sub-Regional and Country Trends: Profitability varies across sub-regions and countries. While some areas yield profits, others face significant losses. For instance, while Canada and Egypt show profits, France and Japan depict substantial losses.

4. City-level Performance: Certain cities exhibit positive profits for the Marketing Suite, such as Helsinki and New York City, while others like Paris and Tokyo face considerable losses.

5. Segment Analysis: The SMB segment represents the largest customer base, suggesting a need to recalibrate marketing strategies to cater more effectively to this segment.
   
### Profitable Aspect for Marketing Suite

1. Segment-wise Profit Leaders: Apple, United Parcel Service, and Amazon are standout performers in their respective segments, contributing significantly to profits.

2. Customer Profitability: Specific customers, like BNP Paribas and Wells Fargo, exhibit high purchase frequencies despite the Marketing Suite's negative profit, indicating potential untapped value or other motivations.

### Areas of Concern

1. Losses in Segments: Identified customers in each segment are causing substantial losses, warranting deeper analysis to understand the factors driving these negative trends.

2. Low Purchase Frequency: Customers like Berkshire Hathaway, Pfizer, Anthem, Bosch, and Glencore might require targeted marketing or engagement strategies to increase their Marketing Suite usage.

3. Profitability Dynamics: The strong negative correlation between discounts and profit/profit margin indicates that higher discounts adversely affect profitability. This suggests a need for a reevaluation of the discount strategy to maintain a balance between boosting sales and preserving profits.

### Recommendation

**1.Srategic Customer Engagement:**

- Focus on understanding the motivations of high-frequency customers like BNP Paribas and Wells Fargo to leverage these insights for better engagement strategies.

**2. Loss Mitigation Strategies:**

- Further analyze the factors contributing to losses among specific customers to develop targeted strategies for improvement or, if necessary, consider reevaluating the relationship.

**3. Pricing Strategy and Cost-Benefit Analysis:**

- Conduct a thorough cost-benefit analysis of the Marketing Suite to understand its cost structure and perceived value. This will aid in assessing whether the pricing strategy aligns with customer expectations and market conditions.

**4. Discount Strategy Optimization:**

- Revisit and optimize the discount strategy to strike a balance between driving sales and preserving profit margins. Consider tiered discounts or conditional offers to maintain profitability.

**5. Sales-Focused Initiatives:**

- Invest in strategies that boost sales without heavily relying on discounts. These strategies, based on the weak positive relationship between sales and profit/profit margin, can potentially improve profitability without compromising on discounts.

## Authors

* **Hieremias Kevin Juwantoro** - *Initial work* - [PurpleBooth](https://github.com/kevinjuwantoro/AWS-SaaS-Sales-Data-Analysis/blob/main/AWS%20SaaS%20Sales%20Capstone%202_Hieremias%20Kevin%20Juwantoro.IPYNB)



