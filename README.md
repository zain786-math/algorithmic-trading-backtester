# 📊 Algorithmic Trading & Portfolio Backtesting Engine

A high-performance, mathematics-driven algorithmic trading simulator built with Python. This engine demonstrates the implementation of quantitative financial strategies using statistical rolling metrics and historical simulated price models.

---

## 🚀 Overview

This repository features a production-ready quantitative backtesting simulation. It calculates mathematical **Moving Average Crossovers** to generate autonomous buy and sell triggers, tracks cash vs. asset exposure, and computes final portfolio returns.

### 🧠 Core Mathematical Architecture
1. **Simple Moving Average (SMA):**
   \[SMA = \frac{P_1 + P_2 + \dots + P_n}{n}\]
2. **Signal Trigger Automation:**
   \[\text{Signal} = \begin{cases} 1 & \text{if } SMA_{\text{short}} > SMA_{\text{long}} \implies \text{Market Exposure (Buy)} \\ 0 & \text{otherwise} \implies \text{Liquidate to Cash (Sell)} \end{cases}\]

---

## 🛠️ Project Structure & Execution

### 1. Requirements
Ensure you have `pandas` and `numpy` installed:
```bash
pip install pandas numpy
```

### 2. Run the Engine
Execute the core script to process simulations and generate analytical financial reports:
```bash
python trading_engine.py
```

---

## 📈 Analytical Report Example Output
```text
=== QUANTITATIVE TRADING ENGINE INITIALIZED ===

Starting Seed Capital : \$10,000.00
Final Portfolio Value : \$12,431.52
Net Strategic Profit  : \$2,431.52 (24.32%)

=== SIMULATION COMPLETED SUCCESSFULLY ===
```

---

## 💼 Professional & Career Scope
This project maps core skills in:
* **Quantitative Mathematics:** Rolling intervals, asset sizing matrices, trend indicators.
* **Data Engineering:** Time-series arrays, chronological parsing with Pandas.
* **Financial Automation:** Risk assessment pipelines, automated entry/exit architectures.

*Disclaimer: This repository is exclusively for educational and portfolio presentation purposes. Past performance simulated here does not guarantee actual financial returns.*
