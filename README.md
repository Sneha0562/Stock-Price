📊 Stock Analysis using Python & yFinance
📝 Overview

This is a beginner-friendly Python project for basic stock market analysis.
It uses the yfinance library to download real-time stock data and performs simple moving average (SMA) analysis to visualize trends.

🚀 Features

Fetches stock price data using Yahoo Finance API (yfinance)

Calculates 20-day and 50-day moving averages

Displays an interactive stock chart with trend lines

Saves all analyzed data to a CSV file

🧰 Technologies Used

Python 3.x

yfinance → for fetching stock data

pandas → for data manipulation

matplotlib → for plotting stock trends

📦 Installation

Clone or download this repository:

git clone https://github.com/yourusername/stock-analysis.git
cd stock-analysis


Install the required Python packages:

pip install yfinance pandas matplotlib

▶️ How to Run

Open the script:

stock_analysis.py


Inside the script, you can set the stock ticker you want to analyze:

ticker = "AAPL"     # Apple
# Example options:
# ticker = "TSLA"   # Tesla
# ticker = "INFY.NS" # Infosys India


Run the script:

python stock_analysis.py


Output:

A plot showing stock price with 20-day and 50-day moving averages

A CSV file named AAPL_stock_data.csv (or your ticker symbol)

📈 Example Output


(Example: Apple stock with SMA 20 & SMA 50)

🧠 Future Improvements

Add RSI, MACD, and Bollinger Bands

Show Buy/Sell signals when moving averages cross

Build a Streamlit dashboard for live analysis

💬 Author

👩‍💻 Sneha Hegde
Exploring Python & Finance
