
# 🏏 IPL Data Analytics Project — Web Scraping, Python, Pandas & Power BI

## 📘 Overview
This project, **“Cricket Data Analysis Using Web Scraping, Python, Pandas & Power BI,”** explores the dynamic world of IPL cricket through the lens of data analytics.  
It demonstrates how data science techniques can be applied to extract, clean, analyze, and visualize real-world cricket data to uncover insights into player performance, team strategy, and match outcomes.

---

## 🎯 Objectives
- Automate data collection from cricket websites using **web scraping**  
- Process and clean datasets using **Python (Pandas, NumPy)**  
- Perform **Exploratory Data Analysis (EDA)** to reveal patterns and correlations  
- Build **interactive dashboards** in **Power BI** for visual storytelling  
- Identify the **best playing XI** based on IPL player statistics  

---

## 🧩 Project Workflow
```

1️⃣ Data Collection → Web Scraping (BeautifulSoup, Selenium)
2️⃣ Data Cleaning → Python & Pandas
3️⃣ EDA → Matplotlib & Seaborn Visuals
4️⃣ Dashboarding → Power BI (Interactive Reports)
5️⃣ Insight Generation → Player & Team Performance Metrics

````

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
````

---

## 💡 Key Insights

### 🏆 Top Performers:

* **Batsmen:** Virat Kohli, KL Rahul, David Warner
* **Bowlers:** Jasprit Bumrah, Kagiso Rabada, Yuzvendra Chahal
* **All-Rounders:** Andre Russell, Hardik Pandya, Sunil Narine
* **Wicket Keeper:** MS Dhoni

### 📈 Team Dominance:

* Mumbai Indians (131 wins)
* Chennai Super Kings (121)
* Kolkata Knight Riders (114)

### 🎯 Match Dynamics:

* 32.5% wins by runs, 44.5% by wickets
* Toss decisions significantly influence match results

---

## 📉 Power BI Dashboard

An **interactive Power BI dashboard** visualizes IPL data with:

* 🏆 Title winners across seasons
* 🧢 Orange & Purple Cap holders
* 💥 Sixes & Fours distribution
* 🎲 Toss decision vs. match result
* 🏟️ Venue-based winning trends

📂 **Dashboard Location:** `PowerBI_Dashboard/IPL_Analysis.pbix`

---

## 🏅 Best Playing XI (Based on Data Insights)

| Role              | Players                                                              |
| ----------------- | -------------------------------------------------------------------- |
| **Batters**       | KL Rahul, Virat Kohli, David Warner                                  |
| **All-Rounders**  | Andre Russell, Sunil Narine, Hardik Pandya                           |
| **Bowlers**       | Jasprit Bumrah, Kagiso Rabada, Yuzvendra Chahal, Nathan Coulter-Nile |
| **Wicket Keeper** | MS Dhoni                                                             |

---

## 📁 Repository Structure

```
IPL_Data_Analytics/
│
├── README.md
├── IPLData.csv
├── Python_EDA/
│   ├── EDA_Code.ipynb
│   └── EDA_Charts/
│       ├── top_batters.png
│       ├── top_bowlers.png
│       └── top_allrounders.png
├── PowerBI_Dashboard/
│   └── IPL_Analysis.pbix
└── FINAL_REPORT/
    └── FINAL REPORT- IPL DATA ANALYTICS.pdf
```

---

## ⚙️ How to Run

### 🔧 Prerequisites

* Python 3.8+
* Power BI Desktop
* Jupyter Notebook or VS Code

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn beautifulsoup4 selenium
```

### ▶️ Steps

1. Clone the repository

   ```bash
   git clone https://github.com/<your-username>/IPL_Data_Analytics.git
   cd IPL_Data_Analytics
   ```
2. Run the Python EDA script

   ```bash
   jupyter notebook Python_EDA/EDA_Code.ipynb
   ```
3. Open Power BI Dashboard

   ```
   PowerBI_Dashboard/IPL_Analysis.pbix
   ```

---

## ✅ Results

* Automated IPL data extraction using web scraping
* Clean and structured datasets using Pandas
* Insightful EDA and visualizations
* Interactive Power BI dashboard with actionable cricket insights

---

## 🚀 Future Scope

* Integrate **live IPL APIs** for real-time updates
* Develop **predictive models** for player and match performance
* Publish dashboards via **Power BI Cloud Service**

---

## 👩‍💻 Author

**Monalika Ghosh**
*M.Sc. Data Analytics | SRM Institute of Science and Technology*
📧 [ghoshmonalika290@gmail.com](mailto:ghoshmonalika290@gmail.com)

---

## 📚 References

* [Python Documentation](https://www.python.org/)
* [Pandas Library](https://pandas.pydata.org/)
* [Power BI](https://powerbi.microsoft.com/)
* [ESPN Cricinfo (Data Source)](https://www.espncricinfo.com/)

---

⭐ *If you found this project insightful, please give it a star on GitHub!*

```

```

