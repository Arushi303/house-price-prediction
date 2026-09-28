# House Price Prediction using Machine Learning

Predict house prices with linear regression and gradient boosting, using features like square footage, bedrooms, location, and more. This project covers data exploration, visualization, and model comparison.

---

## Project Structure

```
data/                         # Dataset used for training and testing
housesales.ipynb              # Main Jupyter Notebook with all code
kc_house_data.csv             # King County house sales data
requirements.txt              # Python dependencies
README.md                     # Project documentation
```

---

## Dataset

This dataset contains details of house listings including:

- Number of bedrooms and bathrooms
- Square footage (with and without basement)
- Waterfront presence
- Location via latitude and longitude
- Zipcode
- Year built and renovated
- Price of the house

**Source:** King County house sales (`kc_house_data.csv`)

---

## Models Used

### Linear Regression
- First model used to understand relationships in data
- Achieved ~73% accuracy

### Gradient Boosting Regressor
- Powerful ensemble model using decision trees
- Achieved **~91.94% accuracy**

---

## Key Visualizations

- Most common house types by bedroom count
- Price vs. Living Area
- Price vs. Location (Latitude and Longitude)
- Influence of features like:
  - Basement area
  - Floors
  - Condition
  - Waterfront

---

## Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
```

### Main Libraries Used

* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn

---

## How to Run

1. **Clone the repository**

```bash
git clone https://github.com/Arushi303/house-price-prediction.git
cd house-price-prediction
```

2. **Install dependencies**

```bash
pip install -r requirements.txt
```

3. **Run the Jupyter Notebook**

```bash
jupyter notebook housesales.ipynb
```

---

## Goal

To achieve over **85% prediction accuracy** in estimating house prices using regression techniques.

Final model using Gradient Boosting achieved **91.94% accuracy**.

---

## Learning Points

* Data cleaning and preprocessing
* Exploratory data analysis
* Feature engineering
* Linear Regression vs Gradient Boosting
* Model evaluation using `r2_score`

---

## Author

**Arushi Gautam** — [github.com/Arushi303]

---
