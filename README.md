# COVID-19 Data Exploration and Dashboard

This project explores global COVID-19 cases, deaths, and vaccinations using SQL-based data analysis,  
followed by creating a professional Tableau dashboard for interactive visual storytelling.

---

## 📊 Project Highlights

- **Data Sources**:
  - COVID-19 Deaths Data (`covid_deaths` table)
  - COVID-19 Vaccinations Data (`covid_vaccinations` table)
- **Database**: Google BigQuery (project: credible-torus-410418)
- **Visualization Tool**: Tableau Public

---

## 🔍 Key SQL Analyses Performed

- Total Cases vs Total Deaths (Calculating likelihood of death upon infection)
- Total Cases vs Population (Infection penetration rate)
- Countries with Highest Infection Rates relative to Population
- Countries and Continents with Highest Death Counts
- Global Aggregations (Total Cases, Total Deaths, Death Percentage globally)
- Population vs Vaccination Rates
- Created **CTEs**, **Temporary Tables**, and **Views** for efficient query management
- Tracked Rolling Vaccination Totals using `SUM() OVER (PARTITION BY ...)`

---

## 📈 Dashboard Visualizations

Built an interactive dashboard showcasing:

- Total Cases vs Total Deaths (by country and globally)
- Infection Rate per Country
- Death Rates by Continent
- Vaccination Progress (% Population Vaccinated)
- Daily Trends and Aggregates

🔗 **Live Dashboard**:  
[COVID-19 Tableau Dashboard](https://public.tableau.com/app/profile/srushti.thakur013/viz/COVID-19Dashboard_17050292654080/Covid-19Dashboard)
