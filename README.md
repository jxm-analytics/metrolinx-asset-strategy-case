# Metrolinx Asset Strategy: Power BI Investment Scoring Dashboard

This project simulates a strategic asset evaluation scenario for Metrolinx, the public transit authority in Ontario. The goal was to assess the performance of real estate assets across four property types and guide decisions to acquire, hold, or divest using a standardized, data-driven scoring model.

---

## Table of Contents

- [Project Objective](#project-objective)
- [Tools and Techniques Used](#tools-and-techniques-used)
- [Data Model and Metrics](#data-model-and-metrics)
- [Business Logic and Thresholds](#business-logic-and-thresholds)
- [Dashboard Overview](#dashboard-overview)
- [Key Takeaways](#key-takeaways)
- [Conclusion](#conclusion)
- [Contact](#contact)
- [License](#license)

---

## Project Objective

To support portfolio-level decision-making at Metrolinx by building a Power BI dashboard that scores properties based on:
- Return on Investment (ROI)
- Capital Expenditure (CapEx)
- Tenant Satisfaction

The objective was to classify each asset into one of three categories:
- Acquire More
- Hold / Monitor
- Consider Selling

---

## Tools and Techniques Used

- Power BI for data modeling, DAX logic, and visualization
- DAX measures for ROI thresholds, investment logic, and sentiment weighting
- Excel for initial data preparation and layout mapping
- Custom logic thresholds for investment scoring based on internal performance and market-aligned benchmarks

---

## Data Model and Metrics

The project used simulated portfolio data for 26 real estate assets across four property types: Industrial, Residential, Office, and Retail.

Each asset included:
- ROI (Return on Investment in $)
- CapEx (Total capital invested)
- Tenant Satisfaction (scaled score from 0 to 100)

All metrics were standardized for cross-comparison and filtered by property type and classification.

---

## Business Logic and Thresholds

To simulate real-world investment review, the following classification logic was applied:

**Acquire More:**
- ROI > 1000
- CapEx < 300K
- Tenant Satisfaction > 80

**Consider Selling:**
- ROI < 500
- CapEx > 400K
- Tenant Satisfaction < 70

**Hold / Monitor:**
- Assets that did not meet acquire or divest thresholds but showed moderate potential or efficiency

This logic was implemented using nested DAX conditions and visually displayed in the dashboard for executive clarity.

---

## Dashboard Overview

The Power BI dashboard includes:

- A summary table with dynamic filters by asset type, ROI tier, and investment classification
- Cards showing total ROI, average CapEx, and overall satisfaction
- Bar charts comparing property performance within and across types
- A matrix summarizing property status with drill-down capability


---

## Key Takeaways

- A scoring system using real estate KPIs can quickly surface underperforming assets
- Adding tenant sentiment balances short-term ROI with long-term livability and service goals
- Benchmarking alone isn’t enough — internal comparisons drive sharper strategy
- Decision-makers benefit from visuals that connect financial, operational, and satisfaction metrics

---

## Conclusion

This project reflects real-world asset management decision-making by combining financial, operational, and user experience data in a unified dashboard. It demonstrates intermediate-level Power BI and DAX skills, business-first thinking, and a clear path from raw data to stakeholder-ready recommendations.

---

## Contact

Created by [Jake Ma](https://www.linkedin.com/in/jake-ma-0a4278282/)  
Let’s connect if you’re hiring or want to discuss asset intelligence in public infrastructure.

---

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.
