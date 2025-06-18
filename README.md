Investment Advisor
Overview
The Investment Advisor is a comprehensive platform designed to assist users in managing their investments, including mutual funds, stocks, and tax planning. This project leverages machine learning, data visualization, and AI-powered recommendations to provide personalized financial insights. Built with Python and Streamlit, it offers a user-friendly interface for exploring funds, optimizing portfolios, analyzing stocks, and planning taxes.
Features

User Profile Management: Create and save personalized investment profiles based on age, income, risk tolerance, and goals.
Mutual Fund Recommendations: AI-driven recommendations using KNN and Random Forest algorithms tailored to user profiles.
Portfolio Optimization: Optimize portfolio allocation for maximum returns using Modern Portfolio Theory (MPT).
Stock Analysis: Analyze stock performance with historical data, technical indicators, and financial metrics from Yahoo Finance and Screener.in.
Tax Planning: Calculate capital gains tax and get ELSS fund recommendations for tax savings under Section 80C.
Interactive Visualizations: Explore fund performance and risk-return analysis with Plotly charts.

Requirements

Python 3.8+
Required Python packages (install via pip install -r requirements.txt):
streamlit
pandas
numpy
scikit-learn
scipy
plotly
yfinance
requests
beautifulsoup4
mftool
groq



Installation

Clone the repository:git clone https://github.com/Atharv901/investment-advisor.git
cd investment-advisor


Install the required dependencies:pip install -r requirements.txt


Set up environment variables (e.g., Groq API key):
Create a .env file and add GROQ_API_KEY=your_api_key_here.
Install python-dotenv if needed: pip install python-dotenv.


Run the application:streamlit run app.py



Usage

Navigate through the sidebar menu to access different sections:
Home: Overview and key features.
User Profile: Set up your financial profile.
Explore Funds: Browse and filter mutual funds.
Fund Recommendations: Get personalized fund suggestions.
Portfolio Optimization: Optimize your investment allocation.
Stock Analysis: Analyze individual stocks.
Tax Planning: Plan investments for tax efficiency.


Follow the on-screen instructions to input data and generate insights.

Files

app.py: Main Streamlit application file.
tax.py: Tax calculation and ELSS recommendation logic.
data_processor.py: Data preprocessing for mutual fund analysis.
portfolio_optimizer.py: Portfolio optimization using MPT.
tax_planning.py: Tax planning UI and calculations.
visualizations.py: Plotly-based visualization functions.
llm_integration.py: Integration with Groq LLM for SIP and portfolio suggestions.
recommendation_engine.py: Hybrid ML recommendation system.

Data

The application uses a sample dataset (comprehensive_mutual_funds_data.csv) included in the attached_assets directory.
Stock data is fetched live from Yahoo Finance and Screener.in.

Contributing
Contributions are welcome! Please fork the repository and submit pull requests for any enhancements or bug fixes.
Disclaimer
The investment analysis and recommendations provided are based on historical data and AI analysis. Past performance is not indicative of future results. Always conduct your own research and consult a financial advisor before making investment decisions.
License
This project is licensed under the MIT License - see the LICENSE file for details.
