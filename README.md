# LSTM River Water Level Prediction Direct vs Recursive with/without Forecast Rainfall
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
- `Direct prediction_clear.ipynb`  
  Direct prediction (DP): multi-step prediction for a fixed lead time using observed rainfall inputs.

- `Direct prediction with forecast rain_clear.ipynb`  
  DP using forecasted rainfall as inputs.

- `Recursive prediction_clear.ipynb`  
  Recursive prediction (RP): multi-horizon (e.g., up to 24 h) prediction by feeding model outputs back as inputs, using observed/past rainfall.

- `Recursive prediction with forecast rain_clear.ipynb`  
  RP using forecasted rainfall as inputs.

### Data
- `고수위_이벤트_데이터.xlsx`  
  Event-based rainfall and water-level data used for the confluence case study (Events #8 and #9).

---

### Reproducibility notes

- Results may vary slightly depending on random seeds, hardware (CPU/GPU), and library versions.

- Please follow the same event split and lead-time settings described in the notebooks to reproduce the paper experiments.

- To reduce run-to-run variation, fix random seeds and, if needed, enable deterministic operations in the deep-learning framework. However, exact bitwise reproducibility is not always guaranteed across different hardware/software environments.

---
