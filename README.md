# Global AI Workforce Displacement EDA (2020–2026)

## Project Overview

This project uses Exploratory Data Analysis (EDA) to examine patterns in global AI-related workforce displacement from 2020 to 2026. It explores workforce displacement, new roles created, AI adoption, automation risk, net workforce change, and differences across countries, regions, industry sectors, and income groups.

> **Important data note:** The dataset's `data_source_notes` field identifies it as research-calibrated synthetic data. The analysis describes patterns within this dataset and must not be presented as verified measurements of real-world workforce displacement or as evidence of causal relationships.

## Dataset

- **File:** `ai_workforce_displacement_global_2020_2026.csv`
- **Period covered:** 2020–2026
- **Scope:** Global records with country, region, income-group, and industry-sector information.
- **Data type:** Research-calibrated synthetic data, according to the dataset notes.

Place the CSV file in the `Dataset/` folder. In the notebook, use a project-relative path such as:

```python
df = pd.read_csv("../Dataset/ai_workforce_displacement_global_2020_2026.csv")
```

Adjust the relative path if your notebook is stored in a different folder.

## Analysis Performed

- Dataset loading and initial inspection
- Data cleaning, duplicate checks, and data-type review
- Missing-value checks and handling
- Categorical-value and numeric-range inspection
- Descriptive statistics and percentile analysis
- Workforce displacement comparisons by country, region, and industry
- AI adoption and automation-risk comparisons
- Net workforce change and new-role creation analysis
- Distribution and relationship visualizations
- IQR-based outlier analysis
- Suggestions and recommendations based on observed dataset patterns

## Tools and Libraries

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Project Structure

```text
AI-Workforce-Displacement-EDA/
├── Dataset/
│   └── ai_workforce_displacement_global_2020_2026.csv
├── Notebook/
│   └── ai_workforce_displacement_eda_project.ipynb
├── README.md
└── requirements.txt
```

## How to Run

1. Clone or download this repository.
2. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

3. Place the dataset in the `Dataset/` folder.
4. Open the notebook in Jupyter Notebook, JupyterLab, or a compatible IDE.
5. Update the CSV path in the dataset-loading cell if your folder structure differs.
6. Run the notebook cells in order.

## Interpretation and Limitations

The dataset is identified as synthetic in its `data_source_notes` field. Therefore:
- Findings are descriptive patterns in the supplied dataset only.
- They should not be treated as official global statistics.
- Correlations or group differences do not establish causation.
- Recommendations are exploratory and would require validation with reliable real-world data before policy or business decisions.

## Author

**Gautham Krishna S**
