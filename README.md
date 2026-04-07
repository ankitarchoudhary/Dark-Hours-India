# 🌑 Dark Hours of India
### *"We shine light on India's darkest hours"*
> Every year, 4-5 lakh Indians die in accidents. Not because accidents 
> are unavoidable — but because no one studied the patterns deeply enough.
> This project does exactly that.
---
## 🎯 The Problem
India records **4-5 lakh accidental deaths every year.**
We always say *"accidents happen"* — but no one asks:
- **When** do they happen? (Which hours? Which months?)
- **Where** do they happen? (Which states? Which roads?)
- **Why** do they keep happening at the same places, same times?
- **Who** is most vulnerable? (Age, gender, profession?)
**Dark Hours of India** answers all of these questions — using real 
government data, not assumptions.
---
## 🔍 What We Analyse
### ⏰ Time Analysis
- Which hours of the day are most dangerous?
- Which months see the highest fatalities?
- Seasonal patterns — Summer vs Monsoon vs Winter?
### 📍 Place Analysis
- Which states have the highest accidental death rates?
- Highway vs City Roads vs Railway accidents
- Urban vs Rural vulnerability
### ⚠️ Cause Analysis
- Road accidents, drowning, fire, poisoning — what dominates?
- Age and gender patterns
- Natural vs Un-natural causes
---
## 📊 Data Source
**NCRB — Accidental Deaths & Suicides in India (ADSI)**
- Source: [data.gov.in](https://data.gov.in) — Official Govt of India
- Years: 2015 to 2022
- Coverage: All Indian States & UTs
- Tables: State-wise, Time-wise, Cause-wise, Age/Gender-wise
---
## 🌍 Real World Impact
This is not just a portfolio project. The insights can directly inform:
Data Analysis ↓ Hidden Patterns Discovered ↓ Evidence-Based Recommendations ↓ Better Road Lighting • Smarter Ambulance Deployment Better Traffic Management • Targeted Awareness Campaigns ↓ Fewer Deaths ✅
**Example:** If analysis shows drowning deaths spike in Maharashtra during June-July → Government can deploy extra beach guards + run targeted awareness campaigns in that exact window. 
---
## 🛠️ Tech Stack | Tool | Purpose | |------|---------| | Python (Pandas, NumPy) | Data cleaning & analysis | | Matplotlib, Seaborn | Statistical visualizations | | Plotly | Interactive charts | | Folium | India map visualizations | | SQL (SQLite) | Data storage & queries | | Power BI | Final interactive dashboard | | Jupyter Notebook | Analysis environment | 
---
## 📁 Project Structure
Dark-Hours-India/
├── data/
│   ├── raw/          ← Original NCRB data
│   ├── processed/    ← Cleaned data
│   └── final/        ← Merged analysis-ready data
├── notebooks/
│   ├── 01_data_collection.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_eda.ipynb
│   ├── 04_correlation_analysis.ipynb
│   └── 05_visualization.ipynb
├── dashboard/        ← Power BI dashboard
├── README.md
└── requirements.txt