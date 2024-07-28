# Model Card

## Model Description

**Input:** Race data from the 1983 Formula 1 season onwards, including information about the drivers, teams, and circuits, as well as the starting grid positions and race finish positions for each round of the championship.

**Output:** Predictions of the podium winners for each round of the championship.

**Model Architecture:** Support Vector Machine Classifier

## Performance

For the purpose of assessing performance, the F1 score was used as the primary metric, as it provides a balance between precision and recall. The model was evaluated using a 5-fold cross-validation strategy.

F1 score: 0.90
Weighted Avg. Precision: 0.90
Weighted Avg. Recall: 0.90

## Limitations

The model is intended to predict whether a driver will finish on the podium or not, rather than predicting the exact finishing position. This means that the model does not take into account the order of the podium finishers, only whether a driver will finish in the top 3 or not.

## Trade-offs

The model is sensitive to the driver performance features used as input. If the model is trained on data from a specific era of Formula 1, it may not perform as well on data from a different era, as the performance of drivers and teams can change over time.
