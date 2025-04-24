# 🏢 Metrolinx Real Estate Asset Management – Portfolio Strategy Case Study

This case study analyzes Metrolinx’s real estate asset portfolio using Power BI and DAX logic to assess asset performance and inform data-driven investment strategies. The goal is to identify underperforming properties, uncover root causes, and recommend actions like acquisition, divestment, or renovation.

---
## 📑 Table of Contents

- [Objective](#objective)
- [Data Preparation & Cleaning](#data-preparation--cleaning)
- [Tools Used](#tools-used)
- [Key Methodology](#key-methodology)
  - [Performance Thresholds](#performance-thresholds)
  - [ROI Strategy Matrix (Logic-Based Recommendations)](#roi-strategy-matrix-logic-based-recommendations)
- [Key Visuals (Screenshots in folder)](#key-visuals-screenshots-in-folder)
- [Summary of Recommendations](#summary-of-recommendations)
- [Strategic Insights](#️-strategic-insights)
- [What’s Next (If More Data Was Available)](#whats-next-if-more-data-was-available)
- [Folder Contents](#folder-contents)

---
## 📌 Objective

Evaluate a portfolio of 26 real estate assets across four property types — Industrial, Office, Residential, and Retail — to:
- Identify underperforming properties
- Analyze factors behind low occupancy and ROI
- Assess alignment between operating costs and income
- Recommend tailored investment actions based on performance logic

---

## 🧹 Data Preparation & Cleaning

- Removed irrelevant columns and standardized headers
- Validated consistency of date formats and data types
- Created new calculated fields:
  - **Occupancy Rate** = Leased Area / Total Area
  - **ROI (%)** = (Rental Income – Operating Costs) / Capital Expenditures
  - **Years Since Last Renovation** = Current Year – Renovation Year
- Verified data integrity (no duplicates or missing values)

---

## 📊 Tools Used

- Power BI (visualization, dashboarding)
- Power Query (data transformation)
- DAX (custom measures, logic-based classification)
- Excel (initial audit)

---

## 🧠 Key Methodology

### Performance Thresholds
Benchmarks were defined using industry standards:
- **Occupancy**: 85%+ for Office, 90%+ for Residential, 95%+ for Industrial
- Properties below **70% of these benchmarks** were flagged as underperforming

### ROI Strategy Matrix (Logic-Based Recommendations)
Used SWITCH + TRUE() DAX structure to categorize each property type:
- **✅ Acquire More**: ROI > 1000%, Satisfaction > 80, CapEx < $300K
- **❌ Consider Selling**: ROI < 500%, Satisfaction < 70, CapEx > $400K
- **⚠️ Renovation Potential / Optimization Opportunity**: Selective conditions met
- **⚪ Hold / Monitor**: All others

---

## 📈 Key Visuals (Screenshots in folder)

- Clustered bar charts by ROI, CapEx, Satisfaction
- Bubble charts to assess Renovation Age vs Performance
- Matrix with dynamic conditional logic and strategy icons
- Benchmark overlay visual for Occupancy Rate vs Standards

---

## 💡 Summary of Recommendations

| Property Type | ROI | CapEx | Satisfaction | Recommendation |
|---------------|-----|-------|--------------|----------------|
| Industrial    | ✅ Very High | ✅ Low | ✅ High | ✅ Acquire More |
| Residential   | ❌ Low       | ❌ High | ❌ Low  | ❌ Consider Selling |
| Office        | ⚠️ Mid       | ❌ High | ⚠️ Borderline | ⚪ Hold / Monitor |
| Retail        | ⚠️ Mid       | ⚠️ Borderline | ❌ Low  | ⚪ Hold / Monitor |

---

## 🗺️ Strategic Insights

- **Industrial** assets are high performers with strong ROI and low CapEx → clear candidates for expansion.
- **Residential** assets suffer from weak ROI and tenant satisfaction → consider divestment or redevelopment.
- **Office/Retail** assets are mixed and may benefit from operational improvements or renovations based on market demand.

---

## 📌 What’s Next (If More Data Was Available)

With additional data such as lease turnover dates, tenant feedback logs, or market rent benchmarks, the analysis could expand into:
- Lease expiry risk mapping
- Rent gap detection
- Predictive churn modeling
- Continuous asset health dashboards

---

## 🧰 Folder Contents

- `.pbix` – Power BI file with full dashboard
- `.pdf` – Strategic summary presentation


---

> Built by Jake Ma | [LinkedIn](https://www.linkedin.com/in/jake-ma-0a4278282/)  
> Google Data Analytics Certified | Passionate about data-driven urban strategy
