# Linear Regression Model

## 📌 Project Overview
This repository contains a **Linear Regression Model** to analyze customer spending behavior based on multiple input features. The model is trained on the `Ecommerce Customers` dataset to predict **Yearly Amount Spent** using various customer attributes.

## 📊 Dataset Description
The dataset includes the following key features:
- **Avg. Session Length** – Average duration of a user session
- **Time on App** – Time spent using the mobile application
- **Time on Website** – Time spent on the website
- **Length of Membership** – Duration of customer membership
- **Yearly Amount Spent** *(Target Variable)* – Annual expenditure of the customer

## ⚙️ Installation & Requirements
Ensure you have Python installed along with the necessary dependencies:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## 🚀 How to Run the Model
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/linear-regression-project.git
   cd linear-regression-project
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Model_linear_regression.ipynb
   ```
3. Execute the notebook cells to:
   - Load and preprocess the dataset
   - Train the **Linear Regression Model**
   - Evaluate model performance
   - Visualize results

## 📈 Model Performance & Evaluation
The regression model was trained and tested, yielding the following results:

### **🔹 Regression Coefficients** (Effect of each feature on `Yearly Amount Spent`)
```python
W : [25.60, 38.79, 0.31, 61.90]
```
- **Intercept:** `-1044.26`

### **📊 Model Metrics**
| Metric | Value |
|--------|--------|
| **Mean Absolute Error (MAE)** | 8.56 |
| **Root Mean Squared Error (RMSE)** | 10.48 |
| **R² Score** | 0.978 |

## 📊 Visualizations
The notebook includes the following key plots:
- **Actual vs. Predicted Values** – A scatter plot comparing true vs. predicted spending.
- **Residual Distribution** – A histogram of the model errors.

## 🔍 Key Insights
- **Length of Membership** has the highest positive correlation with spending.
- **Time on App** also significantly impacts spending.
- **Time on Website has minimal influence**, suggesting a stronger focus on mobile engagement.
- The model explains **98.20%** of the variance in customer spending, demonstrating high accuracy.

## 📝 Author
Developed as part of a **machine learning project on Linear Regression**, focusing on customer behavior analysis.

## 📜 License
This project is open-source and available under the **MIT License**.
