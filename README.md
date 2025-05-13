# Polynomial Regression (Temperature & Auto MPG Dataset)

This project demonstrates **Polynomial Regression** using:

1. **Temperature vs Pressure** dataset
2. **Auto MPG** dataset (`horsepower` vs `mpg`)

## Tasks Completed

1. ✅ Implemented **Polynomial Regression** using sklearn
2. ✅ Visualized data and regression curve for different degrees
3. ✅ Preprocessed **Auto MPG** dataset (handled missing values, type conversions)
4. ✅ Compared model behavior for different polynomial degrees

## Activity Tasks

### 🔁 Change the `degree` variable and observe:

- **Degree 1**: Straight line (underfitting)
- **Degree 2**: Captures curvature well
- **Higher Degrees**: May overfit depending on dataset

### 🚗 Auto MPG Dataset Implementation

- Used `horsepower` as input and `mpg` as target
- Replaced `?` with NaN, dropped missing values
- Applied polynomial transformation and linear regression
- Visualized actual vs predicted data

## Evaluation Results

- Plotted prediction curves for different degrees
- Observed performance visually
- Underfitting vs Overfitting demonstrated clearly

## Libraries Used

- `numpy`, `pandas`, `matplotlib`
- `sklearn.linear_model.LinearRegression`
- `sklearn.preprocessing.PolynomialFeatures`
