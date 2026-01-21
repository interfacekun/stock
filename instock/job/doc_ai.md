---
title: job Root Folder Documentation
summary: Scheduled job and background task implementations directory
tags: [jobs, scheduling, background-tasks, automation]
---

# job Root Folder

## Description
This is the scheduled job and background task implementations directory containing automated processes that run on a schedule for the stock trading platform. The job folder houses various daily, weekly, and other periodic tasks that maintain and update the trading data.

## Contents Overview
- __init__.py: Python package initialization
- .gitignore: Git ignore configuration
- backtest_data_daily_job.py: Daily job for backtest data updates
- basic_data_after_close_daily_job.py: Daily job for post-market data
- basic_data_daily_job.py: Daily job for basic stock data updates
- basic_data_other_daily_job.py: Daily job for additional stock data
- execute_daily_job.py: Main daily job execution controller
- indicators_data_daily_job.py: Daily job for technical indicator updates
- init_job.py: Initialization job for application setup
- klinepattern_data_daily_job.py: Daily job for K-line pattern data
- selection_data_daily_job.py: Daily job for stock selection data
- strategy_data_daily_job.py: Daily job for strategy data updates

## Key Components
- `execute_daily_job.py`: Central controller for daily job execution
- `basic_data_daily_job.py`: Core daily data update job
- `indicators_data_daily_job.py`: Technical indicator calculation job
- `klinepattern_data_daily_job.py`: K-line pattern detection job

## Subdirectories Index
 - `__init__.py`: __init__.py file
 - `.gitignore`: .gitignore file
 - `backtest_data_daily_job.py`: backtest_data_daily_job.py file
 - `basic_data_after_close_daily_job.py`: basic_data_after_close_daily_job.py file
 - `basic_data_daily_job.py`: basic_data_daily_job.py file
 - `basic_data_other_daily_job.py`: basic_data_other_daily_job.py file
 - `execute_daily_job.py`: execute_daily_job.py file
 - `indicators_data_daily_job.py`: indicators_data_daily_job.py file
 - `init_job.py`: init_job.py file
 - `klinepattern_data_daily_job.py`: klinepattern_data_daily_job.py file
 - `selection_data_daily_job.py`: selection_data_daily_job.py file
 - `strategy_data_daily_job.py`: strategy_data_daily_job.py file