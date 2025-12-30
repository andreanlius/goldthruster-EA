# goldthruster-EA
Expert Advisor for Metatrader 5
# GoldThruster v1.0: Precision Grid Trading. Shared Risk. Exponential Potential.

## The Next Evolution in Automated Forex Trading

Are you tired of missing opportunities and struggling to manage complex grid strategies manually? The **GoldThruster v1.0** is a sophisticated Expert Advisor (EA) designed for the modern MetaTrader 5 platform, offering a powerful, automated solution to capitalize on market volatility. This bot is engineered for traders who understand the mechanics of grid trading and are ready to leverage a high-potential, Martingale-based system with advanced risk controls.

## Core Strategy: Dynamic Martingale Grid

The GoldThruster v1.0 operates on a proven, configurable grid strategy, automatically placing a series of pending orders (Buy Limit or Sell Limit) at user-defined intervals.

*   **Intelligent Entry:** The bot uses a dual-filter system combining the **Relative Strength Index (RSI)** and a **Dual Moving Average (MA) Trend Filter** to ensure that the initial grid is only launched when the market shows signs of a potential reversal (RSI) that is aligned with the broader trend (MA cross).
*   **Martingale Acceleration:** By default, the bot employs a **Martingale Lot Sizing** system, doubling the volume for each subsequent grid level (1x, 2x, 4x, 8x, etc.). This aggressive approach is designed to rapidly reduce the break-even point and accelerate profit realization when the market reverses.
*   **Configurable Depth:** Set your maximum grid depth up to **10 levels** to match your account size and risk tolerance.

## Unique Risk and Profit Management System

What sets the GoldThruster v1.0 apart is its innovative approach to managing the entire grid as a single, cohesive trade.

| Feature | Description | Benefit to the Trader |
| :--- | :--- | :--- |
| **Shared Stop Loss (SL)** | A single, unified Stop Loss is applied to **all** positions in the grid, calculated from the furthest (last) grid level. | Provides a clear, defined maximum risk for the entire strategy, protecting your capital from catastrophic, sustained market moves. |
| **Global Take Profit (TP)** | A single, unified Take Profit is applied to **all** positions, calculated from the closest (first) grid level. | Ensures all positions close simultaneously, locking in profit efficiently and preventing partial exits that leave high-volume positions exposed. |
| **Profit Target Feature** | An optional feature that closes the entire grid immediately if a pre-set dollar amount (e.g., $10) is reached, but **only after all grid levels have been triggered**. | Acts as a powerful recovery mechanism, allowing the bot to quickly exit a deep drawdown once a full-grid reversal generates sufficient profit. |
| **Half Grid TP Detection** | If half of the grid positions reach the Global TP, the bot automatically cancels all remaining pending orders. | A proactive risk-off measure that secures partial gains and prevents further exposure if the market shows signs of a strong reversal. |

## Key Features at a Glance

*   **Platform:** MetaTrader 5 (MT5) Expert Advisor (.mq5)
*   **Strategy:** Dynamic Grid Trading with Martingale Lot Sizing (Optional)
*   **Entry Filters:** RSI (Oversold/Overbought) and Dual EMA Trend Filter (100/300 periods by default)
*   **Risk Control:** Shared Stop Loss (SL) for the entire grid (default 50 pips from last level)
*   **Profit Control:** Global Take Profit (TP) for all positions (default 50 pips from first level)
*   **Recovery Feature:** Dollar-based Profit Target for full-grid recovery and exit.
*   **Flexibility:** Configurable Grid Spacing, Base Volume, and Timeframe (M1, M5, M15, M30, H1).
*   **Control:** Automatic and Manual Trading Modes, with manual override to close all trades.

---

## Important Risk Disclosure

The GoldThruster v1.0 utilizes a Martingale-based strategy, which is inherently high-risk. While the bot includes a Shared Stop Loss for capital protection, this strategy can lead to significant drawdowns and is not suitable for all investors. **Use only with capital you can afford to lose.** We strongly recommend thorough backtesting and forward testing on a demo account before deploying this EA on a live account.

**Ready to transform your trading?** [Get the GoldThruster v1.0 today!](https://wa.me/62895612344661?text=Halo%20GoldThrusher,%20saya%20tertarik%20untuk%20menggunakan%20bot%20trading%20emas%20MT5.)

