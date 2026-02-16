# Time Series Forecasting with Transformer Architectures

## Overview

Questo progetto implementa e confronta modelli di previsione per serie temporali,
includendo baseline statistiche classiche e architetture Transformer moderne.

L’obiettivo è analizzare le performance di modelli deep learning rispetto a metodi
tradizionali su un dataset reale, utilizzando metriche standard e validazione rolling-window.

---

## Project Structure

notebooks/

01_Python_exercises.ipynb  
02_EDA_timeseries.ipynb  
03_Literature_review.ipynb  
04_Case_study_definition.ipynb  
05_Baselines.ipynb  
06_Transformers_library_overview.ipynb  
07_Informer_train.ipynb  
08_Variant_comparison.ipynb  
09_Evaluation.ipynb  
10_Ablation.ipynb  

src/  
data/  
checkpoints/

---

## Methodology

Il progetto segue le seguenti fasi:

1. EDA e analisi proprietà della serie temporale
2. Definizione caso di studio e metriche
3. Implementazione baseline classiche (ARIMA, ETS, Prophet)
4. Studio API HuggingFace Transformers
5. Implementazione Informer
6. Confronto con PatchTST / variante LLM-style
7. Valutazione estesa (Hold-out, Backtesting, Diebold-Mariano)
8. Analisi di ablation e sensitivity

---

## Evaluation Metrics

- MAE
- RMSE
- MAPE
- sMAPE

---

## Validation Strategy

- Train/Validation/Test split temporale
- Rolling-window validation
- Hold-out finale
- Diebold-Mariano test per confronto statistico

---

## Reproducibility

- Random seed fissato
- Scaling solo su training set
- Metriche calcolate in modo consistente
- Confronti effettuati sullo stesso split

---

## Requirements

Python 3.10+

Librerie principali:

- numpy
- pandas
- matplotlib
- scipy
- statsmodels
- prophet
- torch
- pytorch-lightning (se usato)
- transformers
- scikit-learn

---

## Note

I notebook contengono sezioni markdown esplicative per garantire
chiarezza metodologica e tracciabilità sperimentale.

