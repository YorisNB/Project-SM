# ProjectSolvay

Prerequisites - Data Extraction

For this project, you will need to extract information from the Finnhub API on 10 companies: 5 will be from the GAFAM (Google, Amazon, Facebook, Apple, and Microsoft), and 5 will be specified in an accompanying document. Therefore, it's necessary to have an account on Finnhub linked to your ULB email address.

Part 1 – Database

The first step is to generate a database containing at least:

The names of the companies.
Their sectors of activity.
The prices and volumes of their stocks since January 1, 2019, including all candlestick prices, volume, and associated dates.
"Alerts" linked to a ticker, containing:
A name.
A start date.
An end date.
A start value.
An end value.
A related data type, called "source" (open, close, high, or low).
A direction (max or min).
The database must be normalized, meaning each piece of information should appear only once. The deliverables include the database and the code to produce it in a notebook.

Part 2 – Data Analysis

This section focuses on analyzing the extracted data and includes the following:

Differences: Finding the largest differences and daily variations for each ticker.

Growth: Developing functions to calculate price variations over a given period and to determine the number of days where the price variation exceeds a set limit.

Graphs: Creating a function to produce a graph representing price evolution between two dates, with horizontal lines indicating the maximum and minimum values reached by the stock.

Alerts: Developing functions to add alerts to the database and to determine the number of days where values exceed specified alerts.

Technical Indicators: Creating functions to calculate average values and establish envelopes, with the production of diagrams representing these envelopes.

Volumes: Displaying traded volume as a histogram for each day, with indication of stock value variation through the color of the bars.

Volume Weighted Average Price: Calculation and graphical representation of the Volume Weighted Average Price for each day.

These analyses aim to provide a deep understanding of the extracted data and to identify potential trends and opportunities in the financial markets.
