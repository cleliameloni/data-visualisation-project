#  Gender Pay Gap Analysis in Europe (2006-2022)

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Library](https://img.shields.io/badge/Pandas-Data%20Analysis-orange)
![Library](https://img.shields.io/badge/Matplotlib-Visualization-red)
![Data Source](https://img.shields.io/badge/Data%20Source-Eurostat-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

##  Project Overview

This project analyzes the evolution of the **Gender Pay Gap (GPG)** across European countries over a 16-year period (2006-2022). Using official unadjusted data from **Eurostat**, the analysis aims to visualize disparities, track progress over time, and challenge assumptions about the relationship between national wealth and wage equity.

The project highlights not just the raw numbers, but the **velocity of change**—identifying which nations are actively closing the gap and which are stagnating.

---

##  Research Questions

### Primary Question
> **Which European countries demonstrated an effective reduction in the Gender Pay Gap between 2006 and 2022?**

### Secondary Questions
* **Champions of Change:** Which nations achieved the most significant decrease, showing the strongest policy commitment?
* **Geographic Patterns:** Is there a visible divide between Eastern and Western Europe?
* **The Wealth Paradox:** Do stronger economies necessarily have lower wage gaps?

---

##  Key Findings & Insights

Based on the Exploratory Data Analysis (EDA), three critical trends emerged:

### 1. The "Wealth ≠ Equity" Paradox
Surprisingly, high GDP does not guarantee equal wages. Strong economies like **Austria** and the **United Kingdom** have historically maintained high gaps (often exceeding **20%**), proving that economic prosperity does not automatically translate into gender pay equity.

### 2. Significant Outliers
The gap is not uniform across the continent.
* **Estonia** stands out as a persistent outlier, maintaining very high levels (peaking at **28.6%** in 2006) and distancing itself from the EU average.

### 3. Rapid Policy Impacts
Despite general rigidity, some nations show that rapid change is possible.
* **Cyprus** recorded a dramatic decline (dropping from **30% to 23%** in a short period), suggesting that targeted policies and cultural shifts can drive fast results.

---

##  Data Source

* **Provider:** Eurostat (European Commission) - https://ec.europa.eu/eurostat/databrowser/view/earn_ses_pub2s__custom_19373321/default/table?page=time:2006
* **Dataset Code:** `sdg_05_20` (Gender pay gap in unadjusted form)
* **Definition:** The unadjusted Gender Pay Gap represents the difference between average gross hourly earnings of male paid employees and of female paid employees as a percentage of average gross hourly earnings of male paid employees.
* **Timeframe:** 2006 - 2022

---

##  Tech Stack

* **Python 3.x**
* **Pandas & NumPy:** Data cleaning and manipulation.
* **Matplotlib & Seaborn:** Static visualizations (Slope charts, heatmaps).
* **Plotly (Optional):** Interactive geographic maps.

---

##  Repository Structure

```text
├── data/
│   ├── raw/                 # Original Eurostat datasets (CSV/JSON)
│   └── processed/           # Cleaned data ready for analysis
├── notebooks/
│   ├── 01_Data_Cleaning.ipynb     # Preprocessing and handling missing values
│   ├── 02_EDA_Trends.ipynb        # Exploratory Analysis & Statistical Summary
│   └── 03_Visualizations.ipynb    # Final charts generation
├── images/                  # Exported plots for the README/Report
├── requirements.txt         # Project dependencies
└── README.md                # Project documentation
