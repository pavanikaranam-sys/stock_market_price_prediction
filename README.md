📈 Stock Market Price Prediction with Live Data

This project predicts stock prices using real-time data from financial APIs. It uses machine learning models to analyze stock trends and forecast future prices based on historical closing values and moving averages.
🚀 Features

    ✅ Fetches real-time stock data using an API (like Alpha Vantage)

    📊 Calculates technical indicators (MA20, MA50)

    🤖 Predicts future stock prices using Linear Regression

    📈 Visualizes actual vs predicted prices

    🧠 Evaluates model with R², MAE, MSE

🛠️ Technologies Used

    Python 🐍

    Pandas, NumPy

    Scikit-learn

    Matplotlib, Seaborn

    Alpha Vantage or yfinance (for live data)


🧪 How It Works

    Fetch stock data using API (e.g., for AAPL, MSFT)

    Compute moving averages:

    df['MA20'] = df['Close'].rolling(window=20).mean()
    df['MA50'] = df['Close'].rolling(window=50).mean()

    Split the data into training and test sets

    Train a Linear Regression model

    Predict closing prices

    Visualize predictions and evaluate metrics

📊 Sample Output

    R² Score: 0.99995+

    MAE: 0.43

    MSE: 0.63



🧑‍💻 Author:
Pavani Karanam
📧 pavanikaranam7@gmail.com
🌐 GitHub: pavanikaranam-sys
