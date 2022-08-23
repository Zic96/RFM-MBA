# RFM-Market Basket Analysis

## RFM
RFM analysis is a marketing technique used to quantitatively rank and group customers 
based on the recency, frequency and monetary total of their recent transactions to identify 
the best customers and perform targeted marketing campaigns. The system assigns each customer
numerical scores based on these factors to provide an objective analysis. RFM analysis is based
on the marketing adage that "80% of your business comes from 20% of your customers."

RFM analysis ranks each customer on the following factors:

**Recency.** How recent was the customer's last purchase? Customers who recently made a purchase will still have the product on their mind and are more likely to purchase or use the product again. Businesses often measure recency in days. But, depending on the product, they may measure it in years, weeks or even hours.<br>
**Frequency.** How often did this customer make a purchase in a given period? Customers who purchased once are often are more likely to purchase again. Additionally, first time customers may be good targets for follow-up advertising to convert them into more frequent customers.<br>
**Monetary.** How much money did the customer spend in a given period? Customers who spend a lot of money are more likely to spend money in the future and have a high value to a business.
<br><br>
**How RFM analysis works**<br>
RFM analysis scores customers on each of the three main factors. Generally, a score from 1 to 5 is given, with 5 being the highest. Various implementations of an RFM analysis system may use slightly different values or scaling, however.

The collection of three values for each customer is called an RFM cell. In a simple system, organizations average these values together, then sort customers from highest to lowest to find the most valuable customers. Some businesses, instead of simply averaging the three values, weigh the values differently.
<br>soucre: https://www.techtarget.com/searchdatamanagement/definition/RFM-analysis


## Market Basket Analysis

Market Basket Analysis is one of the key techniques used by large retailers to uncover associations between items. It works by looking for combinations of items that occur together frequently in transactions. To put it another way, it allows retailers to identify relationships between the items that people buy.

**Association Rules** are widely used to analyze retail basket or transaction data, and are intended to identify strong rules discovered in transaction data using measures of interestingness, based on the concept of strong rules.

**An example of Association Rules** <br><br>

Assume there are 100 customers<br>
10 of them bought milk, 8 bought butter and 6 bought both of them.<br>
bought milk => bought butter<br>
**support** = P(Milk & Butter) = 6/100 = 0.06<br>
**confidence** = support/P(Butter) = 0.06/0.08 = 0.75<br>
**lift** = confidence/P(Milk) = 0.75/0.10 = 7.5

<br>source: https://towardsdatascience.com/a-gentle-introduction-on-market-basket-analysis-association-rules-fa4b986a40ce
