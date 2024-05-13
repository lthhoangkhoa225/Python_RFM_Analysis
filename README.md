# Python_RFM_Analysis
## I. Introduction
### 1. About RFM Analysis
### Why RFM?
- RFM is a marketing analysis technique that stands for Recency, Frequency, and Monetary Value.
  - Recency: measures how recently a customer has made a purchase.
  - Frequency: measures how often a customer has made purchases.
  - Monetary Value: measures the total amount of money a customer has spent on purchases.
- RFM is used to identify and categorize customers based on their purchasing behavior and how recently and frequently they have made purchases, as well as the monetary value of those purchases.
### How?
- In RFM analysis, customers are scored based on three factors (Recency - how recently, Frequency - how often, Monetary - how much), then labeled based on the combination of RFM scores
### Reference
- [RFM Analysis For Successful Customer Segmentation](https://www.putler.com/rfm-analysis)
### 2. Business Questions
- The Marketing Department needs to classify the segments of each customer to deploy each marketing program suitable for each customer group.
- The Marketing Director also proposed a plan to use the RFM model in Python to segment customers, and then launch marketing campaigns to thank customers for supporting the company over the past time. As well as exploit potential customers to become loyal customers.
- Suggestions to the Marketing and Sales team with the company's retail model, which of the three indicators R, F, and M should be most interested in?
## II. Data Visualization
![image](https://github.com/lthhoangkhoa225/Python_RFM_Analysis/assets/168264791/1d235093-1c3b-4a68-a3e9-b778ab665df2)
![image](https://github.com/lthhoangkhoa225/Python_RFM_Analysis/assets/168264791/c3bbb9bc-89e2-4d20-8600-3631fa8a8d09)
![image](https://github.com/lthhoangkhoa225/Python_RFM_Analysis/assets/168264791/f4ada567-891a-401f-b7cf-8090170fa667)
![image](https://github.com/lthhoangkhoa225/Python_RFM_Analysis/assets/168264791/34436525-5bb5-48d7-9e2d-eca84f42b6c3)
![image](https://github.com/lthhoangkhoa225/Python_RFM_Analysis/assets/168264791/1ef6b1ad-0d90-4785-8745-e2f741915439)
![image](https://github.com/lthhoangkhoa225/Python_RFM_Analysis/assets/168264791/dcda603b-e240-47fb-a00c-cbf6aa46f69c)
![image](https://github.com/lthhoangkhoa225/Python_RFM_Analysis/assets/168264791/fc63be5c-84d7-4db8-b51c-6951dc9de122)
![image](https://github.com/lthhoangkhoa225/Python_RFM_Analysis/assets/168264791/e35df3fa-0f98-40b2-ba56-89f1e5f12bb9)
## III. Insights
### Customer groups are accounting for a high proportion
- The customer groups that account for a high percentage of customers are Champions (19.18%), Hibernating Customers (16.38%), Lost Customers (11.10%) and 3 groups with approximately 10% are At Risk, Loyal, Potential Loyalist.
- Customer groups with a high percentage of Sales are Champions (60.79%), Loyal (11.84%), At Risk (8.98%), Need Attention (6.06%).
### Corporate performance
- In terms of number of customers, customer groups that have not purchased for a long time account for a high proportion (45.78%) including: About to sleep, At Risk, Can't Lose Them, Hibernating Customers, Lost Customers.
- Regarding sales, important customer groups still bring high revenue (91.10%) to businesses including: Champions, Loyal, At Risk, Need Attention, Hibernating Customers.
### Characteristics of customer groups
- Champions: Average Recency is 31.59 (days), Average Frequency is 11.87 (orders), Average Monetary is 5907.99 ($).
- Loyal: Average Recency is 57.14 (days), Average Frequency is 5.33 (orders), Average Monetary is 2253.36 ($).
- Potential Loyalist: Average Recency is 46.99 (days), Average Frequency is 2.45 (orders), Average Monetary is 529.13 ($).
- New Customers: Average Recency is 49.3 (days), Average Frequency is 1.07 (orders), Average Monetary is 210.88 ($).
- Promising: Average Recency is 45.19 (days), Average Frequency is 	1.31 (orders), Average Monetary is 725.25 ($).
- Need Attention: Average Recency is 53.13 (days), Average Frequency is 3.11 (orders), Average Monetary is 1665.21 ($).
- About To Sleep: Average Recency is 107.69 (days), Average Frequency is 1.31 (orders), Average Monetary is 269.06 ($).
- Can’t Lose Them: Average Recency is 259.65 (days), Average Frequency is 2.51 (orders), Average Monetary is 2180.99 ($).
- Hibernating Customers: Average Recency is 170.13 (days), Average Frequency is 1.53 (orders), Average Monetary is 390.58 ($).
- Lost Customer: Average Recency is 293.52 (days), Average Frequency is 1.07 (orders), Average Monetary is 191.33 ($).
## IV. Recommendations
### Businesses should focus on customer groups
- **Champions:** Occupies the highest percentage of customers and sales.
- **At Risk:** High ratio of number of customers and sales.
- **Need Attention:** Has a fair purchase frequency and cart value, has not returned to purchase recently.
- **Hibernating Customers:** Accounts for a high number of customers, but there is a risk that businesses may lose these customers because they have not returned to purchase for a long time.
- **Potential Loyalist:** Has a high customer number ratio, has the potential to increase spending for the business
- **Can’t Lose Them:** Having a nearly equal ratio of customers and sales shows a stable spending level. But haven't come back to buy in a while.
### Campaign for each customer groups
#### Champions
- Offer exclusive rewards or VIP benefits to reward their loyalty.
- Provide early access to new products or services as a token of appreciation.
- Create a referral program to incentivize them to spread the word about your brand.
#### At Risk
- Send personalized offers or discounts to encourage repeat purchases.
Implement a re-engagement campaign with compelling content to reignite their interest.
- Offer extended warranties or loyalty perks to show appreciation and reinforce their value to your business.
#### Need Attention
- Send targeted emails with product recommendations based on their past purchases.
- Offer a limited-time discount or special promotion to prompt a return visit.
- Provide helpful resources or tips related to their past purchases to keep them engaged.
#### Hibernating Customers
- Launch a win-back campaign with irresistible offers or incentives to encourage a comeback.
- Send personalized emails reminiscing about their past purchases and highlighting new offerings.
- Offer a survey or feedback form to understand why they haven't returned and how to improve their experience
#### Potential Loyalist
- Offer exclusive membership benefits or rewards to encourage increased spending.
- Provide personalized recommendations based on their browsing or purchase history.
- Invite them to join a loyalty program with tiered rewards to incentivize continued engagement.
#### Can’t Lose Them
- Send targeted emails showcasing new products or services that align with their past purchases.
- Offer a special discount or incentive to encourage a return visit.
- Provide helpful resources or content related to their interests to keep them engaged and loyal.
