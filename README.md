# predicting-engagement-success-ml
Machine learning project that predicts social media engagement success using early persuasion signals, influencer authority, and algorithmic amplification in a two-stage framework.

## Project Overview
This project predicts social media engagement success using machine learning.

## Objective
To understand how early persuasion signals and algorithmic amplification influence engagement.

## Dataset
- Source: Dataset provided by Dr. Pouyan Eslami
- Size: 10,000 samples
- Description: Social media engagement data, including early persuasion signals and amplification features

## Methods
- Machine Learning models (e.g., Regression, Random Forest, etc.)
- Two-stage framework

## Results

### Key Findings

- Early persuasion signals are strong predictors of engagement success.
- The best-performing model (Ridge) achieved an R² of approximately 0.50.

### Person 1: Pre-visibility Prediction
- Early features (likes, comments, engagement velocity) explain about 50% of engagement variance.

### Person 2: Amplification vs Early Signals
- Pre-only model: R² ≈ 0.50  
- Amplification-only model: R² ≈ 0.11  
- Combined model: no significant improvement  

👉 This suggests that algorithmic amplification alone is a weak predictor.

### Person 3: Two-stage Mediation Analysis
- Pre-only model: R² ≈ 0.488  
- With mediator: R² ≈ 0.485  

👉 Adding algorithmic amplification as a mediator did not significantly improve prediction performance.

### Conclusion
Early persuasion signals play a dominant role in engagement success, while algorithmic amplification has limited additional predictive value.

### Note

👉 These findings highlight the primary importance of early user engagement signals over platform-driven amplification mechanisms.

## Authors
- Selda Firouzmand
- Zahra Gharehdaghi
- Nafiseh Rezaei
