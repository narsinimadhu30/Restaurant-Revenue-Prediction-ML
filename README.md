

\# Restaurant Revenue Prediction





\## Project Overview



This project focuses on predicting restaurant revenue using machine learning regression techniques.



The goal is to estimate the expected revenue of a restaurant based on structured operational and business-related features. The project demonstrates an end-to-end ML pipeline including data preprocessing, model training, evaluation, and model comparison.





\## Dataset Information



Dataset Link:- https://drive.google.com/file/d/1LjGoQqL6gjXG7MR-xrqtwm1PjClxu98y/view?usp=sharing



* **Total Samples**: 100 restaurants
* **Total Features**: 8 columns
* **Target Variable**: Revenue
* **Problem Type**: Supervised Regression



The dataset contains structured numerical features representing restaurant attributes influencing revenue.



Due to the relatively small dataset size, special care was taken to prevent overfitting and ensure proper validation.





\## Workflow



1\. Data Loading

2\. Exploratory Data Analysis (EDA)

3\. Data Cleaning

4\. Train-Test Split

5\. Model Training

6\. Model Evaluation

7\. Model Comparison Visualization





\## Models Implemented



* Linear Regression (Baseline Model)
* Decision Tree Regressor
* Random Forest Regressor



Each model was evaluated and compared using regression metrics.





\## Evaluation Metrics



The following metrics were used:



\* MAE (Mean Absolute Error)

\* MSE (Mean Squared Error)

\* RMSE (Root Mean Squared Error)

\* R² Score





\## Final Model Performance



Average Revenue: ₹ 46,61,188

RMSE: ₹ 6,74,445

RMSE %: 12.28%



This means the model's predictions are off by approximately 11% relative to the average revenue, which indicates good predictive performance for a dataset of this size.





\## Key Learnings



* &nbsp;Understanding regression fundamentals
* &nbsp;Comparing multiple ML models
* &nbsp;Interpreting business-focused error metrics
* &nbsp;Handling small datasets carefully
* &nbsp;Avoiding overfitting





\## Tech Stack



* &nbsp;Python
* &nbsp;Pandas
* &nbsp;NumPy
* &nbsp;Scikit-learn
* &nbsp;Matplotlib



\## Future Improvements



* &nbsp;Apply K-Fold Cross Validation
* &nbsp;Log transformation of revenue
* &nbsp;Hyperparameter tuning's
* &nbsp;Implement Gradient Boosting / XGBoost
* &nbsp;Deploy model using FastAPI









\## Conclusion



This project demonstrates a complete machine learning regression pipeline for revenue prediction. Despite the small dataset size, the model achieved strong predictive performance and highlights the importance of proper evaluation and benchmarking.



