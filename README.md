**Analyzing Historical Stock/Revenue Data and Building a Dashboard**

Final assignment for the IBM Python for Data Science, AI & Development course.

As a data scientist at an investment firm, this project extracts stock price and revenue data for Tesla (TSLA) and GameStop (GME) and builds dashboards that compare share price against revenue.

What the notebook does
#	Task	Method
1	Extract Tesla stock data	yfinance (Ticker("TSLA"), history(period="max"))
2	Extract Tesla revenue data	Web scraping with requests, BeautifulSoup and pandas.read_html
3	Extract GameStop stock data	yfinance (Ticker("GME"), history(period="max"))
4	Extract GameStop revenue data	Web scraping with requests, BeautifulSoup and pandas.read_html
5	Tesla stock and revenue dashboard	Plotly subplots via make_graph()
6	GameStop stock and revenue dashboard	Plotly subplots via make_graph()
7	Share the notebook	Public link to this repository
Files
Analyzing_Historical_Stock_Revenue_Data_and_Building_a_Dashboard.ipynb: the executed notebook with code and outputs for all questions.
Requirements
Python 3.9+
yfinance, pandas, requests, beautifulsoup4, lxml, html5lib, plotly

Install them with:

bash
pip install yfinance pandas requests beautifulsoup4 lxml html5lib plotly
How to run
Open the notebook in Jupyter, JupyterLab or Google Colab.
Run Kernel → Restart & Run All.
Each question's output (tables and dashboards) appears below its code cell.
Dashboards

The make_graph() function draws two stacked charts for each company:

Historical share price (closing price in US dollars)
Historical revenue (quarterly revenue in US millions of dollars)

Stock data is limited to dates up to June 2021 and revenue data to April 2021, to match the revenue data source.

Data sources
Stock prices: Yahoo Finance via the yfinance library
Revenue: static HTML pages provided by the IBM Skills Network course labs

Author
Awais Qarni
