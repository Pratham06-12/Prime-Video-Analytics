<div align="center">

# 🎬 Amazon Prime Video — Content Analysis

**An interactive Power BI dashboard exploring 100+ years of Prime Video content**

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

</div>

---

##  Dashboard Preview

![Dashboard](./images/Screenshot%202026-02-20%20163307.png)

---

## 📌 Overview

This project analyzes the **Amazon Prime Video** content catalog using Power BI. The dashboard provides visual insights into content distribution, genre trends, audience ratings, production countries, and how the platform's library has grown over time.

---

## 📁 Project Structure

```
Prime_Analysis/
├── prime video analysis.pbix    ← Power BI Dashboard
├── data/
│   └── amazon_prime_titles.csv  ← Dataset (9,655 titles)
├── images/
│   └── Dashboard Screenshot
└── README.md
```

---

##  Key Insights

| Metric | Value |
|---|---|
| 🎬 Total Titles | **9,655** |
| ⭐ Content Ratings | **25** |
| 🎭 Unique Genres | **519** |
| 🎥 Directors | **5,771** |
| 📅 Year Range | **1920 – 2021** |

- **� TV Shows dominate** — 80.82% of content is TV Shows vs. 19.18% Movies
- **🎭 Drama leads genres** — followed by Comedy, Suspense, and Animation
- **🔞 13+ is the top rating** — Prime primarily targets teen-and-above audiences
- **📈 Explosive growth post-2000** — content production surged with the rise of streaming
- **🌍 Global catalog** — USA and India lead production, with presence across all continents

---

## �️ Dataset

**File:** `data/amazon_prime_titles.csv`

The dataset includes columns such as: `title`, `type`, `director`, `cast`, `country`, `release_year`, `rating`, `duration`, `listed_in` (genres), and `description`.

---

## 🛠️ Tools Used

- **Microsoft Power BI Desktop** — Dashboard & Visualizations
- **Power Query** — Data cleaning and transformation
- **DAX** — Custom KPIs and calculated measures
- **Bing Maps** — Geographic heatmap visual

---

## 🚀 How to Open

1. Install [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/) (free)
2. Clone or download this repository
3. Open `prime video analysis.pbix` in Power BI Desktop
4. If prompted, relink the data source to `data/amazon_prime_titles.csv`

---

<div align="center">

*Made with ❤️ using Power BI*

⭐ **Star this repo if you found it useful!**

</div>
