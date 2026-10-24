# Analytics Mini Projects

Small, reproducible exercises in SQL and Python using synthetic data.

| Project | Focus | Run |
| --- | --- | --- |
| [SQL Window Functions](sql-window-kpis/README.md) | LAG, cumulative revenue, month-over-month changes | `python3 sql-window-kpis/analyze.py` |
| [ETL Data Validation](etl-data-validation/README.md) | Duplicate detection, amount validation, reconciliation | `python3 etl-data-validation/analyze.py` |
| [Fraud Threshold Evaluation](fraud-threshold-evaluation/README.md) | Precision, recall and alert-volume trade-offs | `python3 fraud-threshold-evaluation/analyze.py` |

## Run locally

Requires Python 3. No third-party packages.

```bash
python3 sql-window-kpis/analyze.py
python3 etl-data-validation/analyze.py
python3 fraud-threshold-evaluation/analyze.py
```

The fraud evaluation uses `bank-fraud/transactions.csv`, a small synthetic dataset included in this repository. Chargeback is used as a proxy label, not confirmed fraud.

## Scope

These are compact technical exercises, not production systems or analyses of real customer data.
