# Stocks_Dashboard
The Crypto Stock Dashboard lets users track cryptocurrency trends with ease. Select a crypto to view a graph of daily price fluctuations, along with key metrics like opening price, closing price, high, and low values. Designed for simplicity and efficiency, it’s perfect for traders and enthusiasts to analyze market movements at a glance.
# Stocks Dashboard – Automating Data Import for Power BI
![P](https://github.com/user-attachments/assets/3ecdc418-5399-4833-90c6-572860b8e974)
The Stocks Dashboard simplifies importing and analyzing historical stock and cryptocurrency data for Power BI. It automates data fetching, processing, and visualization, making it easier to track market trends effectively.

The dashboard begins by converting dates in the format YYYY-MM-DD into UNIX timestamps, required by Yahoo Finance for specifying date ranges. It dynamically fetches the current date to serve as the end point for historical data retrieval.

A CSV file containing stock symbols and their types (e.g., Stock, Crypto) is processed using Python. The symbols guide the retrieval of historical data for each asset through dynamically constructed Yahoo Finance URLs. This allows the automated download of daily historical data directly into pandas DataFrames.

The data for each stock or cryptocurrency is processed to include additional columns like the asset symbol and type. All individual datasets are then concatenated into a unified DataFrame, ensuring a complete and comprehensive view. The consolidated data includes critical metrics such as open, high, low, close prices, adjusted close, and trading volume.

The resulting dataset is seamlessly integrated into Power BI, enabling users to build dynamic dashboards. These dashboards provide real-time insights into market trends, analyze stock performance, and visualize cryptocurrency fluctuations.

This Stocks Dashboard is a powerful tool that combines Python's automation capabilities with Power BI's visualization strengths, streamlining workflows for analysts and traders while enhancing decision-making efficiency.
# Working
![image 2](https://github.com/user-attachments/assets/20bf7886-5ec5-487a-ab77-f62c56aa0320)
1. Symbol Selection Panel (Left Sidebar):
Displays a list of various cryptocurrency trading pairs (e.g., XRP-USD, BTC-USD).
Users can select a specific cryptocurrency from the list to view its performance details.

2. Main Dashboard Area:
Header Information: Displays the currently selected cryptocurrency pair (e.g., XRP-USD).
Includes a date-time stamp for the latest data.

3. Key Metrics: "OpenValue": Represents the opening price of the selected cryptocurrency.
"open_close_diff": Displays the difference between the opening and closing prices (could indicate market trends or volatility).
"diff%": Shows the percentage change in price, providing a quick performance summary.

4. Candlestick Chart:
Visualizes historical price data (e.g., open, high, low, close) for the selected cryptocurrency.
Offers insight into price trends, including bullish and bearish movements.

5. Timeframe Selection (Top Right):
Offers multiple time intervals, such as 1Y (1 year), 3M (3 months), 5D (5 days), etc.
Enables users to analyze trends over various time periods.

6. Theme Indicators:
Displays weather icons (e.g., day/night mode) to enhance user experience.
This dashboard is a powerful tool for tracking real-time and historical data, empowering traders and analysts to make informed decisions. Its user-friendly design ensures efficient navigation and clear data visualization.

# Benefits:
![image 1](https://github.com/user-attachments/assets/717caff1-ca61-4bed-8e86-3dfc0c34b2a5)
1. Data-Driven Decision Making: The dashboard empowers users to make informed decisions based on real-time market data and insightful analysis.
2. Increased Efficiency: Automation of data extraction and analysis processes saves time and effort.
3. Enhanced Market Understanding: Gain valuable insights into market trends, identify potential opportunities, and track the performance of investments.
4. Improved Communication: Effectively communicate market insights to stakeholders through visually compelling and interactive dashboards.
5. Data Analysts: Enhance your data visualization and reporting skills with advanced Power BI techniques.
6. Financial Analysts: Gain a deeper understanding of financial markets through comprehensive and insightful dashboards.
7. Beginners & Enthusiasts: Learn the fundamentals of Power BI and Python with a step-by-step approach.
8. Developers: Explore the integration of Python and Power BI for creating powerful data solutions.

# Skills Used:
1. Data Extraction & Management:
Python Programming:
Scripting and automation for extracting data from various sources (cryptocurrency exchanges, stock markets, ETF databases).
Data cleaning, transformation, and preparation for analysis.
SQL:
Data querying and manipulation within relational databases.
Power Query:
Data transformation, cleaning, and integration within the Power BI environment.

2. Data Visualization & Reporting:
Power BI:
Creating interactive dashboards and reports.
Designing visualizations like charts, graphs, tables.
Features like slicers, filters, and drill-throughs.
Building and managing data models within Power BI.
DAX (Data Analysis Expressions):
Creating calculated measures and columns for advanced data analysis.
Performing complex calculations and aggregations within Power BI.

3. Data Analysis & Interpretation:
   
4. Software & Tools:
Power BI Desktop
Python
SQL Server/Database Management Systems
Microsoft Excel
