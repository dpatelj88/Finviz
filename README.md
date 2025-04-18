# Finviz Stock Screener Automation

This project automates stock screening using Finviz to identify stocks meeting specific criteria, saves results to text files, commits them to GitHub, and sends SMS notifications with ticker symbols. It runs three predefined scans: 52wk-high, ATH, and 52wk10retrace.

# Features

Three Stock Scans:

52wk-high: Stocks at 52-week highs (Avg Volume > 1M, Current Volume > 1M, Price > $50, ATR > 3, Above 50/200 SMA).

ATH: Stocks at all-time highs (Avg Volume > 1M, Current Volume > 1M, Price > $30, Above 50/200 SMA).

52wk10retrace: Stocks 0-10% below 52-week highs (Avg Volume > 1M, Current Volume > 1M, Price > $50, ATR > 3, Above 20/50/200 SMA).

Result Storage: Saves results as formatted text files in Results/52WK-High, Results/ATH, and Results/52Wk10Retrace.
