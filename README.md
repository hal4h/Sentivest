# Sentivest
AI-Powered Market Sentiment Tracker (Coming Soon)


# 📈 Sentivest – AI-Powered Market Sentiment Tracker (Coming Soon)

> *Decode the market’s mood. Track how the news, Reddit, and Twitter impact your stocks in real time.*

---

## 🚧 Status: In Development
**Sentivest** is a work-in-progress personal FinTech + AI project. This README outlines the planned features, tech stack, and system design to document the project from concept to completion.

---

## 🧠 Project Vision

Sentivest is an AI-powered stock market sentiment tracker that helps users understand the “emotional pulse” of the market across thousands of tickers.

It will analyze and visualize real-time sentiment from:
- 📈 News headlines
- 🗞 Reddit discussions
- 💬 Twitter chatter

…and combine it with:
- 🧠 FinBERT-based sentiment scoring
- 🧠 GPT-4 powered market summaries
- 📊 Time-series price correlation

---

## 🔍 Planned Features

### ✅ Ticker-Based Sentiment Dashboard
- Input any stock symbol (e.g., `$AAPL`, `$TSLA`) to track sentiment over time
- Visualize positive, neutral, and negative sentiment breakdowns

### 🗞 Real-Time News + Social Aggregator
- Pull data from:
  - NewsAPI (financial headlines)
  - Reddit (e.g. r/stocks, r/wallstreetbets)
  - Twitter (using keyword/ticker tracking)

### 🧠 AI-Powered Insights
- **FinBERT** or **VADER** to extract sentiment and classify financial news
- **Named Entity Recognition** to highlight key market-moving topics like “earnings,” “rate hikes,” or “lawsuits”
- **GPT-4 Summaries** to explain daily sentiment in plain English

### 📈 Sentiment vs. Price Overlay
- Track how investor mood aligns with actual price movement using Alpha Vantage data

### 🔔 Bonus Features (Roadmap)
- **Volatility Radar**: Alerts when sentiment surges for a ticker
- **Meme Stock Detector**: Spike alerts based on Reddit/Twitter activity
- **Portfolio Sentiment Summary**: Avg. sentiment across saved tickers
- **“Why is this trending?” AI widget**

---

## 🖥 Planned Tech Stack

| Layer       | Tools & Libraries                            |
|------------|-----------------------------------------------|
| Frontend    | React, TailwindCSS, Chart.js, Recharts       |
| Backend     | Python, FastAPI                              |
| ML/NLP      | FinBERT, VADER, spaCy, OpenAI (GPT-4)        |
| APIs        | NewsAPI, Reddit API, Twitter API v2, Alpha Vantage |
| Database    | Supabase (PostgreSQL + Auth)                 |
| Deployment  | Vercel (frontend), Render (backend)          |

---

## 📦 Project Timeline

| Milestone                        | Status     |
|----------------------------------|------------|
| Project Architecture & Design   | ✅ Complete |
| API Integration (News/Reddit)   | 🚧 In Progress |
| Sentiment Model Integration     | 🔜 Upcoming |
| GPT Summary Feature             | 🔜 Upcoming |
| Dashboard UI                    | 🔜 Upcoming |
| Public Demo                     | 🔜 Targeting Q3 2025 |

---

## 📸 Screenshots / Preview

> Coming soon — will include:
> - Sentiment dashboard mockups
> - GPT-powered ticker summary card
> - Real-time price vs. sentiment chart

---

## 👩‍💻 Author

**Halah Mhanni**  
B.CompSci (Hons) + Stats Minor @ University of Manitoba  
🔗 [LinkedIn](https://linkedin.com/in/halah-mhanni) • [GitHub](https://github.com/hal4h)

---

## ⭐ Stay Tuned

- This project is under active development.
- Watch or star the repo to stay updated!
- If you're interested in collaboration, feel free to open an issue or reach out.

