# Football Match Prediction Using Poisson Distribution

This project builds a simple probabilistic model to estimate football match outcomes using the Poisson distribution.

The model uses historical Premier League 2022/23 match data to estimate expected goals for both teams, calculate scoreline probabilities, match outcome probabilities, fair odds and compare them with market odds.

## Project Overview

The project combines Python analysis with a Power BI dashboard.

The Python notebook is responsible for:

- Loading and cleaning Premier League match data
- Calculating expected goals for the selected match
- Applying the Poisson distribution
- Estimating scoreline probabilities
- Calculating home win, draw and away win probabilities
- Comparing model probabilities with market odds
- Exporting final outputs as CSV files for Power BI

The Power BI dashboard visualizes:

- Expected goals by team
- Goal probability distribution
- Match outcome probabilities
- Most likely scorelines
- Model vs market odds comparison

## Example Match

The model analyzes:

**Liverpool vs Aston Villa**

The expected goals estimated by the model are:

| Team | Expected Goals |
|---|---:|
| Liverpool | 1.95 |
| Aston Villa | 0.70 |

## Methodology

The model calculates expected goals using:

1. League average home goals
2. League average away goals
3. Home team attacking strength
4. Home team defensive factor
5. Away team attacking strength
6. Away team defensive factor

After calculating expected goals, the Poisson distribution is used to estimate the probability of each team scoring 0, 1, 2, 3 or more goals.

The scoreline probabilities are then combined to estimate:

- Home win probability
- Draw probability
- Away win probability

## Power BI Dashboard

The Power BI dashboard was built using the CSV files exported from the Python notebook.

Dashboard file:

<<<<<<< HEAD
The notebook analyzes:

Liverpool vs Aston Villa

The model estimates expected goals for both teams and calculates the probabilities of home win, draw and away win.

## Technologies Used

- Python
- pandas
- numpy
- Jupyter Notebook

## Example Output

For the match Liverpool vs Aston Villa, the model estimates:

| Outcome | Probability | Fair Odd |
|---|---:|---:|
| Home Win | 66.7% | 1.50 |
| Draw | 20.7% | 4.83 |
| Away Win | 12.1% | 8.26 |
=======
```text
poisson_football_dashboard.pbix
>>>>>>> 24eff06 (update folders and add power bi dashboard)
