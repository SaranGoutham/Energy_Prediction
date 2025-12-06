# Energy Prediction

A machine learning project for predicting hourly energy consumption using the American Electric Power (AEP) dataset.

## 📊 Project Overview

This project implements time series forecasting to predict electrical energy consumption patterns based on historical hourly data from AEP's eastern grid. The analysis helps understand energy usage trends and enables more efficient power grid management and planning.

## 🎯 Objectives

- Analyze historical energy consumption patterns
- Build predictive models for energy demand forecasting
- Identify temporal patterns (hourly, daily, seasonal)
- Provide accurate forecasts to optimize grid operations

## 📁 Repository Structure

```
Energy_Prediction/
├── AEP_energy_prediction.ipynb    # Main analysis notebook
├── AEP_hourly.csv                 # Original dataset
├── processed_AEP_hourly.csv       # Preprocessed data
├── .gitignore                     # Git ignore file
└── README.md                      # Project documentation
```

## 📈 Dataset

**Source**: American Electric Power (AEP) Hourly Energy Consumption

**Features**:
- **Datetime**: Timestamp for each observation
- **AEP_MW**: Energy consumption in Megawatts (MW)

**Time Period**: Hourly recordings spanning multiple years

**Format**: CSV (Comma-Separated Values)

## 🛠️ Technologies Used

- **Python 3.x**
- **Jupyter Notebook**
- **Key Libraries**:
  - `pandas` - Data manipulation and analysis
  - `numpy` - Numerical computing
  - `matplotlib` / `seaborn` - Data visualization
  - `scikit-learn` - Machine learning models
  - `statsmodels` - Time series analysis (potential)
  - `prophet` / `LSTM` / `ARIMA` - Forecasting models (potential)

## 🔍 Analysis Workflow

1. **Data Loading & Exploration**
   - Import and inspect the dataset
   - Check for missing values and anomalies
   - Basic statistical analysis

2. **Data Preprocessing**
   - Handle missing values
   - Feature engineering (extract hour, day, month, year)
   - Create lag features for time series
   - Normalize/scale data

3. **Exploratory Data Analysis (EDA)**
   - Visualize consumption patterns over time
   - Identify daily and seasonal trends
   - Analyze correlations and distributions

4. **Model Development**
   - Split data into training and testing sets
   - Train multiple forecasting models
   - Tune hyperparameters for optimal performance

5. **Model Evaluation**
   - Compare model performance using metrics:
     - Mean Absolute Error (MAE)
     - Mean Squared Error (MSE)
     - Root Mean Squared Error (RMSE)
     - R² Score
   - Visualize predictions vs actual values

6. **Results & Insights**
   - Present best performing model
   - Discuss findings and patterns
   - Provide recommendations

## 🚀 Getting Started

### Prerequisites

```bash
python >= 3.7
jupyter notebook
```

### Installation

1. Clone the repository:
```bash
git clone https://github.com/SaranGoutham/Energy_Prediction.git
cd Energy_Prediction
```

2. Install required packages:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Usage

1. Launch Jupyter Notebook:
```bash
jupyter notebook
```

2. Open `AEP_energy_prediction.ipynb`

3. Run cells sequentially to reproduce the analysis

## 📊 Key Insights

*Analysis results will include*:
- Peak consumption hours and periods
- Seasonal variations in energy demand
- Model accuracy metrics
- Feature importance rankings
- Forecast visualizations

## 🎓 Learning Outcomes

- Time series data preprocessing techniques
- Feature engineering for temporal data
- Implementation of forecasting algorithms
- Model evaluation and comparison
- Energy consumption pattern analysis

## 🔮 Future Enhancements

- [ ] Incorporate weather data for improved predictions
- [ ] Implement advanced models (LSTM, GRU, Transformers)
- [ ] Add real-time prediction capabilities
- [ ] Deploy model as a web application
- [ ] Expand to multi-region predictions
- [ ] Include anomaly detection for unusual consumption patterns

## 📚 References

- [AEP - American Electric Power](https://www.aep.com/)
- Kaggle: [Hourly Energy Consumption Dataset](https://www.kaggle.com/datasets/robikscube/hourly-energy-consumption)
- Time Series Forecasting Best Practices

## 👤 Author

**Saran Goutham**

- GitHub: [@SaranGoutham](https://github.com/SaranGoutham)

## 📝 License

This project is open source and available for educational purposes.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

---

⭐ Star this repository if you find it helpful!
