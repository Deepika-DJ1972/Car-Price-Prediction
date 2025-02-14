# 🚗 Car Price Prediction

## 📌 Overview
This project predicts the selling price of used cars based on various features such as manufacturing year, fuel type, transmission type, and number of owners. The model is built using **Random Forest Regressor** and incorporates **feature scaling and encoding** for accurate predictions.

## 📂 Dataset
The dataset used for training the model contains the following features:
- `Year`: Year of manufacture
- `Present_Price`: Current ex-showroom price (in lakhs)
- `Driven_kms`: Total distance driven (in kilometers)
- `Fuel_Type`: Type of fuel (Petrol, Diesel, CNG)
- `Transmission`: Manual or Automatic transmission
- `Owner`: Number of previous owners
- `Selling_Price`: The target variable (price at which the car was sold)

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-Learn
- Random Forest Regressor
- Pipeline & ColumnTransformer

## ⚙️ Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Car-Price-Prediction.git
   cd Car-Price-Prediction

