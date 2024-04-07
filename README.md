# Resale Price Prediction for Flats in Singapore

## Overview

This project aims to develop a machine learning model and deploy it as a user-friendly web application to predict the resale prices of flats in Singapore. The model will be based on historical data of resale flat transactions obtained from the Singapore Housing and Development Board (HDB). The application will assist both potential buyers and sellers in estimating the resale value of a flat by considering various factors such as location, flat type, floor area, and lease duration.

## Motivation

The resale flat market in Singapore is highly competitive, and accurately estimating the resale value of a flat can be challenging due to numerous influencing factors. By leveraging machine learning techniques, this project seeks to provide users with a reliable estimate of resale prices based on historical transaction data. This will empower buyers and sellers to make more informed decisions in the housing market.

## Scope

### Tasks Involved:

1. **Data Collection and Preprocessing:** Collect historical resale flat transaction data from the Singapore HDB website and preprocess it to clean and structure it for machine learning.
2. **Feature Engineering:** Extract relevant features from the dataset, such as town, flat type, storey range, floor area, flat model, and lease commence date. Create additional features if necessary to enhance prediction accuracy.
3. **Model Selection and Training:** Choose an appropriate regression model (e.g., linear regression, decision trees, random forests) and train it on the preprocessed data.
4. **Model Evaluation:** Evaluate the model's performance using regression metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R2 Score.
5. **Web Application Development:** Develop a user-friendly web application using Streamlit, Flask, or Django that allows users to input details of a flat and provides them with a resale price prediction.
6. **Deployment:** Deploy the web application on a cloud platform (e.g., Render) to make it accessible to users over the internet.
7. **Testing and Validation:** Thoroughly test the deployed application to ensure its functionality and accuracy in providing resale price predictions.

### Deliverables:

- Well-trained machine learning model for resale price prediction.
- User-friendly web application deployed on the Render platform.
- Documentation and instructions for using the application.
- Project report summarizing the data analysis, model development, and deployment process.

## Data Source

The dataset used for this project is obtained from the Singapore HDB website, specifically the [Resale Flat Prices](https://beta.data.gov.sg/collections/189/view) collection.

## Results

The project will benefit both potential buyers and sellers in the Singapore housing market by providing them with accurate resale price estimates. Buyers can use the application to make informed decisions, while sellers can gauge their flat's potential market value. Additionally, the project showcases the practical application of machine learning in real estate and web development.
