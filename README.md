# 📈 StockMind AI — Beginner-Friendly Stock Analyser

> A fully client-side, single-file HTML stock analysis app powered by **Claude AI** + **OpenAI GPT-4** with real-time data from **Alpha Vantage** and **NewsAPI**.

![StockMind Screenshot](https://img.shields.io/badge/version-2.0.0-cyan) ![License](https://img.shields.io/badge/license-MIT-green) ![HTML](https://img.shields.io/badge/built%20with-HTML%2FCSS%2FJS-orange)

---

## ✨ Features

| Feature | Description |
|---|---|
| 🗞️ **Agent 1 — News Themes** | AI clusters headlines into market themes with sentiment |
| 🛡️ **Agent 2 — Risk Scorer** | Dynamic risk score adjusted by user risk profile |
| 📊 **Agent 3 — Watchlist Ranker** | Ranks stocks by sentiment + momentum + risk |
| 🧠 **Agent 4 — Decision Engine** | Buy/Hold/Sell probabilities from Claude + GPT-4 |
| 🏢 **Company Profile** | About the company + what they invest in |
| 📰 **AI News Explainer** | Each headline explained in beginner-friendly language |
| ⇄ **Claude vs GPT-4 Compare** | Side-by-side AI comparison with consensus |
| 🎓 **Beginner Mode** | Full plain-English explanations for new investors |

---

## 🚀 Quick Start

### Option A — No API Keys (Demo Mode)
1. Download `index.html`
2. Open in Chrome / Edge / Firefox
3. Everything works with mock data instantly ✅

### Option B — Live Mode with Real Data
1. Get free API keys:
   - **Claude**: [console.anthropic.com](https://console.anthropic.com)
   - **Alpha Vantage** (stock prices): [alphavantage.co/support/#api-key](https://www.alphavantage.co/support/#api-key)
   - **NewsAPI** (headlines): [newsapi.org/register](https://newsapi.org/register)
   - **OpenAI** (optional): [platform.openai.com](https://platform.openai.com)
2. Open the app → click **🔑 API Keys**
3. Paste your keys → Save → Switch to **LIVE MODE**

---

## 📁 Repository Structure

```
stockmind/
│
├── index.html          ← Complete app (single file, open in browser)
├── README.md           ← This file
└── LICENSE             ← MIT License
```

---

## 🔑 API Keys Needed

| Service | Used For | Free Tier |
|---|---|---|
| Anthropic Claude | AI analysis (Agent 1-4) | $5 free credit |
| Alpha Vantage | Real stock prices + quotes | 25 req/day free |
| NewsAPI | Live headlines | 100 req/day free |
| OpenAI (optional) | GPT-4 comparison | $5 free credit |

---

## ⚙️ How It Works

```
User selects stock
      ↓
[Agent 1] NewsAPI → Claude clusters headlines into themes
      ↓
[Agent 2] Alpha Vantage volatility → Risk score (0-100)
      ↓
[Agent 3] Sentiment + Momentum → Watchlist ranking
      ↓
[Agent 4] All data → Claude + GPT-4 → Buy/Hold/Sell %
      ↓
Company Profile + Beginner AI Explainer shown
```

---

## ⚠️ Disclaimer

> StockMind provides AI-generated probability scores for **educational and informational purposes only**.
> This is **NOT financial advice**. Always consult a qualified financial advisor before making investment decisions.
> Past performance does not predict future results.

---

## 📄 License

MIT © 2025 StockMind
