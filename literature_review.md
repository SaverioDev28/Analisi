# Literature Review – Transformer for Time Series Forecasting

## Introduction
Transformer-based models have recently become state-of-the-art for time series forecasting,
thanks to their ability to model long-term dependencies and complex temporal patterns.

## Paper Overview

### Informer
- Key idea: sparse attention
- Strength: long sequence efficiency
- Limitation: less effective on short sequences

### Autoformer
- Key idea: series decomposition
- Strength: explicit modeling of seasonality
- Limitation: assumes regular patterns

### PatchTST
- Key idea: patch-based tokenization
- Strength: noise reduction, strong performance
- Limitation: patch size sensitivity

### FEDformer
- Key idea: frequency-domain modeling
- Strength: complex seasonal patterns
- Limitation: higher model complexity

### TimesNet
- Key idea: 2D temporal modeling
- Strength: general-purpose
- Limitation: higher computational cost

## Summary
These models demonstrate the effectiveness of Transformer architectures for time series
forecasting, motivating their adoption in the proposed case study.