⚽ ScoutML: European Football Market Value Analytics
An end-to-end data science project focused on identifying and quantifying the economic drivers of professional football player valuations across Europe's "Top 5" Leagues (Premier League, La Liga, Bundesliga, Serie A, and Ligue 1).

📌 Project Overview
This repository hosts a comprehensive analytical pipeline designed to decode the relationship between on-pitch performance, contractual status, and market capitalization. The project transitions from raw, multi-source data ingestion to advanced feature engineering and multi-dimensional exploratory data analysis (EDA).

🔍 Analytical Core
The analysis utilizes statistical methods to validate industry-specific hypotheses:

Market Segmentation: Measuring the valuation delta between elite European tiers and global benchmarks.

Positional Lifecycle: Mapping peak valuation windows across different player roles (e.g., Attackers vs. Goalkeepers).

Efficiency Metrics: Evaluating the correlation between "Goal Contribution per 90 Minutes" and market value versus traditional volume-based stats.

Institutional Value: Assessing the "Club Multiplier" effect—how a club's total financial stature impacts individual player price points.

🛠️ Data Engineering & Features
The following features were engineered to enhance the predictive power and interpretability of the dataset:

Contract Longevity: Derived remaining contract duration to analyze depreciation as players approach free agency.

Normalized Performance (Per 90): Calculated goals and assists per 90 minutes played to eliminate bias toward high-volume starters.

Squad Role Classification: Segmented players into tiers (Key Player, Regular, Rotation, Bench) based on seasonal workload.

Defensive Tiers: Categorized goalkeepers by clean-sheet efficiency and minutes played.

📊 Key Insights
Financial Synergy: A strong correlation (>0.80) exists between total club value and individual player valuation, highlighting the impact of institutional branding.

Contract Dynamics: Market values exhibit sharp declines once a contract enters its final 18 months, regardless of consistent performance.

Volatility: Attacker valuations show significantly higher sensitivity to short-term performance spikes compared to defensive roles.

📂 Repository Structure
Plaintext

├── data/               # Documentation for data sources and acquisition
├── notebooks/          # Modular Jupyter notebooks for EDA and Preprocessing
├── README.md           # Project documentation
└── requirements.txt    # Environment dependencies
🚀 Getting Started
Clone the repository:

Bash

git clone https://github.com/furkankumrudev/player-market-value-analysis.git
Install dependencies:

Bash

pip install -r requirements.txt
Execute the analysis:

Bash

jupyter notebook notebooks/player-market-value-analysis.ipynb
