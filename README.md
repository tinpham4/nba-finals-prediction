# 🏀 2026 NBA Finals Prediction
Predicting the 2026 NBA Finals between the San Antonio Spurs and New York Knicks using real data scraped from Basketball-Reference.

## Result
Model correctly predicted the New York Knicks win the Finals 63.6% probability.

## What it does
- Scrapes team stats, playoff stats, and player impact data from Basketball-Reference
- Blends regular season and playoff metrics into a weighted win probability formula
- Simulates the 7-game series 10,000 times with home court and rest day advantage
- Visualizes the results

## Key Insight
Regular season stats alone pointed to SAS. Weighting playoff scoring and turnover data more heavily flipped the prediction to NYK — which turned out to be correct.

## Data Sources
- [Basketball-Reference.com](https://www.basketball-reference.com)

## Stats Used
- Offensive and Defensive Rating
- Net Rating
- Pace
- Four Factors (eFG%, TOV%, ORB%, FT Rate)
- Playoff scoring, rebounding, assists, turnovers
- Player impact (BPM, VORP, PER)
- Rest days between series and Finals

## Libraries
- requests
- beautifulsoup4
- pandas
- numpy
- matplotlib
- seaborn

## How to run
1. Install libraries: `pip install requests beautifulsoup4 pandas numpy matplotlib seaborn`
2. Open `NBA FINALS.ipynb` in Jupyter
3. Run all cells top to bottom
