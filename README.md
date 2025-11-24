# 🚗 Fuel Efficiency Prediction Using Regression Models

## 📝 Project Summary
This project predicts the **fuel efficiency (MPG)** of automobiles using key vehicle attributes such as **horsepower, displacement, weight, acceleration, cylinders, origin, and model year**.

The workflow includes:
- Data preprocessing and feature engineering  
- Building multiple regression models:  
  - **Linear Regression**  
  - **Random Forest Regressor**  
- Comparing the performance of each model

Among all models tested, the **Random Forest Regressor** delivered the best performance with an **R² score of 0.88**, effectively capturing complex non-linear relationships in the data and providing the most accurate fuel efficiency predictions.

## 📈 Insights

- The analysis revealed a **strong negative correlation** between horsepower, displacement, weight, and fuel efficiency (MPG) — meaning heavier and more powerful vehicles consume more fuel.
- **Model year** showed a positive correlation with MPG, indicating that newer cars are generally more fuel-efficient due to technological advancements.
- After comparing multiple regression models, the **Random Forest Regressor** achieved the best performance (**R² = 0.88**), followed by Ridge and Lasso Regression.
- **Ridge Regression** performed slightly better than Linear Regression, reducing overfitting and improving prediction stability.
- The project demonstrates how **data-driven insights** can guide automotive manufacturers to design **lighter, more efficient, and eco-friendly vehicles**.
- The developed model can be integrated into **vehicle design simulations** to predict MPG before production, saving both time and cost.
