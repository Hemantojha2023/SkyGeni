# SkyGeni
SkyGeni Assignment
Approach

The analysis was conducted using Python in JupyterLab.

Step 1: Data Preparation

Loaded CRM dataset using pandas

Converted deal outcome into binary format (Won = 1, Lost = 0)

Cleaned and structured the data

Step 2: Exploratory Analysis

Calculated win rate by:

Industry

Region

Product type

Compared deal volume vs conversion rate

Step 3: Custom Business Metrics

Two custom metrics were designed:

1️. Revenue Opportunity Efficiency (ROE)

Formula:

ROE = Win Rate × log(1 + Total Deals)

Purpose:

Balance conversion quality and deal volume

Identify scalable high-performance industries

2️. Regional Product Risk Index (RPRI)

Formula:

RPRI = 1 − Win Rate

Purpose:

Detect risky product-region combinations

Highlight underperforming markets

Key Business Insights

FinTech shows the highest win rate → Strong product-market fit.

SaaS and E-commerce have high deal volume but lower win rate → Conversion inefficiency.

SaaS performs well in APAC but poorly in North America → Need for regional strategy.


How to Run the Project
1️. Clone the repository
git clone https://github.com/your-username/SkyGeni.git
cd SkyGeni

2. Install dependencies
pip install -r requirements.txt
pandas
numpy
scikit-learn
matplotlib
seaborn

3️. Run Jupyter Notebook
jupyter lab

Then open:

skygeni.ipynb

Key Decisions:- 

1. Used log scaling in ROE to prevent large deal volume from dominating.

2. Designed custom metrics instead of relying only on win rate.

3. Focused on actionable insights rather than only descriptive statistics.

4. Structured analysis to connect data findings directly to business decisions.
