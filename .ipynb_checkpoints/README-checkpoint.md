# Assignment14-LSTM

## This repo contains the LSTM stock predictor homework for week 14.

## This exercise included nuilding a LSTM model and deducing data from it using 'summary' and 'evaluate' function. Analysis of the loss performance and the comparison of real vs predicted values is also included.

## The libraries required include numpy, pandas, hvplot, sklearn, tensorflow, and matplotlib.

### The Closing Prices RNN model has the lower loss compared to the FNG RNN model at 0.0502 vs 0.1183 with a 10-day window.

### Similarly to the loss metric, closing prices RNN model also tracks the actual values better over time as observed from their plots of actual vs predicted values.

### Loss of 0.0502 with 10-day window.
### Loss of 0.1039 with 1-day window.
### Loss of 0.0340 with 5-day window.
### Loss of 0.0290 with 4-day window.
### Loss of 0.0244 with 3-day window.
### Loss of 0.0231 with 2-day window.

### Interestingly, the window size with the lowest loss for the closing prices RNN model is a 2-day window when compared between 1-10 day windows.

### The plots included also confirms that the 2-day window is more approriate than the default 10-day window.
### Not too sure why this is the case, rather complexing that the windows are not proportionate in results.

### As for experimenting with the batch size, 1 was the best as anything higher worsened the model.