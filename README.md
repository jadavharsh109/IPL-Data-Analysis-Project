# IPL Data Analysis (2008 - 2024)

An extensive exploratory data analysis (EDA) of the Indian Premier League (IPL) using Python. This project analyzes over a decade of cricket data to uncover match trends, player performance statistics, and venue insights.

## 📊 Project Overview
The objective of this project is to process and visualize IPL historical data to answer key questions such as:
* How does the toss decision affect the match outcome?
* Which players have the highest impact across different seasons?
* Performance analysis of teams across various venues and cities.

## 📁 Dataset Summary
The analysis is powered by four primary datasets:

| Dataset | Description | Rows | Key Columns |
| :--- | :--- | :--- | :--- |
| **Matches** | Match-level details (2008-2024) | 1,169 | `match_id`, `season`, `venue`, `toss_winner`, `match_winner` |
| **Ball-by-Ball** | Granular delivery data | 278,205 | `batter`, `bowler`, `total_runs`, `is_wicket`, `innings` |
| **Players** | Metadata for IPL athletes | 772 | `player_name`, `bat_style`, `bowl_style` |
| **Teams** | Franchise information | 16 | `team_name`, `team_name_short` |

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** * `pandas` (Data Cleaning & Manipulation)
    * `numpy` (Numerical Operations)
    * `matplotlib` & `seaborn` (Data Visualization)

## 🔍 Key Features of Analysis
* **Match Trends:** Analysis of winning margins (runs vs. wickets) and seasonal growth.
* **Toss Impact:** Correlation between winning the toss and winning the match.
* **Batting & Bowling:** In-depth look at runs, strike rates, and wicket-taking patterns.
* **Data Cleaning:** Handling missing values in `city`, `win_by_runs`, and `player_of_match` to ensure accuracy.

## 🚀 How to Use
1.  **Clone the Repo:**
    ```bash
    git clone [https://github.com/yourusername/ipl-analysis.git](https://github.com/yourusername/ipl-analysis.git)
    ```
2.  **Install Requirements:**
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```
3.  **Run the Notebook:**
    Launch Jupyter and open `IPL_analysis1.ipynb`.

---
*Analysis performed as part of an Exploratory Data Analysis portfolio.*
