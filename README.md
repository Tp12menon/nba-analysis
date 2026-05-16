# 🏀 NBA Player Analysis Portfolio (2005–2014)
 
A collection of data analysis projects exploring the performance, salary, and playing styles of 10 elite NBA players across 10 seasons using **R** and **Python**.
 
---
 
## 📁 Project Structure
 
| # | Project | Language | Key Topics |
|---|---------|----------|------------|
| 01 | [Player Efficiency Analysis](./01-player-efficiency/) | R | Points per minute, FG%, efficiency trends |
| 02 | [Salary vs Performance](./02-salary-vs-performance/) | R | Value contracts, correlation analysis |
| 03 | [Career Trajectory](./03-career-trajectory/) | Python | Career arcs, peak seasons, injury impact |
| 04 | [Player Clustering](./04-player-clustering/) | Python | K-Means clustering, PCA, playing styles |
 
---
 
## 📊 Dataset
 
10 NBA players tracked across 10 seasons (2005–2014):
 
**Players:** Kobe Bryant, LeBron James, Kevin Durant, Dwyane Wade, Carmelo Anthony, Chris Paul, Dwight Howard, Derrick Rose, Chris Bosh, Joe Johnson
 
**Metrics:** Points, Salary, Games Played, Minutes Played, Field Goals, Field Goal Attempts
 
> Data source: [SuperDataScience](https://www.superdatascience.com) — publicly available NBA statistics
 
---
 
## 🛠️ Tools & Libraries
 
**R:** `tidyverse` `ggplot2` `dplyr` `knitr`
 
**Python:** `pandas` `matplotlib` `seaborn` `scikit-learn`
 
---
 
## 🔍 Key Findings
 
- **LeBron James** was the most consistently efficient scorer across the decade
- **Kevin Durant** showed the steepest improvement trajectory from 2007 onwards
- **Derrick Rose** was automatically isolated into his own cluster by K-Means due to injury impact — showing the algorithm detected a real pattern
- Higher salary does **not** strongly correlate with more points scored
- Northern veteran players on rookie contracts deliver the best points-per-dollar value
---
 
## 🚀 How to Run
 
**R Projects:**
1. Clone the repo
2. Open `nba-analysis.Rproj` in RStudio
3. Run `data/basketball_data.R` to load the data
4. Knit any `.Rmd` file to generate the HTML report
**Python Projects:**
1. Install dependencies: `pip install pandas matplotlib seaborn scikit-learn`
2. Open any `.ipynb` file in VS Code or Jupyter Notebook
3. Run all cells top to bottom
---
 
*Built as part of a data analysis portfolio — 2024*