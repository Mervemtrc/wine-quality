# WINE QUALITY PREDICTION - MACHINE LEARNING PROJECT

## 📄 Project Overview
This project leverages machine learning to predict the quality of red wine based on its physicochemical properties. The model analyzes features such as acidity, sugar levels, and alcohol content to predict a wine's quality score. The insights can help winemakers assess factors that influence quality and make improvements.

## 🗂️ Dataset
- **Source**: `winequality-red.csv`
- **Content**: Contains physicochemical properties of red wine samples along with a quality score (0–10 scale). Key features include:
  - `fixed acidity`, `volatile acidity`, `citric acid`, `residual sugar`, `chlorides`
  - `free sulfur dioxide`, `total sulfur dioxide`, `density`, `pH`, `sulfates`, `alcohol`
  - `quality`: Target variable for predicting wine quality.

## 🛠️ Project Workflow
This project involves the following steps:

1. **Data Preparation** (`winequality.ipynb`)
   - **Understanding Features**: Analyzing the impact of each feature on wine quality.
   - **Handling Missing Values**: Verifying data integrity and handling missing values as needed.
   - **Correlation Analysis**: Exploring relationships among features (e.g., alcohol and quality).
   - **Normalization and Standardization**: Standardizing features to improve model performance, particularly for algorithms sensitive to data scales.

2. **Model Training**
   - **Algorithms Used**:
     - Regularized Linear Regression (Lasso, Ridge, Elastic Net) to control overfitting and simplify model interpretation.
     - Support Vector Regression (SVR) with regularization to explore non-linear relationships.
     - Random Forest Regression to capture complex interactions between features.
   - **Hyperparameter Tuning**: Using cross-validation to find the optimal parameters (e.g., `alpha` for regularized models, `C` for SVR).

3. **Evaluation**
   - **Metrics**: Models are evaluated on Mean Squared Error (MSE) and Mean Absolute Error (MAE).
   - **Regularization Insights**: Comparison of different regularization effects on model complexity and interpretability.
   - **Feature Importance**: Analysis of key features contributing to the prediction of wine quality.

## 📊 Technologies Used
- **Programming Language**: Python
- **Tools and Libraries**:
  - **Pandas** for data manipulation
  - **NumPy** for numerical computations
  - **Scikit-Learn** for machine learning models and evaluation
  - **Matplotlib & Seaborn** for data visualization
  - **Jupyter Notebook** for interactive exploration and analysis

## Usage
To run the project:
1. Open `winequality.ipynb` in Jupyter Notebook.
2. Execute each cell sequentially to preprocess data, train models, and observe results.

## References
- Red wine quality dataset: UCI Machine Learning Repository
- Module guidelines: *Applied Statistics & Machine Learning*, Continuous Assessment Two instructions.



