# IVT Traffic Analysis Dashboard

## Overview
This repository contains the analysis of Invalid Traffic (IVT) patterns for multiple apps using aggregated ad request data. The analysis focuses on identifying suspicious or bot-driven traffic, understanding trends, and providing actionable insights.

## Data Description
The dataset includes the following columns:

- **Date/Hour**: Timestamp representing when the aggregated data was recorded.
- **unique_idfas**: Count of unique device identifiers (IDFAs) generating ad requests.
- **unique_ips**: Count of unique IP addresses originating the requests.
- **unique_uas**: Count of unique User-Agent strings detected.
- **total_requests**: Total ad requests received.
- **requests_per_idfa**: Average requests per device (total_requests ÷ unique_idfas).
- **impressions**: Total ads successfully rendered.
- **impressions_per_idfa**: Average impressions per device.
- **idfa_ip_ratio**: Ratio of devices per IP.
- **idfa_ua_ratio**: Ratio of devices per User-Agent.
- **IVT**: Flag indicating invalid traffic (estimated bot or non-human activity).

The dataset includes 3 apps marked as IVT and 3 apps not marked, recorded across hourly, daily, and total data sheets.

## Analysis
The analysis is performed using **Power BI** and includes:

1. **Traffic Overview** – Total requests, impressions, IVT %, and hourly/daily trends.  
2. **Device & Request Metrics** – Requests per IDFA, impressions per IDFA, idfa_ip_ratio, idfa_ua_ratio.  
3. **IVT Detection Patterns** – Comparison between flagged vs non-flagged traffic.  
4. **Temporal & Anomaly Analysis** – Highlighting spikes and unusual traffic patterns.  
5. **Correlation Analysis** – Relationships between metrics and IVT.  
6. **Comparative Insights** – Observations on apps flagged at different times.  
7. **Recommendations & Actionable Insights** – Suggestions for improving traffic quality and IVT detection.

## Dashboard
A **Power BI dashboard** was created to visualize these metrics. The dashboard includes:

- KPI cards for total requests, impressions, and IVT %  
- Bar/column charts comparing flagged vs non-flagged traffic  
- Line/area charts for temporal trends  
- Optional scatter plots and heatmaps for anomaly detection


## Files
- `IVT_Traffic_Analysis_PPT.pdf` – PowerPoint report summarizing the analysis and findings.  
- `Dashboard.png` – Folder containing screenshots of the Power BI dashboard.  
- `Data` – Optional folder for dataset (if allowed to share).

## Conclusion
This analysis provides a clear view of traffic quality, highlights potential bot activity, and offers actionable recommendations to improve IVT detection and campaign effectiveness.

---

*Prepared by [Rimsha Iram]*
