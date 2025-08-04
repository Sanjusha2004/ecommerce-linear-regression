# ecommerce-linear-regression
# 🛍️ E-Commerce Customer Spending Analysis

This project uses Linear Regression to predict customer yearly spending based on behavioral data from an E-commerce company based in New York City. The company sells clothing online and provides in-store personal stylist sessions. The goal is to help the business decide whether to prioritize their **mobile app** or **website** experience to increase revenue.

---

## 📊 Project Overview

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

## 🧠 Dataset Features

| Column Name            | Description                             |
|------------------------|-----------------------------------------|
| `Avg. Session Length`  | Average session on the website (in mins)|
| `Time on App`          | Time spent on mobile app (in mins)      |
| `Time on Website`      | Time spent on website (in mins)         |
| `Length of Membership` | Customer membership duration (in years) |
| `Yearly Amount Spent`  | 💰 Target: Annual spending of customer   |
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

## 📈 Results

- **R² Score**: 0.98+ (on training data)
- **Interpretation**: App engagement shows a higher impact on yearly spend than website interaction.

---

## 🔍 Key Learnings

- How to apply linear regression to real-world data
- Importance of visual EDA before modeling
- Translating business questions into data solutions

---

## 📁 Folder Structure

