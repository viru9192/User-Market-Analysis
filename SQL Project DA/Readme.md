# Market Funnel & Revenue Analysis  
### End-to-End SQL Analytics Project using Google BigQuery

---

## Project Overview

This project performs a complete sales funnel and revenue analysis using event-level e-commerce data in Google BigQuery.

The analysis focuses on:

- User conversion behavior
- Funnel performance
- Marketing channel efficiency
- Time-to-conversion
- Revenue optimization

All metrics are calculated for the last 30 days of user activity.

---

# Executive KPI Summary

| Metric | Value |
|--------|-------|
| Total Visitors | 2,630 |
| Total Buyers | 424 |
| Total Orders | 424 |
| Overall Conversion Rate | 16.12% |
| Total Revenue | $45,224.97 |
| Average Order Value (AOV) | $106.66 |
| Revenue per Buyer | $106.66 |
| Revenue per Visitor | $17.20 |
| Avg Total Journey Time | 24.3 minutes |

---

# 1️⃣ Funnel Stage Analysis

## Funnel Breakdown

| Stage | Users | Conversion Rate |
|--------|--------|----------------|
| Page Views | 2,630 | — |
| Add to Cart | 829 | 31.52% |
| Checkout Start | 580 | 69.96% |
| Payment Info | 457 | 78.79% |
| Purchase | 424 | 92.78% |
| **Overall Conversion** | — | **16.12%** |

---

## Key Insights

- Largest drop-off occurs between **Page View → Add to Cart (68.48% loss)**.
- Checkout and payment stages perform efficiently.
- Payment → Purchase conversion is very strong (92.78%).

### Business Interpretation

The main opportunity lies in improving product engagement and cart motivation rather than checkout optimization.

---

# 2️⃣ Funnel Analysis by Traffic Source

| Source | Views | Cart | Purchases | Cart Conversion | Purchase Conversion |
|--------|-------|------|----------|----------------|-------------------|
| Organic | 1069 | 358 | 182 | 33.49% | 17.03% |
| Paid Ads | 490 | 187 | 102 | 38.16% | 20.82% |
| Email | 280 | 177 | 91 | 63.21% | 32.50% |
| Social | 791 | 107 | 49 | 13.53% | 6.19% |

---

## Channel Performance Insights

### Best Performing Channel: EMAIL
- Highest cart conversion: 63.21%
- Highest purchase conversion: 32.50%

Email traffic is highly targeted and purchase-intent driven.

### Paid Ads
- Strong purchase rate (20.82%)
- Efficient ROI candidate

### Organic
- Highest traffic volume
- Moderate conversion

### Underperforming Channel: SOCIAL
- Very low purchase conversion (6.19%)
- Low cart conversion (13.53%)

---

## Strategic Recommendation

- Increase budget for Email and Paid Ads
- Optimize social targeting or content strategy
- Improve organic page experience to lift cart additions

---

# 3️⃣ Time-to-Conversion Analysis

| Metric | Value |
|--------|-------|
| Converted Users | 424 |
| Avg View → Cart | 11.12 minutes |
| Avg Cart → Purchase | 13.18 minutes |
| Avg Total Journey | 24.3 minutes |

---

## Behavioral Insights

- Users convert relatively quickly (within 24 minutes).
- Decision window is short.
- Indicates impulse-driven or strong purchase intent.

### Business Opportunity

- Implement real-time retargeting within 30 minutes.
- Offer limited-time discounts during early session.
- Improve mobile checkout experience.

---

# 4️⃣ Revenue Funnel Analysis

| Metric | Value |
|--------|-------|
| Total Revenue | $45,224.97 |
| Total Orders | 424 |
| Average Order Value | $106.66 |
| Revenue per Buyer | $106.66 |
| Revenue per Visitor | $17.20 |

---

## Revenue Insights

- Strong AOV at $106.66
- Monetization per visitor is $17.20
- Improving overall conversion by even 2% could significantly increase revenue.

---

# Business Impact Estimation

If overall conversion increases from:

16.12% → 18%

With 2,630 visitors:

Expected Buyers = 473  
Estimated Revenue = $50,455  

Potential Revenue Lift ≈ $5,000+

---

# Technical Implementation

- Google BigQuery
- Standard SQL
- CTEs
- Conditional Aggregation
- Timestamp Calculations
- Revenue Metrics
- Conversion Rate Computation

---

# Project Structure

market-funnel-analysis/
│
├── README.md
├── market_analysis.sql
└── screenshots/

---

# Skills Demonstrated

- Funnel Analytics
- Revenue Modeling
- Marketing Performance Analysis
- Customer Journey Evaluation
- KPI Design
- Business Interpretation of Data
- SQL-based Analytics Engineering

---

# Future Enhancements

- Cohort Retention Analysis
- Customer Lifetime Value (CLV)
- Product-Level Revenue Breakdown
- Funnel Segmentation by Device
- Dashboard Integration (Looker / Power BI)

---

# Author

Viranchi More  
MS in Information Systems  
Data Analytics | SQL | BigQuery | Business Intelligence  

---

