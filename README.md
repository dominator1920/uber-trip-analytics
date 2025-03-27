# Uber Trip Analytics

## Overview

This project analyzes Uber trip data to extract insights on trip duration, speed, and travel patterns. Using machine learning techniques, it predicts speed based on trip attributes.

## Features

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA) with visualizations
- Feature engineering (trip duration, peak hours, etc.)
- Predictive modeling using **Random Forest Regressor**
- Model evaluation with RMSE, MAE, and R²

## Technologies Used

- **Python** (pandas, numpy, matplotlib, seaborn, scikit-learn)
- **Jupyter Notebook** for analysis
- **Git & GitHub** for version control

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/dominator1920/uber-trip-analytics.git
   ```
2. Navigate to the project folder:
   ```sh
   cd uber-trip-analytics
   ```
3. Create a virtual environment:
   ```sh
   python -m venv venv
   ```
4. Activate the virtual environment:
   - **Windows:** `venv\Scripts\activate`
   - **Mac/Linux:** `source venv/bin/activate`
5. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage

- Open `uber analysis.ipynb` or `uber trip analysis2.ipynb` in Jupyter Notebook.
- Run the cells step-by-step to analyze the dataset and train the model.

## Model Performance

- **Root Mean Squared Error (RMSE):** 11.37
- **Mean Absolute Error (MAE):** (Add value here)
- **R² Score:** (Add value here)


## Model Performance

You can calculate model performance using the following code:

```python
from sklearn.metrics import mean_absolute_error, r2_score

# Assuming y_test and y_pred are your actual and predicted values:
mae = mean_absolute_error(y_test, y_pred)
r2 = r2_score(y_test, y_pred)

print(f"Mean Absolute Error (MAE): {mae}")
print(f"R² Score: {r2}")


## Contributing

Feel free to fork this repository and submit pull requests with improvements or additional features.


---

🚀 Happy Coding!

