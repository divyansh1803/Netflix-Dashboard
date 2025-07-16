# Netflix-Dashboard

# 🎬 Netflix Dashboard (Tableau)

This repository contains a Tableau dashboard project that visualizes Netflix content data, including Movies and TV Shows, genres, release trends, ratings, and regional availability. The dashboard provides interactive, visual insights into Netflix’s global content strategy and user preferences.

---

## 📄 Abstract

The **"Netflix Dashboard"** project leverages Tableau's powerful visualization capabilities to analyze Netflix's content dataset. It presents a comprehensive view of the platform's offerings by type, genre, release year, and country. By enabling exploratory filtering and visual storytelling, the dashboard helps uncover trends in content creation, regional diversity, and rating distribution. This project is useful for analysts, media researchers, and business strategists interested in digital streaming analytics.

---

## 🚀 Key Features

- 🎞️ **Content Overview:** Differentiates Movies vs. TV Shows with total counts and proportions.
- 📆 **Yearly Trends:** Tracks number of titles added each year.
- 🌍 **Country-Level Analysis:** Top contributing countries by content volume.
- 🎭 **Genre Breakdown:** Distribution of content across multiple genres.
- 🧾 **Rating Categories:** Insight into maturity ratings (TV-MA, PG, R, etc.).
- 🔍 **Interactive Filtering:** Year, Country, Type, and Rating filters for custom exploration.

---

## 🧰 Technology Stack

| Layer | Tool | Purpose |
|-------|------|---------|
| **Data Source** | CSV (Netflix Titles) | Contains movie/show metadata like title, cast, country, release year, genre, rating |
| **Data Cleaning** | Tableau Prep / Excel | Clean nulls, split multivalued fields, transform date formats |
| **Data Visualization** | Tableau Public / Desktop | Build interactive dashboards |
| **Data Hosting (Optional)** | Tableau Public | Share online interactive dashboard |
| **Documentation** | Markdown (`README.md`) | GitHub project overview and explanation |
| **Version Control** | Git + GitHub | Repository for workbook files, dataset, and documentation |

---

## 📈 Methodology

1. **Data Collection**  
   Used a publicly available dataset (e.g., Kaggle’s Netflix titles dataset).

2. **Preprocessing**  
   - Removed missing and duplicate values.
   - Split multi-value columns (e.g., genres, countries).
   - Converted date columns for time-series analysis.

3. **Dashboard Design in Tableau**  
   - Imported cleaned data into Tableau Desktop.
   - Created calculated fields for metrics like content count, genre frequency.
   - Used maps, bar charts, pie charts, and heatmaps.
   - Added parameter controls and filter actions for interactivity.

4. **Insights Uncovered**  
   - Growth in content across years.
   - Dominant countries and genres.
   - Analysis of Netflix’s content maturity (TV-MA, PG, etc.).
   - Differences between movie and TV show catalogs.

---

## 📂 Repository Structure

