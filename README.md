# Football Match Prediction Using Poisson Distribution

This project builds a simple probabilistic model to estimate football match outcomes using the Poisson distribution.

The model uses historical Premier League 2022/23 match data to estimate expected goals for both teams and calculate probabilities for:

- Home win
- Draw
- Away win
- Possible scorelines
- Fair odds
- Potential value bets

## Dataset

The data comes from Football-Data.co.uk and includes Premier League 2022/23 match results.

The model uses the following columns:

- Home team
- Away team
- Full-time home goals
- Full-time away goals

## Methodology

The model calculates:

1. League average home goals
2. League average away goals
3. Home team attacking strength
4. Home team defensive factor
5. Away team attacking strength
6. Away team defensive factor
7. Expected goals for each team
8. Scoreline probabilities using the Poisson distribution
9. Match outcome probabilities
10. Fair odds and expected value

## Important Note

This is not a machine learning model.

It is a simple statistical model based on historical goal averages and the Poisson distribution.

It does not include:

- Injuries
- Lineups
- Recent form
- Real xG data
- Tactical context
- Market movement
- Player-level data

## Example Match

The notebook analyzes:

Liverpool vs Aston Villa

The model estimates expected goals for both teams and calculates the probabilities of home win, draw and away win.

## Technologies Used

- Python
- pandas
- numpy
- Jupyter Notebook