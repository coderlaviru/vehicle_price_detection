# 🚗 Vehicle Price Prediction💰

## Overview

This project focuses on predicting vehicle prices using a dataset that contains various features of vehicles such as make, model, year, and other specifications. The goal is to build a robust model that accurately estimates vehicle prices, which can be valuable for both buyers and sellers.

## Dataset

The dataset used for this project is `vehicle_price_prediction.csv`. It contains a variety of information about vehicles, including:

-   **name**: The full name of the vehicle.
    
-   **description**: A brief description of the vehicle.
    
-   **make**: The manufacturer of the vehicle (e.g., Ford, Toyota).
    
-   **model**: The model name of the vehicle.
    
-   **year**: The year the vehicle was manufactured.
    
-   **price**: The price of the vehicle in USD.
    
-   **engine**: Details about the engine.
    
-   **cylinders**: The number of cylinders in the engine.
    
-   **fuel**: The type of fuel used by the vehicle (e.g., Gasoline, Diesel).
    
-   **mileage**: The mileage of the vehicle.
    
-   **transmission**: The type of transmission (e.g., Automatic, Manual).
    
-   **trim**: The trim level of the vehicle.
    
-   **body**: The body style of the vehicle (e.g., SUV, Sedan).
    
-   **doors**: The number of doors on the vehicle.
    
-   **exterior_color**: The exterior color of the vehicle.
    
-   **interior\_color**: The interior color of the vehicle.
    
-   **drivetrain**: The drivetrain of the vehicle (e.g., All-wheel Drive, Front-wheel Drive).

## Files 📂

-   `vehicle_price_prediction.csv`: The dataset containing vehicle information.
    
-   `vehicle_price_prediction.ipynb`: The Jupyter Notebook containing the code for data preprocessing, model training, and evaluation.
    
-   `Predict Vehicle Prices.pdf`: A document providing an overview of the project.
    
-   `vehicle_price_prediction.pptx`: Presentation slides summarizing the project.

## Dependencies ⚙️

-   pandas
-   numpy
-   matplotlib
-   seaborn
-   scikit-learn

## Data Preprocessing 🛠️

The data preprocessing steps included:

-   Handling missing values 🤔.
    
-   Encoding categorical variables using LabelEncoder 🔡.
    
-   Scaling numerical features using StandardScaler.

## Exploratory Data Analysis (EDA) 🔍

-   Univariate and bivariate analysis using matplotlib and seaborn 📊📉.
    
-   Correlation heatmap to analyze relationships between features and the target variable (price).

## Model Selection and Training 🧠

-   **Model**: Random Forest Regressor.
    
-   **Library**: scikit-learn (sklearn.ensemble.RandomForestRegressor).

## Model Evaluation ✅

The model was evaluated using the following metrics:

-   Mean Absolute Error (MAE)
    
-   Mean Squared Error (MSE)
    
-   R² Score

## Results ✨

The Random Forest model performed well in predicting vehicle prices, as shown by the evaluation metrics and visualizations.

## Setup ⚙️

1.  Clone the repository.
2.  Install the required dependencies using `pip install pandas numpy matplotlib seaborn scikit-learn`.
3.  Run the Jupyter Notebook `vehicle_price_prediction.ipynb` to reproduce the results.

## Usage  ▶️

The `vehicle_price_prediction.ipynb` notebook can be used to:

-   Explore the dataset 🧐.
    
-   Preprocess the data 🧹.
    
-   Train the Random Forest Regressor model  🚂.
    
-   Evaluate the model's performance 📈.

## Contributing 🤝

Contributions to this project are welcome! If you have ideas for improvements or find any issues, please feel free to submit a pull request 🚀.

## License 📄

This project is open source and available under the MIT License.
