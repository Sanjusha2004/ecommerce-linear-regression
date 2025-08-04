# ecommerce-linear-regression
# E-Commerce Customer Spending Analysis

This project uses Linear Regression to predict customer yearly spending based on behavioral data from an E-commerce company based in New York City. The company sells clothing online and provides in-store personal stylist sessions. The goal is to help the business decide whether to prioritize their **mobile app** or **website** experience to increase revenue.

---

## Project Overview

- **Business Problem**:  
  The company wants to determine whether customers who spend more time on the **mobile app** or the **website** are more likely to spend more money annually.

- **Objective**:  
  Build a **linear regression model** to predict `Yearly Amount Spent` using customer behavior features.

- **Tech Stack**:
  - Python
  - Pandas, NumPy
  - Seaborn, Matplotlib
  - Scikit-learn
  - Jupyter / Google Colab

---

## Dataset Features

| Column Name            | Description                             |
|------------------------|-----------------------------------------|
| `Avg. Session Length`  | Average session on the website (in mins)|
| `Time on App`          | Time spent on mobile app (in mins)      |
| `Time on Website`      | Time spent on website (in mins)         |
| `Length of Membership` | Customer membership duration (in years) |
| `Yearly Amount Spent`  | Target: Annual spending of customer   |
| `Email`, `Address`, `Avatar` | Ignored for analysis             |

---

## 🛠️ Steps Performed

1. **Exploratory Data Analysis (EDA)**  
   - Visualized relationships between features  
   - Checked correlations with the target variable

2. **Feature Selection**  
   - Selected key numeric features for the regression model

3. **Model Training**  
   - Used `LinearRegression()` from `sklearn`  
   - Evaluated model using MSE and R² score

4. **Insights**  
   - Discovered that **Time on App** was a stronger predictor than **Time on Website**  
   - Provided business recommendations based on findings

---

## Model Results

- **Model** : Linear Regression
- **Mean Absolute Error (MAE): 7.22+
- **R² Score**: 0.98+ (on training data)
- **Interpretation**: App engagement shows a higher impact on yearly spend than website interaction.
- <p align="center"> <img src="notebook/actual_vs_predicted.png" width="500"> </p>

---

## Key Insights

- Time on App has a stronger correlation with spending than Time on Website.
- Customers who spend more time with the app tend to spend more money.
- The regression model predicts customer spending with high accuracy.

---

How to Run
Clone this repo
git clone https://github.com/yourusername/ecommerce-customer-spending-analysis.git

Open notebook/linear_regression_analysis.ipynb in Jupyter or Google Colab.

Install dependencies (if needed):
pip install pandas numpy matplotlib seaborn scikit-learn


---

## Folder Structure

ecommerce-customer-spending-analysis/
├── data/
│   └── Ecommerce Customers.csv
├── notebook/
│   └── linear_regression_analysis.ipynb
├── README.md
└── actual_vs_predicted.png




