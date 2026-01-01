📊 Impact of Market Sentiment on Trader Performance in Cryptocurrency Markets
📌 Project Overview

This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed) and cryptocurrency trader performance using real historical trading data.
The goal is to uncover how market psychology influences trader behavior, risk-taking, and profitability, and to derive insights that can help in designing smarter trading and risk-management strategies.

The analysis combines:

Market sentiment data (Fear–Greed Index)

Historical trader-level trading data (Hyperliquid)

🎯 Objectives

Study how Fear vs Greed market conditions affect trader performance

Analyze profit & loss (PnL) behavior under different sentiments

Examine leverage usage and risk patterns

Identify hidden behavioral trends among traders

Provide data-driven strategy recommendations

📂 Datasets Used
1️⃣ Bitcoin Market Sentiment Dataset

Columns

Date – Calendar date

Classification – Market sentiment (Fear / Greed)

This dataset represents the emotional state of the crypto market.

2️⃣ Historical Trader Data (Hyperliquid)

Key Columns

account – Trader identifier

symbol – Traded asset

execution price – Price at which trade was executed

size – Trade size

side – Buy / Sell

Timestamp IST – Trade timestamp

closedPnL – Final profit or loss

leverage – Leverage used

This dataset reflects real trader behavior and outcomes.

🛠️ Technologies & Libraries

Python

Pandas – Data manipulation

NumPy – Numerical operations

Matplotlib & Seaborn – Data visualization

SciPy – Statistical testing

Jupyter Notebook

🔄 Workflow

Data Cleaning & Preprocessing

Timestamp conversion

Handling missing values

Feature alignment

Data Integration

Merging trading data with sentiment data using date

Exploratory Data Analysis (EDA)

PnL distribution analysis

Trade frequency comparison

Leverage usage patterns

Statistical Analysis

T-test to validate sentiment impact on PnL

Insight Extraction

Behavioral and risk-related patterns

Identification of consistent traders

📈 Key Insights

Greed periods show higher leverage usage and greater PnL volatility

Fear periods result in more conservative trading and stable returns

High leverage during Greed often leads to larger losses

Increased optimism does not guarantee higher profitability

Only a small fraction of traders are consistently profitable

💡 Strategy Recommendations

Reduce leverage during Greed phases

Avoid overtrading in highly optimistic market conditions

Use market sentiment as a risk filter, not a direct trade signal

Focus on risk management and consistency over emotional trading

📁 Repository Structure
├── primetrade.ipynb        # Main analysis notebook
├── historical_data.csv    # Trader data
├── fear_greed_index.csv   # Market sentiment data
└── README.md              # Project documentation

▶️ How to Run

Clone the repository

git clone https://github.com/your-username/your-repo-name.git


Install dependencies

pip install pandas numpy matplotlib seaborn scipy


Open and run the notebook

jupyter notebook primetrade.ipynb

🎓 Academic & Practical Relevance

This project demonstrates:

Data cleaning and merging

Time-series alignment

Behavioral finance analysis

Statistical reasoning

Real-world trading analytics

Suitable for:

Data Science portfolios

FinTech projects

Academic assignments

Research-oriented analysis

👤 Author

Pappala Karthik
B.Tech – Artificial Intelligence & Data Science
IIITDM Kurnool
GitHub: https://github.com/karthikpappala/Karthik1703

LinkedIn: https://www.linkedin.com/in/karthik-pappala-6b305928a

⭐ Acknowledgements

Bitcoin Fear & Greed Index

Hyperliquid trading data

Open-source Python community
