# 📈 Smart Stock Market Analysis Engine

**Real-time stock insights powered by Yahoo Finance, n8n, and AI**

This project provides on-demand analysis for any stock. Enter a stock name or symbol (e.g., `TCS.NS`, `RELIANCE.NS`, `MRF.NS`) and instantly get a full market report including price, sentiment, trends, and AI-powered recommendations.

---

## 🚀 Features

✅ **Market Status**  
- Live price, % change, volume  
- Day range, 52-week high/low, volatility

📰 **News Sentiment**  
- Fetches latest headlines via Yahoo Finance  
- Uses AI to classify sentiment: Positive, Neutral, or Negative

📈 **Technical Signals & Trends**  
- Calculates RSI, SMA, EMA  
- Detects support/resistance levels and breakout patterns

💬 **AI Insights & Recommendations**  
- Summarizes trends and sentiment into buy/hold/avoid advice

⚠️ **Risks & Caveats**  
- Flags volatility, earnings dates, or conflicting signals


## 🛠 Tech Stack

| Tool | Purpose |
|------|---------|
| [Yahoo Finance API](https://www.npmjs.com/package/yahoo-finance2) | Stock data + headlines |
| [n8n](https://n8n.io) | Workflow automation engine |
| JavaScript | Technical indicator calculations |
| DeepSeek / OpenAI | Natural language generation |
| Webhooks & JSON | For clean data handling |

