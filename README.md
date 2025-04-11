# Car-Price-Predictions
This project presents a machine learning approach to predict car prices using various regression models. The objective is to assist buyers and sellers in understanding the fair market value of a car based on its attributes. The notebook includes data preprocessing, feature engineering, model training, and performance evaluation.

## 📊 Insights & Methodology

- **Dataset**: Cleaned dataset loaded from `df_cleaned.csv`
- **Target Variable**: Car price
- **Features**: A mix of numerical and categorical variables such as brand, year, mileage, engine size, and transmission type
- **Preprocessing**:
  - Label encoding for categorical variables
  - Feature scaling with `StandardScaler`
- **Train/Test Split**: 80/20

## 🧠 Models Used

- **Ordinary Least Squares (OLS)** with `statsmodels`
- **Linear Regression**
- **Ridge Regression**
- **Lasso Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**

Each model is evaluated using:
- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)

## 📈 Evaluation Results

- OLS provides interpretability with statistical summaries.
- Ridge and Lasso help with regularization and handling multicollinearity.
- Decision Tree shows non-linear relationships and can capture complex patterns.

## 🛠️ Technologies

- Python
- pandas, numpy
- scikit-learn
- statsmodels
- matplotlib / seaborn (if plots are used)

## 🚀 Getting Started

To run this notebook:

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/car-price-prediction.git
   cd car-price-prediction
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook Car_price_prediction.ipynb
   ```

## 📌 Notes

- Ensure `df_cleaned.csv` is available in the working directory.
- All warnings are suppressed for readability.

## 📂 File Structure

```
car-price-prediction/
│
├── Car_price_prediction.ipynb
├── df_cleaned.csv
├── README.md
└── requirements.txt
```

---
