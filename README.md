# Product-quality-produced-by-a-roasting-machine

This project focuses on predicting production quality using machine learning models based on historical production data. The dataset includes input features (data_X.csv), target quality metrics (data_Y.csv), and a submission template (sample_submission.csv). To ensure temporal alignment, the data is preprocessed by converting timestamps, grouping features by hour, and shifting the quality metrics to match the corresponding production inputs. Additional features such as year, month, day, and hour are extracted to enhance the predictive modeling.

Principal Component Analysis (PCA) is applied to reduce the dimensionality of the dataset while retaining 95% of the variance. Several regression models, including Random Forest and XGBoost, are trained on the processed dataset to predict production quality. The models are evaluated using Mean Absolute Error (MAE) to ensure reliable performance. The best-performing model is selected based on the lowest MAE score, ensuring accuracy and robustness in the final predictions.

The final predictions are made on a validation dataset and updated in the submission template. This project demonstrates a complete end-to-end pipeline, from data preprocessing and feature engineering to model selection and deployment. It highlights the use of PCA for dimensionality reduction and ensemble methods like Random Forest and XGBoost for their effectiveness in handling tabular data. The repository includes reproducible steps, making it easy to adapt and extend for similar use cases.

I have taken the dataset from kaggle, You can access the dataset from [here](https://www.kaggle.com/datasets/podsyp/production-quality/data)
