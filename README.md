# CFPB Credit Card Complaint Dashboard

Analysis of 150,000+ real CFPB consumer complaints to monitor credit card complaint risk by issue type, issuer, and geography.

## Analyses
1. Monthly complaint volume by issue category
2. Top issuers: volume vs. timely response rate (90% CFPB threshold)
3. State heatmap — complaints per 100k population
4. Resolution quality breakdown by issuer

## Tools
Python · pandas · matplotlib · seaborn · plotly · Jupyter

## How to run
```bash
pip install pandas matplotlib seaborn plotly requests
jupyter notebook notebooks/cfpb_analysis.ipynb
```

Data downloads automatically on first run (~300 MB from CFPB).
