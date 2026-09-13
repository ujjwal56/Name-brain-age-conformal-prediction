# Brain Age Conformal Prediction

Analysis code for Samanta et al., "Quantifying Uncertainty in Brain Age Predictions via Conformal Prediction" (2026).
Preprint: https://doi.org/10.64898/2026.09.04.749442

## Notebooks
- `Conformal_interferance__with_Functional___GV___CT.ipynb` — 
  Split, CV+, and CQR conformal prediction across functional, structural, 
  and multimodal feature sets. Produces Figure 2 and results.

- `with_pFactor.ipynb` — 
  100-split CV+ analysis for p-factor associations. Produces Figure 4 
  and coverage-vs-sample-size scatter (Figures 3B/3C).

- `parental.ipynb` — 
  100-split CV+ analysis for parental education associations. Produces 
  Figure 5. Includes BH correction and BAG-education 
  OLS comparison.

## Data
Data are publicly available from the Reproducible Brain Charts (RBC) project 
at https://reprobrainchart.github.io/. This repo does not include the raw data.

## Dependencies
Python 3.9, scikit-learn, xgboost, pandas, numpy, statsmodels, scipy, matplotlib, seaborn
