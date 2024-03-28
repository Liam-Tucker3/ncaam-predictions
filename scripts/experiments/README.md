# Experiments
This folder contains a number of notebooks with different experiments aimed at optimizing hyperparameters for different models or exploring the efficacy of models across slightly different sets of games. Once I determine an optimal set of hyperparameters, I'll train an optimal model in **/scripts/models**. I may only explore results to a limited extent here.

# Experiment List

| Title | Filename | Model Type | Description |
| :---:   | :---: | :---: | :---: |
| Regression Hyperparameter Optimization | fivethirtyeight-elo-ratings-regression-params.ipynb   | elo | This file determines the optimal values for three hyperparameters: K (learning rate), CONF_REGRESSION_FACTOR (how much a team's elo rating is regressed towards their conference's mean rating each year), and D1_REGRESSION_FACTOR (how much a team's elo rating is regressed towards the mean of all D1 basketball teams-- 1500-- each year). |