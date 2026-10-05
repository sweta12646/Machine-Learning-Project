📊 E-commerce Sales Revenue Prediction Using Regression

📌 Project Overview

This project focuses on predicting e-commerce revenue using different machine learning regression techniques.

The dataset contains 5,000 e-commerce transactions with information such as quantity, unit price, discount, delivery days, customer rating, payment method, product category, and region.

Three regression models were implemented and compared:

- Simple Linear Regression
- Multiple Linear Regression
- Gradient Boosting Regression

The main objective is to identify which model provides the best performance for predicting revenue.

---

📂 Dataset

The dataset contains 5,000 rows and 12 columns.

Main Features

Feature| Description
"order_id"| Unique order identifier
"order_date"| Date of the order
"customer_id"| Customer identifier
"product_category"| Product category
"region"| Customer/order region
"quantity"| Quantity purchased
"unit_price"| Price per unit
"discount"| Discount applied
"payment_method"| Payment method used
"delivery_days"| Number of delivery days
"customer_rating"| Customer rating
"revenue"| Revenue generated

---

🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

🤖 Machine Learning Models

1. Simple Linear Regression

Simple Linear Regression was used to understand the relationship between quantity and revenue.

Results:

- Training Accuracy (R²): 38.06%
- Test Accuracy (R²): 41.05%

The model showed relatively low predictive performance.

---

2. Multiple Linear Regression

Multiple Linear Regression used the following features:

- Quantity
- Unit Price
- Discount
- Delivery Days
- Customer Rating

Results:

- Training Accuracy (R²): 87.10%
- Test Accuracy (R²): 86.07%

The model performed significantly better than Simple Linear Regression.

---

3. Gradient Boosting Regression

Gradient Boosting Regression was trained using the same five numerical features:

- Quantity
- Unit Price
- Discount
- Delivery Days
- Customer Rating

Results:

- Training Accuracy (R²): 99.85%
- Test Accuracy (R²): 99.80%
- MAE: 27.73
- RMSE: 36.62
- R² Score: 1.00

The Actual vs Predicted graph shows that most predictions are very close to the actual revenue values.

---

📊 Model Comparison

Model| Training Accuracy| Test Accuracy / Model Efficiency
Simple Linear Regression| 38.06%| 41.05%
Multiple Linear Regression| 87.10%| 86.07%
Gradient Boosting Regression| 99.85%| 99.80%

🏆 Best Model

Based on the results, Gradient Boosting Regression performed the best among the three models.

The overall performance ranking is:

Gradient Boosting Regression > Multiple Linear Regression > Simple Linear Regression

---

📈 Key Insights

- Simple Linear Regression had the lowest predictive performance.
- Multiple Linear Regression provided a significant improvement by using multiple variables.
- Gradient Boosting Regression achieved the highest training and test performance.
- The Actual vs Predicted graph for Gradient Boosting shows predictions close to the perfect prediction line.
- The low MAE and RMSE indicate relatively small prediction errors.
- Gradient Boosting was the most effective model for revenue prediction in this dataset.

---

📁 Project Structure

E-commerce-Sales-Revenue-Prediction/
│
├── data/
│   └── ecommerce_sales_analytics.csv
│
├── notebook/
│   └── Data_Analysis_Practice.ipynb
│
├── images/
│   └── model_comparison.png
│
├── README.md
└── requirements.txt

---

🚀 How to Run the Project

1. Clone the repository

git clone https://github.com/sweta12646/Machine-Learning-Project.git

2. Install the required libraries

pip install pandas numpy matplotlib seaborn scikit-learn jupyter

3. Open the Jupyter Notebook

jupyter notebook

Open the project notebook and run the cells.

---

🔍 Conclusion

This project demonstrates how different regression techniques can be used to predict e-commerce revenue.

Among the three models tested, Gradient Boosting Regression achieved the highest predictive performance, with approximately 99.85% training accuracy and 99.80% test accuracy based on R².

Therefore, Gradient Boosting Regression was selected as the best-performing model for this dataset.
