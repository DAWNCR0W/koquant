# KOQUANT

KOQUANT is a Korean stock realtime quant trading platform project for research, backtesting, paper trading, and risk-controlled live automation.

## Goals

- Build a Korean-market-first quant trading system for individual operators.
- Support research, historical data collection, strategy backtesting, paper trading, and cautious live trading.
- Treat risk controls, broker API limits, order traceability, and operational runbooks as first-class features.
- Start with Korea Investment & Securities Open API integration, while keeping broker adapters replaceable.

## Planned Stack

- Python, FastAPI, asyncio
- React, TypeScript
- PostgreSQL, TimescaleDB
- Redis Streams
- pykrx, FinanceDataReader
- Korea Investment & Securities Open API
- pytest, Playwright
- Docker Compose

## Status

This repository is currently in the planning and scaffolding phase.

## Safety Notice

KOQUANT does not provide investment advice and does not guarantee returns. Automated trading can cause financial loss because of strategy errors, API failures, network issues, market volatility, duplicate orders, rejected orders, or stale account state. Live trading should only be enabled after backtesting, paper trading, risk-limit verification, and small-scale validation.
