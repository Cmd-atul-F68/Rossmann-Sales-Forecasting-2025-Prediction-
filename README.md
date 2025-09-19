# Rossmann-Sales-Forecasting-2025-Prediction
# Rossmann Store Sales Forecasting

This project focuses on forecasting **Rossmann store sales** using historical sales data (2013–2015) and a **Random Forest model** built with scikit-learn. It provides a practical example of an **end-to-end retail demand forecasting pipeline** that can be adapted for similar business scenarios.

## 📊 Project Overview  
- **Data Preprocessing & Feature Engineering**  
  Cleaned and processed the Rossmann dataset, handled mixed data types, and engineered features (store info, dates, promotions) to make it ML-ready.  

- **Model Training**  
  Trained a Random Forest model on historical data to learn sales patterns and saved the model for reuse.  

- **Future Forecasting**  
  Generated synthetic feature data for **September 2025** aligned with training data format. Predicted daily sales using the trained model.  

- **Comparison with Historical Data**  
  Selected a historical month from 2015 and compared it to the predicted 2025 month to visualize how sales trends might evolve.  

- **Visualization**  
  Created and saved a graph comparing **historical vs. predicted sales** for easy interpretation.  

## 📁 Repository Structure

Rossmann_Sales_Forecasting/
├── README.md <- Project overview & instructions
├── requirements.txt <- Python dependencies
├── data/ <- Original & future feature data
│ ├── train.csv
│ └── future_features_with_storeinfo.csv
├── models/ <- Saved model file
│ └── rossmann_rf_model.pkl
├── outputs/ <- Predictions & generated graphs
│ ├── future_sales_predictions.csv
│ └── historical_vs_future_plot.png
└── notebooks/ <- Jupyter notebooks
└── Rossmann_Forecast.ipynb


## 🛠 Requirements  
Install all dependencies with:  

```bash
pip install -r requirements.txt
🚀 Usage

Open the Jupyter notebook:

jupyter notebook notebooks/Rossmann_Forecast.ipynb


Run the cells to preprocess data, train the model (optional), and generate forecasts.

📈 Results

Daily predictions for September 2025

Comparison graph between 2015 and 2025 sales trends

Reusable Random Forest model for future predictions

