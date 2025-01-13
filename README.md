# Laptop Price Prediction Using Machine Learning

This project predicts the price of laptops based on various features like brand, specifications, and other attributes. It uses machine learning algorithms to analyze the data and provide accurate price predictions.

## Features of the Project
- Cleaned and preprocessed raw data for better model performance.
- Explored and visualized data to identify trends and correlations.
- Implemented feature engineering for optimal input to the model.
- Trained and evaluated multiple machine learning algorithms.
- Built a user-friendly interface for input and prediction.

## Tech Stack
- **Programming Language**: Python
- **Libraries Used**: 
  - Pandas (Data manipulation and analysis)
  - NumPy (Numerical computations)
  - Scikit-learn (Machine learning algorithms)
  - Matplotlib & Seaborn (Data visualization)

## Dataset
- The dataset contains information on laptop brands, specifications (e.g., RAM, processor, storage), and prices.
- Preprocessed to handle missing values, normalize numerical data, and encode categorical features.

## Steps in the Project
1. **Data Collection**: Collected a dataset of laptops with their specifications and prices.
2. **Data Cleaning**: Removed missing values, handled outliers, and formatted data.
3. **Exploratory Data Analysis (EDA)**: Visualized relationships between price and features.
4. **Feature Engineering**: Selected and transformed features to improve model accuracy.
5. **Model Training**:
   - Trained models like Linear Regression, Random Forest, and XGBoost.
   - Performed hyperparameter tuning for best results.
6. **Evaluation**: Assessed model performance using metrics like MAE, MSE, and R2 score.
7. **Prediction**: Built a pipeline for predicting laptop prices based on user inputs.

## How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/laptop-price-prediction.git
   cd laptop-price-prediction

## Install the required libraries:
- pip install -r requirements.txt
- python app.py


##Results

    Achieved a high prediction accuracy with Random Forest.
    Key insights from the data:
        Brand and processor have a significant impact on price.
        RAM and storage also influence pricing significantly.
