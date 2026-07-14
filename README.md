# Renewable Energy Consumption Analysis

---

<p align="center">

![Python](https://img.shields.io/badge/Python-Programming-blue?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-EDA-0099CC?style=for-the-badge)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-Portfolio-black?style=for-the-badge&logo=github)

</p>

<p align="center">
<b>A data analysis project that explores global renewable energy consumption trends to uncover patterns across countries, energy sources, and time periods.</b>
</p>

---

# Table of Contents

- [Project Overview](#-project-overview)
- [Business Problem](#-business-problem)
- [Project Objectives](#-project-objectives)
- [Dataset Information](#-dataset-information)
- [Tech Stack](#-tech-stack)
- [Project Workflow](#-project-workflow)
- [Data Preprocessing](#-data-preprocessing)
- [Exploratory Data Analysis](#-exploratory-data-analysis)
- [Key Insights](#-key-insights)
- [Visualizations](#-visualizations)
- [How To Run](#-how-to-run)
- [Repository Structure](#-repository-structure)
- [Skills Demonstrated](#-skills-demonstrated)
- [Future Enhancements](#-future-enhancements)
- [Business Impact](#-business-impact)
- [Conclusion](#-conclusion)
- [Author](#-author)

---

#  Project Overview

The shift toward renewable energy is one of the most important global trends in addressing climate change and energy security. Understanding how renewable energy consumption has evolved across countries and energy sources helps policymakers, researchers, and businesses make informed decisions.

This project analyzes global renewable energy consumption data to identify trends, compare countries and regions, and understand the growth of different renewable energy sources over time.

The project combines:

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Trend and comparative analysis
- Data visualization
- Insight generation

The analysis helps:

- Track the growth of renewable energy adoption over time
- Compare renewable energy consumption across countries/regions
- Identify which energy sources are growing fastest
- Support data-driven energy policy and sustainability decisions

---

#  Business Problem

Governments, energy companies, and researchers need clear, data-backed visibility into renewable energy trends to plan for a sustainable future.

Common challenges include:

- Renewable energy data spread across multiple sources and formats
- Difficulty comparing consumption trends across countries
- Lack of clarity on which renewable sources are scaling fastest
- Limited visibility into the pace of transition from fossil fuels to renewables

Key questions addressed:

- How has renewable energy consumption changed over time?
- Which countries/regions lead in renewable energy adoption?
- Which renewable energy sources (solar, wind, hydro, etc.) are growing the fastest?
- What patterns exist between economic development and renewable energy usage?

---

#  Project Objectives

### Analytical Objectives

- Analyze global/regional renewable energy consumption trends
- Compare renewable energy usage across countries and time periods
- Identify the fastest-growing renewable energy sources
- Visualize consumption patterns for easy interpretation
- Generate actionable insights on the renewable energy transition

---

#  Dataset Information

**Dataset Source:** Renewable Energy Consumption Dataset *(update with actual source, e.g., Our World in Data / IEA / Kaggle)*

### Dataset Summary

| Metric | Value |
|----------|--------|
| Total Records | *(update with actual row count)* |
| Total Features | *(update with actual feature count)* |
| Time Period Covered | *(e.g., 2000–2023)* |
| Data Type | Structured Time-Series Data |

---

### Features Included

| Feature | Description |
|-----------|-------------|
| Country/Region | Name of the country or region |
| Year | Year of recorded consumption |
| Energy Source | Type of renewable source (Solar, Wind, Hydro, Biomass, etc.) |
| Consumption | Energy consumption value (e.g., in TWh) |
| Total Energy Consumption | Total energy consumption (renewable + non-renewable) |
| Renewable Share (%) | Percentage of total energy from renewable sources |
| Population / GDP | Optional socio-economic indicators (if available) |

*(Update the feature list above to match the exact columns in your dataset.)*

---

#  Tech Stack

| Technology | Purpose |
|------------|----------|
| Python | Programming |
| Pandas | Data Manipulation |
| NumPy | Numerical Operations |
| Matplotlib | Data Visualization |
| Seaborn | Exploratory Data Analysis |
| Jupyter Notebook | Analysis Environment |
| Git/GitHub | Version Control |

---

#  Project Workflow

```text
Raw Dataset (.CSV)
          │
          ▼
Data Cleaning & Preprocessing
          │
          ▼
Exploratory Data Analysis
          │
          ▼
Trend & Comparative Analysis
          │
          ▼
Data Visualization
          │
          ▼
Insight Generation
          │
          ▼
Final Report / Notebook
```

---

#  Data Preprocessing

Data preprocessing was performed before analysis.

### Tasks Performed

- Imported dataset
- Checked and handled missing values
- Removed duplicates
- Standardized country names and units
- Filtered relevant years/columns
- Data type conversions (e.g., year, numeric fields)

---

#  Exploratory Data Analysis

Exploratory analysis was conducted to understand renewable energy trends and relationships.

### Analysis Performed

- Year-over-year renewable energy consumption trends
- Country-wise and region-wise comparison
- Energy source-wise contribution analysis
- Renewable vs. non-renewable share over time
- Correlation between economic indicators and renewable adoption (if applicable)

### Key Observations

*(Update with your actual findings, e.g.:)*

- Global renewable energy consumption has shown consistent year-over-year growth
- Solar and wind energy are among the fastest-growing sources
- A small group of countries account for a large share of total renewable consumption
- Renewable energy share tends to increase alongside GDP growth in several regions

---

#  Key Insights

*(Replace with the actual insights from your notebook, e.g.:)*

- Certain countries have significantly outpaced others in renewable adoption
- The share of renewables in total energy mix has steadily risen over the analyzed period
- Some energy sources show accelerating growth in the most recent years
- Regional disparities remain in renewable energy transition

---

#  Visualizations

- Line charts showing consumption trends over time
- Bar charts comparing countries/regions
- Pie/stacked charts showing energy source contribution
- Heatmaps for correlation analysis
- Choropleth/geographic visualizations (if applicable)

---

#  How To Run

### Clone Repository

```bash
git clone https://github.com/KartikKachwahe/RENEWABLE-ENERGY-CONSUMPTION-ANALYSIS.git
```

### Move into Project Directory

```bash
cd RENEWABLE-ENERGY-CONSUMPTION-ANALYSIS
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Notebook

```bash
jupyter notebook Renewable-Energy-Consumption-Analysis.ipynb
```

---

#  Repository Structure

```text
RENEWABLE-ENERGY-CONSUMPTION-ANALYSIS
│
├── Renewable-Energy-Consumption-Analysis.ipynb
├── renewable_energy_data.csv
├── images/
│   └── charts and visualizations
├── README.md
```

*(Update file names above to match your actual repository contents.)*

---

#  Skills Demonstrated

### Python

- Data Cleaning
- Data Manipulation
- Time-Series Analysis

### Data Analysis

- Exploratory Data Analysis (EDA)
- Trend Analysis
- Comparative Analysis
- Data Visualization

### Domain Knowledge

- Renewable Energy Metrics
- Sustainability Analytics
- Energy Policy Data Interpretation

### Tools

- Jupyter Notebook
- Git Version Control
- GitHub Portfolio Management

---

#  Future Enhancements

- Add predictive modeling to forecast future renewable energy consumption
- Build an interactive dashboard (Power BI/Streamlit) for exploration
- Include additional socio-economic variables for deeper analysis
- Add geographic/choropleth mapping for regional comparison
- Automate data updates from live energy data sources

---

#  Business Impact

Potential benefits:

✅ Clearer visibility into global renewable energy trends

✅ Data-backed support for energy policy decisions

✅ Identification of leading countries and fastest-growing energy sources

✅ Better understanding of the pace of the renewable energy transition

✅ Foundation for further predictive/sustainability research

---

#  Conclusion

This project demonstrates how data analysis can be used to understand global renewable energy consumption trends and support the broader conversation around sustainable energy transition.

The project covers a complete end-to-end analysis workflow:

- Data preprocessing
- Exploratory Data Analysis
- Trend and comparative analysis
- Visualization
- Insight generation

Understanding these patterns can help governments, businesses, and researchers make more informed decisions in the transition toward renewable energy.

---

# 👨‍💻 Author

## Kartik Kachwahe

**Aspiring Data Scientist | Data Analyst | Machine Learning | SQL | Power BI | Python**

📧 Email: kartikkachwahe25@gmail.com

💼 LinkedIn: https://www.linkedin.com/in/kartikkachwahe021

💻 GitHub: https://github.com/KartikKachwahe

---

## ⭐ Support

If you found this project useful, consider giving the repository a star.

Your support motivates future projects and helps others discover this work.

---

**Thank you for visiting this repository 🌱**
