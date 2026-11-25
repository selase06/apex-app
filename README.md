# APEX Portfolio Intelligence

> Bloomberg Terminal × Arc Browser × Linear.app — a self-hostable PWA for portfolio tracking, budgeting, and AI-assisted investing.

## Live App

**GitHub Pages:** https://selase06.github.io/apex-app/

## Features

- Portfolio Tracker — real-time price fetch, P&L, sector allocation, performance chart
- Signals Engine — RSI, MACD, Bollinger Bands, momentum score per position
- Watchlist — add tickers, track price + change
- Budget Module — income, expenses, savings goals with donut visualization
- AI Coach — Ollama-powered local LLM analysis
- Multi-Profile — isolated localStorage per family member / user
- PWA — installable on Android and iOS, splash screen, offline fallback

## Stack

Single-file HTML PWA — no build step, no framework. All CSS/JS/HTML in `index.html`.

## Settings

Open Settings to configure:
- Proxy URL — your ouroboros-proxy address (e.g. `http://10.0.0.150:8503`)
- Ollama URL — your local Ollama instance (e.g. `http://10.0.0.150:11434`)
- Currency — USD, EUR, GBP, CAD, JPY, CHF, AUD
- User Profiles — add/switch profiles for each family member

## License

MIT
