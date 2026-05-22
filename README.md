# Trading-Correlation-Panel-
NinjaTrader 8  trading correlation dashboard add-on


WT Correlation Panel Guide
Overview
The WT Correlation Panel is a live multi-market correlation and market alignment dashboard for NinjaTrader.

It monitors: or any 4 other tickers you choose in settings 
•	RTY
•	NQ
•	ES
•	YM

The panel provides:
•	Live price tracking
•	Candle alignment
•	Historical correlation analysis
•	Trend strength analysis
•	Volume strength analysis
•	Real-time market sentiment visualization

The system automatically adapts to the active chart timeframe.
Live Ticker Boxes
Displays:
•	Current live price
•	Candle price change
•	Percentage change
•	Candle range size

Green = bullish candle
Red = bearish candle

The ticker boxes follow the active chart timeframe.
Correlation Matrix
Measures how strongly markets move together.

+1.00 = perfect positive correlation
0.00 = no correlation
-1.00 = inverse correlation

Green = strong positive correlation
Yellow = moderate correlation
Gray = weak correlation
Red = negative correlation
Correlation Graph
Visualizes rolling historical correlation movement between the markets over time.

Each colored line represents one ticker’s average correlation against the others.
Market Gauge
Measures overall market trend alignment.

Gauge Right = bullish trend
Gauge Center = neutral
Gauge Left = bearish trend

The gauge evaluates all four tickers together.
All Tickers Alignment
Displays current candle direction for all four markets.

Green Dot = bullish candle
Red Dot = bearish candle

ALL GREEN = all bullish
ALL RED = all bearish
MIXED = mixed market direction
Current Bar Volume Strength
Measures current candle volume against recent average volume.

Green = strong volume
Yellow = moderate volume
Red = weak volume
Average Volume Strength
Calculates overall participation strength across all four futures markets.
Dynamic Timeframe Adaptation
The entire panel dynamically adjusts to the active chart timeframe.

Current candle sections:
•	ticker direction
•	market gauge
•	all tickers alignment
•	volume strength

Historical sections:
•	correlation matrix
•	correlation graph
Real-Time Updating
The panel updates automatically every 250 milliseconds using DispatcherTimer.
Collapse System
Collapsed mode:
•	shrinks into WT tab
•	saves chart space

Expanded mode:
•	restores full panel
Main Purpose
Designed to help traders identify:
•	market agreement
•	market divergence
•	institutional alignment
•	trend continuation
•	momentum confirmation
•	weak market structure
Intended Usage
Best used for:
•	momentum confirmation
•	trend validation

