# Momentum Trader

A single-file paper-trading demo app.

## What it does
- Opens with a privacy, security and risk disclosure gate (agree/decline).
- Connects to an Alpaca PAPER trading account using API keys you generate yourself.
- Falls back to a built-in Simulation Mode if the browser blocks the broker API (CORS).
- Runs a 5/20 simple moving-average crossover momentum strategy with an Auto-Trade toggle.
- Shows portfolio value, cash, P/L, a watchlist with live signals, positions, and an activity log.

## Run it
Open `stock-trader.html` in any modern browser. No build step required.

## Important
This is a simulated, educational tool. It uses paper (sandbox) funds only, never real money or bank details, and nothing in it is financial advice. Algorithmic strategies can lose money.
