# Exploratory Data Analysis & Statistical Insights

Internship-ready exploratory analysis of a Sample Superstore retail order-line dataset. The executed notebook audits/cleans the data, reports descriptive statistics, saves six visualizations, tests three business hypotheses, and produces five quantified findings with recommendations.

## Quick start
```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\\Scripts\\activate
pip install -r requirements.txt
jupyter notebook notebooks/Exploratory_Data_Analysis.ipynb
```

## Dataset
See [`data/README.md`](data/README.md) for provenance, column descriptions, data quality and redistribution caveat. Educational fictional/sample retail data, not actual company records. The notebook downloads the input into `data/cleaned_dataset.csv` on first run; it is intentionally not committed because redistribution terms are unclear.

## Contents
- `notebooks/Exploratory_Data_Analysis.ipynb` — executed analysis and inline graphics
- `visualizations/` — saved PNG charts
- `reports/EDA_Findings_Summary.md` — top-five evidence-backed takeaways
- `data/` — analysis dataset and provenance notes

Statistical tests use alpha 0.05; findings are exploratory and associational, not causal. More limitations are documented in the notebook.
