# &#x20;**Restaurant Profitability Analysis**







#### &#x20;   **Table of Contents**





* 1\.  Purpose
* 2\.  Business Problem
* 3\.  Project Objectives
* 4\.  Dataset
* 5\.  Tools \& Technologies
* 6\.  Analytical Approach
* 7\.  Key Findings
* 8\.  Recommendations
* 9\.  Data Quality \& Limitations
* 10\. Project Files
* 11\. Conclusion









\## 1. Purpose



* Understand the profitability gap and identify the major cost and margin drivers.







\## 2. Business problem:





* Revenue increasing significantly
* Profitability lower than expectation 
* Target margin approximately 25%
* Analysis objective is to understand profitability and identify major cost/margin drivers.







\## 3. Project Objectives





* Calculate profitability
* Understand the cost structure
* Analyze product and category profitability
* Identify monthly profitability trends
* Identify data quality issues
* Suggest actionable areas for improvement



## 4. Dataset

| Table | Purpose |
|---|---|
| Orders | Orders, revenue, discounts, status, channel |
| Order Items | Product-level quantities and prices |
| Products | Product/category and food-cost information |
| Delivery | Delivery-related costs/status |
| Operating Costs | Operating expenses |
| Branches | Branch information |
| Customers | Customer information |



## 5. Tools & Technologies






\## 5. Tools \& Technologies





* Python
* Pandas
* NumPy
* Jupyter Notebook
* Excel







\## 6. Analytical Approach





* Business problem → Data understanding → Data-quality checks → Validation → KPI calculation → Profitability analysis → Product/category analysis → Cost analysis → Findings → Recommendations.







\## 7. Key Findings





* Revenue increased across the period, but profitability remained volatile rather than showing a single continuous decline.						
* Current calculated margin is 18.55% versus the 25% target; total food + operating cost burden is 81.45% of revenue.						
* Food cost is about 44.03% of revenue and remained broadly stable as a percentage of revenue across months.						
* Discount rate stayed around 8.7%; the analysis does not show a major change in discount intensity as the primary explanation for the margin gap.

&#x09;					

* Combos are the largest revenue category (23.45%) and have the lowest category margin (52.59%); several combo products also have relatively low margins.

&#x09;					

* Delivery-related amounts increased with delivery volume, while per-delivery values stayed broadly stable; available analysis does not indicate major per-order deterioration.						

&#x09;					





\## 8. Recommendations





* Recommended areas for management review



* Set cost-control workstreams around food cost and operating cost; track margin monthly.
* Review recipe/BOM costs, supplier pricing, waste and portion controls before changing menu prices.
* Break operating costs into controllable vs fixed components and investigate major monthly spikes.
* Review low-margin/high-volume products for pricing, recipe cost, portion and bundle economics.
* Monitor discount effectiveness; compare incremental sales/profit by promotion before changing discount policy.
* Continue monitoring per-order economics and failed/returned orders; do not treat delivery as the demonstrated primary cause.







\## 9. Data Quality \& Limitations





* Overall calculated profit is not presented as audited/net accounting profit; it is the project-defined revenue less food cost less operating cost.			
* Product profitability is product-level gross profit before allocated operating and delivery costs.			
* Exact savings required to reach 25% margin cannot be assigned to individual levers from the current dataset.			
* 2027-01 operating-cost data exists in the source but is outside the project period and is excluded from monthly conclusions.		
* Branch-level root-cause analysis was not used as a primary conclusion because the available analysis did not establish that branch performance explains the overall margin gap.			







\## 10. Project Files





* README.md —  Provides an overview of the project, including the business problem, objectives, analytical approach, key findings, recommendations, and limitations.



* Restaurant\_Profitability\_Analysis.ipynb —  Contains the Python/Pandas-based data analysis, calculations, and analytical workflow.



* Restaurant\_Profitability\_Client\_Report.xlsx —  Contains the final client-facing report with summarized findings, supporting evidence, and recommendations.







\## 11 Conclusion 





* The analysis established a significant gap between the current calculated profit margin and the target margin. The analysis identified major cost and margin drivers that management should review, particularly food cost, operating costs and product/category profitability. However, the available data does not support attributing the entire gap to one specific root cause or quantifying exact savings from individual actions.

