# BMW Global Sales Intelligence (2019–2023)

End-to-end sales analytics case study for BMW, transforming raw transactional data into an interactive Power BI dashboard and executive-ready report. The project focuses on global revenue performance, time & seasonality, model portfolio strength, regional markets, and pricing dynamics.

---

## 1. Project Overview

This project analyzes **BMW sales across 5 years (2019–2023)**, covering:

- **15K+ vehicles sold**
- **26 BMW models**
- **5 regions** (Africa, Asia, Europe, North America, South America)
- **3 sales channels** (Wholesale, Dealership, Online)

The goal is to demonstrate how a Data Analyst can structure and deliver a complete analytics solution:
from dataset → insights → interactive dashboard → stakeholder-facing documentation.

---

## 2. Business Objectives

The analysis is designed to answer key business questions, such as:

- How have **revenue, units, and ASP** evolved over time?
- Which **models, regions, and channels** drive the majority of sales?
- How **balanced/diversified** is BMW’s portfolio across countries and models?
- Where do we see **strong vs. fragile** performance in terms of mix and pricing?
- How can these patterns inform **future market, channel, and model strategy**?

---

## 3. Data Overview

**File:** `Dataset/BMW_Sales_Data.csv`  

Each row represents a vehicle sale, including:

- Date of sale (2019–2023)
- Region & Country
- Sales Channel (Wholesale, Dealership, Online)
- BMW Model
- Units Sold
- Revenue / Selling Price

The dataset is synthetic but structured to resemble realistic multi-market automotive sales data.

---

## 4. Dashboard Overview

**Interactive Power BI Dashboard:**  
👉 https://tinyurl.com/BMW-Dashboard  

The dashboard is organized into multiple pages:

- **Page 1 — Topline Performance**  
  Executive snapshot of total revenue, units, ASP and YoY growth. Highlights top models and countries, and compares volume vs. price contribution across the portfolio.

- **Page 2 — Time & Seasonality**  
  Quarterly and monthly trends for revenue and units. Shows softer vs. stronger periods and how performance has evolved over the 2019–2023 timeline.

- **Page 3 — Model Portfolio**  
  Deep-dive into 26 BMW models. Ranks models by revenue and units, and compares model mix across regions and channels (core volume vs. premium halo vs. niche models).

- **Page 4 — Markets & Channels**  
  Regional and country-level performance, including Region × Channel breakdown. Highlights how balanced BMW is across Africa, Asia, Europe, North America, and South America and which channels dominate in each market.

- **Page 5 — Pricing & ASP**  
  Focus on pricing dynamics. Tracks ASP trends over time and compares ASP by model, region, and channel—supporting strategic decisions on pricing and premium positioning.

For a concise visual summary of the dashboard, use:

- **`Interactive Dashboard/Interactive_Dashboard_OnePager.pdf`**  
  (One-page overview with access link + page descriptions.)

---

## 5. Repository Structure

```text
.
├── Dataset
│   └── BMW_Sales_Data.csv
│
├── Interactive Dashboard
│   ├── BMW_Dashboard_Link              # Raw text file with the dashboard URL
│   └── Interactive_Dashboard_OnePager.pdf
│
└── Reports
    └── BMW Global Sales Intelligence Report.pdf
