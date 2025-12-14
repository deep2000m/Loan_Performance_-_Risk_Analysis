**Loan Performance & Risk Analysis**

This project presents a comprehensive analysis of loan performance and risk factors using the given dataset. The study was conducted in two phases—Loan Performance Analysis and Risk Analysis—with dashboards developed for both. The findings aim to highlight borrower behavior, portfolio health, and actionable recommendations for improving loan management strategies.


---

1. Project Overview

Dataset Focus: Loan records with customer demographics, loan characteristics, credit risk indicators, and repayment details.

Objective: To analyze borrower patterns, loan performance, and associated risks to uncover inefficiencies and provide actionable recommendations.

Deliverables:

Loan Performance Dashboard

Risk Analysis Dashboard

Business Insights & Recommendations


---

2. Loan Performance Analysis

Portfolio Summary

Total Loan Amount: 25M

Average Metrics:

Credit Score: 563

Interest Rate: 9.95%

DTI (Debt-to-Income): 21.4

Tenure: 99 months (~8 years)



Borrower Segmentation

Income Groups:

EMI 1500k–2000k → High income group

DTI 200k–700k → Low income group (38.9% of borrowers)


LTI (Loan-to-Income): 0.38, concentrated in the high-income group (1500k–2000k).


Loan Distribution

Age vs Loan Size: Majority of loans are taken by customers aged 19–35 (working class).

Tenure Patterns: Most loans are below 100 months, indicating preference for medium-term repayment.


Credit Score vs Loan Behavior

Correlation (Loan vs Credit Score): -0.02 → negligible relationship.

Suggests loans are issued irrespective of creditworthiness.




---

3. Risk Analysis

Portfolio Risk Indicators

Total Outstanding: 2.06M

Recovered Amount: 724k

Collateral Amount: 1.07M

Average CCR (Credit Conversion Rate): 10.03

Average EAD (Exposure at Default): 61.6k


LGD (Loss Given Default)

Highest LGD observed in 1500k–200k loan segment.


Loan Characteristics

Interest Rate Bands:

Clustered around 5–7% (low range) and 12–15% (high range).


Secured vs Unsecured:

69.64% of loans classified as unsecured, exposing lenders to higher risk.




---

4. Key Insights

1. Borrowers prefer long-term loans (5–8 years) for repayment flexibility.


2. Loan demand is strongest among younger working-class customers (19–35 age group).


3. Lifestyle patterns may drive frequent short-notice loan applications.


4. Credit score is not a determining factor, indicating weak underwriting practices.


5. A significant proportion of high-interest (>10%) loans suggests frequent use of immediate or emergency loans.


6. High share of unsecured lending (≈70%) significantly increases portfolio risk.




---

5. Recommendations

Strengthen Credit Evaluation: Introduce stricter credit score checks to prevent riskier disbursements.

Risk-Based Pricing: Align interest rates with borrower profiles rather than issuing uniformly across score ranges.

Collateral Enforcement: Reduce unsecured lending by mandating collateral for larger loan sizes.

Targeted Financial Products:

Offer shorter-term, lower-interest loans for younger segments.

Develop structured products tailored to high-income vs low-income groups.


Early Warning Monitoring: Implement dashboards to flag high LGD segments and track EAD trends.

Customer Education: Financial literacy programs to reduce reliance on emergency, high-cost loans.



---

6. Conclusion

This analysis demonstrates how a lender’s portfolio can be at risk if creditworthiness is overlooked and unsecured lending dominates. By applying data-driven insights and targeted interventions, financial institutions can improve repayment outcomes, reduce defaults, and design customer-centric yet risk-sensitive loan products.

---

8. Dashboard Mock Layouts

A. Loan Performance Dashboard

Objective: Highlight borrower demographics, loan distribution, and repayment trends.

Layout Idea:

Top KPIs (cards at the top):

Total Loan Amount = 25M

Avg Credit Score = 563

Avg Interest Rate = 9.95%

Avg Tenure = 99 months


Visuals:

📊 Bar Chart → Loan Size by Age Group (showing 19–35 dominance).

📉 Line Chart → Average Loan Tenure vs Loan Amount.

🥧 Pie/Donut Chart → Income Group Segmentation (High vs Low).

📊 Scatter Plot → Loan Amount vs Credit Score (flat line showing negligible correlation).

![Image](https://github.com/user-attachments/assets/31f78750-1f92-4b03-aa81-7aee634e10c3)
---

B. Risk Analysis Dashboard

Objective: Evaluate portfolio risks, LGD, collateral, and unsecured exposure.

Layout Idea:

Top KPIs (cards at the top):

Total Outstanding = 2.06M

Recovered Amount = 724k

Collateral = 1.07M

Avg CCR = 10.03

Avg EAD = 61.6k


Visuals:

📊 Stacked Bar Chart → Secured vs Unsecured Loan Share (≈70% unsecured).

📉 Heatmap → LGD across Loan Segments (highlight 1500k–200k as highest).

📈 Histogram → Interest Rate Distribution (clusters at 5–7% and 12–15%).

📊 Waterfall Chart → Outstanding → Recovered → Loss (visualizing gaps).


![Image](https://github.com/user-attachments/assets/c2b6be0d-970e-4f41-9a9b-3d6a639e08e7)

---

9. How to Use

1. Open the dashboards in Power BI / Tableau (depending on tool).


2. Use slicers/filters to explore:

Age groups

Income segments

Loan size bands

Secured vs Unsecured loans




Portfolio Positioning:

This project demonstrates:

Domain Knowledge → Loan underwriting, risk metrics (LGD, EAD, CCR, DTI, LTI).

Analytical Depth → Correlation testing, income-based segmentation, repayment analysis.

BI Skills → Dashboard design (segmentation, distribution, KPI tracking).

Business Value → Clear recommendations that link analysis to risk management strategy.
