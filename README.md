Bayesian Neural Networks for Uncertainty-Aware Regression

This repository contains the full code, figures, and tutorial associated with the assignment "Bayesian Neural Networks for Uncertainty-Aware Regression".
The project demonstrates how Bayesian neural networks (BNNs) quantify uncertainty, how they differ from deterministic neural networks, and how concepts such as aleatoric and epistemic uncertainty arise in practice.

## Repository Structure
├── notebooks/
│   └── Nikhil_ML_Code.ipynb   # Full Jupyter Notebook (all code + plots)
│
├── figures/                               # Auto-generated figures
│   ├── predictive_comparison.png
│   ├── uncertainty_decomposition.png
│   ├── region_uncertainty.png
│   └── reliability_diagram.png
│
├── tutorial.pdf                           # Final report / tutorial
├── LICENSE                                # MIT License
└── README.md                              # Project documentation

Project Overview

This project compares:

A deterministic neural network trained with MSE

A Bayesian neural network using Monte Carlo dropout

We evaluate both models on a synthetic 1D regression dataset with heteroscedastic noise and analyse:

Predictive means

Aleatoric & epistemic uncertainty

Regional uncertainty (low-noise vs high-noise areas)

Calibration via reliability diagram

The goal is to illustrate why Bayesian methods provide more trustworthy and interpretable predictions.

How to Run the Notebook

Clone the repository:

git clone https://github.com/nikhil182007/ML-Assignment.git



Install requirements:

pip install -r requirements.txt

Run the Jupyter notebook:

jupyter notebook notebooks/bnn_uncertainty_regression.ipynb

All figures will be generated automatically when the notebook is executed.

Dataset Description

The notebook generates a synthetic 1D regression dataset with variable noise levels.
This allows clear demonstration of:

Aleatoric uncertainty (noise-driven)

Epistemic uncertainty (data sparsity-driven)

No external datasets are required.

Accessibility Notes

Plots use colour-blind-safe palettes.

All images include alt text describing visual content.

High-contrast line and fill colours improve readability.

Document headings follow a clear hierarchical structure for screen readers.

License

This project is released under the MIT License.
