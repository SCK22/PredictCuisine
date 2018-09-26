# PredictCuisine
## Kaggle link to the dataset - https://www.kaggle.com/c/whats-cooking

Predict the cuisine using the ingredients of a dish.

Approach:

Used context based embeddings and trained multiple models with varying number of LSTM cells, dense layers and number of nodes in the dense layers.

Results:

Achieved 72% recall on the test data upon submission in kaggle.
Most models had a validation recall of 70%, which is very close to the recall on the test data.

<src img = "img/tensorboard.PNG">
