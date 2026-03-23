# quant-options-decision-support
Trading signal decision support system
# Quant Options Decision Support System

A multi-factor trading signal and decision-support system designed to improve short-term options trade selection through structured technical confirmation, risk-aware signal logic, and alert automation.

This project combines indicator research, signal design, backtesting, and alert workflow architecture into a practical decision-support framework for trading liquid instruments such as leveraged ETFs, commodities, metals, and selected crypto-linked products.

## Project Summary

Most technical indicators work poorly in isolation. This system was built around the idea that higher-quality trade decisions come from **stacked confirmation**, not single-indicator signals.

The framework evaluates combinations of:

- RSI and Stochastic RSI exhaustion / reversal behavior
- MACD crossover and histogram transition patterns
- Volume-based confirmation
- Multi-timeframe alignment
- Structured entry, confirmation, and exit logic

The goal was not to create a “black box predictor,” but to develop a **repeatable decision-support process** that improves trade timing, reduces false positives, and supports more disciplined options positioning.

## Core Objective

To design a practical signal engine that identifies higher-probability short-term trading opportunities and supports risk-adjusted decision-making for options trades.

Primary use cases include:

- Upside setups over short holding windows
- Downside reversal trades over compressed time horizons
- Alert-based monitoring instead of continuous chart watching
- Decision support for leveraged and high-volatility instruments

## Instruments Evaluated

The research and signal framework were tested against assets and products of active interest, including:

- TQQQ
- USO
- GLD
- SLV
- DIA
- ES-linked products
- volatility-related instruments
- selected crypto and crypto-linked products

## System Design

The signal model is organized into three stages:

### 1. Initial Setup
Detects an exhaustion or reversal condition after momentum has become stretched.

Examples include:
- RSI or Stochastic RSI dropping from overbought into deeply oversold territory
- momentum deceleration shown in MACD histogram behavior
- negative trend exhaustion conditions beginning to stabilize

### 2. Confirmation
Requires additional evidence before treating the setup as actionable.

Typical confirmation includes:
- MACD crossing above signal line
- histogram improvement from strongly negative to less negative
- increase in buy-side volume
- alignment with higher-timeframe behavior

### 3. Exit / Sell Logic
Uses a separate rule set for managing exits rather than relying on arbitrary profit-taking.

Examples include:
- RSI reaching extreme levels on a higher timeframe
- MACD slope deterioration after positive momentum expansion
- histogram contraction on the positive side
- evidence of weakening momentum after confirmation

## Why This Project Matters

AI and rule-based systems often produce outputs that look correct in theory but fail under real-world conditions. This project was built to address that problem directly.

The system emphasizes:

- structured signal validation
- multi-factor confirmation
- real-world chart behavior
- reduction of false positives
- practical deployment thinking, not just indicator theory

This work reflects a broader strength in:

- quantitative reasoning
- applied trading systems design
- decision-support architecture
- translating complex logic into production-ready workflows

## Repository Contents

### `/docs`
Project case study, signal visuals, and methodology notes.

### `/research`
Early-stage research on indicator selection, asset focus, and hypothesis development.

### `/strategy`
Clear documentation of setup, confirmation, and exit logic.

### `/tradingview`
Pine Script implementation and alert template structure.

### `/backtests`
Backtest summaries, trade examples, and performance notes.

### `/automation`
Architecture for alerting, reporting, and future monitoring workflows.

## Case Study

A full case study is included here:

**[Download the case study PDF](./docs/case-study.pdf)**

This case study outlines:

- project objective
- methodology
- signal design logic
- examples of successful buy setups
- practical implementation direction

## Example Signal Characteristics

The preferred framework evolved toward a blend of:

- RSI / Stochastic RSI exhaustion and recovery behavior
- MACD crossover confirmation
- histogram color / momentum transition analysis
- selective volume confirmation
- timeframe-specific sell criteria

In testing, this combined approach showed stronger decision value than relying on RSI or MACD alone.

## Current Status

Current development includes:

- refining signal definitions by asset class
- improving exit logic
- organizing historical signal examples
- building alert and monitoring workflows
- preparing for ongoing performance tracking and reporting

## Next Development Steps

Planned next steps include:

- expanding historical backtesting
- tracking triggered trades and forward performance
- improving alert routing and reporting automation
- integrating daily summary reporting
- evaluating opportunities for AI-assisted performance analysis

## Professional Positioning

This repository represents applied work in:

- Quantitative Trading Systems
- Decision Support Tools
- Signal Research and Validation
- TradingView / Pine Script Logic
- Alert Automation and Monitoring Design

It is intended as a portfolio project demonstrating the ability to move from concept to structured technical implementation.

## Contact

For portfolio, project, or contract opportunities:

- LinkedIn: www.linkedin.com/in/levongoldblatt
- Website:  https://ronfromfrontroyal.com/content-services

---
**Keywords:** Quant Trading, Trading Systems Analyst, Options Decision Support, Signal Engine, Technical Analysis, Pine Script, Alert Automation, MACD, RSI, Stochastic RSI, Backtesting
