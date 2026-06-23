# Business Insights

## Customer Revenue Insights

* Customer **SM-20320** generated the highest total sales of **25,043.07**, making them the top-performing customer in the dataset.
* Customers **TC-20980** and **RB-19360** ranked second and third with total sales of **19,052.22** and **15,117.35** respectively.
* The top 5 customers each generated more than **14,000** in sales, indicating that a significant portion of revenue comes from a small group of customers.
* Several customers generated sales well above the average customer sales value of **2,896.85**, forming a strong high-value customer segment.

## Order Insights

* The highest individual order value observed was **22,638.48** placed by customer **SM-20320**.
* Multiple orders exceeded **10,000** in sales, showing that a small number of transactions contribute significantly to overall revenue.
* The highest order value varies considerably across customers, highlighting differences in purchasing behavior.

## Ranking Insights

* Customer ranking identified **SM-20320**, **TC-20980**, and **RB-19360** as the top three customers based on total sales.
* ROW_NUMBER() successfully assigned rankings within each customer group, helping identify the highest-value orders for individual customers.
* RANK() clearly demonstrated the sales gap between top-performing customers and the rest of the customer base.

## Customer Behavior Insights

* Some customers placed only **one order**, indicating potential opportunities for customer retention and engagement strategies.
* Customers such as **CJ-11875**, **LD-16855**, and **MG-18205** were identified among the single-order customer group.
* Customer sales distribution is highly uneven, with a few customers contributing a major share of total sales.

## Overall Observation

* Sales performance is strongly influenced by a relatively small number of high-value customers and large transactions.
* Customers generating above-average sales represent an important segment for business growth and retention efforts.
* The use of Subqueries, CTEs, JOINs, and Window Functions provided valuable insights into customer performance, order patterns, and revenue distribution.
