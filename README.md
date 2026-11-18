# Airbnb Singapore: Short-Term Hospitality & Pricing Intelligence

An advanced, high-end Power BI analytics dashboard exploring Singapore’s short-term rental market dynamics, pricing distributions, room-type market shares, and host performance under regulatory constraints (Singapore's 90-day minimum stay cap).

---

## 🚀 Project Overview
* **Domain:** Tourism & Short-Term Hospitality Analytics (Singapore Market)
* **Key Question:** How do Singapore’s 90-day minimum stay regulations, room types, and regional saturation impact nightly pricing and guest review momentum across districts?
* **Primary Tool:** Power BI Desktop (DAX, Power Query, Star Schema Architecture)

---

## 📌 Data Source
* Data compiled and processed from [Inside Airbnb](https://insideairbnb.com/get-the-data/)

---

## 🎥 Demo Video
- **Watch Walk-through:** [Airbnb Singapore Dashboard Demo](https://drive.google.com/file/d/1CmHhpgYlxjL4qgHUq95VxNEr1gUIQoX_/view?usp=sharing)
- Overview: A complete video walkthrough covering the interactive multi-page dashboard, regional map filtering, tooltips, and DAX measure performance.

---

## 📊 Dashboard Architecture & Features
1. **Interactive Multi-Page Layout:**
   * **About Me:** Professional profile and project context.
   * **Dashboard:** Core interactive analytics featuring a Treemap, Donut Chart, Scatter Plot (Price vs. Reviews), Top-5 Host Bar Chart, and Regional Map.
   * **Notes Page:** Comprehensive documentation covering recommendations, data sources, assumptions, and AI verification notes alongside active KPI summary cards.
2. **Advanced Interactivity:**
   * **Report-Page Tooltip:** Custom floating hover card displaying host portfolio size and average nightly rate.
   * **Dynamic Filtering & Slicers:** Synchronized room type and neighbourhood group filtering across all visual elements.
3. **Core DAX Measures:**
   * `Total Listings`: `DISTINCTCOUNT(cleaned_listings[id])`
   * `Pct of Total Listings`: Dynamic ratio calculation handling room-type proportions.
   * `Reviews LTM`: Time-intelligence measure tracking trailing twelve-month engagement.
   * `Avg Price`: Financial aggregation of nightly rates.

---

## 📂 Repository Structure
* `/dashboard` — Contains the main `airbnb-singapore.pbix` file.
* `/data/raw` — Original unaltered datasets (`listings.csv`, `reviews.csv`, `neighbourhoods.csv`).
* `/data/processed` — Cleaned analytical datasets ready for modeling.
* `/assets` — Custom theme configuration (`airbnb_theme.json.txt`), brand logos, and spatial boundaries (`neighbourhoods.geojson`).
* `/media` — Full walk-through demo video (`airbnb demo.mp4`).

---
