# Nutrition Analysis Predictor - Predictive Modelling in Nutrition 

This repository is an exploration of predictive models in the realm of nutrition and wellness. We have developed various models to predict Body Mass Index (BMI) based on various nutrition and lifestyle factors. 

The work represented here is suitable for nutritionists, fitness trainers, and health tech companies looking for an understanding of predictive modeling in nutrition, or wanting to implement these models into their own systems.

## 📝 Dataset 

Our dataset comprises numerous variables that reflect a person's nutrition habits, lifestyle habits, and demographics. These variables include:

1. `Gender`
2. `Age`
3. `Height`
4. `Weight`
5. `family_history_with_overweight` 
6. `JUNK` (Intake of junk food)
7. `VeggieCount` (Number of servings of vegetables per day)
8. `MealCount` (Number of meals per day)
9. `Snacking` (Snacking habits)
10. `SMOKE` (Smoking habits)
11. `CH2O` (Daily water intake)
12. `CalorieMonitoring` (Whether the person monitors their calorie intake or not)
13. `ActivityFreq` (Frequency of physical activity)
14. `Screentime` (Amount of screen time per day)
15. `AlcoholFreq` (Frequency of alcohol intake)
16. `Transportation` (Primary mode of transportation)
17. `BMI` (Body Mass Index) - **Target variable**

These variables form the basis of our predictions.

## 📈 Models 

We've employed several models and evaluated their performance on this dataset. The table below illustrates the models we used and their performance:

| Model | Mean Absolute Error (MAE) | Mean Squared Error (MSE) | Root Mean Squared Error (RMSE) | R2 Score | RMSE (Cross-Validation) |
| --- | --- | --- | --- | --- | --- |
| RandomForestRegressor | 5.262574 | 74.706264 | 8.643279 | 0.89405 | 16.356488 |
| SVR | 9.43287 | 175.509946 | 13.248017 | 0.751089 | 24.24906 |
| Ridge | 14.106736 | 310.850615 | 17.630956 | 0.559147 | 24.521576 |
| LinearRegression | 14.166991 | 310.877068 | 17.631706 | 0.559109 | 24.621349 |
| Lasso | 16.393615 | 413.850997 | 20.343328 | 0.41307 | 26.452884 |

In addition to using the standard configurations of these models, we also employed hyperparameter tuning to optimize their performance.

**Note**: This project is exploratory and meant for educational purposes. The results and models should not be used for medical or diagnostic purposes.

For any queries or suggestions, feel free to open an issue. Contributions are also welcomed! 

Stay healthy! 🍎🥦💪

