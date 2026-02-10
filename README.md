# LSTM-River-Water-Level-Prediction-Direct-vs-Recursive-with-without-Forecast-Rainfall
Effects of Forecasted Rainfall on Direct and Recursive LSTM‐Based River Water Level Predictions - Journal of Flood Risk Management

---

This repository provides the Jupyter notebooks and an example dataset used in the following paper:

**Ji, Y., Lim, Y., Kim, D., Sung, J., & Kang, B. (2025).**
*Effects of Forecasted Rainfall on Direct and Recursive LSTM-Based River Water Level Predictions.*
**Journal of Flood Risk Management, 18(4), e70147.**
doi:10.1111/jfr3.70147

---

## Contents

### Notebooks
- `notebooks/direct_prediction.ipynb`  
  Direct prediction (DP): multi-step prediction for a fixed lead time using observed rainfall inputs.

- `notebooks/direct_prediction_forecast_rain.ipynb`  
  DP using forecasted rainfall as inputs.

- `notebooks/recursive_prediction.ipynb`  
  Recursive prediction (RP): multi-horizon (e.g., up to 24 h) prediction by feeding model outputs back as inputs, using observed/past rainfall.

- `notebooks/recursive_prediction_forecast_rain.ipynb`  
  RP using forecasted rainfall as inputs.

### Data
- `고수위_이벤트_데이터.xlsx`  
  Event-based rainfall and water-level data used for the confluence case study (Events #8 and #9).

---
