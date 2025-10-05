# Demand Prediction for Algorithmic & Dynamic Pricing

**Goal:** Forecast demand accurately and translate predictions into pricing decisions (revenue/profit tradeoffs).  
**Notebook analyzed:** `Demand_Prediction_for_Algorithmic_and_Dynamic_Pricing_Using_Principal_Components_and_Perceptrons (3).ipynb` (last processed 2025-10-05)

## TL;DR
- **Pipeline:** PCA → Perceptron (neural) model with standard feature engineering and evaluation.
- **Models detected in code:** Dense, Keras, PCA, Sequential, tf.keras
- **Metrics:** Metrics printed in the notebook; include exact values/screenshots in `/reports/figures`.

## Notebook Outline (auto-extracted)
- # Demand Prediction for Algorithmic and Dynamic Pricing Using Principal Components and Perceptrons
- ## Takeaways
- ## Concepts I Explored
- # Introduction to Dynamic and Algorithmic Pricing Strategies
- ## Dynamic Pricing vs. Personalized Pricing
- ## How Dynamic Pricing Affects a Business Model
- ## Demand Forecasting as the Core
- ## Sales as a Proxy for True Demand
- ### Estimating True Demand
- # Walmart Sales Data Project
- ## Why Departments?
- ## Formal Problem
- ## Training and Loss
- ## Challenge: Holiday Events
- ## 1. Datasets
- #### Dataset: features.csv
- #### Contents
- #### Holiday Weeks in the Data
- ### Dataset: stores.csv
- #### Contents
- …

## Methods (matched to your notebook)
- **Data checks & leakage control** (time ordering, splits)
- **Feature engineering:** calendar features, lags/rolling stats, promo/price flags (adapt details to your actual cells)
- **Dimensionality reduction: PCA** for stability and speed.
- **Neural model (Perceptron/MLP or Keras Sequential)** for nonlinearity.
- **Time-series cross-validation** (sliding/expanding window)
- **Uncertainty / intervals** (if present in notebook)

## Results
- Summarize **MAPE / RMSE / R²** from your evaluation cells.
- Add 2–3 key visuals (forecast vs. actuals, residuals, price-response curve).

## Business Link
- Convert demand forecasts into **price → demand → revenue** simulations.
- Show guardrails (inventory, margin floors, capacity) and sensitivity to elasticity.
- Provide a one-paragraph “decision playbook” (when to raise/lower prices).

## Repo Structure
```
data/              # sample/synthetic (no PII)
notebooks/         # the notebook above + stripped versions for reading
src/               # data.py, features.py, model.py, metrics.py
reports/           # figures + one_pager.pdf
```

## How to Run
```bash
python -m venv .venv && source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter lab
```

## Next Steps
- Add segment- or product-level models.
- Estimate price elasticity with controls; validate with backtesting.
- Add prediction intervals to drive risk-aware pricing.
