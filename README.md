📊 Impact of Market Sentiment on Trader Performance in Cryptocurrency Markets

📌 Project Overview

This project investigates how Bitcoin market sentiment—captured using the Fear & Greed Index—impacts cryptocurrency trader performance using real historical trading data from Hyperliquid.

By combining behavioral finance with data-driven analysis, the study explores how emotions like fear and greed influence trader decision-making, leverage usage, risk exposure, and overall profitability. The insights derived aim to support smarter trading strategies and improved risk management.
🎯 Objectives

Analyze trader performance under Fear vs Greed market conditions

Examine Profit & Loss (PnL) behavior across sentiment phases

Study leverage usage and risk-taking patterns

Identify behavioral trends among traders

Provide actionable, data-driven trading recommendations

📂 Datasets Used
1️⃣ Bitcoin Market Sentiment Dataset (Fear & Greed Index)

Columns

Date – Calendar date

Classification – Market sentiment (Fear / Greed)

This dataset represents the emotional state of the crypto market.

2️⃣ Historical Trader Data (Hyperliquid)

Key Columns

account – Trader identifier

symbol – Traded asset

execution price – Trade execution price

size – Trade size

side – Buy / Sell

Timestamp IST – Trade timestamp

closedPnL – Final profit or loss

leverage – Leverage used

This dataset reflects real-world trader behavior and outcomes.

🛠️ Technologies & Libraries

Python

Pandas – Data manipulation

NumPy – Numerical operations

Matplotlib & Seaborn – Data visualization

SciPy – Statistical testing

Jupyter Notebook

🔄 Workflow
1️⃣ Data Cleaning & Preprocessing

Timestamp conversion

Handling missing values

Feature standardization

2️⃣ Data Integration

Merging trading data with sentiment data using date alignment

3️⃣ Exploratory Data Analysis (EDA)

PnL distribution analysis

Trade frequency comparison

Leverage usage patterns

4️⃣ Statistical Analysis

T-test to validate the impact of sentiment on PnL

5️⃣ Insight Extraction

Behavioral and risk-related patterns

Identification of consistently profitable traders

📈 Key Insights

Greed periods show higher leverage usage and increased PnL volatility

Fear periods encourage conservative trading and more stable returns

High leverage during Greed often results in larger losses

Market optimism does not guarantee higher profitability

Only a small fraction of traders are consistently profitable

💡 Strategy Recommendations

Reduce leverage during Greed-dominated markets

Avoid overtrading in highly optimistic conditions

Use sentiment as a risk filter, not a direct buy/sell signal

Prioritize risk management and consistency over emotional trading

📁 Repository Structure
├── primetrade.ipynb          # Main analysis notebook
├── historical_data.csv       # Trader-level trading data
├── fear_greed_index.csv      # Bitcoin market sentiment data
└── README.md                 # Project documentation

▶️ How to Run
1️⃣ Clone the repository
git clone https://github.com/your-username/your-repo-name.git

2️⃣ Install dependencies
pip install pandas numpy matplotlib seaborn scipy

3️⃣ Run the notebook
jupyter notebook primetrade.ipynb

🎓 Academic & Practical Relevance

This project demonstrates:

Data cleaning and preprocessing

Time-series alignment

Behavioral finance analysis

Statistical hypothesis testing

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

🔗 GitHub: https://github.com/karthikpappala/Karthik1703

🔗 LinkedIn: https://www.linkedin.com/in/karthik-pappala-6b305928a

⭐ Acknowledgements

Bitcoin Fear & Greed Index

Hyperliquid trading data

Open-source Python community
