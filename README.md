# 2026 NBA Finals Prediction
Predicting the 2026 NBA Finals between the San Antonio Spurs and New York Knicks using real data scraped from Basketball-Reference.

## What it does
- Scrapes team stats, playoff stats, and player impact data from Basketball-Reference
- Compares both teams across 21 different metrics
- Simulates the 7-game series 10,000 times with home court advantage
- Visualizes the results

## Data Sources
- [Basketball-Reference.com](https://www.basketball-reference.com)

## Stats Used
- Offensive & Defensive Rating
- Net Rating
- Pace
- Four Factors (eFG%, TOV%, ORB%, FT Rate)
- Playoff scoring, rebounding, assists, turnovers
- Player impact (BPM, VORP, PER)

## Result
Model predicts **SAS wins the Finals with 66.1% probability**

## Libraries
- requests
- beautifulsoup4
- pandas
- numpy
- matplotlib
- seaborn
