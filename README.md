# 📈 AlphaTrend Auto Strategy

The **AlphaTrend Auto Strategy** is a precision-built Pine Script strategy for TradingView that combines ATR-based volatility modeling, RSI momentum filters, and customizable stop loss/take profit logic. Designed to help traders automate decisions while maintaining flexibility in risk control.

---

## ⚙️ Key Features

- 📊 **Trend Filter**: RSI threshold integrated with ATR range detection
- 📈 **Signal Generation**: Entry points triggered by crossover mechanics
- 🎯 **Risk Management**:
  - Optional fixed SL/TP mode
  - Dynamic swing high/low based protection
  - Selectable 1:1 risk-to-reward ratio mode

- 🖥️ **Visual Aids**:
  - Blue line: AlphaTrend adaptive filter
  - Green triangle: Buy signal
  - Red triangle: Sell signal

---

## 🔍 Parameter Breakdown

| Parameter           | Description                                   |
|---------------------|-----------------------------------------------|
| `Multiplier`        | Controls ATR sensitivity                      |
| `Common Period`     | RSI & ATR calculation period                  |
| `Price Source`      | Data input for signal logic                   |
| `Use Fixed SL/TP`   | Enables/disables percentage-based exits       |
| `1:1 Risk to Reward`| Equalizes stop-loss and target distance       |
| `SL / TP Percentage`| Fixed exit percent when static mode is on     |

---

## 📈 Trading Logic Overview

- **AlphaTrend Line**:
  - RSI ≥ 50 → use lower threshold
  - RSI < 50 → use upper threshold
- **Buy** when price crosses **above** AlphaTrend
- **Sell** when price crosses **below** AlphaTrend

- **Stop Loss / Take Profit** adjusts depending on:
  - Fixed vs. swing-based logic
  - Optional equalized SL:TP distances

---

## 🚀 Deployment Guide

1. Open TradingView and head to Pine Editor
2. Paste in the strategy script
3. Save and add to your chart
4. Fine-tune settings based on asset and timeframe
5. Backtest performance using Strategy Tester

---

## 🧑‍💻 Author

Developed by [Rao Aksee Nasir] — AI automation & trading systems enthusiast building scalable portfolio tools.

---
## 📝 License

This strategy is open-source under the MIT License. Attribution is appreciated but not required.

---

## 💬 Feedback & Contributions

Bug fixes, enhancements, or usage reports welcome! Submit issues or pull requests directly through GitHub.
