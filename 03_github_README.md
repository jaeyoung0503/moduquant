# [GitHub Repository README — google 색인 효과]
# 저장소명 제안: moduquant / korean-quant-backtest
# 설명: Korean quant backtesting platform — no coding required
# 토픽 태그: quant, backtest, korean-stock, fintech, investing, kospi, kosdaq

---

# ModuQuant — Korean Quant Backtesting Platform

[![Website](https://img.shields.io/badge/Website-moduquant.com-blue)](https://www.moduquant.com)
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

> 코딩 없이 10년 KOSPI·KOSDAQ 데이터로 퀀트 전략 수익률을 즉시 검증하는 한국 주식 백테스트 플랫폼

**English**: ModuQuant is a Korean stock backtesting platform that lets anyone verify quant investment strategies against 10 years of KOSPI/KOSDAQ data — no coding required.

## Features

- **No-code Strategy Builder** — RSI, MACD, Moving Average, Bollinger Bands, Value (PBR/PER)
- **10-Year Historical Data** — 2015 to present, all KOSPI & KOSDAQ stocks (~2,000 tickers)
- **AI Parameter Search** — automatically explores 500+ parameter combinations
- **Walk-Forward Analysis** — prevents overfitting by validating across multiple time windows
- **Factor Model** — momentum, value, quality, low-volatility multi-factor portfolios
- **ETF Backtest** — Korean and US ETF strategy testing
- **Free Plan** — 5 backtests/day, no credit card required

## Quick Start

1. Visit [www.moduquant.com](https://www.moduquant.com)
2. Sign up for free (email or Kakao)
3. Go to [Strategy Builder](https://www.moduquant.com/strategy_builder)
4. Select a strategy → set parameters → run backtest
5. View CAGR, MDD, Sharpe ratio, monthly returns chart

## Strategy Types

| Strategy | Description | URL |
|----------|-------------|-----|
| RSI Reversal | Buy oversold (RSI<30), sell overbought (RSI>70) | [/strategy_builder](https://www.moduquant.com/strategy_builder) |
| MACD Golden Cross | Buy on MACD crossover signal | [/strategy_builder](https://www.moduquant.com/strategy_builder) |
| Moving Average Cross | Dual MA crossover momentum | [/strategy_builder](https://www.moduquant.com/strategy_builder) |
| Value (PBR/PER) | Low P/B or P/E ratio investing | [/factor_model](https://www.moduquant.com/factor_model) |
| Momentum | 52-week high momentum | [/strategy_improved](https://www.moduquant.com/strategy_improved) |

## Documentation

- [What is Backtesting?](https://www.moduquant.com/strategy_docs/what-is-backtest)
- [Factor Investing Guide](https://www.moduquant.com/strategy_docs/factor-investing-intro)
- [Platform Guide](https://www.moduquant.com/guide)
- [Learning Center](https://www.moduquant.com/learning)

## Pricing

| Plan | Price | Backtests |
|------|-------|-----------|
| Free | ₩0 | 5/day |
| Advanced | ₩11,000/month | Unlimited |

7-day full refund guarantee.

## Tech Stack

- **Frontend**: Next.js 16 (App Router), TypeScript, Tailwind CSS
- **Infrastructure**: Cloudflare Workers (OpenNext), D1 Database
- **Data**: Real KRX market data (HTS feed)

## Links

- 🌐 Website: [www.moduquant.com](https://www.moduquant.com)
- 📖 Docs: [www.moduquant.com/strategy_docs](https://www.moduquant.com/strategy_docs)
- 📧 Contact: support@moduquant.com

---

*All backtest results are educational simulations and not investment advice.*
