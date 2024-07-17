# NeutralizeRisk
Feature Neutralization
One thing that makes predicting the stock market so hard is the "non-stationary" relationship between features and returns. Features can have strong predictive power some eras but not others - or may completely reverse over time.

This uncertainty is what we call "feature risk". In order to create models that have consistent performance, it is helpful to reduce this feature risk via "feature neutralization". In this notebook, we will:

Learn how to quantify feature risk
Measure our model's feature exposure
Apply feature neutralization to our predictions
Measure the performance of our neutralized predictions
Pickle and upload our feature-neutral model
