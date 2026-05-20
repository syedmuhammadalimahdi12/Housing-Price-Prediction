# Housing Price Prediction using Machine Learning

## Project Overview

This project is a Machine Learning-based Housing Price Prediction system developed using the California Housing Dataset. The main objective of this project is to predict house prices based on features such as location, number of rooms, population, households, and median income. Random Forest Regression is used to train the model and improve prediction accuracy.

---

## Dataset

The project uses the California Housing Dataset from Kaggle.

Dataset Link:  
https://www.kaggle.com/datasets/camnugent/california-housing-prices

---

## Features Used

- Longitude
- Latitude
- Housing Median Age
- Total Rooms
- Total Bedrooms
- Population
- Households
- Median Income
- Ocean Proximity

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

---

## Machine Learning Model

The Random Forest Regression algorithm is used in this project because it provides high prediction accuracy and handles complex datasets effectively.

---

## Project Workflow

1. Load Dataset
2. Data Preprocessing
3. Handle Missing Values
4. Data Visualization
5. Feature Encoding
6. Feature Scaling
7. Train-Test Split
8. Train Random Forest Model
9. Model Prediction
10. Model Evaluation
11. Save Trained Model

---

## Data Preprocessing

The dataset contains missing values in the `total_bedrooms` column. Missing values are handled using the median value of the column. Categorical data is converted into numerical format using One-Hot Encoding.

---

## Visualizations

The project includes different visualizations for better data understanding:

- House Price Distribution
- Correlation Heatmap
- California Housing Location Plot
- Actual vs Predicted Graph
- Feature Importance Graph

---

## Model Evaluation Metrics

The following metrics are used to evaluate model performance:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R2 Score

The model achieved approximately 85% to 90% R2 Score on the testing dataset.

---

## Manual Prediction

The trained model can predict house prices using custom user input values such as location, rooms, population, and income.

---

## Files Included

- `housing_price_prediction.ipynb`
- `housing_price_prediction.py`
- `requirements.txt`
- `README.md`
- `housing_model.pkl`

---

## How to Run the Project

1. Open Google Colab
2. Upload the dataset file (`housing.csv`)
3. Run all notebook cells
4. Train the model
5. Test custom predictions

---

## Future Improvements

- Deploy model using Flask or Streamlit
- Add GUI for user interaction
- Use advanced models such as XGBoost
- Support datasets from other countries

---

## Author

Syed Muhammad Ali Mahdi

---

## Conclusion

This project demonstrates the implementation of a complete Machine Learning workflow for predicting housing prices using regression techniques. The Random Forest Regression model provides accurate predictions and helps in understanding the impact of different housing features on property prices.