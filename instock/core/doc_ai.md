---
title: core Root Folder Documentation
summary: Core business logic and data processing modules directory
tags: [core, business-logic, data-processing, algorithms]
---

# core Root Folder

## Description
This is the core business logic and data processing modules directory containing the essential algorithms and data processing functionality for the stock trading platform. The core folder houses the primary business logic components including data fetching, analysis, and processing utilities.

## Contents Overview
- __init__.py: Python package initialization
- .gitignore: Git ignore configuration
- backtest/: Directory containing backtesting functionality
- crawling/: Directory containing web crawling utilities
- eastmoney_fetcher.py: Module for fetching data from East Money
- indicator/: Directory containing technical indicators
- kline/: Directory containing K-line chart utilities
- pattern/: Directory containing pattern recognition
- singleton_proxy.py: Singleton module for proxy management
- singleton_stock_web_module_data.py: Singleton for stock web module data
- singleton_stock.py: Singleton module for stock management
- singleton_trade_date.py: Singleton module for trade date management
- stockfetch.py: Stock data fetching module
- strategy/: Directory containing trading strategies
- tablestructure.py: Database table structure definitions
- web_module_data.py: Web module data handling

## Key Components
- `eastmoney_fetcher.py`: Data fetching from East Money service
- `stockfetch.py`: Core stock data fetching functionality
- `tablestructure.py`: Database schema definitions
- `singleton_*`: Various singleton pattern implementations for shared resources

## Subdirectories Index
 - [backtest](backtest/doc_ai.md): backtest directory
 - [crawling](crawling/doc_ai.md): crawling directory
 - [indicator](indicator/doc_ai.md): indicator directory
 - [kline](kline/doc_ai.md): kline directory
 - [pattern](pattern/doc_ai.md): pattern directory
 - [strategy](strategy/doc_ai.md): strategy directory
 - `__init__.py`: __init__.py file
 - `.gitignore`: .gitignore file
 - `eastmoney_fetcher.py`: eastmoney_fetcher.py file
 - `singleton_proxy.py`: singleton_proxy.py file
 - `singleton_stock_web_module_data.py`: singleton_stock_web_module_data.py file
 - `singleton_stock.py`: singleton_stock.py file
 - `singleton_trade_date.py`: singleton_trade_date.py file
 - `stockfetch.py`: stockfetch.py file
 - `tablestructure.py`: tablestructure.py file
 - `web_module_data.py`: web_module_data.py file