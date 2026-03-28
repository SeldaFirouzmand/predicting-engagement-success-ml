# Stage 2: Amplification vs Early Signals

## Overview
This stage compares the predictive power of early engagement signals and algorithmic amplification features.

## Objective
To evaluate whether algorithmic amplification adds predictive value beyond early user interactions.

## Key Findings
- The pre-only model achieved an R² of approximately 0.50.
- The amplification-only model achieved a significantly lower R² (~0.11).
- The combined model did not improve performance beyond the pre-only model.

## Interpretation
These results suggest that algorithmic amplification alone is a weak predictor of engagement success. Early engagement signals remain the dominant factor, and adding amplification features does not significantly improve model performance.

## Figures

### Model Comparison (R²)
![Stage 2 Comparison](./all_figures/7.png)

### Model Comparison (RMSE)
![Stage 2 RMSE](./all_figures/8.png)

### Combined Model Prediction
![Best Model](./all_figures/9.png)

### Combined Model Residuals
![Residuals](./all_figures/10.png)

### Feature Stability
![Feature Stability](./all_figures/11.png)
