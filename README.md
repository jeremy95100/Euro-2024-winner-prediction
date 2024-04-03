# Euro 2024 Predictor

This project aims to predict the winner of the Euro 2024 matches using the Poisson probability theory. The method relies on the assumption that the number of goals scored by each team in a football match can be modeled using a Poisson distribution.

## How It Works?

The prediction of a match winner is done by using Poisson probabilities to estimate the number of goals scored by each team. Then, by comparing the estimated goals scored by both teams, we determine the probability of each possible outcome (home team win, away team win, draw). Finally, the probability of a team winning is calculated based on the probabilities of each outcome.

## How to Use the Code?

1. Make sure you have Python installed on your system.
2. Clone this repository to your machine.
3. Install dependencies by running `pip install -r requirements.txt`.
4. Use the available data files to train the model or use your own data.
5. Run the main script to make predictions.


## Example Usage

```bash
python src/main.py

