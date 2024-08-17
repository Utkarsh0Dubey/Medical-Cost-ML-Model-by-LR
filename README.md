# Medical Cost Estimation: Linear Regression

## Project Overview
This project aims to predict medical insurance costs based on features such as age, BMI, smoking status, and region. The dataset contains information about individuals and their insurance costs, with both categorical and numerical features. Linear Regression is used as a baseline model for predicting these costs.

## Dataset
- **Source**: The dataset used in this project is a medical insurance dataset, commonly available on platforms like Kaggle and other machine learning repositories.
- **Features**: 
  - `age`: Age of the individual
  - `sex`: Gender of the individual
  - `bmi`: Body Mass Index
  - `children`: Number of children/dependents
  - `smoker`: Whether the individual is a smoker
  - `region`: Region where the individual resides
- **Target**: 
  - `charges`: Medical insurance costs for the individual

## Project Steps
1. **Data Preprocessing**: 
   - Encoding categorical variables (e.g., `sex`, `smoker`, `region`) using one-hot encoding.
   - Feature scaling to standardize the numerical features before training the model.
2. **Model Training**:
   - Used `scikit-learn`'s `LinearRegression` to train the model on 80% of the data (training set).
3. **Model Evaluation**:
   - Evaluated the model on both training and testing sets using Mean Squared Error (MSE) and R-squared metrics.
   - Generated visualizations to compare actual vs. predicted values for both training and testing data.

## Results
- **Training MSE**: 36,000,000 (RMSE ≈ 6,000)
- **Testing MSE**: 36,000,000 (RMSE ≈ 6,000)
- **Conclusion**: The linear regression model provided a good baseline, but the error rate of around $6,000 is substantial, especially for individuals with lower medical costs. The model can be further improved using more complex techniques.

## How to Run
1. **Clone the repository**:
   ```bash
   git clone https://github.com/Utkarsh0Dubey/Medical-Cost-ML-Model-by-LR.git
   cd Medical-Cost-ML-Model-by-LR
