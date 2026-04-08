# 🌙 Dark Hours India
### Analyzing Road Accident Patterns Across India (2015-2022)

![Python](https://img.shields.io/badge/Python-3.13-blue?style=flat&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-2.0-green?style=flat&logo=pandas)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=flat&logo=jupyter)
![Data](https://img.shields.io/badge/Data-NCRB%20ADSI-red?style=flat)
![Years](https://img.shields.io/badge/Years-2015--2022-purple?style=flat)
![Records](https://img.shields.io/badge/Records-280%20State%2FUT-teal?style=flat)
![Status](https://img.shields.io/badge/Status-In%20Progress-yellow?style=flat)

---

## 📌 Project Overview

**Dark Hours India** is a comprehensive data analysis project that uncovers hidden patterns in road accident data across all Indian States and Union Territories from 2015 to 2022.

The project dives deep into **when**, **where**, **how**, and **who** is most at risk on Indian roads — with a special focus on identifying the deadliest time windows, the Dark Hours.

> *"1800-2100 hrs accounts for the highest road accidents across India — every single year."*

---

## 🔥 Key Findings

| # | Finding | Insight |
|---|---------|---------|
| 🌙 | **Dark Hour Identified** | 1800-2100 hrs — 6,45,868 total accidents (2015-2022) |
| 🛵 | **Two Wheeler Dominance** | 38% of all vehicle deaths — 4,60,871 fatalities |
| ❄️ | **Most Dangerous Month** | January — 3,18,712 accidents — Winter fog effect |
| 🌧️ | **Most Dangerous Season** | Monsoon — 88.6% of states peak in monsoon |
| 🏙️ | **Most Dangerous State (Per Capita)** | Chhattisgarh — 51.6 deaths per lakh — NOT Maharashtra! |
| 🌃 | **Darkest City** | Delhi — 51.8% accidents happen at night |
| 📈 | **2022 — All Time High** | 4,30,504 deaths — highest in 8 years |
| 🛣️ | **Most Dangerous Road** | Other Roads — 4,71,575 deaths |
| 🌾 | **Rural vs Urban** | Rural — 7,64,334 vs Urban — 4,53,702 accidents |
| 😷 | **COVID Impact** | 2020 — 11.1% drop — but 2022 surpassed all records |

---

## 📊 Data Source

| Detail | Info |
|--------|------|
| **Source** | National Crime Records Bureau (NCRB) |
| **Report** | Accidental Deaths & Suicides in India (ADSI) |
| **Years** | 2015 — 2022 |
| **Coverage** | 35 States & Union Territories |
| **Tables Used** | Table 1.2, 1A.4, 1A.5, 1A.6, 1A.7, 1A.11 |

---

## 📁 Project Structure

    dark-hours-india/
    |
    +-- data/
    |   +-- raw/                          # Original NCRB CSV files (year-wise)
    |   |   +-- 2015/ (6 files)
    |   |   +-- 2016/ (6 files)
    |   |   +-- ...
    |   |   +-- 2022/ (6 files)
    |   |
    |   +-- processed/                    # Cleaned & standardized files
    |   |   +-- total_accidental_deaths_2015_2022.csv
    |   |   +-- mode_of_transport_2015_2022.csv
    |   |   +-- month_of_occurrence_2015_2022.csv
    |   |   +-- time_of_occurrence_2015_2022.csv
    |   |   +-- road_classification_2015_2022.csv
    |   |   +-- place_of_occurrence_2015_2022.csv
    |   |
    |   +-- final/                        # Merged master dataset (WIP)
    |
    +-- notebooks/
    |   +-- 01_data_cleaning.ipynb        # Data cleaning & standardization
    |   +-- 02_eda.ipynb                  # Exploratory Data Analysis
    |   +-- 03_analysis.ipynb             # Deep Analysis & Insights
    |   +-- 04_visualization.ipynb        # Advanced Visualizations (WIP)
    |
    +-- dashboard/                        # Power BI Dashboard (WIP)
    +-- README.md
    +-- requirements.txt

---

## 🗂️ Processed Datasets

| File | Description | Shape |
|------|-------------|-------|
| total_accidental_deaths_2015_2022.csv | State/UT wise total accidental deaths | 280 x 4 |
| mode_of_transport_2015_2022.csv | Deaths by vehicle type | 280 x 10 |
| month_of_occurrence_2015_2022.csv | Road accidents by month | 280 x 15 |
| time_of_occurrence_2015_2022.csv | Road accidents by time slot | 280 x 11 |
| road_classification_2015_2022.csv | Deaths by road type | 280 x 8 |
| place_of_occurrence_2015_2022.csv | Accidents by place (Rural/Urban) | 280 x 19 |

---

## 🔍 Analysis Performed

### 1️⃣ Exploratory Data Analysis
- Year wise total deaths trend
- Top 10 most dangerous states
- Time of occurrence — Dark Hours identification
- Month wise accident patterns
- Road classification breakdown
- Place of occurrence — Rural vs Urban
- Mode of transport analysis

### 2️⃣ Deep Analysis
- **Correlation Matrix** — Key accident variables
- **State wise Deep Dive** — Top 5 states profiled
- **Year over Year Growth** — Most improved & most dangerous
- **Night vs Day Ratio** — All states + Top 10 darkest
- **Season Analysis** — Winter Fog Belt, Monsoon Vulnerability Index
- **Climate Zone Analysis** — 5 zones compared
- **Two Wheeler Dominance** — North vs South India
- **Dark Hours + Road Type Combo** — Peak Danger Windows
- **Deaths per Lakh Population** — Real dangerous states revealed
- **COVID-19 Impact** — Drop, Recovery, State wise analysis

---

## 💡 Surprising Insights

### 🏆 The Real Most Dangerous State
Maharashtra has the highest **absolute** deaths but **Chhattisgarh** leads in deaths per lakh population (51.6 per lakh) — making it India's most dangerous state per capita.

### 🌙 The Dark Hour
**1800-2100 hrs** consistently records the highest accidents across all years, all states — this is India's true Dark Hour.

### ❄️ Winter > Monsoon
Contrary to popular belief, **January** records more accidents than any monsoon month — Winter fog in North India is severely underestimated.

### 🛵 Two Wheeler Crisis
Two Wheelers account for **38% of all vehicle deaths** — South India states like Goa (88%), Kerala (46%) show extreme dominance.

### 😷 COVID Paradox
2020 saw an 11.1% drop due to lockdowns — but **2022 surpassed all records** at 4,30,504 deaths — the deadliest year in this dataset.

---

## 🛠️ Tech Stack

| Tool | Usage |
|------|-------|
| Python 3.13 | Data processing & analysis |
| Pandas | Data manipulation |
| Matplotlib | Visualizations |
| Seaborn | Statistical charts |
| Jupyter Notebook | Analysis notebooks |
| Power BI | Dashboard (WIP) |

---

## 📈 Project Status

| Milestone | Status |
|-----------|--------|
| Data Collection | ✅ Complete |
| Data Cleaning | ✅ Complete |
| Exploratory Data Analysis | ✅ Complete |
| Deep Analysis | ✅ Complete |
| Advanced Visualizations | ⏳ In Progress |
| Power BI Dashboard | ⏳ In Progress |
| Behance Case Study | ⏳ Planned |

---

## 👩‍💻 Author

**Ankita R. Singh**
Data Analyst | Passionate about turning raw data into impactful stories

[![GitHub](https://img.shields.io/badge/GitHub-ankitarchoudhary-black?style=flat&logo=github)](https://github.com/ankitarchoudhary)

---

*Data Source: National Crime Records Bureau (NCRB), Ministry of Home Affairs, Government of India*
