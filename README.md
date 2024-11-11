# Wine Quality Prediction: A Comparative Analysis of Regularized Regression Models

## Overview
This project analyzes a dataset of red wine quality using machine learning techniques. The goal is to explore and implement regression models to predict wine quality based on various chemical properties. This project fulfills the requirements of the **Applied Statistics & Machine Learning** module, specifically focusing on regression analysis as outlined in the Continuous Assessment Two brief.

## Project Structure
- `winequality-red.csv`: Dataset containing various chemical properties of red wines and their quality ratings.
- `winequality.ipynb`: Jupyter notebook implementing data preparation, regression models, and evaluation metrics.

## Dataset
The dataset includes attributes such as acidity, chlorides, sulfur dioxide levels, and alcohol content, with wine quality as the target variable. There are **11 input features** and **1,599 instances**.

## Requirements
The project requires the following libraries:
- `pandas`: Data manipulation and analysis.
- `numpy`: Numerical operations.
- `scikit-learn`: Machine learning models and evaluation metrics.
- `matplotlib`: Data visualization.

## Implementation
### Data Preparation
- **Data Cleaning**: Handling missing values, outliers, and normalization.
- **Feature Engineering**: Feature scaling and transformations to improve model performance.

### Models
The following models were implemented:
1. **Regularized Linear Regression**: Using L1, L2, and Elastic Net regularizations to observe the impact on coefficients, performance, and interpretability.
2. **Support Vector Regression (SVR)**: Examined the effect of L2 regularization on SVR's performance and interpretability.
3. **Random Forest Regression** (optional): Comparison with regularized regression models regarding performance and interpretability.

### Evaluation
Each model was evaluated using appropriate regression metrics to assess prediction accuracy and interpretability.

## Results
Summary of the findings:
- **Linear Regression**: Regularization techniques' effects on performance and feature importance.
- **SVR with L2 Regularization**: Impact on model accuracy and coefficient sparsity.
- **Random Forest**: Comparative results in terms of accuracy and interpretability.

## Conclusion
The project successfully demonstrates the application of various regression techniques and highlights the strengths and limitations of each model in predicting wine quality.

## Usage
To run the project:
1. Open `winequality.ipynb` in Jupyter Notebook.
2. Execute each cell sequentially to preprocess data, train models, and observe results.

## References
- Red wine quality dataset: UCI Machine Learning Repository
- Module guidelines: *Applied Statistics & Machine Learning*, Continuous Assessment Two instructions.



