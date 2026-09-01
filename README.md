# Nigeria & Africa: Population Growth Dashboard

**AnalystLab Africa Data Analytics Internship — Week 8 Capstone Project**

Nigeria's population growth analyzed in comparison with 7 other major African countries, using World Bank World Development Indicators (WDI) data.

---

## 📌 Project Overview

This project analyzes Nigeria's population growth from 1990–2023 in comparison with seven other major African countries — Ethiopia, Egypt, DR Congo, South Africa, Kenya, Ghana, and Cameroon — using World Bank World Development Indicators (WDI) data. The project follows the full data analytics workflow: data extraction, cleaning, exploratory analysis, and interactive dashboard development.

## 🌍 Data Source

World Bank World Development Indicators (WDI): https://datatopics.worldbank.org/world-development-indicators/

## 📊 Indicators Analyzed

| Indicator | Description |
|---|---|
| Population, total | Total population count |
| Population growth (annual %) | Year-over-year population growth rate |
| Urban population (% of total) | Share of population in urban areas |
| Population density | People per sq. km of land area |
| Fertility rate, total | Average births per woman |
| Age dependency ratio | Ratio of dependents to working-age population |

## 🗺️ Countries Studied

Nigeria, Ethiopia, Egypt (Arab Rep.), DR Congo, South Africa, Kenya, Ghana, Cameroon — covering 1990 to 2023.

## 🧹 Data Cleaning Process

- Filtered the full WDI dataset (396,970 rows) down to 8 countries and 6 indicators.
- Identified and backward-filled 3 missing values (Ethiopia's population density, 1990–1992).
- Checked for and confirmed no duplicate country-indicator records.
- Verified column and country name standardization.
- Reshaped data from wide format to long format (1,632 rows) for analysis and dashboarding.

## 🔑 Key Findings

- **Population Scale:** Nigeria's population (227.9M) is nearly double the next-largest country studied (Ethiopia, 128.7M).
- **Growth Rate:** Nigeria's average growth rate (2.59%) is mid-pack — behind DR Congo (3.21%) and Ethiopia (3.03%).
- **Urbanization:** Nigeria's urban share rose from 35.2% to 62.2% (1990–2023) — the largest shift of all 8 countries.
- **Fertility:** Nigeria's fertility rate (4.48) is the second-highest studied, behind DR Congo (6.05).
- **Dependency Ratio:** Nigeria's dependency ratio (80.2%) is nearly tied for second-highest, behind DR Congo (96.7%).

## 💡 Insights

- Scale, not speed, defines Nigeria's population story — its outsized influence on Africa's population comes from the size of its existing base rather than an unusually fast growth rate.
- Nigeria is urbanizing faster than any peer in this study, with direct implications for housing, infrastructure, and health service access in fast-growing cities.
- High fertility continues to drive future growth, meaning Nigeria's population will likely keep expanding significantly for decades.
- Nigeria carries one of the heaviest dependency burdens in the region, placing economic pressure on its working-age population.
- Growth patterns cluster into two groups: high-fertility/high-growth countries (Nigeria, Ethiopia, Cameroon, DR Congo) vs. more demographically stabilized countries (South Africa, Egypt).

## ✅ Recommendations

1. Prioritize urban infrastructure investment to keep pace with rapid rural-to-urban migration.
2. Expand voluntary family planning and reproductive health access.
3. Invest in youth education and job creation to convert Nigeria's large youth population into a productive workforce.
4. Strengthen rural healthcare and services so migration to cities remains a choice, not a necessity.
5. Study policy lessons from lower-growth peers such as South Africa and Egypt.

## 🛠️ Tools Used

- **Python (Pandas)** — data cleaning, reshaping, exploratory analysis
- **Jupyter Notebook** — analysis documentation
- **Microsoft Power BI** — interactive dashboard development

## 📁 Repository Contents

| File | Description |
|---|---|
| `Week8_Population_Growth_Africa_EDA.ipynb` | Jupyter notebook with full data cleaning and EDA process |
| `wdi_population_africa_cleaned.csv` | Cleaned dataset (wide format) |
| `wdi_population_africa_long.csv` | Reshaped dataset (long format, used in Power BI) |
| `Nigeria_Africa_Population_Growth_Dashboard.pbix` | Interactive Power BI dashboard file |
| `Nigeria_Africa_Population_Growth_Capstone_Report.pdf` | Final written report |
| `README.md` | This file |

## 📈 How to View the Dashboard

1. Download `Nigeria_Africa_Population_Growth_Dashboard.pbix`
2. Open it in [Microsoft Power BI Desktop](https://www.microsoft.com/en-us/power-platform/products/power-bi/desktop) (free download)
3. Use the **Country Name** and **Year** slicers at the top to filter the dashboard interactively

## 👤 Author

**Chisom Nwangele** — Data Analytics Intern, AnalystLab Africa | 3MTT Fellow, Data Analysis and Visualization Track

#AnalystLabAfrica
