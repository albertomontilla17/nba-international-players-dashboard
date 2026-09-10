# NBA International Players Dashboard

Interactive Tableau dashboard analyzing the growth and impact of international players in the NBA from 1996 to 2023.

🌐 **[View live on Tableau Public](https://public.tableau.com/app/profile/alberto.montilla6349/viz/NBA_international_players/Dashboard1)**

---

## Overview

This project explores how international representation in the NBA has evolved over nearly three decades, using a Kaggle dataset covering player statistics and country of origin across 27 seasons (1996–97 through 2022–23).

Built as a Data Analytics final project at Miami Dade College.

---

## Key Insights

- **419 unique international players** from **40+ countries** have appeared in the NBA since 1996–97
- International representation grew **14.8x** — from **9 players** in 1996–97 to **133 players** in 2021–22, the most ever recorded
- **Canada** is the top feeder nation with **45 unique players**, ahead of **France (37)** and **Australia (22)**
- **2010–2020** was the golden era of international drafting, peaking at **23 players drafted in 2016**
- **116 international players** in the dataset went undrafted entirely
- **Luka Dončić** leads all international players at **28.4 PPG** — nearly 5 points ahead of Giannis Antetokounmpo (23.5 PPG) in second place, and more than double the output of Jamal Murray (17.5 PPG) at #10
- **Dirk Nowitzki** played **21 seasons** — the longest career of any international player in NBA history, 3 more than the next closest (Tony Parker, Steve Nash, and Pau Gasol, tied at 18)

---

## Key Features

- **Country of Origin Analysis** — world map tracking which countries have contributed the most players over time
- **Season-by-Season Trends** — visualizes the rise of international players as a share of the league, from 9 (1996–97) to 133 (2021–22)
- **Draft Trends** — international players drafted per year, highlighting the 2010–2020 golden era
- **Top 10 Leaderboard with Stat Selector** — toggle the leaderboard between PPG, RPG, and APG with a single dropdown to compare international players across categories
- **Career Longevity** — seasons played by the longest-tenured international players
- **Player Classification** — uses calculated fields and COUNTD logic to distinguish domestic vs. international players
- **Interactive Filters** — parameter-based sheet swapping for dynamic exploration by season, country, and position

---

## Data Cleaning

The raw dataset stored height and weight as text (e.g. `6'4"`, `209 lbs`), which isn't usable for analysis or visualization as-is. Before building the dashboard, the data went through a full clean in Excel:

- Converted height strings to total inches using `LEFT`/`FIND`/`MID` formulas
- Converted weight strings to numeric values using `VALUE`/`SUBSTITUTE`
- Standardized ~12,000+ player-season records (1996–2023) across a Raw → Cleaning → Final workflow before loading into Tableau

---

## Tools & Skills

- **Excel** — data cleaning, formula-based text-to-numeric conversion, multi-sheet wrangling workflow
- **Tableau** — calculated fields, parameters, COUNTD, dashboard actions, stat selector
- Exploratory data analysis
- Kaggle dataset (1996–2023 NBA seasons)

---

## How to View

The dashboard is published on [Tableau Public](https://public.tableau.com/app/profile/alberto.montilla6349/viz/NBA_international_players/Dashboard1) — no download required.

Alternatively, download the `.twbx` file and open with [Tableau Public Desktop](https://public.tableau.com/en-us/s/download) (free).

---

## Dataset

Source: [NBA Players Data — Kaggle](https://www.kaggle.com/datasets/justinas/nba-players-data)

---

## Authors

Alberto Montilla & Rick Parra — Miami Dade College, Data Analytics
