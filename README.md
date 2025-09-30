# Sales Data Integration and Profiling Notebook

This project demonstrates a practical data engineering workflow using two complementary datasets:
a **synthetic sales dataset** generated for educational purposes and a **public 1000 Sales Records** dataset.
The notebook covers loading, profiling, cleaning, transformations, feature engineering, aggregation,
and documentation of unified field definitions to support downstream analytics or reporting.

### Quick Start

```bash
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r requirements.txt
jupyter notebook
```

### Data Sources

- **Synthetic Dataset**: `synthetic_sales.csv` (created programmatically in this repository)
- **Reference Dataset**: `1000 Sales Records.csv`  
  Source: [Excel BI Analytics – Sample CSV Files](https://excelbianalytics.com/wp/downloads-18-sample-csv-files-data-sets-for-testing-sales/)

### Contents

- **sales_analysis.ipynb**: End-to-end workflow for data cleaning, profiling, and feature engineering  
- **cleaned_sales.json**: Serialized cleaned data checkpoint

### Links to other projects in my GitHub

- [PROG-8431-workshop1](https://github.com/elopezcs/PROG-8431-workshop1.git)
- [Intro To Inference Workshop](https://github.com/elopezcs/IntroToInferenceWorkshop.git)
- [Predictive-Maintenance-Linear-Regression](https://github.com/elopezcs/predictive-maintenance-linear-regression.git)



