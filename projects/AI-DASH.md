# AI-DASH — Prediction-Informed Adaptive Dual-Mode Scheduling

**Status:** Manuscript submitted for peer review (2026); **not accepted or published**  
**Researcher:** Mysha Nishat Bidhu

## Research overview

AI-DASH extends the RT-DASH scheduling direction by using predictive workload information as an **advisory input** to the controller, while retaining deterministic high-criticality safeguards. The goal is to evaluate whether early warning of resource pressure can support better mode-entry decisions in variable smart-home workloads.

## Core approach

- ARIMA and multivariate LSTM workload forecasting
- Predictive resource-pressure signals for CPU, memory, storage and bandwidth
- Chronological evaluation and rolling-origin robustness checks
- Policy comparisons, forecasting ablations and fault-sensitivity analysis
- Mixed-criticality scheduling simulation and recovery-aware operation

## Research evaluation

The reported research workflow includes **4,043 held-out forecast examples**, **714 matched scheduler simulations**, **5,724 additional robustness simulations**, and **eight rolling-origin forecasting folds**. These describe the study's software-based experimental scope; they are not hardware performance or safety certification claims.

## Publication and reproducibility status

This is an overview of a **submitted manuscript**, not a peer-reviewed publication. The complete validated AI-DASH source code, configurations, trained artifacts and experiment archive **have not been uploaded to this public location**. No executable or independently verified reproduction package is claimed here.

The work builds on the [published RT-DASH study](https://doi.org/10.3390/a19100863).

[Return to academic website](https://mysha-nishat-bidhu.github.io/)
