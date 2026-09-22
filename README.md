# ✈️ Worldwide Aviation Performance & Analytics Dashboard

An interactive Power BI dashboard analyzing global airline performance across financials, traffic, routes, fleet, and safety — built to turn raw aviation data into decision-ready insights.

---

## 📊 Overview

This dashboard consolidates worldwide airline data into a single Power BI report with six focused pages, covering revenue, operating margins, passenger traffic, route profitability, fleet orders, and flight safety. It's designed for stakeholders who need a quick executive pulse as well as analysts who need to drill into route-level and airline-level detail.

**Key metrics tracked:**
- Total Revenue, Operating Margin, Load Factor, Aircraft Orders, and Incident counts
- Revenue & passenger growth trends (2010–2026)
- Airline-level financial performance and profitability
- Regional traffic (RPK/ASK) and load factor trends
- Route-level revenue and fare-distance relationships
- OEM order backlogs and delivery share by aircraft category
- Fatal incident trends and aircraft safety records

---

## 🗂️ Report Pages

| # | Page | Description |
|---|------|-------------|
| 1 | **Executive Overview** | High-level KPIs — total revenue, aircraft orders, operating margin, incidents, and global load factor — plus top revenue routes and a 15-year revenue/passenger trend |
| 2 | **Financial Performance** | Operating margin trends by region, airline-level revenue/margin/YoY growth table, top 15 airlines by revenue, and load factor vs. operating margin |
| 3 | **Global Traffic** | Regional load factor trends over time and RPK vs. ASK (capacity vs. demand) by year |
| 4 | **Route Performance** | Revenue by route corridor (treemap), sortable route detail table, and a distance-vs-fare bubble chart sized by passenger volume |
| 5 | **Fleet & Manufacturers** | Aircraft orders by year split by manufacturer (Airbus, Boeing, COMAC, Embraer), delivery share by aircraft category, and order backlog trends |
| 6 | **Safety & Incidents** | Fatal incident log sorted by fatalities, incident severity breakdown, fatalities by aircraft type, and incident count by year |

---

## 🛠️ Tools & Techniques

- **Power BI** — report design, page navigation, bookmarks
- **DAX** — calculated KPIs (Book-to-Bill Ratio, Fatal Incident Rate %, YoY Growth, Operating Margin %)
- **Power Query** — data cleaning, shaping, and transformation
- **Data Modeling** — relationships across airline, route, fleet, and incident tables

---

## 📸 Preview


| Executive Overview | Financial Performance |
|---|---|
| ![Executive Overview](https://github.com/PUNIT227/Worldwide_Aviation_Performance_-_Analytics-Dashboard/blob/main/executive%20Overview.png) | ![Financial Performance]([screenshots/page2.png](https://github.com/PUNIT227/Worldwide_Aviation_Performance_-_Analytics-Dashboard/blob/main/financial%20Performance.png)) |

| Passanger Traffic | Route Performance |
|---|---|
| ![Passanger Traffic](https://github.com/PUNIT227/Worldwide_Aviation_Performance_-_Analytics-Dashboard/blob/main/Passanger%20Traffic.png) | ![Route Performance](https://github.com/PUNIT227/Worldwide_Aviation_Performance_-_Analytics-Dashboard/blob/main/WW%20Route.png) |

| Fleet & OEM | Safety & Incidents |
|---|---|
| ![Fleet & OEM](https://github.com/PUNIT227/Worldwide_Aviation_Performance_-_Analytics-Dashboard/blob/main/Fleet%20and%20oem.png) | ![Safety & Incidents](https://github.com/PUNIT227/Worldwide_Aviation_Performance_-_Analytics-Dashboard/blob/main/SAFETY%20%26%20INCIDENT.png) |

---


---

## 📁 Repository Structure

```
├── Aviation_Performance_Dashboard.pbix   # Main Power BI report file
├── data/                                 # Source data files (if included)
├── screenshots/                          # Dashboard preview images
└── README.md
```

---

## 📌 Notes

- Data covers 2010–2025/2026 across regions: Africa, Asia Pacific, Europe, Latin America, Middle East, and North America
- Dashboard is built for demonstration/portfolio purposes using aggregated industry-style aviation data

---

## 👤 Author

**Punit Kumar Singh**
[GitHub](https://github.com/PUNIT227) · [LinkedIn](https://linkedin.com/in/punit-kumar-singh-7a7065100)
