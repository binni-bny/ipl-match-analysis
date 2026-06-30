\# IPL Match Analysis \& Win Predictor



\## Problem Statement

Analyze IPL match data (2008-2024) to understand what factors influence match outcomes, and build a model to predict match winners.



\## Dataset

IPL Complete Dataset (Kaggle) - 1,095 matches including teams, toss details, venue, and outcome.



\## Tools Used

Python, pandas, matplotlib, seaborn, scikit-learn, Jupyter Notebook



\## Approach

\- Cleaned match data and explored win patterns by team, toss decision, and season

\- Investigated whether winning the toss predicts winning the match

\- Encoded categorical features and trained a Random Forest classifier

\- Evaluated feature importance to see what actually drives match outcomes



\## Key Insights

\- Toss winners win the match only 50.8% of the time, almost exactly a coin flip

\- Venue was the strongest predictor of match outcome, more important than team identity

\- Model achieved 47.7% accuracy predicting the winner



\## How to Run

1\. Clone this repo

2\. Install requirements: python -m pip install pandas matplotlib seaborn scikit-learn jupyter notebook

3\. Open ipl\_analysis.ipynb in Jupyter Notebook

