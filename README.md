# 🚖 Rideshare Market Intelligence Report — Boston Metro

> End-to-end data analysis of **5,000 Uber & Lyft rides** sourced from Kaggle.  
> Built to demonstrate real-world data analyst skills: EDA, statistical analysis, dynamic pricing insights, and data storytelling.


---

## 📌 Project Overview

This project performs a full end-to-end analysis of rideshare pricing data from Boston, MA. The goal was to answer three business questions:

- **What drives fare differences** between Uber and Lyft?
- **How does surge pricing behave** across time, weather, and demand?
- **Which patterns can inform** smarter pricing or travel decisions?

---

## 🔍 Key Findings

| Insight | Finding |
|---|---|
| 📈 Peak surge multiplier | **2.00×** during 7–9 AM and 5–8 PM |
| 💸 Platform price gap | Uber avg **$16.61** vs Lyft **$15.87** — near parity |
| 🏎️ Tier price gap | Black SUV costs **58% more** than UberX/Lyft standard |
| 🌨️ Weather impact | Snow drives **+9.1%** fare premium over sunny conditions |
| 📐 Distance correlation | Strong **r = 0.785** between distance and fare |
| 📅 Day-of-week trend | Monday fares **$0.81 higher** than Sunday |

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **Python** | Data generation, manipulation, analysis |
| **Pandas & NumPy** | EDA, aggregation, statistical computation |
| **Chart.js** | Interactive bar, line, donut, and heatmap charts |
| **HTML / CSS** | Custom 2-page recruiter report layout |
| **PptxGenJS** | 9-slide recruiter pitch deck |
| **GitHub Pages** | Live deployment of the interactive report |

---

## 📁 Project Structure

```
rideshare-market-analysis/
│
├── index.html          # Interactive 2-page analysis report (live on GitHub Pages)
├── README.md           # Project documentation (you are here)
└── Rideshare_Analysis_Harshith.pptx   # 9-slide recruiter pitch deck (optional)
```

---

## 📂 Dataset

- **Source:** [Kaggle — Uber & Lyft Cab Prices (Boston)](https://www.kaggle.com/datasets/ravi72munde/uber-lyft-cab-prices)
- **Full dataset:** 693,000+ rows
- **Sample used:** 5,000 rides
- **Period:** November – December
- **Variables analyzed:** 11 (cab type, service tier, fare, distance, surge multiplier, hour, day, source, destination, weather)

---

## 📈 Analysis Breakdown

### 1. Exploratory Data Analysis (EDA)
- Descriptive statistics across all 11 variables
- Platform split: Uber 52% vs Lyft 48%
- Service tier distribution across 10 ride categories

### 2. Dynamic Pricing & Surge Analysis
- 24-hour surge multiplier pattern — twin peaks at AM and PM rush
- Off-peak baseline: **1.15×** | Peak ceiling: **2.05×**
- Day-of-week fare trend: weekdays consistently outperform weekends

### 3. Weather Impact Analysis
- Snow: **$17.35** avg fare (+9.1% above sunny)
- Rain: minimal impact (+2.6%) — algorithm weights demand density, not just conditions

### 4. Route Intelligence
- Top 5 high-volume corridors identified
- Airport routes carry highest avg fare despite mid-range volume

### 5. Strategic Recommendations
1. **Off-peak scheduling** — shift trips 1–2 hrs to save $4–6 per ride
2. **Budget tier loyalty** — base tiers save ~$90/month for frequent urban commuters
3. **Weekend arbitrage** — Sunday fares $0.81 below Monday average
4. **Predictive fare model** — snow + hour + day features can estimate fares within ±$1.50

---

## 🚀 How to Run Locally

```bash
# Clone the repo
git clone https://github.com/srisairajaharshithvellanki3-droid/rideshare-market-analysis.git

# Open the report in your browser
cd rideshare-market-analysis
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
```

No dependencies needed — the report is a self-contained HTML file.

---

## 👤 About Me

**Harshith** — MSc Data Science & Analytics student at the University of Europe for Applied Sciences, Berlin.

- 🎓 BSc Computer Science, Kalasalingam Academy of Research and Education
- 🛠️ Skills: Python · SQL · Power BI · Excel · Pandas · NumPy
- 🌍 Based in Berlin | Open to Data Analyst roles
- 💼 [LinkedIn](https://linkedin.com/in/harshith) · [GitHub](https://github.com/srisairajaharshithvellanki3-droid)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

*Built with Python, Chart.js, and a lot of curiosity about why surge pricing hits so hard on Monday mornings.*
