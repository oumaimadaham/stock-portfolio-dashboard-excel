# Stock Portfolio Dashboard (Excel)
A complete, step-by-step data analyst case study that turns stock price data extracted from **Yahoo Finance** via **Google Sheets** into a polished Excel dashboard for tracking portfolio performance, sector exposure, and daily movers.

**Goal**: Provide a reproducible blueprint that anyone can clone, open in Excel, refresh, and immediately see their portfolio KPIs.
---

## Business Problem
Investors often need a clean way to track portfolio performance and stock movements.

The dashboard answers key questions:
- What is my current portfolio value?
- What is my overall profit/loss and % return?
- Which sectors drive my exposure and profit?
- Who are today’s top gainers/losers?
- Where are wins/losses concentrated?

## What you’ll find in this repo

**`data`** — example Google Sheets exports containing data from Yahoo Finance.

**`excel/Portfolio_Dashboard.xlsx`** — the finished dashboard workbook.

**`dashboard.png`** — dashboard screenshot used in this README.

You can replace the sample exports with your own and press Data ▸ Refresh All in Excel.

## Data Source

All stock prices and company details were fetched from **Yahoo Finance** using **Google Sheets** functions and then exported to Excel.

**1.** Search for a company.

**2.** Go to Historical Data.

**3.** Choose a date range.

**4.** Click Download CSV.

## Data Model
|Coloumn Name|Type|Description|
|-----------|---------|---------|
|Company|Text|
|Qty|Number|
|Purchase Price|Number|
|Investment|Number|
|Purchase Date|Date|
|Currrent Price|Number|
|Prev Price|Number|
|Today's Diff|Number|
|Prev Value|Number|
|Current Value|Number|
|Today Gain|Number|
|Overall Profit/Loss|Number|
|Profit/Loss %|Percentage|
|Sector|Text|
