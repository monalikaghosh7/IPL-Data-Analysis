# 🏏 IPL Data Analytics Project — Web Scraping, Python, Pandas & Power BI

### 📘 Overview
This project, **“Cricket Data Analysis Using Web Scraping, Python, Pandas & Power BI,”** explores the dynamic world of IPL cricket through the lens of data analytics.  
It demonstrates how data science techniques can be applied to extract, clean, analyze, and visualize real-world cricket data to uncover insights into player performance, team strategy, and match outcomes.

---

## 🎯 Objectives
- Automate data collection from cricket websites using **web scraping**.
- Process and clean datasets using **Python (Pandas, NumPy)**.
- Perform **Exploratory Data Analysis (EDA)** to reveal patterns and correlations.
- Build **interactive dashboards** in **Power BI** for visual storytelling.
- Identify the **best playing XI** based on IPL player statistics.

---
1️⃣ Data Collection → Web Scraping (BeautifulSoup, Selenium)
2️⃣ Data Cleaning → Python & Pandas
3️⃣ EDA → Matplotlib & Seaborn Visuals
4️⃣ Dashboarding → Power BI (Interactive Reports)
5️⃣ Insight Generation → Player & Team Performance Metrics


---

## 🧠 Technologies Used
| Category | Tools / Libraries |
|-----------|------------------|
| Programming Language | Python 3.x |
| Data Analysis | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn |
| Business Intelligence | Microsoft Power BI |
| Web Scraping | BeautifulSoup, Selenium |
| Version Control | Git & GitHub |

---

## 📊 Exploratory Data Analysis (EDA)
EDA was conducted to understand:
- Batting & Bowling trends across IPL seasons  
- Strike rates, averages, and wicket-taking efficiencies  
- Player performance consistency  
- Comparative analysis of capped players across roles  

📂 **EDA Charts stored in:** `Python_EDA/EDA_Charts/`

Example visualization snippet:
```python
sns.barplot(x='Player Name', y='Strike_Rate', data=top_batters)
plt.title('Top Batters by Strike Rate')
💡 Key Insights
🏆 Top Performers:

Batsmen: Virat Kohli, KL Rahul, David Warner

Bowlers: Jasprit Bumrah, Kagiso Rabada, Yuzvendra Chahal

All-Rounders: Andre Russell, Hardik Pandya, Sunil Narine

Wicket Keeper: MS Dhoni

📈 Team Dominance:

Mumbai Indians (131 wins)

Chennai Super Kings (121)

Kolkata Knight Riders (114)

🎯 Match Dynamics:

32.5% wins by runs, 44.5% by wickets

Toss decisions significantly influence match results

📉 Power BI Dashboard

An interactive Power BI dashboard visualizes IPL data with:

🏆 Title winners across seasons

🧢 Orange & Purple Cap holders

💥 Sixes & Fours distribution

🎲 Toss decision vs. match result

🏟️ Venue-based winning trends

📂 Dashboard Location: PowerBI_Dashboard/IPL_Analysis.pbix
