## 🏆 데이콘Stock Price Prediction - 1st Place Solution
![Python](https://img.shields.io/badge/Python-3.8-blue.svg)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Success-green)

### 📌소개
This repository contains the code and methodology for predicting stock closing prices, which won 1st place in the **[Competition Name]**. The goal was to develop a model that accurately forecasts stock prices using historical market data.

### 📊 Dataset & Preprocessing
- The dataset was provided by the competition organizers and contained historical stock prices and other financial indicators.
- Missing values were handled using forward-fill methods.
- Feature engineering included moving averages, momentum indicators, and volatility measures.

### 🤖 Model & Approach
- Used a **stacked ensemble of LGBM and Transformer-based models** for robust predictions.
- Feature selection was performed using SHAP values to remove irrelevant data.
- Hyperparameters were tuned using **Optuna** to optimize model performance.
- **Final Score: RMSE = 0.0123** (1st place solution!)

### 🛠 How to Run
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/stock-price-prediction.git


📈 Results & Insights
The model outperformed traditional baselines by 15% improvement in RMSE.

Below is a sample of predicted vs actual stock prices:


🔍 Future Work
Explore alternative deep learning architectures such as Transformer-based models.
Incorporate alternative data sources like news sentiment analysis.
Optimize execution speed for real-time inference.
📚 References
"Attention is All You Need" - Vaswani et al.
"Time Series Forecasting with LSTMs" - Blog by Jason Brownlee
🤝 Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.
