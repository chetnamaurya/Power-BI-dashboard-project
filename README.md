# 🏠 Airbnb Market Comparison Dashboard: Chicago vs New Orleans

**Transforming an EDA project into interactive Power BI dashboards**

A five-page Power BI report that turns an exploratory data analysis (EDA) of Airbnb listings into an executive-ready dashboard. It compares the **Chicago** and **New Orleans** short-term rental markets across market size, property mix, pricing and host performance, and ends with concrete business recommendations.

### 🎥 Video Explanation

A walkthrough of the dashboard, page by page:

[![Watch the video explanation](https://img.shields.io/badge/%E2%96%B6_Watch-Video_Explanation-FF0000?style=for-the-badge&logo=googledrive&logoColor=white)](https://drive.google.com/file/d/1jrjj9GJBJFOejmiCDmV1v9ZHr-eAw9_q/view?usp=sharing)

---

## 📌 Project Overview

The original EDA answered questions about the Airbnb market in notebooks and static charts. This capstone project moves those findings into **interactive dashboards**, so that a business user can explore the data with slicers, maps and drill-downs instead of reading code.

**Business questions answered:**

1. How big is each market, and how do prices compare?
2. What kinds of properties dominate the supply?
3. How does pricing vary by neighbourhood, property type and room type?
4. Do Superhosts perform better than regular hosts?
5. What should hosts and investors do based on these findings?

---

## 🛠️ Tools & Skills

| Area | Details |
|---|---|
| Tool | Microsoft Power BI |
| Modelling | Single fact table (`Airbnb_Listings`) |
| Calculations | DAX measures (KPIs, averages, revenue, percentages) |
| Visuals | KPI cards, map, column/bar/clustered charts, pie, donut, funnel, scatter, slicers |
| Storytelling | An *Executive Insight* panel on every page, plus a summary and recommendations page |

---

## 📂 Dataset

Airbnb listing-level data for **Chicago** and **New Orleans** (~8,000 listings in total), loaded into Power BI as one table, `Airbnb_Listings`.

**Key fields used:**

| Category | Fields |
|---|---|
| Location | `city`, `neighbourhood_cleansed`, `latitude`, `longitude` |
| Property | `property_type`, `room_type`, `bedrooms`, `bathrooms`, `accommodates` |
| Pricing | `price`, `Price Range` (price-band column) |
| Reviews | `reviews_per_month`, review scores |
| Hosts | `host_name`, `host_is_superhost`, `hosts_time_as_host_years` |

---

## 📐 DAX Measures

| Measure | Purpose |
|---|---|
| Total Listings | Number of listings |
| Average Price | Average nightly price |
| Average Rating | Average guest rating |
| Average Reviews | Average number of reviews per listing |
| Average Bedrooms | Average bedrooms per listing |
| Average Accommodates | Average guest capacity |
| Revenue | Estimated revenue (used to compare Superhosts and non-Superhosts) |
| Listing % | Share of total listings |
| Price per Bedroom | Average price divided by bedrooms |

---

## 📊 Dashboard Pages

### 1. Executive Overview
KPI cards (Total Listings, Average Price, Average Rating, Average Reviews, Average Bedrooms, Average Accommodates), a **city slicer**, listings by neighbourhood, and an **interactive map** of listings with rating, review and bedroom tooltips.

<img width="100%" alt="Executive Overview" src="https://github.com/user-attachments/assets/61076153-87f3-45dd-804e-868a90bd7342" />

### 2. Property Analysis
Listings by property type (pie), room type (donut), bedrooms, bathrooms and guest capacity.

<img width="100%" alt="Property Analysis" src="https://github.com/user-attachments/assets/3b12fab2-ca3e-45ad-abd4-3b73130c89c9" />

### 3. Pricing Analysis
Average price by neighbourhood, property type and room type (funnel), price vs. reviews per month by room type (scatter), listings per price band by city, a **price-range slicer**, and a Price per Bedroom KPI.

<img width="100%" alt="Pricing Analysis" src="https://github.com/user-attachments/assets/63008160-c8de-4460-b764-87f8793c2213" />

### 4. Host Analysis
Superhosts vs. non-Superhosts compared on listings, revenue, average reviews and average price. Also includes the top hosts by number of listings, and hosting experience vs. rating (scatter).

<img width="100%" alt="Host Analysis" src="https://github.com/user-attachments/assets/ff03ce6d-010f-45eb-8e03-b97dffe7e5eb" />

### 5. Executive Summary & Business Recommendations
Key findings, five recommendations and a final conclusion on one page.

---

## 🔍 Key Insights

- **Market size:** Chicago has about **5,000 listings**, roughly **67% more** than New Orleans (about 3,000).
- **Pricing:** Chicago's average nightly price is higher (**$301 vs. $261**).
- **Guest engagement:** New Orleans earns more reviews per listing (**104.48 vs. 87.15**) and a slightly higher rating (**4.83 vs. 4.81**).
- **Property mix:** **Entire homes/apartments make up 82.94%** of listings. Rental units (43.97%) and entire homes (24.97%) are the most common property types. Most listings have 2–4 bedrooms and 1–2 bathrooms.
- **Price bands:** Most listings fall in the **$101–$300** range. Entire homes/apartments have the highest average price (**$311**) and shared rooms the lowest (**$68**).
- **Superhosts:** Superhosts manage more listings (**~4.7K vs. ~3.2K**), generate **over 3× the revenue**, and receive far more reviews (**~115 vs. ~65**). Both groups keep ratings above 4.7.

---

## 💡 Business Recommendations

1. 🏠 **Grow supply in New Orleans' high-demand areas** to take advantage of its strong guest engagement.
2. 💰 **Keep premium pricing in Chicago** while monitoring neighbourhood-level competition.
3. ⭐ **Help more hosts reach Superhost status** through better guest service, since Superhosts earn much more revenue and more reviews.
4. 🛏️ **Focus on entire homes/apartments for small groups**, where demand is strongest.
5. 📈 **Price by neighbourhood**, not uniformly, because average prices vary a lot between areas.

**Conclusion:** Chicago leads in market size and pricing, while New Orleans leads in guest engagement. Property type, pricing strategy and host quality are the main drivers of Airbnb performance in both cities.

---

## ▶️ How to Use

1. Install **[Power BI Desktop](https://powerbi.microsoft.com/desktop/)** (free, Windows).
2. Download `Transforming_EDA_Project_to_Dashboards_using_power_BI.pbix` from this repository.
3. Open it in Power BI Desktop. The data is already embedded, so no extra setup is needed.
4. Use the **City** slicer (page 1) and the **Price Range** slicer (page 3), and click on any chart to cross-filter the others.

---

## 📁 Repository Structure

```text
├── Transforming_EDA_Project_to_Dashboards_using_power_BI.pbix   # Power BI report
└── README.md
```

---

## 👤 Author

**Chetna Maurya**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Chetna%20Maurya-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chetna-maurya-56a542431/)
