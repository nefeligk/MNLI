# MNLI
MNLI task (7 different variants of SGD)
We split the dataset into five different splits maintaining the class distribution, so as to estimate the generalization performance of each optimizer.
For each optimizer we ran 30 trials of different combinations of hyperparameter values selected by the optuna framework.
We trained the models with the optimizers with the tuned hyperparameter values and for comparison we trained optimizers with default hyperparameter values, as well.
