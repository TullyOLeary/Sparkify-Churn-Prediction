# [Sparkify-Churn-Prediction](https://medium.com/@tullyro/predicting-user-churn-for-sparkify-a-data-driven-journey-in-retention-strategy-226e23b51cd0)

## Project Overview
This project is an in-depth analysis of user churn for Sparkify, a digital music service, where identifying churn patterns is essential to retention strategies. Using Sparkify’s user data, we explore engagement trends, analyze key metrics, and build predictive models that highlight churn-prone user behaviors. This project also details actionable insights that can guide Sparkify's strategies for retaining users.

## Libraries Used
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- JSON

## Files in Repository
- `Sparkify.ipynb`: Main notebook containing the data analysis, exploration, feature engineering, and model development.
- `mini_sparkify_event_data.json`: Dataset used in this analysis (provided by Udacity).
- `README.md`: Project documentation and instructions.

## Summary of Results
The project demonstrates:
- Clear patterns in user engagement by subscription type, showing that paid users generally have higher engagement metrics and less exposure to ads.
- Key features such as the average time between sessions and the number of ads encountered were significant predictors of user churn.
- Ensemble models (Random Forest and XGBoost combined) showed an AUC score of 0.89, providing a robust predictive foundation.

## Business Questions Addressed
1. What are the engagement patterns between free and paid users?
2. What are the most important factors influencing user churn?
3. How can we identify users likely to churn?
4. What actionable strategies can Sparkify implement to reduce churn?

## Blog Post
You can read more about this analysis in my blog post: [Predicting User Churn for Sparkify: A Data-Driven Journey in Retention Strategy](https://medium.com/@tullyro/predicting-user-churn-for-sparkify-a-data-driven-journey-in-retention-strategy-226e23b51cd0).

## Acknowledgements
Dataset provided by Udacity as part of the Nanodegree program.

## Motivation
Understanding churn is vital for any subscription-based service. This project’s insights into user engagement and churn patterns are designed to help Sparkify retain users by identifying the main drivers of user disengagement.

## How to Use This Repository
1. Clone this repository.
2. Run the notebook (`Sparkify.ipynb`) for a detailed analysis and model-building steps.
3. Install necessary libraries by running:
    ```bash
    pip install -r requirements.txt
    ```
4. Adjust the code as needed to test different parameters or add new features for analysis.
