### Bank Customer Churn Prediction Model Using Machine Learning: A Case Study on Islamic Bank Data

A `Sharia Bank` that implements `religion of Islam` shariah contract in its business processes where it only provides buying and selling services, not a contract of borrowing money with usury to the first party (`developer / seller`), second (`bank`) and third (`customer`). Customers who want something but are constrained by costs can use this facility, where goods are purchased by the bank and then resold at a higher margin to the customer by paying installments over a certain period of time.

The customers of the `Islamic Bank` are leaving the company: little by little, their number is decreasing every month. Bank employees realized that it would be more cost-effective if companies focused on retaining their loyal old customers rather than attracting new ones.
In this case, our task is to predict whether a customer will leave the bank soon or not. We have data regarding clients past behavior and history of termination of their contracts with the bank. The target is stated as `Class 0` that the customer will not leave soon and `Class 1` that the customer will leave soon.

Based on the explanation above, the selected `machine learning model` is a type of `classification - supervised learning`. We'll be looking for the maximum possible F1 score and looking at the AUC-ROC metric. The F1 threshold set for this project is 0.59.

Some of the objectives and formulation of the problem from this project analysis:
- Knowing the best algorithm for `machine learning` model for `Sharia Bank` dataset
- What is the best `Hyperparameter` in `machine learning` models
- Does class imbalance affect `machine learning model` quality metrics?
- Is it true that a model that has been trained using a balanced data class (`balance`) produces better F1 quality metrics?

| Project | Description | Library |
| ------- | ------- | ------- |
| [Prediction Model for Customer Churn](https://github.com/fuadraharjo/TripleTen_ENG/blob/main/Project-06%20-%20Prediction%20Model%20for%20Customer%20Churn/Prediction%20model%20for%20bank%20customer%20churn%20using%20machine%20learning.ipynb) | The classification prediction model to determine which customers will `churn` uses the `scikit-learn` module and applies techniques such as `one hot encoding (OHE)`, `scaling features` and `balancing target`. | *pandas*, *sklearn*, *matplotlib*, *seaborn* |