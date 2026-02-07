# Crop_Yield_Prediction_Using_Machine Learning
🌾 Crop Yield Prediction using Machine Learning
#📌Project Overview:This project implements a machine learning–based predictive model to estimate future crop yield using historical agricultural and environmental data. The model analyzes factors such as rainfall, temperature, pesticide usage, and year to predict crop production.The focus of this project is on model reasoning and explainability, not just achieving high accuracy.
🎯 Problem Statement:Build a predictive model using a real or public dataset to predict a future value and explain the results.In this project, a crop yield dataset is used to predict future crop yield values based on past trends and environmental conditions.
📊 Dataset Description:
Dataset: yield_df.csv
Type: Public agricultural dataset
Features:
.Year
.Average Rainfall
.Average Temperature
.Pesticide Usage
.Target Variable:
.Crop Yield
🔄 Model Pipeline:
1.Dataset loading and exploration
2.Data preprocessing
.Handling missing values
.Feature selection
.Data transformation
3.Train–test split
4.Model selection and training
5.Model evaluation using regression metrics
6.Saving trained model and preprocessing steps
7.Future crop yield prediction and inference explanation
🤖 Machine Learning Model Used
.Decision Tree Regressor
>Selected for its ability to capture non-linear relationships
>Easy to interpret and explain
>Suitable for real-world agricultural data
📈 Evaluation Metrics
.Mean Absolute Error (MAE):
Measures the average difference between predicted and actual crop yield values.
.R² Score:
Indicates how well the model explains variations in crop yield.
🔍 Results & Inference
.The model successfully learns relationships between environmental factors and crop yield.
.Sample prediction output:
Predicted Future Crop Yield: 512.45
.This value represents the expected crop yield under given environmental conditions.
.Rainfall and temperature were observed to have a strong influence on crop production.
🛠️ Technologies Used
.Python
.Pandas
.NumPy
.Scikit-learn
.Flask (for deployment)
.Jupyter Notebook
✅ Conclusion:This project demonstrates an end-to-end machine learning workflow, including data preprocessing, model training, evaluation, and deployment. It highlights strong ML fundamentals, effective data handling, and a clear focus on explainable predictions aligned with real-world agricultural applications.
