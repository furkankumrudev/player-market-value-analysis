# ⚽ ScoutML: European Football Market Value Analytics

[![Python](https://img.shields.io/badge/python-3.10+-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-%234479A1.svg?style=for-the-badge&logo=pandas&logoColor=white)](https://seaborn.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)](https://matplotlib.org/)

An end-to-end data science project focused on identifying and quantifying the economic drivers of professional football player valuations across Europe's **"Top 5" Leagues** (Premier League, La Liga, Bundesliga, Serie A, and Ligue 1).

## 📌 Project Overview
This repository hosts a comprehensive analytical pipeline designed to decode the relationship between on-pitch performance, contractual status, and market capitalization. The project transitions from raw, multi-source data ingestion to advanced feature engineering and multi-dimensional exploratory data analysis (EDA).

## 🔍 Analytical Core
The analysis utilizes statistical methods to validate industry-specific hypotheses:
* **Market Segmentation:** Measuring the valuation delta between elite European tiers and global benchmarks.
* **Positional Lifecycle:** Mapping peak valuation windows across different player roles (e.g., Attackers vs. Goalkeepers).
* **Efficiency Metrics:** Evaluating the correlation between "Goal Contribution per 90 Minutes" and market value versus traditional volume-based stats.
* **Institutional Value:** Assessing the "Club Multiplier" effect—how a club's total financial stature impacts individual player price points.

## 🛠️ Data Engineering & Features
The following features were engineered to enhance the predictive power and interpretability of the dataset:
* **Contract Longevity:** Derived remaining contract duration to analyze depreciation as players approach free agency.
* **Normalized Performance (Per 90):** Calculated goals and assists per 90 minutes played to eliminate bias toward high-volume starters.
* **Squad Role Classification:** Segmented players into tiers (Key Player, Regular, Rotation, Bench) based on seasonal workload.
* **Defensive Tiers:** Categorized goalkeepers by clean-sheet efficiency and minutes played.

## 📊 Key Insights
* **Financial Synergy:** A strong correlation exists between total club value and individual player valuation, highlighting the impact of institutional branding.
* **Contract Dynamics:** Market values exhibit sharp declines once a contract enters its final 18 months, regardless of consistent performance.
* **Volatility:** Attacker valuations show significantly higher sensitivity to short-term performance spikes compared to defensive roles.

## 📂 Repository Structure

```text
├── data/               # Documentation for data sources and acquisition
├── notebooks/          # Modular Jupyter notebooks for EDA and Preprocessing
├── README.md           # Project documentation
└── requirements.txt    # Environment dependencies
