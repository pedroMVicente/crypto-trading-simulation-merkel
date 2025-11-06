# Crypto Trading Simulation (Merkel)

A command-line cryptocurrency trading simulator built in C++ that allows users to practice trading strategies in a simulated market environment without financial risk.

## Overview

This application simulates a cryptocurrency exchange where users can place bids and asks, manage their wallet, and track market statistics across different timeframes. The simulator processes historical trading data and matches orders using realistic market mechanics.

## Features

- **Real-time Market Statistics**: View current ask/bid prices, highs, lows, and order volumes for multiple trading pairs
- **Order Placement**: Place ask (sell) and bid (buy) orders with custom prices and amounts
- **Wallet Management**: Track your cryptocurrency holdings and validate order feasibility
- **Order Matching Engine**: Automatic matching of bids and asks based on market prices
- **Time Progression**: Step through historical market data timeframe by timeframe
- **Multi-Product Support**: Trade multiple cryptocurrency pairs (e.g., ETH/BTC, DOGE/BTC)

## Technical Highlights

- **Object-Oriented Design**: Clean separation of concerns with dedicated classes for OrderBook, Wallet, and CSVReader
- **CSV Data Processing**: Reads and parses historical trading data from CSV files
- **Order Book Implementation**: Efficient order matching algorithm for simulating real exchange behavior
- **Input Validation**: Robust error handling for user inputs and wallet validation

## How It Works

1. **Initialize**: The simulator loads historical trading data and sets up your initial wallet with starter funds
2. **Analyze**: View market statistics to understand current prices and trends
3. **Trade**: Place buy or sell orders based on your analysis
4. **Progress**: Advance to the next timeframe to see order matching results
5. **Track**: Monitor your wallet balance and successful trades

## Menu Options

1. **Print Help** - Display trading objectives and tips
2. **Print Exchange Stats** - View current market data for all products
3. **Place an Ask** - Create a sell order
4. **Place a Bid** - Create a buy order
5. **Print Wallet** - Display current cryptocurrency holdings
6. **Continue** - Advance to next timeframe and process orders
7. **Exit** - Close the application

## Technologies Used

- C++
- Object-Oriented Programming
- STL (Standard Template Library)
- CSV file processing
- Exception handling

## Educational Purpose

This project demonstrates key concepts in:
- Financial market simulation
- Order matching algorithms
- Data structure management
- User input validation
- Time-series data processing

Perfect for learning C++ while understanding the mechanics of cryptocurrency exchanges and trading strategies.

---

**Note**: This is a simulation tool for educational purposes. No real cryptocurrency or money is involved.
