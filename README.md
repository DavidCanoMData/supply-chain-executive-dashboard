# Delivery Performance Intelligence

## Executive Summary

Operational analytics solution designed to monitor delivery effectiveness, SLA compliance and regional logistics performance.

Built using Python, Power BI and a dataset of 41,967 shipments, the project identifies operational bottlenecks affecting service levels, customer experience and transportation efficiency.

---

## Business Problem

The operation was experiencing:

* Low delivery effectiveness
* SLA breaches
* Delayed national arrivals
* Delivery returns
* Increased operational costs

Decision makers lacked a centralized view to understand where performance was deteriorating and what actions would generate the highest operational impact.

---

## Dataset

| Metric             | Value                  |
| ------------------ | ---------------------- |
| Shipments Analyzed | 41,967                 |
| Variables          | 30                     |
| Period             | Q1 2026                |
| Regions            | 6                      |
| Main KPI           | Delivery Effectiveness |

---

## Tech Stack

* Python
* Pandas
* NumPy
* Power BI
* Excel

---

## Data Engineering

Data preparation included:

* Date standardization
* Data type correction
* Category normalization
* Field renaming
* Business rule validation

---

## KPIs

* Total Shipments
* Successful Deliveries
* Delivery Effectiveness
* Total Weight Moved (KG)
* Delivery Status Distribution
* Regional Performance

---

## Key Findings

### Critical Operational Risk

53% of national vehicles arrive late at destination.

This delay directly impacts:

* SLA compliance
* Delivery effectiveness
* Customer satisfaction
* Operational costs

### Regional Performance Gap

Significant effectiveness differences exist between operational regions, creating opportunities for targeted improvement plans.

### Reactive vs Predictive Operations

The analysis revealed that delayed vehicle arrivals are often addressed after operational impact occurs, reducing the ability to recover service levels.

---

## Business Impact

This solution enables leaders to:

* Monitor SLA compliance
* Detect operational bottlenecks
* Prioritize improvement initiatives
* Optimize transportation performance
* Increase delivery effectiveness
* Support data-driven decision making

---

## Supply Chain Competencies Demonstrated

* Logistics Analytics
* Last Mile Performance
* SLA Monitoring
* KPI Design
* Business Intelligence
* Data Cleaning
* Data Visualization
* Operational Performance Management
* Root Cause Analysis
* Decision Support Systems

---

## Author

David Cano M

Supply Chain Data Analyst

Power BI • Python • SQL • Logistics Operations • Business Intelligence

Transforming operational data into strategic decisions.



## Recommendations




1. Establish an early-arrival monitoring process for national vehicles.

2. Create proactive alerts for SLA risk shipments.

3. Prioritize corrective actions in low-performance regions.

4. Implement operational escalation protocols for late arrivals.

5. Track effectiveness weekly at route and driver level.



---

## 🔄 Data Pipeline

The analytical workflow follows a structured process designed to transform operational records into decision-ready intelligence.

```text
Raw Data
    ↓
Data Quality Assessment
    ↓
Data Cleaning & Standardization (Python)
    ↓
Feature Engineering
    ↓
Business Rules Validation
    ↓
Analytical Dataset
    ↓
Power BI Data Model
    ↓
Operational Decision Support Dashboard
```

This pipeline ensures data consistency, KPI reliability and traceability across the entire analytical process.

---

## 🧹 Data Preparation & Quality Assurance

The original dataset required multiple validation and transformation stages before becoming suitable for operational analysis.

### Data Quality Challenges

* Missing values in operational and delivery-related fields
* Inconsistent date and timestamp formats
* Incomplete shipment records
* Incorrect data types affecting KPI calculations
* Non-standardized categorical variables

### Data Engineering Actions

* Null value treatment based on business relevance
* Date-time standardization using Pandas
* Data type correction and validation
* Category normalization
* Column renaming and semantic standardization
* Creation of analytical fields for logistics performance measurement
* Dataset optimization for Power BI consumption

### Output

A clean and validated analytical dataset containing 41,967 shipments and 30 operational variables ready for business intelligence reporting.

📓 Notebook:
`notebooks/RegBucaramanga.ipynb`

---

## 📊 Analytics Dashboard

The dashboard was designed as an operational control tower for monitoring delivery performance, SLA compliance and regional effectiveness.

### Executive KPIs

* Total Shipments
* Successful Deliveries
* Delivery Effectiveness Rate
* Total Weight Processed (KG)
* Delivery Status Distribution
* Regional Performance Ranking

### Analytical Dimensions

* Regional Performance
* Driver Performance
* SLA Compliance
* Shipment Evolution
* Delivery Status
* Operational Effectiveness

### Decision Support Capabilities

The dashboard enables managers to:

* Detect operational bottlenecks
* Monitor SLA compliance
* Identify underperforming regions
* Compare driver effectiveness
* Track shipment trends
* Prioritize improvement initiatives

---

## 💡 Strategic Findings

### Critical Risk to Service Levels

53% of national vehicles arrive late at destination.

This represents the most significant operational constraint affecting delivery effectiveness and SLA compliance.

### Impact Chain Identified

Late Vehicle Arrival
→ Reduced Processing Time
→ Delivery Delays
→ SLA Breaches
→ Customer Dissatisfaction
→ Increased Operational Costs

### Regional Performance Opportunities

Performance variability between operational regions indicates opportunities for targeted improvement programs and best-practice replication.

### Operational Maturity Opportunity

The analysis revealed a predominantly reactive operational model.

Implementing early warning indicators for late arrivals would significantly improve service recovery capabilities and delivery effectiveness.

---

## 🚀 Recommendations

### Immediate Actions

1. Establish arrival-time monitoring for national vehicles.
2. Implement SLA risk alerts before operational impact occurs.
3. Create escalation protocols for delayed arrivals.
4. Review processing capacity during peak arrival windows.
5. Monitor effectiveness weekly at regional and driver levels.

### Strategic Actions

1. Transition from reactive to predictive operational management.
2. Develop a logistics control tower model.
3. Introduce leading indicators for service performance.
4. Strengthen root-cause analysis for SLA breaches.
5. Standardize best operational practices across regions.

---

## ▶️ Reproducibility

### Python Environment

```bash
git clone https://github.com/your-user/delivery-performance-intelligence.git

pip install -r requirements.txt

jupyter notebook notebooks/RegBucaramanga.ipynb
```

### Power BI

1. Open the `.pbix` file located in `/reports`.
2. Refresh the data model.
3. Explore KPIs and operational insights through interactive filters.

---

## 👤 Author

David Cano M

Supply Chain Data Analyst

Power BI • Python • SQL • Logistics Analytics • Business Intelligence

Transforming operational complexity into measurable business performance.

---

## 📄 License

MIT License

Feel free to use, adapt and expand this project with proper attribution.

