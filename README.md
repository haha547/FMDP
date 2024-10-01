# Financial Market Data Platform

This project is a personal side project developed alongside my Ph.D. studies in computer science. It is designed to showcase my technical and financial skills by building a comprehensive platform for stock data analysis, timing strategies, asset allocation simulation, and personalized financial advice, all integrated into a Django-based web application.

## Features

### 1. Stock Data Crawler
- **Description**: A web crawler that collects historical stock data from the Taiwan Stock Exchange (TSE) and Over-the-Counter (OTC) market.
- **Technology**: Python, SQLite.
- **Status**: Completed.
- **Details**: 
  - The crawler collects daily data such as opening price, closing price, highest price, lowest price, and trading volume.
  - Data is stored in an SQLite database for efficient querying.
  - Automatic updates are scheduled daily.

### 2. Django-based Stock Query Website (Integrated with Timing Strategy, Asset Allocation, and LLM-based Analysis)
- **Description**: A web application that allows users to query stock data, visualize trends, analyze timing strategies, simulate asset allocation, and receive personalized financial advice.
- **Technology**: Django, JavaScript, PyTorch, PyPortfolioOpt, OpenAI API (for LLM).
- **Status**: In progress.
- **Details**:
  - **Stock Query and Timing Strategy**: Users can query stock data and view timing strategy suggestions (e.g., buy/sell signals based on technical indicators and machine learning models).
  - **Asset Allocation Simulation**: Users can create custom portfolios by selecting multiple stocks, and the system will simulate asset allocation based on user-defined preferences (e.g., risk tolerance, industry preference). Backtesting results are also provided to evaluate past performance.
  - **LLM-based Financial Report Analysis**: Automatically analyzes company financial reports and generates key metrics or recommendations. Users can input their investment preferences (e.g., risk level, industry sectors), and the system will use LLM to suggest suitable asset allocations.

## Future Plans
- Enhance user interface for personalized financial recommendations.
- Implement more advanced visualizations and expand international stock data coverage.
- Refine backtesting functionality for both timing strategies and asset allocation.

## Contact
If you're interested in this project or have any questions, feel free to contact me at [your email].
