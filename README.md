# FICO Score & Loan Default Modeling Project

Credit risk assessment using FICO score segmentation, loan default modeling, discretization techniques, and log-likelihood evaluation for predictive analytics in financial services.

## Objective

Analyze loan customer data to understand relationships between credit lines, debt, income, employment, FICO scores, and loan default. Develop risk segmentation models using bucketing/discretization and evaluate log-likelihoods for predictive analytics.

## Workflow & Methods

### Data Loading
- Loads a CSV dataset "Task 3 and 4_Loan_Data" with features including:
  - `customer_id`
  - `credit_lines_outstanding`
  - `loan_amt_outstanding`
  - `total_debt_outstanding`
  - `income`
  - `years_employed`
  - `fico_score`
  - `default` flag

### Preprocessing
- Cleans and structures data for modeling
- Prepares features for analysis and risk assessment

### Discretization & Bucketing
- Uses `KBinsDiscretizer` to segment customers by FICO score ranges
- Creates MSE buckets for risk stratification
- Calculates min, max, count, and bucket MSE for each FICO segment

### Log-Likelihood Evaluation
- Computes log-likelihood score boundaries
- Calculates overall log-likelihood for the loan default prediction model
- Evaluates predictive quality of the model

## Insights & Results

- Tabulates FICO score buckets and their statistics for risk analysis
- Assesses default risk, variance, and predictive quality using log-likelihood approach
- Provides customer segmentation by FICO score ranges
- Evaluates the relationship between credit metrics and default probability

## Conclusion

This notebook supports credit risk assessment, customer segmentation by FICO score, and evaluation of loan default risk with statistical modeling. It is suitable for financial analytics and predictive modeling use cases.

## Use Cases

- **Credit Risk Assessment**: Evaluate borrower creditworthiness using FICO scores and other financial metrics
- **Financial Analytics**: Analyze patterns in loan defaults and customer behavior
- **Predictive Modeling**: Build models to forecast loan default probability
- **Customer Segmentation**: Group customers into risk categories for targeted strategies
- **Portfolio Management**: Support decision-making for loan approval and risk management

## Technologies & Tags

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-Machine%20Learning-yellow)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-lightblue)

**Topics**: Credit Risk, FICO Score, Loan Default, Risk Modeling, Discretization, Log-Likelihood, Financial Analytics, Predictive Modeling, Customer Segmentation, Machine Learning

## Files

- `fico_loan_default_project.ipynb` - Main Jupyter notebook with analysis and modeling
- Dataset: "Task 3 and 4_Loan_Data.csv" (to be uploaded)

## Getting Started

1. Clone this repository
2. Install required dependencies: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`
3. Open `fico_loan_default_project.ipynb` in Jupyter Notebook or JupyterLab
4. Run the cells to reproduce the analysis

## License

This project is available for educational and analytical purposes.
