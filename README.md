# premier-league-round30-shot-analysis
A Python project analyzing Premier League Round 30 player shot data using SofaScore, including shots, goals, expected goals (xG), and finishing efficiency.
# Premier League Round 30 Shot Analysis

This project analyzes player shot performance in **Round 30 of the Premier League** using **SofaScore data**.

## Features

- Collects and processes shot data per player
- Calculates total **shots**, **goals**, **xG**, and **finishing efficiency**
- Identifies top performers and most active shooters
- Visualizes shot performance and efficiency

## Sample Output

| Player      | Shots | Goals | Total xG | Finishing Efficiency |
|------------|-------|-------|----------|--------------------|
| O’Reilly   | 4     | 0     | 0.62     | 0                  |
| Armstrong  | 3     | 1     | 0.47     | 2.11               |
| McNeil     | 3     | 0     | 0.34     | 0                  |
| Diarra     | 1     | 0     | 0.02     | 0                  |

## Requirements

- Python 3.x
- pandas
- requests or curl_cffi
- matplotlib / seaborn (optional for visualizations)

## How to Run

```bash
git clone https://github.com/<your-username>/premier-league-round30-shot-analysis.git
cd premier-league-round30-shot-analysis
python round30_analysis.py
