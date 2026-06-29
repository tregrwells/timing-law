# Timing Law Analysis - Wells (2026)

This repository contains the complete analysis code for the paper:

> **"The Inverse Relationship Between Target Duration and Subjective Time Dilation: A Large-Scale Behavioral Study"**  
> *Treg R. Wells (2026)*

## Overview

This analysis reproduces all figures and statistics from the paper, including:
- Subject-level correlation analysis (94.1% negative correlation).
- Group-level sigmoid fitting.
- Model comparison (Linear, Quadratic, Power, Sigmoid) with AIC/BIC.
- Individual-level fit quality (R² distribution).
- Cross-validation.

## Data Source

The data is from the **Timing Database** (OSF.io/vrwjz). The specific CSV used is included in this repository for reproducibility.

## How to Run

Click the badge below to open the analysis notebook directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tregrwells/timing-law/blob/main/Timing_Law_Analysis.ipynb)

Alternatively, you can download the notebook and run it locally.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21043192.svg)](https://doi.org/10.5281/zenodo.21043192)

## Requirements

- Python 3.8+
- Libraries: pandas, numpy, matplotlib, scipy, seaborn, scikit-learn

Install dependencies via:
```bash
pip install -r requirements.txt
