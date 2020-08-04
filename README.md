# Predicting Bitcoin Prices With LSTM Neural Nets
## Project Summary & Notes:
**Data Source** - https://alternative.me/crypto/fear-and-greed-index/ (CSVs contained in this repo)

**Purpose:**
To compare the predictive power of FNG Sentiment against historical closing price data
* Repo contents: 
* 1. Methodology
* 2. LSTM Sentiment Model
* 3. LSTM Closing Model
* 4. Summary Assessment

### Methodology:
* Baseline comparison performed using the following parameters:
* Train/test split: 70/30
* Scaler: MinMax
**LSTM RNN Parameters:**
* See notebooks

### LSTM Sentiment Model:
* Loss: .0226
* Actuals v Predicted: Considerably Less Variance (see notebook for visual over time)
* Window Size: 10

### LSTM Closing Model:
* Loss: .0445
* Actuals v Predicted: Significant Variance (see notebook for visual over time)
* Window Size: 10

### Summary Assessment:
* Sentiment data substantially outperformed that of closing prices