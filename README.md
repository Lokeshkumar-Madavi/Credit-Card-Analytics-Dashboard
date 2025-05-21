#  Credit Card Insights Dashboard

## 1. Background and Overview

This project presents a comprehensive **Credit Card Weekly Dashboard** developed using Power BI. The goal is to provide stakeholders with **real-time visibility into key performance metrics** across customer segments, card categories, transaction types, and revenue channels. This dashboard helps streamline decision-making by enabling detailed tracking and analysis of trends in card usage, revenue generation, and customer behavior.

---
! [[Click here to explore the interactive Power BI dashboard] (# https://app.powerbi.com/view?r=eyJrIjoiN2VkNTZjYjktODI2Ni00MDlmLTgyODYtMDk5MzdiNTJjM2JjIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9 )]

## 2. Data Structure Overview

The report consists of two main datasets visualized across multiple interactive dashboards:

- **Transaction Dataset**
  - `Revenue`
  - `Total_Trans_Ct` (Transaction Count)
  - `Total_Trans_Amt` (Total Transaction Amount)
  - `Interest_Earned`
  - `Card_Category`
  - `Use_Type`: Swipe, Chip, Online
  - `Week_Start_Date` (Time Series Analysis)

- **Customer Dataset**
  - `Income`
  - `Customer_Job`
  - `Education`
  - `Age Group`
  - `Dependent Count`
  - `Gender`
  - `State`
  - `CSS` (Customer Satisfaction Score)
  - `Marital Status`

---
![data model](https://github.com/user-attachments/assets/f878be29-eafc-4860-81ea-30d0ae902300)

## 3. Executive Summary

The dashboard captures credit card usage patterns and revenue distribution across customer and card dimensions. Key figures:

- **Total Revenue:** $57M  
- **Total Interest Earned:** $8M  
- **Total Transactions:** 667K  
- **Total Customer Income Analyzed:** $588M  
- **Customer Satisfaction Score (CSS):** 3.19 (out of 5)

The **Blue Card** dominates the market in both usage and revenue, followed by **Silver**, **Gold**, and **Platinum** categories. 

Revenue peaks were seen in **Q3 and Q4**, with transaction volumes steadily holding above **160K per quarter**. 

---

## 4. Insights Deep Dive

###  Revenue & Transactions
- **Revenue by Quarter:** Consistent across Q1–Q4 (~$14M per quarter).
- **Transaction Count:** Peaked in Q2 (~173K) and remained stable across other quarters.

### Card Performance
- **Blue Card**: $47M in revenue, $6.6M interest – top-performing card.
- **Platinum Card**: Lowest usage and revenue.
- **Swipe** usage contributed most revenue ($36M), followed by Chip ($17M) and Online ($4M).

###  Customer Segments
- **Top Profitable Job Segments**:
  - Businessman: $18M revenue, $2.6M interest.
  - White-collar and Self-employed follow next.
- **Education**:
  - Graduates and Uneducated segments bring the most revenue ($10M and $13M respectively).
- **Age Groups**:
  - 50–60 years: Highest revenue segment (~$14M).
  - Followed by 20–30 and 60+ age groups.

###  Demographics & Geography
- **Top States**:
  - CA, TX, NY, FL, and NJ lead with ~$6–7M each.
- **Marital Status**:
  - Unknown status customers account for the highest revenue ($16M).
- **Dependents**:
  - Customers with 0 or 2 dependents generate the highest revenue.

---

## 5. Recommendations

1. **Expand Blue Card Offers**:
   - Leverage Blue Card’s success with targeted promotions to boost usage further.

2. **Optimize Digital Channels**:
   - Online usage generates low revenue; consider improving digital card offerings and incentives.

3. **Target High-Income and Business Segments**:
   - Businessmen and high-income individuals drive the majority of revenue; tailored rewards or concierge services may enhance retention.

4. **Boost Usage in Low-performing States**:
   - Consider localized campaigns in underperforming regions to expand reach.

5. **Enhance Customer Satisfaction**:
   - With a CSS of 3.19, focus on improving customer service and digital UX to enhance loyalty.
