# Survey Response Score Modeling Using Demographic and Psychometric Factors

## 📌 Project Overview
This project aims to predict **employee survey satisfaction levels** using demographic and psychometric factors.  
Regression techniques are applied to analyze how numerical employee attributes influence overall satisfaction.



## 📂 Dataset Description
- **Source:** https://www.kaggle.com/datasets/redpen12/employees-satisfaction-analysis
- **Target Variable:** `satisfaction_level`
- **Feature Type:** Numerical demographic and psychometric variables
- **Preprocessing:** Missing values handled, irrelevant identifiers removed



## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib



## ⚙️ Data Preprocessing
- Removed non-informative identifier column (`Emp ID`)
- Selected only numerical features
- Handled missing values
- Split data into training and testing sets (80/20)
- Standardized features using `StandardScaler`



## 📈 Models Used
### 1. Linear Regression
- Used as a baseline regression model
- Provides interpretability through feature coefficients

### 2. Ridge Regression
- Applied to reduce overfitting
- Penalizes large coefficients for better generalization


## 📊 Model Evaluation Metrics
- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- R² Score


## 📉 Visualizations

### 🔹 Feature Importance
*(Insert bar chart showing feature coefficients here)*

📎 **Attach Image:**  
<img width="989" height="489" alt="image" src="https://github.com/user-attachments/assets/029df2a3-5549-4e7b-9f41-1fad4baa8288" />



### 🔹 Actual vs Predicted Satisfaction
*(Scatter plot comparing actual and predicted values)*

📎 **Attach Image:**  
<img width="571" height="455" alt="image" src="https://github.com/user-attachments/assets/680824fc-38bb-482f-8fae-e84be5e387bd" />



### 🔹 Residual Analysis
*(Residuals vs predicted values plot)*

📎 **Attach Image:**  
<img width="689" height="547" alt="image" src="https://github.com/user-attachments/assets/e576149d-61ab-4e1c-b1ad-af627b504e4b" />



## 📊 Model Comparison
| Model               | R² Score |
|--------------------|----------|
| Linear Regression  | 0. 42    |
| Ridge Regression   | 0. 45    |



## ✅ Results & Insights
- Satisfaction levels can be reasonably predicted using numeric employee attributes.
- Performance evaluation and working hours significantly influence satisfaction.
- Ridge Regression improves model stability over basic Linear Regression.


## 🧠 Conclusion
The project demonstrates that demographic and psychometric factors play an important role in determining employee satisfaction. Regression-based approaches provide interpretable and effective predictive models, making them suitable for organizational survey analysis.


## 🚀 Future Improvements
- Include categorical features using encoding
- Apply advanced models like Random Forest or Gradient Boosting
- Perform hyperparameter tuning
- Increase dataset size for better generalization


