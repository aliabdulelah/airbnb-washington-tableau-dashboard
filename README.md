# Airbnb Washington — Tableau Investment Dashboard

Tableau dashboard analysing Airbnb listing data for Washington, USA (2016) to identify the most profitable investment locations based on revenue, average price, and bedroom competition.

**Business question:** Which zip codes and property sizes offer the best return for a short-term rental investment in Washington State?

---

## Dashboard preview

![Airbnb Dashboard Overview](<img width="1500" height="1000" alt="DSC8396-1500x1000" src="https://github.com/user-attachments/assets/cf301b9a-ec7c-4b73-ac7c-fcec8abbc334" />
)

---

## Key findings

| Insight | Detail |
|---|---|
| **Highest-revenue zip code** | 98146 — average $157.04/night |
| **Peak revenue week** | Week 26 — $46.4M total revenue |
| **Best bedroom count for ROI** | 1-bedroom (highest listing count, lower competition per unit) |
| **Most competitive market** | 3-bedroom properties — highest distinct listing count |

---

## Tools used

- **Tableau** — dashboard design, data visualisation, geographic mapping
- **Excel** — initial data cleaning and preparation
- **Data source** — [Kaggle: Airbnb Listings 2016 Dataset](https://www.kaggle.com/datasets/alexanderfreberg/airbnb-listings-2016-dataset/code)

---

## Dashboard components

1. **Average price by zip code** — bar chart + interactive map
2. **Revenue over time** — weekly revenue line chart (full year)
3. **Average price by bedroom count** — bar chart
4. **Distinct bedroom listing count** — competition analysis

---

## Process

**Data cleaning**
- Loaded and inspected raw listing, review, and calendar datasets
- Handled missing values and removed incomplete records
- Standardised formatting across date and price fields

**Analysis**
- Calculated average price per zip code and mapped geographically
- Aggregated weekly revenue across all listings for the full year
- Compared average price and listing count by bedroom number to identify supply-demand gaps

---

## Recommendations

1. **Target zip code 98146** for investment — highest average nightly price with strong demand signals
2. **Consider 1-bedroom properties** — lower acquisition cost, lower competition density, consistent occupancy
3. **Plan for seasonality** — revenue peaks in Week 26 (late June); pricing strategy should reflect demand curve
4. **Monitor Week 38 dip** — potential seasonal decline; reduce pricing during this window to maintain occupancy

---

## Files

| File | Description |
|---|---|
| `README.md` | This file |
| `screenshots/` | Dashboard and chart screenshots |

> The Tableau workbook (.twbx) is available on request or viewable via the [DataCamp Portfolio](https://www.datacamp.com/portfolio/aliabdulelah).
