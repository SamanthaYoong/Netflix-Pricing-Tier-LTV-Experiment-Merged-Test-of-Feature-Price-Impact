# 📊 Netflix Pricing Tier LTV Experiment: Merged Test of Feature & Price Impact

> **Simulated case study to demonstrate data analysis logic and product thinking.**  
> Tools: SQL, Excel, Tableau, GitHub  
> 🔗 [View the Interactive Tableau Dashboard](https://public.tableau.com/views/NetflixPricingTierLTVExperimentMergedTestofFeaturePriceImpact/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## 🖼️ Dashboard Preview

![Dashboard Preview](./Executive-Overview(3).png)

---

## 📊 Problem Statement

User participation during e-commerce livestreams was underperforming, as indicated by low Clickthrough Rate (CTR) and Livestream Conversion Rate.  
To remain competitive, increasing engagement and loyalty was critical.

---

## 📊 Objective

- Increase Clickthrough Rate by **20%**
- Reduce Bounce Rate by **15%**
- Improve Livestream Conversion Rate by **10%**

---

## 📊 Hypothesis

If we introduce **exclusive livestream-only prices** and add a **live chat overlay** directly on the display, user participation will increase — because customers are incentivized and influenced by real-time chat before purchasing.

---

## 📊 Test Setup

| Element        | Description                                                       |
|----------------|-------------------------------------------------------------------|
| **Duration**   | Simulated 7-day experiment                                        |
| **Sample Size**| 10,000 simulated user records                                     |
| **Audience**   | Frequent platform visitors                                        |
| **Split**      | 50% Control (A) / 50% Variant (B)                                 |
| **Tools**      | SQL, Excel, Tableau, GitHub                                       |

**Test Groups:**

| Group           | Description                                                                 |
|------------------|------------------------------------------------------------------------------|
| **Control (A)**  | Original product prices + separate live chat window                         |
| **Variant (B)**  | Exclusive livestream prices + live chat overlay on display screen           |

---

## 📊 Results (Simulated)

| Metric                     | Control (A) | Variant (B) | Uplift         |
|----------------------------|-------------|-------------|----------------|
| Clickthrough Rate (CTR)    | 5.10%       | 5.26%       | **+0.16 pp**   |
| Livestream Conversion Rate | 3.28%       | 2.86%       | **-0.42 pp**   |
| Livestream Bounce Rate     | 21.10%      | 19.90%      | **-1.20 pp**   |

---

## 📊 Insights & Interpretation

- Variant B showed a **small CTR improvement** but a **decline in conversion rate**.
- Customers may still **perceive prices as too high** or lack urgency to purchase.
- Slight reduction in bounce rate may reflect better session engagement.

---

## 📊 Recommendations

- Benchmark competitor pricing and **adjust perceived value**
- Introduce **urgency triggers** (e.g. countdowns, limited offers)
- Segment audiences by behavior (e.g. cart size, new vs returning)
- Explore additional layout and chat format tests

---

## 📊 Tools Used

- **SQL** – Data shaping and filtering logic  
- **Excel** – Mock dataset generation (10,000 rows)  
- **Tableau Public** – Interactive dashboard for A/B comparison  
- **GitHub** – Case study documentation

---

## 📊 Reflection

This self-designed experiment helped me practice product analytics, hypothesis framing, test simulation, and dashboard communication.  
Next, I plan to build a **Lifetime Value (LTV)** experiment to evaluate how pricing tiers influence retention and revenue.

---

## 📊 Related Files

- 📄 `ab_test_dataset.csv` – Mock user-level data
- 📊 `dashboard_link.twbx` – Tableau Public Dashboard *(link or file)*
- 📝 `README.md` – Case study documentation

---
