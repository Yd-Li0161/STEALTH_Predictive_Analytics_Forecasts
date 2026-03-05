# STEALTH Predictive Analytics Forecasts

A forecasting project for **Tesla (TSLA)**, **Google (GOOGL)**, **Bitcoin (BTC-USD)**, and **Ethereum (ETH-USD)** across multiple time horizons.

## Project Overview

This repository focuses on an end-to-end notebook workflow:

- Data collection from Yahoo Finance
- Feature engineering (technical indicators, volatility, lag features, macro & cross-asset signals)
- Modeling (SARIMAX, GBM, Random Forest, and optional LSTM section)
- Evaluation (point errors + interval quality)
- Forecast outputs for 30D, 3M, 6M, 1Y, 3Y, 5Y, 10Y

## Repository Structure

```text
.
├── README.md
├── LICENSE
├── .gitignore
├── requirements.txt
├── requirements-optional.txt
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
├── TASK_1000_—_Predictive_Analytics_Forecasts.ipynb
├── STEALTH_Predictive_Analytics_Forecasts.pdf
├── STEALTH_Predictive_Analytics_Forecasts.pptx
└── .github/
    ├── pull_request_template.md
    ├── ISSUE_TEMPLATE/
    │   ├── bug_report.md
    │   └── feature_request.md
    └── workflows/
        └── ci.yml
```

## Quick Start

### 1) Clone

```bash
git clone <your-repo-url>
cd STEALTH_Predictive_Analytics_Forecasts
```

### 2) Create environment

```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
```

### 3) Install dependencies

Core dependencies:

```bash
pip install -r requirements.txt
```

Optional (for LSTM cells):

```bash
pip install -r requirements-optional.txt
```

### 4) Run notebook

```bash
jupyter notebook TASK_1000_—_Predictive_Analytics_Forecasts.ipynb
```

## Current Gaps / Notes

- The notebook includes an LSTM section that requires TensorFlow. If TensorFlow is not installed, only non-LSTM sections should be run.
- Data comes from Yahoo Finance and may vary by run date, which can affect reproduced metrics.
- For cleaner PRs, clear heavy notebook outputs before committing unless output diffs are required.

## Main Deliverables

- `TASK_1000_—_Predictive_Analytics_Forecasts.ipynb`: full workflow.
- `STEALTH_Predictive_Analytics_Forecasts.pdf`: report-style output.
- `STEALTH_Predictive_Analytics_Forecasts.pptx`: presentation slides.

## License

This project is released under the MIT License. See [LICENSE](LICENSE).
