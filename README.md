
# LLM Trading Assistant

An LLM-powered trading simulation developed using Python,
LangGraph, and GigaChat.

The project explores how large language models can be used
to make trading decisions in a simulated market environment.

## Overview

The trading assistant processes market information and
generates trading decisions using an LLM-based workflow.

The system includes:

- LLM-driven trading decision-making
- Workflow orchestration using LangGraph
- Conditional routing between workflow nodes
- Transaction fee calculation
- LLM token usage and cost logging
- Trading simulation environment

## Tech Stack

- Python
- LangGraph
- GigaChat
- Jupyter Notebook

## Key Features

### 1. LLM-Based Decision Making

The assistant uses an LLM to analyze available information
and support trading decisions.

### 2. Workflow Routing

LangGraph is used to organize the decision-making workflow
and control transitions between different nodes.

### 3. Transaction Fees

The simulation accounts for transaction fees when
executing trades.

The implemented fee rate is 0.05% per transaction.

### 4. LLM Usage Tracking

A logging component tracks:

- Model name
- Input tokens
- Output tokens
- Cached tokens
- Estimated LLM usage cost

### 5. Trading Simulation

The system supports testing trading decisions in a
simulated environment.

## Project Status

Academic project — development and evaluation.

## Future Improvements

- Performance comparison against a baseline
- Evaluation over longer simulation periods
- Analysis of trading profitability
- Visualization of trading results
- Further improvements to the decision-making workflow

## Disclaimer

This project is intended for educational and research
purposes only. It does not provide financial advice.
