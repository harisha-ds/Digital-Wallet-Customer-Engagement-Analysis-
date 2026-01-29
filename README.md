# Digital Wallet Customer Engagement Analysis
### Python Analytics Project | FinTech / Customer Analytics

---

## Executive Summary
This project analyzes **customer engagement data** for a digital wallet platform to understand the reasons behind declining user activity and increasing inactivity.  
The analysis focuses on **engagement behavior, transaction patterns, reward effectiveness, customer satisfaction, and churn risk**.

Findings show that:
- A large majority of users are dormant
- Inactivity is the strongest predictor of churn
- Reward programs have limited impact on sustained engagement
- Behavioral signals matter more than demographics

---

## Problem Statement
A digital wallet company observed a significant decline in customer engagement across its platform. Many users show:
- Reduced app usage
- Lower transaction activity
- Long inactivity periods since last transaction

This decline negatively impacts **revenue, customer loyalty, and long-term retention**, increasing the risk of churn.

The objective of this project is to analyze customer behavior data and provide **data-driven insights** to improve engagement and retention strategies.

---

## Business Objectives
- Identify active, inactive, and dormant users  
- Understand transaction and spending behavior  
- Evaluate the effectiveness of rewards and incentives  
- Segment customers based on behavior and demographics  
- Identify churn risk and early warning indicators  
- Analyze the impact of customer support and satisfaction  
- Provide actionable recommendations to improve retention  

---

## Stakeholders
This analysis supports:
- **Product Managers** – Engagement and feature strategy  
- **Marketing Teams** – Retention and re-engagement campaigns  
- **Customer Support Teams** – Satisfaction and issue resolution  
- **Business Leadership** – Churn reduction and growth planning  

---

## Dataset Overview
The dataset contains **customer-level behavioral and engagement data**, including:

### Demographics
- Age Group  
- Income Level  
- Location  

### App Usage & Engagement
- App usage frequency  
- Total transactions  
- Days since last transaction  

### Rewards & Incentives
- Cashback received  
- Loyalty points earned  

### Customer Experience
- Satisfaction score  
- Issue resolution time  

The dataset was cleaned and preprocessed to remove missing values and create **derived features** such as engagement level and churn risk.

---

## Methodology
The analysis was performed using **Python** with the following approach:
1. Data cleaning and preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Feature engineering:
   - Engagement level  
   - Activity status  
   - Churn risk  
4. Group-based analysis using aggregation and segmentation  
5. Hypothesis testing to validate assumptions  
6. Interpretation of results using business context  

---

## Tools & Libraries Used
- **Python**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **SciPy** (Hypothesis Testing)

---

## Key Analysis & Findings
### Customer Engagement Overview
- ~76% of users are dormant (inactive for over 90 days)
- Only ~2% of users are highly active
- Engagement is low across all demographic segments
- App usage frequency does not strongly drive transaction volume  

**Insight:**  
Engagement decline is a **platform-wide issue**, not limited to specific demographics.

---

### Transaction & Spending Behavior
- A small group of power users generates most transactions
- Recently active users transact more than inactive users
- High engagement users transact slightly more, but the difference is moderate  
**Insight:**  
**Recency of activity** is a stronger indicator of transactions than usage frequency.

---

### Rewards & Incentives Impact
- Cashback users do not transact more than non-cashback users
- Loyalty points have limited impact on transaction frequency  
**Insight:**  
Current reward programs are **not effective** in driving sustained engagement.

---

### Customer Segmentation
- Engagement is consistently low across age, income, and location
- Mid-age users (36–55) show higher disengagement
- Older users (65+) generate higher transaction volumes despite lower engagement  
**Insight:**  
**Behavioral segmentation** is more meaningful than demographic segmentation.

---

### Churn Risk & Retention
- ~44% of users are identified as high churn risk
- High-risk users show longer inactivity and lower satisfaction
- Inactivity is the strongest early indicator of churn  
**Insight:**  
Early intervention based on inactivity and satisfaction can significantly reduce churn.

---

### Customer Support & Satisfaction
- Satisfaction and resolution time do not immediately increase transactions
- Dissatisfied users may continue transacting short-term but churn later
- Hypothesis testing confirms age does not significantly affect transaction frequency  
**Insight:**  
Support quality impacts **long-term retention**, not immediate revenue.

---

## Business Recommendations
### Improve Engagement & Retention
- Improve early onboarding to prevent early drop-off  
- Use inactivity thresholds (7, 30, 90 days) to trigger re-engagement  
- Shift from demographic targeting to behavior-based personalization  

---

### Reward Strategy Optimization
- Redesign reward programs to encourage consistent usage
- Move away from one-time incentives
- Align rewards with long-term engagement goals  

---

### Support-Driven Retention
- Proactively follow up on low satisfaction scores  
- Focus on issue resolution quality, not just speed  
- Use support interactions to educate users  
- Track repeated issues as early churn indicators  

---

### Churn Risk Reduction
- Monitor inactivity thresholds and trigger early interventions  
- Use personalized re-engagement campaigns  
- Improve onboarding experience  
- Combine behavioral and satisfaction data for churn prediction  
- Prioritize high-value users with declining engagement  

---

## Conclusion
This project shows that declining engagement in a digital wallet platform is primarily driven by:
- Inactivity
- Weak reward effectiveness
- Declining customer satisfaction  

By focusing on **behavioral signals and proactive retention strategies**, the business can improve engagement, reduce churn, and increase long-term customer value.

---

## Project Impact
- Identified churn drivers affecting nearly **half of the user base**
- Highlighted inefficiencies in reward and incentive programs
- Delivered actionable recommendations for retention improvement
- Demonstrated an end-to-end real-world analytics project

---

## Author
**Harisha Thoparapu**  
Data Analyst | Python | SQL | Power BI | Python | Statistics 
