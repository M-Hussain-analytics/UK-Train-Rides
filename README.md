# UK-Train-Rides
Comprehensive analysis of UK National Rail data using Power BI. Focuses on operational performance, punctuality vs. PPM, delay root causes, and revenue analysis. Developed as part of the team training under the Digital Egypt Builders Initiative (DEPI) in Data Analysis.
# UK National Rail Performance & Revenue Analysis

This project is a detailed data analysis initiative developed by the team as part of the **Digital Egypt Builders Initiative (DEPI)** Data Analysis track training. The objective is to utilize Power BI to transform raw transaction data into actionable business intelligence.

---

## 1. Project Overview

This analysis focuses on a dataset of UK National Rail journeys to uncover patterns in passenger behavior, ticket purchasing, travel performance, and operational efficiency. We aim to identify key trends in ticket types, pricing, delays, and the financial impact of refund activity, providing a robust foundation for strategic decision-making in the transport sector.

## 2. Key Objectives

The analysis was guided by diagnostic questions designed to measure performance against industry standards and quantify the cost of disruption:

* **Punctuality Assessment:** Measure "On Time" performance (86.82%) against the national Public Performance Measure (PPM) benchmarks.
* **Root Cause Analysis:** Identify and quantify the primary contributors to service delays.
* **Financial Leakage:** Quantify the total financial cost of refunds (£39K) and the Incident Refund Rate (26.80%) to assess the true cost of operational failure.
* **Growth Sustainability:** Evaluate the impact of service performance on the measured Month-over-Month growth (33.89%).

## 3. Exploratory Data Analysis (EDA)

The dataset encompasses **31,653** train ride transactions, providing the following base figures:

| Metric | Value | Breakdown |
| :--- | :--- | :--- |
| **Total Rides** | 31,653 | |
| **Total Revenue** | £742K | All revenue generated from ticket sales. |
| **On-Time Performance** | **86.82%** | 27,575 rides were on time. |
| **Service Failure Rate**| **13.18%** | Total Delayed (7.24%) and Cancelled (5.94%) rides. |
| **Total Refunds Issued** | £39K | Financial cost due to service disruptions. |
| **MoM Growth** | **33.89%** | Overall monthly growth rate. |

## 4. Analysis & Insights

The findings reveal that while overall performance meets the general PPM target, severe reliability issues must be addressed:

* **High Volatility (Cancellations):** The cancellation rate of **5.94%** exceeds the industry threshold for **severe disruption** (typically >5.0%), indicating systemic service instability despite a solid on-time rate.
* **Infrastructure Priority:** The root cause analysis identifies **Signal Failure** as the single largest contributor to delays, mandating critical investment in infrastructure maintenance and reliability.
* **Cost of Failure:** The **£39K** in refunds and the high **26.80%** Incident Refund Rate quantify the substantial financial penalty incurred from failing to deliver scheduled services, linking operational performance directly to financial leakage.
* **Growth at Risk:** The strong **33.89% MoM Growth** is jeopardized by the underlying service failures, requiring immediate mitigation strategies to sustain customer satisfaction.

## 5. Limitations

The following limitations should be considered when interpreting the results:

* **Time Frame:** The analysis is based on a specific, bounded dataset and may not reflect long-term or seasonal performance trends outside the captured period.
* **Causality Depth:** While the report identifies *Reason for Delay*, it does not delve into secondary causes (e.g., the specific type of signal failure or the severity of operational issues).
* **External Factors:** The dataset’s scope limits the ability to correlate performance with broader external variables (e.g., macroeconomic conditions, competitor performance).

## 6. Dashboard Sample

## 7. Conclusion

The analysis concludes that the rail network exhibits average punctuality but suffers from critical reliability and stability issues, primarily due to infrastructure failures. Future strategy should focus on two main recommendations: **Infrastructure Investment** to mitigate signal failures, and **Process Optimization** to reduce the high cancellation rate, ensuring that the current positive revenue and ridership growth is sustainable.
