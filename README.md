# EAD-Bayesian-Sampling-Battery-Reliability
Supplementary materials for the paper: Bayesian Inference for the Exponentiated Ailamujia Distribution – Comparative Analysis of Advanced Sampling Algorithms with Applications to Electric Vehicle Battery Reliability. Includes code, NASA battery data processing, MCMC diagnostics, model comparisons, and held-out prediction results.
# Bayesian Inference for the Exponentiated Ailamujia Distribution

**Supplementary Materials**

This repository contains the complete code, processed data, numerical results, and graphical diagnostics accompanying the manuscript:

> **Bayesian Inference for the Exponentiated Ailamujia Distribution:  
> Comparative Analysis of Advanced Sampling Algorithms with Applications to Electric Vehicle Battery Reliability**

---

## Contents

| Folder / File | Description |
|---------------|-------------|
| `data/battery_cycle.xlsx` | Processed cycle-level NASA Li-ion Battery Aging data |
| `code/Final_Code.ipynb` | Complete analysis notebook (data loading → MCMC → model comparison → held-out prediction) |
| `results/real_data_output/` | Primary real-data numerical tables and figures |
| `results/reviewer_diagnostic_results/` | Extended diagnostics prepared in response to reviewer comments |
| `results/reviewer_diagnostics/` | Additional diagnostic plots and summaries |
| `results/simulation_output_smoketest/` | Synthetic-data validation and algorithm smoke tests |

---

## Key Features of the Analysis

- Shared log-posterior implementation for fair comparison of six sampling algorithms  
  (Metropolis–Hastings, Adaptive Metropolis, DE-MCMC, Replica-Exchange MCMC, AIES, Slice Sampling)
- Marginal distributional modelling of State-of-Health (SoH) using EAD, Weibull, log-normal and gamma
- Explicit 80% SoH end-of-life (EOL) threshold
- Chronological train/test splits with out-of-sample prediction metrics (MAE, RMSE, bias)
- WAIC / LOO-IC model comparison and posterior predictive checks
- Battery-by-battery analysis (B0005, B0006, B0007, B0018) to avoid pooling chemically distinct cells

---

## How to Reproduce

1. Clone the repository:
   ```bash
   git clone https://github.com/[YourUsername]/EAD-Bayesian-Sampling-Battery-Reliability.git
   cd EAD-Bayesian-Sampling-Battery-Reliability


Qasim Ramzan et al. (2026). Supplementary materials for Bayesian Inference for the Exponentiated Ailamujia Distribution. GitHub repository.
