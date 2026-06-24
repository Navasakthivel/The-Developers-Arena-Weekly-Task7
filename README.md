# Statistical Business Analysis — Sales Dataset

Hypothesis testing, correlation, and regression analysis on 2,000 order-level sales transactions.

## Folder Structure
```
statistical-business-analysis/
├── statistical_analysis.ipynb      # Full analysis notebook (Days 1-7, executed end-to-end)
├── statistical_report.pdf          # 8-page formatted business report
├── hypothesis_tests_results.txt    # Formatted output of all 5 hypothesis tests
├── requirements.txt                # Python dependencies
├── data/
│   └── sales_data.csv              # Source dataset (2,000 rows)
└── figures/
    └── *.png                       # 8 exported charts used in the notebook and report
```

## Status
All deliverables complete: descriptive statistics, distribution testing, correlation
analysis, 5 hypothesis tests, confidence intervals, regression analysis, and the
formatted PDF report are finished and validated.

## Note on Scope
The dataset is order-level transactional data (Price, Quantity, Discount, Revenue, Rating,
Category, Region, Customer Segment, Channel, dates) — it does not include a marketing spend
field. The correlation/regression analysis uses **Price, Quantity, and Discount as predictors
of Revenue** in place of the originally-referenced marketing-spend-vs-revenue relationship.

## Setup
```bash
pip install -r requirements.txt
jupyter notebook statistical_analysis.ipynb
```
