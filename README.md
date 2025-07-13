# 🏏 T20 Men's Cricket World Cup 2022 - Player Performance Analysis Dashboard

An **end-to-end interactive data analytics project** that builds a **Power BI dashboard** showcasing the **Best XI players from the T20 World Cup 2022** using **web-scraped data, Python for cleaning, and Power BI for visualization and analysis**.

The dashboard highlights top performers across:
- Opening Batsmen
- Middle-order Players
- All-rounders
- Tail-enders

It enables **cricket enthusiasts, analysts, and learners** to intuitively explore **player and team statistics** interactively, understand performance metrics, and dynamically visualize **the Best Playing XI** from the tournament using a `.pbix` file in Power BI Desktop.

---

## 🎯 Project Objectives

✅ Build a **visually appealing, interactive dashboard** for cricket performance analysis.

✅ Utilize **real-world data scraping and cleaning workflows**.

✅ Learn and implement **Power BI best practices** including DAX measures, Power Query, and dashboard design.

✅ Enable **dynamic filtering and analysis of player performances** for effective insights.

✅ Share a reusable `.pbix` file for open learning and portfolio showcasing.

---

## 📊 Dashboard Features

The dashboard allows users to:

✅ **Explore the dynamically selected Best Playing XI** based on KPIs and performance metrics across player roles.

✅ Analyze **batting and bowling metrics** including:

* Batting Average
* Strike Rate
* Runs Scored
* Boundary %
* Bowling Economy Rate
* Dot Ball %
* Wickets Taken

✅ **Compare performances across teams, player roles, and matches.**

✅ Use **interactive slicers** to filter by:

* Team
* Player Role
* Match

✅ Hover for **detailed player tooltips** and analyze role-wise contributions.

✅ Navigate across multiple report pages for **batting, bowling, team performance, and Best XI breakdown.**

---

## 📷 Dashboard Preview

![Dashboard Screenshot](images/dashboard.png) <!-- Replace with your actual image path -->

---

## 🛠️ Tools & Technologies Used

| Tool / Technology      | Purpose                                                        |
| ---------------------- | -------------------------------------------------------------- |
| **Python**             | Web scraping, data cleaning, transformation                    |
| **BeautifulSoup**      | Extracting player data from ESPN Cricinfo                      |
| **Pandas**             | Data cleaning, manipulation, CSV preparation                   |
| **Jupyter Notebook**   | Scripting the scraping and preprocessing pipeline              |
| **Power BI**           | Data visualization, DAX-based calculations, dashboard creation |
| **Power Query Editor** | Data shaping and transformations within Power BI               |
| **DAX**                | Calculated columns, measures, KPIs for performance analysis    |

---

## 🌐 Data Source

* Primary Data: **[ESPN Cricinfo](https://www.espncricinfo.com/)** for T20 World Cup 2022 player and match statistics.
* Scraped using Python (`BeautifulSoup`) with structured parsing.
* Cleaned and transformed using Pandas, exported as CSV for Power BI ingestion.

---

## 🔄 Project Workflow

### 1️⃣ Requirement Scoping

Identified the need for an engaging cricket performance analysis dashboard with a focus on building a **Best XI team dynamically using statistics.**

### 2️⃣ Data Collection & Scraping

Used Python with BeautifulSoup to scrape player-level and match-level data from ESPN Cricinfo, handling pagination and structured JSON endpoints.

### 3️⃣ Data Cleaning & Transformation

Utilized Pandas in Jupyter Notebook for:

* Data type conversions
* Null value handling
* Feature engineering (calculating KPIs like boundary %, dot ball %, etc.)
* Exported clean datasets in CSV format.

### 4️⃣ Data Loading into Power BI

Imported CSV datasets into Power BI using Power Query Editor for additional transformation and relationship modeling.

### 5️⃣ Data Modeling & DAX Measures

Created calculated columns and DAX measures for:

* Batting KPIs
* Bowling KPIs
* Role-based player segmentation
* Dynamic Best XI calculation logic

### 6️⃣ Dashboard Development

Developed a clean, intuitive Power BI dashboard with:

* Page navigation
* Role-wise analysis
* Dynamic slicers for interactive filtering
* KPI cards and visual charts
* Hover tooltips for deeper player insights

### 7️⃣ Sharing & Deployment

Published the `.pbix` file for **open learning and analysis**, allowing users to download and interact with the dashboard locally using Power BI Desktop.

---

## 📈 Learning Outcomes

✅ **Web Scraping Automation:** Automating structured data collection from ESPN Cricinfo.

✅ **Data Cleaning & EDA:** Using Pandas for quick inspection and transformation.

✅ **Power BI Modeling:** Learning Power Query for efficient data shaping and DAX for calculated measures.

✅ **Dashboard Design Principles:** Clean layout, consistent color usage, and interactive filtering to enhance user experience.

✅ **Cricket Data Analysis:** Understanding how advanced metrics can evaluate player performance in cricket.

---

If you have any queries or want to collaborate on cricket analytics or Power BI projects:

* 📧 Email: *[shrutijaiswal2905@gmail.com](mailto:your_email@example.com)*
---

## ⭐ Final Notes

This project demonstrates **data collection, cleaning, and visualization for sports analytics** using real-world data. It is an excellent learning resource for **Power BI learners, data analysts, and cricket enthusiasts** aiming to apply data analytics to sports performance analysis.

---
