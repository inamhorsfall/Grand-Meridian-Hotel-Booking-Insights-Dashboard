# 🏨 Grand Meridian Hotel — Booking Insights Dashboard

> **Power BI** | Hospitality Analytics | Revenue Management | Demand Intelligence

Hospitality revenue dashboard analysing £11.90M in bookings across what-if pricing scenarios, seasonal trends, demand segmentation, and RevPAR performance.

---

## 📊 Dashboard Pages

| Page | Description |
|------|-------------|
| **What-If Scenario** | Interactive price change simulator showing impact on Room Revenue, ADR, RevPAR, and Revenue Difference across Suite, Deluxe, and Standard room segments |
| **Monitoring Page** | Live operational tracking of key revenue and occupancy metrics with alerting context |
| **Executive Overview** | High-level summary of total revenue, bookings, ADR, service revenue, occupancy rate, and RevPAR with monthly revenue trend and segment split |
| **Seasonal & Performance Analysis** | Revenue by session (Peak/Base/Moderate), RevPAR split by weekday/weekend, ADR comparison, and monthly RevPAR trend |
| **Demand Segmentation & Revenue Behaviour** | Monthly RevPAR by loyalty segment (Member vs Non-Member), revenue by segment, and full segmentation table with ADR, occupancy, RevPAR, and service revenue |

---

## 🔑 Key Metrics

| Metric | Value |
|--------|-------|
| Total Revenue | £11.90M |
| Total Bookings | 6,867 |
| ADR (Avg. Daily Rate) | £241.15 |
| Service Revenue | £952.2K |
| Occupancy Rate | 0.68 (68%) |
| RevPAR | £164.69 |
| Room Revenue | £10.94M (91.97%) |
| Revenue at Risk | — |

### What-If Scenario (at 0% price change baseline)
| Metric | Value |
|--------|-------|
| Scenario Room Revenue | £10.94M |
| Scenario ADR | £241.15 |
| Scenario RevPAR | £164.69 |
| Revenue Difference | £0.00 |

---

## 💡 Key Insights

- **Room revenue dominates** at 91.97% (£10.94M) of total revenue, with service revenue contributing just 8.03% (£0.96M) — indicating an opportunity to grow ancillary revenue streams.
- **Leisure segment** outperforms Corporate in revenue (£6.3M vs £5.6M), suggesting leisure travellers are the primary revenue driver and should be prioritised in marketing.
- **Peak season** generates £6.6M — more than double Moderate (£1.9M) and nearly double Base (£3.5M), confirming strong seasonal concentration that requires dynamic pricing strategies.
- **Weekday ADR (£241.36)** slightly exceeds Weekend ADR (£240.59), but weekday occupancy (50%) is significantly higher than weekend (18), pointing to an opportunity to drive weekend demand.
- **Members generate lower ADR** (£232.12 weekday) compared to Non-Members (£244.03), but contribute to higher occupancy and loyalty — a classic trade-off for revenue managers.
- **Non-Members account for £9.4M revenue** vs Members at £2.5M, suggesting the loyalty programme needs strengthening to convert more high-value guests.
- **Monthly revenue peaks in December (£1.89M)** and dips in May (£0.50M), providing a clear roadmap for seasonal promotional planning.
- The **What-If scenario tool** enables revenue managers to simulate the P&L impact of rate changes before implementing them — a practical decision-support feature.

---

## 🗂️ Dashboard Features

### What-If Scenario Page
- **Price Change % Slider** — dynamic parameter control to simulate rate adjustments
- **Revenue Comparison** — side-by-side Current vs Scenario bar chart
- **Impact by Segment** — Suite, Deluxe, Standard revenue under scenario
- **Actual vs Scenario RevPAR Trend** — monthly line chart comparison across all 12 months
- **Filters** — Weekday/Weekend toggle

### Executive Overview Page
- **KPI Banner** — Revenue, Bookings, ADR, Service Revenue, Occupancy, RevPAR
- **Revenue by Segment** — Leisure vs Corporate bar chart
- **Revenue Split** — donut (Room Revenue 91.97% / Service Revenue 8.03%)
- **Total Revenue by Month** — line chart Jan–Dec 2025
- **Filters** — Loyalty Status, Weekday/Weekend, Seasonal Adjustment, Room Type, Booking Channel, Ancillary Service

### Seasonal & Performance Page
- **Revenue by Sessions** — Peak (£6.6M), Base (£3.5M), Moderate (£1.9M)
- **Revenue Split** — ADR and Occupancy % by Weekday vs Weekend
- **Monthly RevPAR Trend** — 12-month line chart showing seasonality curve
- **Filters** — Guest Type (Corporate/Leisure), Seasonal Adjustment, Room Type, Booking Channel, Loyalty Status

### Demand Segmentation Page
- **Monthly RevPAR by Segment** — multi-line chart (Member vs Non-Member)
- **Revenue by Segment** — Non-Member (£9.4M) vs Member (£2.5M)
- **Segmentation Summary Table** — Weekday/Weekend breakdown of ADR, Occupancy Rate, RevPAR, and Service Revenue by loyalty status
- **Filters** — Guest Type, Weekday/Weekend, Room Type, Booking Channel, Loyalty Status

---

## 🛠️ Tools & Skills Used

- **Power BI Desktop** — multi-page report, DAX, What-If parameter, data modelling
- **DAX** — RevPAR, ADR, occupancy rate, revenue at risk, scenario delta calculations
- **What-If Parameters** — dynamic price simulation using Power BI parameter sliders
- **Power Query** — booking data transformation, date table creation, seasonal flag logic
- **Data Modelling** — star schema linking bookings, rooms, guests, and date dimensions
- **Visualisations** — KPI cards, line charts, bar charts, donut charts, data tables, slicers
- **Revenue Management Concepts** — ADR, RevPAR, occupancy rate, demand segmentation, seasonal adjustment

---

## 📁 Files in This Repository

```
📂 powerbi-hotel-booking-insights
 ┣ 📄 README.md                        ← You are here
 ┣ 📊 GMH_HotelBooking.pbix            ← Power BI report file
 ┗ 📸 screenshots/
    ┣ what_if_scenario.png
    ┣ executive_overview.png
    ┣ seasonal_performance.png
    ┗ demand_segmentation.png
```

---

## 🚀 How to View

**Power BI Desktop (recommended):**
1. Download the `.pbix` file
2. Open in [Power BI Desktop](https://powerbi.microsoft.com/desktop) (free)
3. Use the **Price Change % slider** on the What-If page to simulate pricing scenarios
4. Explore all pages and filters interactively


---

## 👤 About the Author

Data analyst specialising in Power BI dashboard development across HR, marketing, hospitality, and manufacturing sectors. I transform complex datasets into interactive, insight-driven reports that support strategic decision-making.

🔗 LinkedIn: www.linkedin.com/in/
horsfall-inam-data-analyst
 | 📧 Email: horsfallinam@gmail.com
