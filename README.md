## Customer Churn Prediction

### Project Overview
This machine learning project focuses on predicting customer churn in the telecom sector. By analyzing a dataset containing customer demographic, behavioral, and service usage data, the project aims to provide actionable insights to improve retention strategies and reduce churn rates.

### Research Context
This machine learning project focuses on reproducing and expanding upon findings from key research papers that explore customer churn prediction using data-driven methods. By analyzing a telecom customer churn dataset—consisting of attributes like account duration, international plan subscription, call usage, service charges, customer service interactions, and churn status—the project aims to achieve the following:

Build effective churn prediction models to identify at-risk customers. Analyze key attributes influencing churn behavior (e.g., service plans, call patterns, or customer support usage). Offer actionable insights to optimize customer retention efforts and reduce churn rates. The outcome of this analysis will empower telecom providers to anticipate churn early, focus on high-risk customers, and tailor their strategies to improve customer loyalty and business performance.

#### Key Objectives
Build churn prediction models to identify at-risk customers.
Analyze factors contributing to churn (e.g., service plans, usage patterns).
Deploy the churn prediction model as an interactive web application for business users.


### Methodology
This project is developed using the **CRISP-DM (Cross-Industry Standard Process for Data Mining)** framework:
1. **Business Understanding**: Understand the problem's impact and define objectives.
2. **Data Understanding**: Explore the dataset, identify patterns, and understand attributes.
3. **Data Preparation**: Preprocess, clean, and transform the data for analysis.
4. **Modeling**: Apply machine learning algorithms to predict churn.
5. **Evaluation**: Validate models and select the best-performing ones.
6. **Deployment**: Deploy the solution using Flask and JavaScript for an intuitive web interface.

### Research Papers Used
This project draws inspiration from the following research papers:

###### Implementing Machine Learning Techniques for Customer Retention and Churn Prediction in Telecommunications, DOI: 10.51594/csitrj.v5i8.1489
###### Customer Churn Prediction in Telecom Sector Using Machine Learning Techniques, DOI: 10.1016/j.rico.2023.100342 
###### Explaining Customer Churn Prediction in Telecom Industry Using Tabular Machine Learning Models, DOI: 10.1016/j.mlwa.2024.100567

These papers provided insights into feature engineering, model selection, and interpretability techniques, forming the foundation of our approach.
### Deployment
The model is deployed as a web application using:
- **Flask**: Backend framework for serving the machine learning model.
- **JavaScript**: Enhancing interactivity in the front-end application.
- **HTML/CSS**: Building a responsive and user-friendly interface.

### Features of the Notebook
1. **Business Understanding**: Overview of the problem and its implications.
2. **Data Preparation**: Loading, cleaning, and preprocessing the dataset.
3. **Feature Selection**: Identifying key predictors using statistical methods and model-based approaches.
4. **Model Building**: Training machine learning models such as Logistic Regression, Decision Trees, SVM, and Ensemble methods.
5. **Model Evaluation**: Comparing models using accuracy, precision, recall, F1 score, and ROC AUC.
6. **Visualization**: Creating insights through plots and dashboards.
7. **Deployment Preparation**: Exporting the trained model and integrating it into the Flask framework.

### Steps Completed
1. Loaded necessary libraries and telecom churn dataset.
2. Preprocessed data using encoders and scalers.
3. Explored features contributing to churn using visualizations.
4. Applied feature selection and trained multiple machine learning models.
5. Evaluated model performance and selected the best model.
6. Integrated the trained model with a Flask application for deployment.
7. Enhanced the front end with JavaScript for interactive user input.
