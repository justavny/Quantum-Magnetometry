# Quantum Magnetometry Using Machine Learning

A simulation-based project exploring the application of classical machine learning to quantum magnetometry using Ramsey interferometry.

## Project Overview

The project simulates a Ramsey quantum sensor to study magnetic-field-dependent phase accumulation and decoherence. A Random Forest regression model is then trained to estimate unknown magnetic fields from simulated measurement outcomes.

## Methodology

- Modelled Ramsey interferometry and magnetic-field-dependent phase accumulation.
- Simulated quantum measurement outcomes with finite-shot statistics and decoherence.
- Generated a dataset for magnetic-field estimation.
- Implemented a Random Forest regression model.
- Compared machine-learning predictions with a Bayesian estimation approach.
- Studied the effects of measurement shots and coherence time on estimation accuracy.

## Repository Structure

```text
quantum-magnetometry-ml/
├── notebooks/
│   ├── 01_Ramsey_Quantum_Sensor.ipynb
│   ├── 02_Magnetic_Field_Dataset.ipynb
│   ├── 03_Random_Forest_Estimator.ipynb
│   ├── 04_Bayesian_vs_ML.ipynb
│   └── 05_Noise_and_Performance_Analysis.ipynb
├── data/
├── results/
└── README.md
```

## Technologies

Python, NumPy, Pandas, Matplotlib, Scikit-learn and Jupyter Notebook.

## Objective

To investigate how machine learning and statistical inference can be used to extract magnetic-field information from quantum measurement data.

*Note: This project uses simulated data and does not represent measurements from a physical quantum sensor.*
