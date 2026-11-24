# LuxStay Hotel Revenue Analysis

An individual coursework project using Python and Excel to analyse factors associated with monthly hotel revenue.

Developed for Business Analytics at Universiti Tunku Abdul Rahman (UTAR).

## Project Objective

Explore hotel operating data, address data quality issues and develop a multiple linear regression model to examine factors related to monthly revenue.

## Technologies

- Python
- Pandas and NumPy
- Statsmodels
- OpenPyXL
- Microsoft Excel
- Jupyter Notebook

## Files

| File | Contents |
| --- | --- |
| `hotel_revenue_analysis.ipynb` | Python data preparation, regression analysis and model selection |
| `hotel_revenue_data.xlsx` | Coursework dataset and Excel analysis worksheets |

## Dataset

The hotel dataset contains 150 observations, 10 candidate predictors and one target variable, `Monthly_Revenue_RM`.

Predictors include occupancy rate, average room rate, bookings, marketing expenditure and other hotel operating measures.

## Analysis Process

1. Checked for missing values.
2. Used Z-scores to identify observations with extreme predictor values.
3. Removed six observations, leaving 144 for regression analysis.
4. Fitted a multiple linear regression model and examined statistical significance.
5. Investigated multicollinearity using correlations and variance inflation factors.
6. Compared models and applied backward elimination at a significance level of 0.01.

## Coursework Findings

- No missing values were found in the dataset.
- Occupancy rate and average room rate were retained in the final model.
- The final model had an adjusted R-squared of approximately 0.133, indicating limited explanatory power.

These findings describe associations within the coursework dataset.

## My Work

I completed the data checks, outlier analysis, regression modelling, model selection and interpretation independently, using Python and Excel.

## How to Run

1. Download or clone this repository.
2. Keep the notebook and Excel workbook in the same folder.
3. Install the required packages:

```bash
python -m pip install jupyter pandas numpy statsmodels openpyxl
```

4. Open a terminal in the project folder and start Jupyter:

```bash
jupyter notebook
```

5. Open `hotel_revenue_analysis.ipynb` and run the cells from top to bottom.

## Project Context

The dataset and analysis were used for an academic assignment. The notebook documents the methods used in the submitted coursework.
