# Compustat-Global-Financial
## Analysis of the Impact of Financial Factors on Revenue (TOTAL REVENUE)

### Project Description
This project aims to analyze the impact of independent variables such as research, EBITDA, and sector on the revenue (TOTAL REVENUE) of companies. The focus is to identify how these variables influence revenue and determine the percentage contribution of each factor to the growth or reduction in revenue.

The analysis will be based on financial data provided and will utilize statistical modeling techniques to answer the following question:

> For every dollar invested, how do research, EBITDA, and sector affect the revenue of companies?

### Objective
- Identify the main factors that increase or decrease TOTAL REVENUE.
- Quantify the percentage contribution of each independent variable to revenue.
- Provide insights based on specific sectors.

### Project Structure
The project will be structured as follows:

#### 1. Data Preparation
**Input:** Dataset containing the variables:
- `TOTAL_REVENUE` (dependent variable)
- `RESEARCH` (independent variable)
- `EBITDA` (independent variable)
- `SECTOR` (categorical variable)

**Data Processing:**
- Check for missing values and outliers.
- Transformation and normalization if necessary.
- Encoding of the categorical variable `SECTOR`.

#### 2. Methodology
**Statistical Modeling:**
- Multiple Linear Regression will be used to estimate the relationship between `TOTAL_REVENUE` and the independent variables.
- The model will consider the `SECTOR` variable as a dummy variable to analyze differences between sectors.

**Validation:**
- Model evaluation with metrics such as adjusted R², mean absolute error (MAE), and statistical significance of the coefficients.
- Application of multicollinearity tests (VIF) to ensure model robustness.

#### 3. Expected Results
Quantification of the percentage contribution of:
- Research in increasing/decreasing revenue.
- EBITDA as a proxy for operational profitability.
- Differences between sectors in terms of influence on revenue.

Clear visualizations to aid interpretation:
- Scatter plots.
- Bar graphs for sector-wise analysis.

#### 4. Tools Used
**Programming Language:**
- Python (main libraries: `pandas`, `statsmodels`, `matplotlib`, `seaborn`).

**Statistical Software:**
- Possible use of R for cross-validation.

**Documentation and Presentation:**
- Reports in PDF and interactive graphs.

### Project Requirements
**Project Dependencies:**
- Python 3.10+
- Python Libraries:
  - `pandas`
  - `numpy`
  - `statsmodels`
  - `seaborn`
  - `matplotlib`
  - `scikit-learn`
- Data file in CSV format.




