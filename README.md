# TradeDesk

TradeDesk — AI-Powered Trading Dashboard
A fully client-side paper trading dashboard with live charts, portfolio tracking, news sentiment, and a built-in AI market analyst powered by Claude. No backend, no server, no dependencies to install — just open index.html and trade.
Live demo: your-username.github.io/tradedesk

Features

Market Overview — Real-time simulated prices for AAPL, NVDA, MSFT, TSLA, AMZN, SPY, QQQ, and VOO with live price flickering every 30 seconds
Interactive Charts — Candlestick-style line charts with 1D, 1W, 1M, and 3M range views powered by Chart.js
Paper Trading — Simulate buy and sell orders with a $1,000 starting balance, full order validation, and instant execution
Portfolio Tracker — Real-time P&L, average cost basis, total invested, and cash balance across all holdings
News & Sentiment — Curated market headlines tagged with bullish, bearish, or mixed sentiment
AI Analyst — Ask any question about stocks, strategies, ETFs, or options and get direct, personalized analysis from Claude based on your current portfolio state


Tech Stack

Vanilla HTML, CSS, JavaScript — zero frameworks, zero build tools
Chart.js for price charts
Anthropic Claude API for the AI analyst
Google Fonts — Syne + DM Mono
Hosted on GitHub Pages


Getting Started
Clone the repo and open the file directly in any browser:
bashgit clone https://obwoj1.github.io/tradedesk/
cd tradedesk
open index.html
No npm install. No build step. No config. It just works.

Deployment
This project is built to deploy on GitHub Pages in under 5 minutes.

Fork or clone this repo
Go to Settings → Pages
Set source branch to main, folder to /root
Save — your site goes live at https://your-username.github.io/tradedesk/


AI Analyst Setup
The AI Analyst connects to the Anthropic API directly from the browser. When running locally or on GitHub Pages through the Claude.ai interface, the API key is handled automatically. If you fork this and host it independently, you will need to add your own Anthropic API key.

Roadmap

 Real-time prices via Alpha Vantage or Polygon.io free tier
 Options chain simulator
 Swing trade journal with entry/exit tracking
 Watchlist customization and persistence via localStorage
 Mobile-optimized layout


Disclaimer
TradeDesk is a paper trading simulator for educational purposes only. No real money is involved. Nothing in this app constitutes financial advice. Always do your own research before making investment decisions.
