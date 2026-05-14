# NBA Player Performance Analysis (2026 Season)

## Overview

This project explores modern NBA player statistics using Python-based data analysis techniques. The analysis focuses on identifying scoring trends, player efficiency, positional dominance, and statistical relationships between major basketball performance metrics.

Using Pandas, NumPy, Matplotlib, and Seaborn, the notebook performs end-to-end exploratory data analysis (EDA) on NBA player data from the 2026 season.

The project also introduces a custom efficiency metric called **PES (Player Efficiency Score)** to evaluate overall player contribution beyond raw scoring.

---

# Technologies Used

| Technology       | Purpose                          |
| ---------------- | -------------------------------- |
| Python           | Core programming language        |
| Pandas           | Data manipulation and analysis   |
| NumPy            | Numerical operations             |
| Matplotlib       | Data visualization               |
| Seaborn          | Statistical visualization        |
| Jupyter Notebook | Interactive analysis environment |

---

# Dataset

**Dataset Used:** NBA Stats (1947-present)

Source: Kaggle NBA statistics dataset containing historical and modern player statistics.

The analysis focuses specifically on:

* Modern NBA player statistics
* 2026 season data
* Per-game performance metrics

---

# Key Features of the Project

## 1. Data Cleaning

The notebook performs multiple preprocessing steps including:

* Filtering latest season data
* Removing duplicate traded-player entries
* Keeping only aggregated `TOT` records for traded players
* Handling statistical inconsistencies
* Selecting relevant numerical features

---

## 2. Exploratory Data Analysis (EDA)

The project analyzes:

* Top scorers of the season
* Positional scoring trends
* Rebounding dominance
* Assist distribution
* Age-related performance patterns
* Efficiency vs scoring comparisons

---

## 3. Correlation Heatmap Analysis

A detailed statistical heatmap was generated to study relationships between:

* Points per game
* Rebounds
* Assists
* Steals
* Blocks
* Minutes played
* Shooting efficiency
* Age


## 4. Custom Metric — PES (Player Efficiency Score)

A custom efficiency metric called **PES** was designed to estimate overall player contribution.

### PES Formula

The metric rewards:

* Scoring
* Rebounding
* Playmaking
* Defensive impact

while balancing multiple dimensions of basketball contribution.

## 5. Position-Based Ranking

To reduce bias caused by role differences:

* Players were ranked within their own positions
* Guards and centers were evaluated separately
* Position-normalized efficiency comparisons were performed

This makes the analysis more realistic because NBA positions have very different responsibilities.

---

# Project Structure

```plaintext
nba-player-analysis/
│
├── NBA_Player_Analytics.ipynb
├── README.md
```

# Limitations

This project is exploratory and has several limitations:

* PES is a custom metric and not an official NBA statistic
* Advanced analytics such as PER, TS%, BPM, and RAPTOR were not included
* Team-level context was not deeply analyzed
* Defensive impact is simplified through steals and blocks only
* Injury effects and pace adjustments were not considered

---

# Learning Outcomes

Through this project, the following concepts were practiced:

* Data cleaning
* Filtering and grouping data
* Feature engineering
* Correlation analysis
* Statistical visualization
* Custom metric design
* Data storytelling
* Analytical interpretation

---

# Author

**Vedant Chandak**
ECE Undergraduate | Basketball Athlete | Aspiring Data & AI Enthusiast
