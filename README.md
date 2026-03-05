# STEALTH Predictive Analytics Forecasts

A reproducible forecasting project for **Tesla (TSLA)**, **Google (GOOGL)**, **Bitcoin (BTC-USD)**, and **Ethereum (ETH-USD)** across multiple horizons.

## Project Overview

This repository contains a full end-to-end forecasting workflow implemented in the notebook:

- Data collection from Yahoo Finance
- Feature engineering (technical indicators, volatility, lags, macro and cross-asset signals)
- Multi-model forecasting (SARIMAX, GBM, Random Forest with backtesting support)
- Point forecast and interval evaluation
- Short-, medium-, and long-term forecast reporting (30D, 3M, 6M, 1Y, 3Y, 5Y, 10Y)

## Repository Structure

```text
.
├── README.md
├── LICENSE
├── .gitignore
├── requirements.txt
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
├── TASK_1000_—_Predictive_Analytics_Forecasts.ipynb
├── STEALTH_Predictive_Analytics_Forecasts.pdf
├── STEALTH_Predictive_Analytics_Forecasts.pptx
└── .github/
    ├── pull_request_template.md
    └── ISSUE_TEMPLATE/
        ├── bug_report.md
        └── feature_request.md
```

## Quick Start

### 1) Clone and enter the project

```bash
git clone <your-repo-url>
cd STEALTH_Predictive_Analytics_Forecasts
```

### 2) Create a virtual environment

```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
```

### 3) Install dependencies

```bash
pip install -r requirements.txt
```

### 4) Run the notebook

```bash
jupyter notebook TASK_1000_—_Predictive_Analytics_Forecasts.ipynb
```

## Main Deliverables

- **Notebook**: complete analysis and forecasting workflow.
- **PDF**: presentation/report version.
- **PPTX**: slide deck summary.

## Suggested GitHub Usage

- Use issues for bugs and feature ideas.
- Use pull requests for all code/documentation changes.
- Keep notebook outputs minimal when possible (clear heavy outputs before commit).

## License

This project is released under the MIT License. See [LICENSE](LICENSE).
