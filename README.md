# 📊 Netflix Pricing Tier LTV Experiment  
**Merged Test of Feature & Price Impact**

This case study simulates a pricing tier experiment for a subscription-based product like Netflix. It explores how a newly introduced Premium plan—with a higher price and enhanced features—impacts customer Lifetime Value (LTV), churn, and user upgrade behavior compared to the existing Standard plan.

---

## 📊 Problem Statement

Netflix's product team is exploring two monetization paths:

- **Standard Tier**: $17.99/month — no new features
- **Premium Tier**: $29.99/month — includes a new built-in feature that enables seamless streaming even with poor internet

The Premium tier price was recently increased from **$25.99** to **$29.99**.

---

## 📊 Business Question

> Does introducing a Premium tier with a new feature at a higher price ($29.99) generate higher long-term revenue (LTV) than maintaining a Standard-only plan at $17.99, while keeping churn at an acceptable level?

---

## 📊 Hypotheses

### 1. 📈 **Primary Hypothesis – LTV Impact**

- **H₀**: No significant difference in average LTV between Premium and Standard tiers.
- **H₁**: Premium tier results in a higher average LTV despite potential churn.

### 2. 📈 **Secondary Hypothesis – Churn Risk**

- **H₀**: Churn rate remains the same or lower for Premium tier.
- **H₁**: Churn rate is significantly higher in Premium, potentially offsetting revenue gains.

### 3. 📈 **Tertiary Hypothesis – Feature Value**

- **H₀**: New feature does not improve retention or conversion.
- **H₁**: Feature increases retention/conversion enough to justify price.

### 4. 📈 **Behavioral Hypothesis – User Response**

- **H₀**: Retention and conversion remain the same or fall slightly, while downgrade rate increases.
- **H₁**: Premium tier boosts LTV via higher retention, conversion, and lower downgrade rate.

---

## 📊 Experiment Design

- **Type**: Simulated SaaS Pricing Tier A/B Test (Merged: Feature + Price)
- **Groups**:
  - `Standard`: $17.99/month, no new feature
  - `Premium`: $29.99/month, includes new feature
- **Sample Size**: 1,000 users per group
- **Duration**: 6 months (simulated)
- **Controlled Variables**: Acquisition channels, onboarding, UX

---

## 📊 Key Metrics Tracked

| Metric                  | Description                                      |
|------------------------|--------------------------------------------------|
| **Conversion Rate**    | % of users who convert from trial or free        |
| **Churn Rate**         | % of users who cancel subscription               |
| **Retention Rate**     | % of users who remain active over time           |
| **LTV**                | Lifetime Value = ARPU × 6 (months)               |
| **ARPU**               | Average Revenue Per User                         |
| **Upgrade Rate**       | % of users who move from Standard → Premium      |
| **Downgrade Rate**     | % of users who move from Premium → Standard      |

---

## 📁 Simulated Dataset

>  [Click here to view dataset.csv](./Netflix-Pricing-Tier-LTV-Experiment.csv)

| user_id | group     | month | converted | churned | active | upgraded | downgraded | monthly_revenue | 
|---------|-----------|-------|-----------|---------|--------|----------|------------|---------|
| 001     | Premium   | 1     | 1         | 0       | 1      | 0        | 0          | 29.99   | 
| ...     | ...       | ...   | ...       | ...     | ...    | ...      | ...        | ...     | 

---

## 📊 Key Insights

### 📈 LTV vs. Churn Risk

- Premium users have **~15–18% higher projected LTV** than Standard users.
- Churn risk increases **moderately** in Premium, but not enough to offset the revenue benefit.

### 📈 Conversion Rate Impact

- Premium tier shows a **+19.97% increase** in conversion rate over Standard.
- Indicates stronger perceived value from pricing + feature combo.

### 📈 Upgrade & Downgrade Behavior

- Upgrade rate is nearly **2×** higher than downgrade rate across 6 months.
- Signifies strong acceptance of Premium pricing and product improvements.

---

## 📊 Dashboard Preview

![Dashboard Preview](./Netflix-Pricing-Tier-LTV-Experiment.png)

---

## 📊 Notes

This test assumes:
- Phase 1: Price sensitivity was validated between $25.99 and $29.99.
- Phase 2: Feature acceptance was validated at $25.99.
- Phase 3 (this case): Merged test for full rollout feasibility.

---

