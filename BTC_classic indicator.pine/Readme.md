# ⚡ BTC/USDT Day Trading Setup

This guide explains the **optimized workflow and indicator settings** for day trading **BTC/USDT** using a **1H signal chart** and **4H trend confirmation**.

The system is designed to produce **3–5 high-quality signals per day**, helping traders avoid overtrading while staying aligned with the dominant trend.

---

# 📊 Timeframe Structure

| Role                   | Timeframe | Purpose                |
| ---------------------- | --------- | ---------------------- |
| **Signal Chart**       | **1H**    | Entry signals          |
| **Trend Confirmation** | **4H**    | Trade direction filter |

**Rule:**
Only take signals on the **1H chart that align with the 4H trend direction.**

---

# 🔧 Optimized Indicator Settings (1H Day Trading)

Update the indicator settings as follows:

| Setting               | Default | Day Trading Optimized |
| --------------------- | ------- | --------------------- |
| Min Confirmations     | 3       | **3** (balanced)      |
| RSI Overbought        | 65      | **70**                |
| RSI Oversold          | 35      | **30**                |
| SL ATR Multiplier     | 1.5     | **1.2**               |
| TP ATR Multiplier     | 3.0     | **2.5**               |
| Volume MA Length      | 20      | **20**                |
| Min Volume Multiplier | 1.2     | **1.5**               |

These adjustments make the indicator **less sensitive**, helping filter out weak signals on the **1H timeframe**.

---

# 📋 Day Trading Workflow

## 1️⃣ Before the Trading Session

1. Open **BTC/USDT on the 4H chart**
2. Identify the **trend background**

   * 🟢 Green → Bullish
   * 🔴 Red → Bearish
3. Note the **EMA 200 level**

The **EMA 200 on the 4H chart** often acts as the **key support/resistance level for the day**.

---

## 2️⃣ During the Session

1. Switch to the **1H chart**
2. Wait for a **signal from the indicator**
3. Check alignment with the **4H trend**

| Condition               | Action       |
| ----------------------- | ------------ |
| Signal matches 4H trend | ✅ Take trade |
| Signal against 4H trend | ❌ Skip trade |

**Entry Rule**

Enter **on the open of the next candle after the signal bar closes.**

---

# 🚪 Exit Rules

| Event                           | Action              |
| ------------------------------- | ------------------- |
| Price hits **TP line**          | Close full position |
| Price hits **SL line**          | Exit trade          |
| **4H trend flips during trade** | Consider early exit |

---

# ⏰ Best BTC Trading Hours (UTC)

BTC liquidity peaks during specific market sessions.

| Session             | UTC Time          | Quality            |
| ------------------- | ----------------- | ------------------ |
| Asia Session        | 00:00 – 06:00     | 🟡 Lower Volume    |
| London Open         | 07:00 – 10:00     | 🟢 High            |
| **New York Open ⭐** | **13:00 – 16:00** | 🟢 **Highest**     |
| London/NY Overlap   | 13:00 – 17:00     | 🟢 **Best of Day** |
| Weekend             | Sat/Sun           | 🔴 Avoid           |

💡 **Pro Tip**

The **highest-probability signals occur during the NY Open (13:00–16:00 UTC)** when volume and volatility spike.

If a **1H signal aligns with the 4H trend during this window**, it is considered an **A+ setup**.

---

# 🔔 TradingView Alert Setup

Set alerts on the **BTC/USDT 1H chart**:

### Long Alert

```
Condition: 🟢 BTC LONG Signal  
Alert Type: Notification + Sound  
Trigger: Once Per Bar Close
```

### Short Alert

```
Condition: 🔴 BTC SHORT Signal  
Alert Type: Notification + Sound  
Trigger: Once Per Bar Close
```

This allows you to **avoid watching charts constantly** while still catching valid setups.

When the alert triggers:

1. Check **4H trend direction**
2. Confirm alignment
3. Enter trade on **next candle open**

---

# 🎯 Strategy Goal

* **3–5 high quality trades per day**
* **Trend-aligned entries**
* **Reduced noise from lower-quality signals**
* **Better risk management with ATR-based SL/TP**

---

# ⚠️ Disclaimer

This strategy is for **educational purposes only**.
Cryptocurrency trading carries significant risk. Always use **proper risk management** and never trade with funds you cannot afford to lose.

---
