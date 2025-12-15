# Brownian Motion: Physics → Finance

Random walks → diffusion (Fick’s law) → GBM option pricing → empirical return comparison.

## What this project does
This project connects stochastic processes to real modeling tasks:
- **Physics:** shows how random walks lead to diffusion and relates to **Fick’s law**
- **Finance:** simulates **GBM** and prices European options via **Monte Carlo**, validated against **Black–Scholes**
- **Empirics:** compares **real asset return behavior** to GBM assumptions (distribution + volatility behavior)

## Contents
- `notebooks/<YOUR_NOTEBOOK>.ipynb` — main notebook (derivations, simulations, plots)

## Key results (add plots)
- Diffusion / Fick’s law: model vs theory/fit
- MC option pricing vs Black–Scholes: pricing error across strikes/maturities and/or convergence vs number of paths
- Empirical vs GBM returns: histogram/QQ + rolling volatility / volatility clustering

## How to run
```bash
pip install -r requirements.txt
jupyter notebook
