🏏 IPL Data Analysis (2008–2018)

An exploratory data analysis (EDA) project on **11 seasons of Indian Premier League (IPL)** cricket matches. This project uses Python to clean, analyze, and visualize match data to find interesting patterns and insights.

---

## 📁 Dataset

- **File:** `IPL_Dataset.xlsx`
- **Source:** IPL match records from 2008 to 2018
- **Total matches:** 696
- **Columns:** `id`, `city`, `Season`, `date`, `player_of_match`, `venue`, `team1`, `team2`, `toss_winner`, `toss_decision`, `result`, `winner`, `win_by_runs`, `win_by_wickets`, `umpire1`, `umpire2`

---

## 📊 Charts & What They Show

### 1. Matches Won by Team
A bar chart showing the total number of matches won by each team across all 11 seasons.

- **Mumbai Indians** are the most successful team with **98 wins**
- **Chennai Super Kings** come second with **90 wins**
- **Sunrisers Hyderabad** have the fewest wins (52) among top teams, as they joined IPL later

---

### 2. IPL Title Winners
A doughnut chart showing how many IPL championships each team has won.

- **Mumbai Indians** and **Chennai Super Kings** are joint leaders with **3 titles each**
- **Kolkata Knight Riders** won **2 titles**
- Rajasthan Royals, Deccan Chargers, and Sunrisers Hyderabad each won **1 title**

---

### 3. Toss Decision — Field vs Bat
A doughnut chart showing what captains choose to do after winning the toss.

- **59.3% of captains chose to field first** after winning the toss
- Only **40.7% chose to bat first**
- This shows most teams prefer chasing targets rather than setting them

---

### 4. Top 10 Man of the Match Players
A horizontal bar chart of the players who won the most Man of the Match (MoM) awards.

- **Chris Gayle (CH Gayle)** leads with **20 MoM awards**
- **AB de Villiers** is second with **18 awards**
- **Rohit Sharma (RG Sharma)** and **Yusuf Pathan (YK Pathan)** both have **16 awards**

---

### 5. Matches Per Season
A line chart showing how many matches were played in each IPL season.

- Match count grew from **58 in 2008** to a peak of **76 in 2013**
- The number dropped back to around **60** from 2014 onward
- This reflects team additions and format changes over the years

---

### 6. Top 8 Host Cities
A horizontal bar chart showing which cities hosted the most IPL matches.

- **Mumbai** hosted the most matches (**94**)
- **Kolkata**, **Delhi**, and **Bangalore** follow closely
- **Jaipur** is in the top 8 with **40 matches** hosted

---

## 🔍 Key Findings

| Insight | Finding |
|---|---|
| Most successful team | Mumbai Indians (98 wins) |
| Most titles | Mumbai Indians & CSK (3 each) |
| Toss advantage | Winning toss = winning match only 51.3% of time |
| Most popular toss choice | Field first (59.3%) |
| Top MoM player | Chris Gayle (20 awards) |
| Busiest host city | Mumbai (94 matches) |
| Most matches in a season | 76 (IPL 2013) |

---

## 🛠️ Tools & Technologies

- **Python** — main programming language
- **Pandas** — data loading and analysis
- **Matplotlib / Chart.js** — data visualization
- **Excel (.xlsx)** — data source format

---

## 🚀 How to Run

```bash
# 1. Clone the repo
git clone https://github.com/your-username/ipl-analysis.git
cd ipl-analysis

# 2. Install dependencies
pip install pandas openpyxl matplotlib

# 3. Run the analysis
python ipl_analysis.py
```

---

## 📌 Project Structure

```
ipl-analysis/
│
├── IPL_Dataset.xlsx       # Raw data file
├── ipl_analysis.py        # Main analysis script
├── charts/                # Saved chart images
└── README.md              # This file
```

---

## 💡 What I Learned

- How to load and explore Excel data using **Pandas**
- How to find patterns in sports data (wins, toss decisions, top players)
- How to create clear and meaningful charts from raw data
- How to summarize data into useful insights for others to understand

---# excel-reporting-suite
