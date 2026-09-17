# Patiala Quick-Commerce ETA Volatility & Serviceability Audit

An end-to-end operational investigation and customer-end observation based case study analyzing quick-commerce delivery dynamics, surge behavior, and serviceability collapse for Blinkit across Patiala, Punjab.

---

## 📊 Project Overview
*  Author:  Paras Badhran (Target Role: Associate Program Manager / APM).
*  Primary Dataset:  78 live operational checkpoints across 3 micro-markets (September 17, 2026).
*  Methodology:  Customer-side primary telemetry tracking a standardized 11-item grocery basket (₹533) every 30 minutes across a full operating cycle (10:00 AM – 10:30 PM).
---

## 🔍 Key Findings & Localities Performance

| Locality Name | Total Logs | Active ETA Range | Average ETA | Surge Events | Serviceability % |
| :------------ | :---------:| :--------------: | :---------: | :----------: | :--------------: |
| New Bus Stand | 26 Slots.  | 8–13 mins.       | 10.23 mins. | 0 Events.    | 100.0% Uptime.   |
|   Model Town  | 26 Slots.  | 11–23 mins.      | 15.90 mins. | 3 Events.    | 80.8% (5 Outages)|
|Thapar University| 26 Slots.| 11–30 mins       | 18.87 mins  | 4 Events.    | 88.5% (3 Outages)|

*  Catchment Uptime Divergence:  New Bus Stand maintained 100% serviceability with zero stockouts and tight delivery windows all day..
*  Evening Service Collapse:  Thapar University and Model Town experienced severe ETA spikes up to 30 minutes during the dinner rush, followed by a total serviceability collapse (0% item availability) from 8:30 PM to 10:30 PM..
*  Temporal Surge Windows:  Surge pricing and spikes occurred strictly during two high-demand slots: 
  1. *Evening Tea/Snack Rush (5:03 PM – 5:40 PM)*.
  2. *Dinner Prep Peak (8:01 PM – 8:34 PM)*.

---

## 🛠️ Tech Stack & Artifacts
*  Data Visualization:  Google Looker Studio (Interactive Dashboard)
*  Data Engineering:  Google Sheets (`Blinkit Case Study - Patiala.xlsx`).
*  Core Metrics Tracked:  Average ETA, Serviceability Rate, Surge Incidents, Outage Incidents, and Time-Window SLA Breaches (>20 mins)..

---
