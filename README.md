# Stocks_Dashboard
The Crypto Stock Dashboard lets users track cryptocurrency trends with ease. Select a crypto to view a graph of daily price fluctuations, along with key metrics like opening price, closing price, high, and low values. Designed for simplicity and efficiency, it’s perfect for traders and enthusiasts to analyze market movements at a glance.
# Stocks Dashboard – Automating Data Import for Power BI
The Stocks Dashboard simplifies importing and analyzing historical stock and cryptocurrency data for Power BI. It automates data fetching, processing, and visualization, making it easier to track market trends effectively.

The dashboard begins by converting dates in the format YYYY-MM-DD into UNIX timestamps, required by Yahoo Finance for specifying date ranges. It dynamically fetches the current date to serve as the end point for historical data retrieval.

A CSV file containing stock symbols and their types (e.g., Stock, Crypto) is processed using Python. The symbols guide the retrieval of historical data for each asset through dynamically constructed Yahoo Finance URLs. This allows the automated download of daily historical data directly into pandas DataFrames.

The data for each stock or cryptocurrency is processed to include additional columns like the asset symbol and type. All individual datasets are then concatenated into a unified DataFrame, ensuring a complete and comprehensive view. The consolidated data includes critical metrics such as open, high, low, close prices, adjusted close, and trading volume.

The resulting dataset is seamlessly integrated into Power BI, enabling users to build dynamic dashboards. These dashboards provide real-time insights into market trends, analyze stock performance, and visualize cryptocurrency fluctuations.

This Stocks Dashboard is a powerful tool that combines Python's automation capabilities with Power BI's visualization strengths, streamlining workflows for analysts and traders while enhancing decision-making efficiency.
![P](https://github.com/user-attachments/assets/3ecdc418-5399-4833-90c6-572860b8e974)
# Working
1. Symbol Selection Panel (Left Sidebar):
Displays a list of various cryptocurrency trading pairs (e.g., XRP-USD, BTC-USD).
Users can select a specific cryptocurrency from the list to view its performance details.

2. Main Dashboard Area:
Header Information: Displays the currently selected cryptocurrency pair (e.g., XRP-USD).
Includes a date-time stamp for the latest data.
Key Metrics: "OpenValue": Represents the opening price of the selected cryptocurrency.

"open_close_diff": Displays the difference between the opening and closing prices (could indicate market trends or volatility).
"diff%": Shows the percentage change in price, providing a quick performance summary.

Candlestick Chart:
Visualizes historical price data (e.g., open, high, low, close) for the selected cryptocurrency.
Offers insight into price trends, including bullish and bearish movements.

Timeframe Selection (Top Right):
Offers multiple time intervals, such as 1Y (1 year), 3M (3 months), 5D (5 days), etc.
Enables users to analyze trends over various time periods.

Theme Indicators:
Displays weather icons (e.g., day/night mode) to enhance user experience.
This dashboard is a powerful tool for tracking real-time and historical data, empowering traders and analysts to make informed decisions. Its user-friendly design ensures efficient navigation and clear data visualization.
