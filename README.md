# House Price Prediction

## Business Problem
The goal of this project is to predict house prices based on various features such as area, number of bedrooms, bathrooms, and location.

## Dataset
- **Number of rows:** 1460
- **Target variable:** SalePrice
- **Features:** 80+

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn

## Models Used
- Linear Regression
- Ridge Regression (alpha = 10)

## Results

### Linear Regression
- **Test R² Score:** 0.9026

### Ridge Regression
- **Test R² Score:** 0.8984

The Linear Regression model performed slightly better, explaining approximately **90% of the variance** in house prices on test data.

## Conclusion
The model successfully predicts house prices with good accuracy and can help real estate businesses estimate property value.

---

## How to Run This Project

1. Clone this repository
2. Install requirements: `pip install pandas numpy matplotlib scikit-learn`
3. Open the Jupyter notebook
4. Run all cells

## Files in this Repository
- `README.md` - Project documentation
- `house-price-prediction.ipynb` - Main notebook with analysis and model
- `data.csv` - Dataset (if you're uploading it)

