# Trading Edge — Ticker Scanner

Persönliches Trading-Dashboard nach dem Kullamaggie × Jeff Sun System.

## Features
- ⚡ Ticker Scanner mit Auto-Setup-Rating (A/B/C/D)
- 📊 TradingView Chart (Daily + SMA 10/20/50/100/200)
- 📈 Momentum-Metriken: ATR Extension, RVOL, ADR%, 60% ATR Regel
- 🔢 Options Chain Analyse: Max Pain, IV, P/C Ratio, Key Strikes
- 🧮 Kalkulatoren: Positionsgröße, 4x ATR, 60% ATR
- 💹 VARS (Vol. Adj. RS vs SPY), Earnings, Short Float, VIX

## Datenquellen
- Preis, Optionen, News: Yahoo Finance (kein API-Key nötig)
- SMAs, professionelle Charts: TradingView
- Finnhub (optional): Earnings, Short Float, Sektor

## Lokal ausführen
```
python -m http.server 8080
```
→ http://localhost:8080

---
*Nur für persönliche Analyse. Keine Anlageberatung.*
