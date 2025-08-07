# Public Asset Strategy – Investment Scoring Model

This project demonstrates a simulated strategic portfolio evaluation framework designed for public infrastructure agencies. Using Power BI and DAX, it evaluates asset performance based on ROI, CapEx, and user sentiment, providing actionable recommendations: Acquire, Hold, or Consider Selling.

---

## Table of Contents

- [Project Objective](#project-objective)
- [Tools and Techniques Used](#tools-and-techniques-used)
- [Data Model and Metrics](#data-model-and-metrics)
- [Business Logic and Thresholds](#business-logic-and-thresholds)
- [Dashboard Overview](#dashboard-overview)
- [Real-World Application](#real-world-application)
- [Key Takeaways](#key-takeaways)
- [Conclusion](#conclusion)
- [Contact](#contact)
- [License](#license)

---

## Project Objective
To replicate how governments or agencies assess real estate assets in a capital planning context — optimizing investment based on financial return and stakeholder value:

- Return on Investment (ROI)  
- Capital Expenditure (CapEx)  
- Tenant Satisfaction

The dashboard is designed to simulate a real estate portfolio review tool that flags properties as:
- Acquire More  
- Hold / Monitor  
- Consider Selling

---

## Tools and Techniques Used

- **Power BI**: Data modeling, dashboard design, and interactive visuals  
- **DAX**: Custom logic for ROI classification, thresholds, and risk segmentation  
- **Excel**: Preprocessing of raw metrics and structuring of base tables  

---

## Data Model and Metrics

Each asset record includes:

- **ROI**: Net return in dollars  
- **CapEx**: Capital investment to date  
- **Tenant Satisfaction**: Proxy for livability, experience, or stakeholder support  

Data is categorized by asset type, with filters for drilling into performance by group.

---

## Business Logic and Thresholds

This project applies internal benchmarking logic (rather than external market comparisons) to identify outliers and strategic actions.

**Acquire More**
- ROI > 1000  
- CapEx < 300K  
- Satisfaction > 80  

**Consider Selling**
- ROI < 500  
- CapEx > 400K  
- Satisfaction < 70  

**Hold / Monitor**
- All other cases, including assets with mixed or borderline performance  

This logic enables the Metrolinx asset management team to segment assets into action buckets — helping prioritize which properties need closer monitoring, reinvestment, or replacement.

---

## Dashboard Overview

The Power BI dashboard includes:

- KPI cards summarizing total ROI, average CapEx, and overall tenant sentiment  
- Filterable asset table by type, score tier, and recommendation  
- ROI and CapEx distribution visuals with benchmark overlays  
- Segmented matrix that cross-references satisfaction, CapEx, and ROI  

The visual layout supports both high-level summaries and detailed property-level views.

---

## Real-World Application

This dashboard simulates a decision-support tool for capital planning teams. It helps answer questions such as:

- Are we over-investing in low-return assets?  
- Which properties are most strategically scalable?  
- Where should we consider selling or reinvesting?  

The team can use the model in quarterly review meetings to:

- Align capital deployment with ROI and service experience  
- Flag assets for deeper audits based on cost/return misalignment  
- Justify reinvestment into well-performing segments like Industrial  

The scoring framework can be adapted to any organization managing mixed-use portfolios, combining financial, operational, and user-experience metrics in one view.

---

## Key Takeaways

- A scoring system using ROI, CapEx, and tenant sentiment allows faster identification of priority assets  
- Business logic is embedded directly in the DAX model for consistent evaluation  
- Power BI interactivity makes it easy to filter, drill, and explain decisions to stakeholders  
- The methodology balances financial return with service quality — aligning public and operational goals  

---

## Conclusion

This case study demonstrates how analysts can support real-world infrastructure decisions using interactive BI tools. The project combines custom logic, stakeholder-facing visuals, and domain-specific thresholds to mirror how large agencies like Public assess multi-million dollar asset portfolios. It reflects intermediate-level proficiency in Power BI, business logic modeling, and capital strategy alignment.

---

## Contact

Created by [Jake Ma](https://www.linkedin.com/in/jakexm-analytics/)  
Let’s connect if you’re hiring or want to discuss data analytics for real estate and infrastructure planning.

---
