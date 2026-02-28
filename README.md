# Insurance Claims Risk Analytics & Customer Segmentation (Allianz Case)

> Built a claims risk analytics framework to identify long-duration payout drivers, evaluate broker-level risk exposure, and design segmentation-based pricing strategies.

**Author:** Amisha Farhana Shaik  
**Project Type:** Insurance Risk Analytics | Data Mining | Strategic Modeling  

---

## Business Context

Long-duration disability claims significantly increase insurer liability and long-term payout exposure.  

This project analyzes ~4,900 insurance claims to uncover risk drivers, evaluate broker performance, segment customers by liability profile, and propose scalable machine learning solutions for risk forecasting and premium optimization.

---

## What I Did

### 1️⃣ Identified Drivers of Long-Duration Claims

Defined long-duration claims as:
> Duration > 10 years (75th percentile threshold)

Analyzed patterns across:

- **Age Groups** → Younger customers showed significantly higher claim durations  
- **Gender** → Males exhibited higher normalized long-duration rates  
- **Districts** → Certain regions showed 30–35% long-claim concentration  

**Impact:** Highlighted geographic and demographic risk concentrations that directly affect underwriting strategy.

---

### 2️⃣ Evaluated Broker-Level Risk Performance

Problem:
Small brokers inflated long-claim percentages due to low volume.

Solution:
- Filtered brokers with <10 claims  
- Ranked brokers by volume and long-duration percentage  
- Compared high-volume brokers on risk efficiency  

**Finding:**  
Some high-volume brokers maintain low long-duration ratios, indicating stronger client selection or underwriting discipline.

**Business Implication:**  
Replicating best-performing broker practices could reduce portfolio risk exposure.

---

### 3️⃣ Built Customer Risk Segmentation Model

Method:
- Hierarchical Clustering (7 clusters)
- Features:
  - Age at claim  
  - Claim duration  
  - Annuity  
  - Total amount owed  

Identified segments such as:
- High annuity + long duration → High liability tier  
- Low annuity + short duration → Low-risk tier  
- Older high annuity customers → Premium-sensitive segment  

**Impact:** Enables risk-tiered pricing, targeted underwriting, and liability forecasting.

---

### 4️⃣ Designed Predictive Risk Framework (Proposed)

Proposed a scalable ML pipeline:

- LSTM-based disability ratio forecasting for long-term liability estimation  
- Random Forest classification for high-risk client prediction  
- Salary & employment-based risk scoring for dynamic premium adjustments  

**Strategic Value:**  
Moves Allianz from reactive claims management to proactive risk forecasting and premium optimization.

---

## Key Takeaways

- Long-duration claims are strongly influenced by demographic and regional factors  
- Broker selection behavior materially impacts portfolio risk  
- Segmentation enables structured premium differentiation  
- Predictive modeling can significantly improve liability forecasting accuracy  

---

## Skills Demonstrated

- Insurance Risk Analytics  
- Customer Segmentation  
- Hierarchical Clustering  
- Risk Modeling Strategy  
- Business Interpretation of Data  
- Data-Driven Pricing Recommendations  

---

This project demonstrates the application of analytics in:
Insurance Strategy | Risk & Liability Management | Actuarial Support | Portfolio Optimization
