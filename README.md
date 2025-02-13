# Telco Customer Churn Analysis Project

## **Project Overview**
This project focuses on customer churn prediction for a telecommunications company, aiming to identify high-risk customers and optimize retention strategies. Using machine learning techniques and various resampling methods, the model predicts whether customers will churn based on their subscription history and other features.

## **Project Files**
- **`cleaned_data_telco_customer_churn.csv`**: The cleaned dataset containing customer churn information.
- **`data_telco_customer_churn.csv`**: Raw dataset with customer churn data.
- **`Muhammad Iqbal Hilmy Izzulhaq Capstone Project 3.ipynb`**: Jupyter notebook containing the detailed analysis, data preprocessing, model training, and evaluation.
- **`PPT Muhammad Iqbal Hilmy Izzulhaq.pptx`**: PowerPoint presentation summarizing the project's results and findings.
- **`randomized_search_model.pkl`**: Saved model after hyperparameter tuning using RandomizedSearchCV.
- **`A_professional,_sleek,_blue_pastel-toned_image_ill.png`**: Visual representation of churn analysis.

## **Problem Statement**
The telecommunications industry faces a high churn rate. The goal is to predict customer churn to enable retention strategies and reduce the overall churn rate, thus optimizing marketing resources and maintaining revenue stability.

## **Machine Learning Approach**
- **Data Preprocessing**: Includes cleaning, handling missing values, encoding categorical variables, and feature scaling.
- **Modeling Techniques**: The project uses classification models like Logistic Regression, Gradient Boosting, and XGBoost, alongside different resampling methods (SMOTE, Random OverSampling, Random UnderSampling, etc.) to address class imbalance.
- **Evaluation Metrics**: Focuses on Recall and F2 Score, given the high cost of false negatives (FN) in churn prediction.

## **Key Insights**
- The final model's accuracy was lower compared to the benchmark, but recall was significantly improved by reducing FN.
- The optimized model showed a lower overall cost by improving the FN:FP ratio, reducing costs associated with high-risk customers who were previously undetected.

## **Conclusion & Recommendations**
- The current model can be improved by better understanding churn drivers, advanced resampling techniques, and more sophisticated tuning methods.
- Further exploration of other features and more detailed handling of class imbalances will enhance the model's reliability.
- Regular retraining of the model will help adapt to new trends and improve predictive power over time.

## **Contact**
For any questions or feedback, feel free to reach out at:  
**Muhammad Iqbal Hilmy Izzulhaq**  
JCDS 2502 | BSD
