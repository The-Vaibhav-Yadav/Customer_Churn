# Customer Churn Analysis & Predictive Modeling

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![Dataset](https://img.shields.io/badge/data-10K_Records-blue)
![Machine Learning](https://img.shields.io/badge/ML-Classification-orange)

A specialized analytics repository containing extensive historical banking metrics aimed exclusively at defining and predicting probability vectors using consumer retention structures. Designed as an academic base for structuring, validating, and training predictive computational classification models to minimize sector-wide churn rates.

## Table of Contents
- [Tech Stack & Architecture](#tech-stack--architecture)
- [Prerequisites](#prerequisites)
- [Installation & Local Setup](#installation--local-setup)
- [Usage & Running the App](#usage--running-the-app)
- [Testing](#testing)
- [Deployment](#deployment)
- [Contributing Guidelines](#contributing-guidelines)
- [License and Contact](#license-and-contact)

## Tech Stack & Architecture

- **Primary Dependencies**: Data Modeling natively assumes ingestion via `Pandas`, `NumPy`, and scalable bounds like `Scikit-Learn`.
- **Data Structuring**: Hosted via standard `.csv` architectures optimizing cross-compatibility frameworks structurally.

**High-Level Architecture**:
The system revolves entirely around analyzing `Churn_Modelling.csv`. It encapsulates exactly 10,000 recorded consumer interactions dynamically tracking their banking persistence:
- **Demographics tracked**: `Geography`, `Gender`, `Age`.
- **Financial Status mapping**: `CreditScore`, `Balance`, `EstimatedSalary`.
- **Engagement vectors**: `Tenure`, `NumOfProducts`, `HasCrCard`, `IsActiveMember`.
- **Target Node**: Utilizing the structural boolean `Exited` natively defined (`1` = Customer left, `0` = Customer retained).

*Pro Tip*: This schema operates perfectly utilizing structural Random Forest models or ensemble Gradient Boosting logic (XGBoost) scaling dynamically to predict retention.

## Prerequisites
- Data analytical mapping dependencies: Python Environment natively configured.
- `Pandas` bounds globally installed (`pip install pandas`).

## Installation & Local Setup

Clone the structured data schema natively pointing dependencies into Python logic correctly.

```bash
git clone https://github.com/The-Vaibhav-Yadav/Customer_Churn.git
cd Customer_Churn
```
No environment scaling limitations (`.env`) or explicit DB authorizations exist natively since the dataset is wholly self-contained structurally.

## Usage & Running the App

Instead of executing standard web processes, analysts consume the files locally via IDE boundaries (`Jupyter Notebook`). 

Example standard Pandas extraction logic:
```python
import pandas as pd

# Rapidly load 10K metrics 
df = pd.read_csv('Churn_Modelling.csv')

# Recursively drop string-based indexes mapping integer target arrays natively
X = df.drop(['RowNumber', 'CustomerId', 'Surname', 'Exited'], axis=1)
y = df['Exited']

print(X.head()) # Preview inputs mapped organically
```

## Testing
There are no localized Python assertion tests dynamically. Instead, data integrity is mathematically guaranteed validating dataset accuracy using algorithmic modeling `train_test_split` cross-validation logic.
**Standard Test Metric**: Leverage `F1-score` natively rather than strict accuracy bounds to bypass natural retention biases (class imbalances) logically.

## Deployment
While datasets technically don't "deploy", orchestrators load instances referencing bucket structures dynamically against scheduled AWS S3 endpoints processing nightly batches securely mapping inferences correctly.

## Contributing Guidelines
Exploratory Data Analysis metrics (`.ipynb`) visually graphing consumer distributions are strongly desired!
- **Branch strategy**: Iterate `feature/data-visualization` natively.
- **Merge validations**: Log output conclusions mathematically inside the Pull Requests systematically.

## License and Contact
**License**: MIT 
**Author**: Vaibhav Yadav (https://github.com/The-Vaibhav-Yadav)
