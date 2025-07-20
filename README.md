# 🚀 Breakout Strategy with Custom TP & SL

This **Breakout Strategy** is an advanced Pine Script implementation for TradingView that identifies bullish and bearish breakouts based on swing highs/lows, enhanced by multiple filtering conditions including EMA, RSI, MACD, ATR, volume, and time-of-day controls.

It offers dynamic risk management tools, including fixed or swing-based stop-loss (SL), configurable take profit (TP), and optional 1:1 risk-to-reward logic. Ideal for traders seeking a configurable breakout engine with high-level control.

---

## 📈 Strategy Highlights

- ✅ **Breakout Logic**:
  - Bullish breakout above recent swing high
  - Bearish breakout below recent swing low

- 🔒 **Risk Management**:
  - Toggle between Swing SL or Fixed SL
  - Optional 1:1 Risk-Reward mode
  - TP can be disabled (set to zero) for swing-only exits

- 🧠 **Filters & Enhancements**:
  - EMA 233 trend direction filter
  - ATR volatility filter
  - Volume spike confirmation
  - RSI threshold logic
  - MACD confirmation (optional)
  - Time/session filter for trade windows

- 📊 **Visuals**:
  - SL/TP plotted with dotted lines and labels
  - Breakout signals plotted with colored shapes
  - MACD chart pane (optional)

---

## ⚙️ Input Parameters

| Parameter            | Functionality                              |
|----------------------|---------------------------------------------|
| `Swing Window`       | Lookback period for breakout levels         |
| `Trading Direction`  | Filters long/short entries                  |
| `Take Profit (%)`    | TP target from entry price                  |
| `Stop Loss Type`     | Swing or fixed percentage-based SL          |
| `Fixed SL (%)`       | SL percentage (if using Fixed SL)           |
| `Use 1:1 RR`         | TP equals SL for symmetrical exits          |
| `Use EMA Filter`     | Trend confirmation based on EMA233          |
| `Use ATR Filter`     | Volatility filter using ATR                 |
| `Use Volume Filter`  | Confirms breakout with high volume          |
| `Use Session Filter` | Restrict entries to specific hours          |
| `Use RSI Filter`     | RSI confirmation logic                      |
| `Use MACD Filter`    | Optional MACD signal filtering              |

---

## 💡 Usage Instructions

1. Copy the code into Pine Script editor on TradingView.
2. Adjust parameters based on asset type and trading goals.
3. Add to chart and toggle visualization options (MACD, labels, etc.).
4. Backtest using Strategy Tester and refine SL/TP levels.
5. Deploy across crypto, forex, or index pairs for adaptive performance.

---

## 👨‍💻 Author

Created by [Rao Aksee Nasir](https://github.com/your-username), software engineer and automation strategist passionate about smart trading systems and global tech solutions.

---

## 📄 License

Distributed under the MIT License. Free to fork, modify, and share with attribution.

---

## 📬 Contact & Contributions

Pull requests and feedback welcome! Share performance metrics or report issues directly on GitHub.
