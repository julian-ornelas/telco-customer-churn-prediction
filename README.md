## Telco Churn Prediction

This project involves building and evaluating machine learning models to predict customer churn using a telecommunications dataset of a hypothetical company, Telco.


### Features

- Dataset preprocessing and cleaning
- Feature selection using chi-square and ANOVA tests
- Model training and evaluation with Logistic Regression, Random Forest, and CatBoost
- Visualizations


### Results

- CatBoost achieved 80% recall for identifying churners, and 84% ROC-AUC to differentiate between churners and non-churners.

- Insights revealed key factors influencing churn, such as contract type and tenure.


### Running The Project

1. Download repo:

```
https://github.com/julian-ornelas/telco-customer-churn-prediction
```

2. Create a virtual environment:

```
python -m venv venv
```

3. Activate the virtual environment:

- On Windows:

```
venv\Scripts\activate
```

- On macOS/Linux:

```
source venv/bin/activate
```

4. Install dependencies:

```
pip install -r requirements.txt
```