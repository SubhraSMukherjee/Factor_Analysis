## Factor(Feature) Analysis of Customer Churn


Understanding customer churn is crucial for businesses to identify patterns, factors, and indicators that contribute to customer attrition. By modelling churn behavior on its associated features, we isolate the key reasons of churn and their relative importance. These reasons can be further analysed and improved on to reduce overall churn

---
The underlying dataset lists the following features per customer along with whether or not they have churned

- CustomerID (Unique numeric identifier of the Customer)
- Age
- Gender
- Tenure
- Usage Frequency
- Support Calls
- Payment Delay
- Subscription Type
- Contract Length
- Total Spend
- Last Interaction
___

The analysis lists the following features along with their relative importance (represented by their respective bar) in causing Customer Churn

*For technical details as to how we come up this conclusion see detailed analysis [here](https://github.com/SubhraSMukherjee/Factor_Analysis/blob/main/LGBM_Factor_Analysis.ipynb)*
<br></br>
![Page_1](https://github.com/SubhraSMukherjee/Factor_Analysis/blob/main/screenshots/factors.png)
<br></br>
**Support calls** is thus a primary leading indicator of churn with more support calls possibly meaning dissatisfaction while **subscription type** has no impact on the propensity to churn as per the analysis
<br></br>
The raw data corrorborates these findings as seen below
<br></br>
<img src="https://github.com/SubhraSMukherjee/Factor_Analysis/blob/main/screenshots/support.png" align="center" width="480" height="400"></img> <img src="https://github.com/SubhraSMukherjee/Factor_Analysis/blob/main/screenshots/subscription.png" align="center" width="480" height="400"></img>

