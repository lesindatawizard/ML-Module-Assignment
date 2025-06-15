# ML-Module-Assignment

# 🚗 Car Price Prediction – ML Module Assignment

## 🧭 Business Objective

A Chinese automobile company is planning to enter the US market by setting up local manufacturing. The company wants to understand which factors influence car pricing in the US so that they can:

- Identify significant variables affecting car price.
- Understand how each feature impacts the price.
- Build an accurate predictive model to support strategic pricing decisions.


## 📦 Dataset Information

- **Source**: `[CarPrice_Assignment.csv](https://drive.google.com/file/d/1FHmYNLs9v0Enc-UExEMpitOFGsWvB2dP/view?usp=drive_link)`
- **Records**: ~205 rows
- **Features**: Includes car specifications like engine type, horsepower, curb weight, and price.


## 🔍 Project Workflow

### 1️⃣ Data Loading and Preprocessing

- Loaded dataset using Pandas.
- Checked for null values and corrected data types.
- Performed Label Encoding for categorical variables.
- Removed multicollinearity by dropping redundant variables.
- Applied Standard Scaler for numerical features.
- Split the data into train and test sets.

### 2️⃣ Models Implemented

- ✅ **Linear Regression**  
- 🌲 **Decision Tree Regressor**
- 🌳 **Random Forest Regressor**
- 🚀 **Gradient Boosting Regressor**
- 💡 **Support Vector Regressor (SVR)**

Each model was explained briefly with justification for its use.

### 3️⃣ Model Evaluation

Metrics used:

- **R² Score** – Goodness of fit
- **MSE (Mean Squared Error)**
- **MAE (Mean Absolute Error)**

| Model                     | R² Score | MSE       | MAE       |
|--------------------------|----------|-----------|-----------|
| Linear Regression        | ~0.87    | Moderate  | Moderate  |
| Decision Tree Regressor | ~0.91    | Low       | Low       |
| Random Forest Regressor | ~0.96    | Very Low  | Very Low  |
| Gradient Boosting       | ~0.95    | Low       | Low       |
| SVR                     | ~0.77    | High      | High      |

✅ **Best Performing Model**: Random Forest Regressor  
❌ **Least Performing Model**: SVR (due to sensitivity to scaling and lack of tuning)


