# Jeff Sun (CFTe) — Complete Trader's Guide: Process, Tools, Routine, Core Beliefs & FAQs
**Source:** https://jfsrev.substack.com/p/my-trading-tools-process-routine  
**Author:** Jeff Sun, CFTe | @jfsrev | Published: Sep 07, 2025  
**Bio:** 16 years of stop losses, pain & grit to $10M+ multi-asset portfolio. Closed-end fund manager, performance-fee basis only. CFTe certified. No courses/services sold.

---


Hier ist die echte, inhaltlich vollständige Version — mit den tatsächlichen Regeln, Erklärungen und Methoden direkt aus den Tweets, nicht nur Links:

---

```markdown
# JEFF SUN (CFTe) — COMPLETE TRADING SYSTEM
## For AI Mindmap Generation
**Source:** jfsrev.substack.com | @jfsrev | 16 years of trading, $10M+ multi-asset portfolio

---

# 1. GLOSSARY — CRITICAL TERMS

## LoD (Low of Day)
The current intraday low **at the exact moment you're making a decision** — NOT the end-of-day low.
- LoD starts every day at 0% (price hasn't moved down yet)
- LoD = 0% if stock is trading at its intraday low right now
- Critical: LoD is dynamic — it changes every minute during trading hours
- For ORH entries (buy-stop orders), LoD does NOT account for the high of day

## RVOL (Relative Volume)
Current volume run-rate compared to 50-day average session volume.
- Formula: current volume / average daily volume × (time factor)
- RVOL > 1.0 = above average. The higher, the better for entry confirmation
- **Why it matters:** Price ALWAYS fades outside of RVOL. Without elevated RVOL, a breakout has no conviction and will revert
- Statistical edge: RVOL-based ORH entries have proven edge in backtests
- Saved Jeff from countless unnecessary stop losses year after year
- Exception: Mega-cap liquid stocks ($1B+ avg daily $ vol) — no RVOL requirement needed

## R-Multiple
Initial risk on a trade = entry price minus stop-loss price = 1R  
- Example: Entry $50, stop $48 → 1R = $2
- If trade reaches +$6, that's +3R
- Jeff's goal: average loss = -0.67R (not -1R), average winner = several R
- "One trade to cover 13 losing streaks is my style" — asymmetric R is the goal
- Actual 1R loss in practice = 1.03–1.3R due to slippage, spread, borrowing costs

## ATR vs ADR%
- **ATR (Average True Range):** Includes price gaps — Jeff PREFERS this because gaps represent real price extensions
- **ADR% (Average Daily Range %):** Excludes gaps — less accurate for Jeff's purposes
- ATR is used as a "spring coil" — visualize the stock's daily volatility budget

## VCP (Volatility Contraction Pattern)
Developed by Mark Minervini. A series of price contractions getting progressively tighter.
- Pattern: Stock contracts → volume dries up → price tightens above key MAs → breakout
- **Jeff's absolute rule:** He will NEVER enter a stock with prior loose/wide price action
- Every sustainable price expansion rally is ALWAYS preceded by VCP

## VARS (Volatility Adjusted Relative Strength)
Enhanced version of traditional RS — adjusts RS score by each stock's unique volatility.
- Problem with traditional RS: A high-volatility stock and low-volatility stock get same RS score even if their move quality differs
- VARS normalizes this — gives a more accurate picture of which stock is truly leading
- Jeff published his own VARS with histogram (Oct 2025)

## T+3 Framework
- T = execution day (Day 0)
- T+1 = Day 1 after execution (trading days only, no weekends/holidays)
- T+2 = Day 2
- T+3 = Day 3 — by this point, a winning trade should be showing clear progress
- Durable portfolio = positions held beyond T+3 that are clearly above breakeven

## PEAD (Post-Earnings Announcement Drift)
Stocks continue drifting in the direction of earnings surprise for weeks/months after announcement.
- Well-documented market anomaly
- Provides opportunity to exploit the market's delayed response
- Jeff uses this for extended hold thesis on earnings runners

---

# 2. CHARTING SETUP (TradingView)

## The 4 Core Indicators (2025 Setup)

### Indicator 1: Swing Data Panel (ADR% / RVOL / PVol / Float% / Avg $Vol)
Shows in a compact table on each chart:
- **ADR%** — how volatile is this stock daily? Higher = can move more per day
- **RVOL** — is today's volume running above or below average?
- **PVol** — projected volume for the full day based on current run-rate
- **Float%** — what % of float has traded today? High % = conviction move
- **Avg $Vol** — average dollar volume — screens out illiquid names
- **Market Cap** — context for interpreting the above

**Why ADR% matters for position sizing:**
A stock with 5% ADR% needs much less capital allocation than a 2% ADR% stock to achieve the same risk per trade. High ADR% securities = fewer shares needed = less slippage.

### Indicator 2: ATR% Multiple from 50-MA
Shows exactly how many ATR units the stock is extended from its 50-day MA.
- **0–2x ATR:** Tight, early in move — ideal entry zone
- **2–4x ATR:** Still tradeable but getting extended
- **4x+ ATR:** DO NOT ENTER (Hard Rule #2) — too extended, fade risk is high
- **6–7x ATR on INDEXES:** Extension signal → start reducing longs / consider shorts
- **10x+ ATR:** Only possible for meme/squeeze stocks (FFIE, AMC, OPEN) — recalibrate with different tools

**Key insight:** ATR% from 50-MA ACCOUNTS for volatility, whereas simple % extension from MA does NOT. A 10% move on a 5% ADR stock is very different from 10% on a 1% ADR stock.

### Indicator 3: VARS with Histogram
Replaces traditional RSI-style RS lines.
- Shows which stocks are gaining RS relative to market, adjusted for their own volatility
- Settings Jeff uses as swing trader: (refer to tweet thread for exact numbers)
- Alternative: IBD-style RS by @Fred6724 — full MarketSmith RS model replicated free on TradingView

### Indicator 4: Simple Volume with Pocket Pivots
Clean volume bars with pocket pivot identification.
- **Pocket Pivot:** A day where volume exceeds the highest down-volume day of the prior 10 sessions — signals quiet accumulation
- If uncertain whether RVOL qualifies as "high": use Projected Volume with 50% haircut as your threshold
- One day of strong price + high volume can completely change the narrative of 3 months of prior price action

## Two Templates
1. **Default Template** — used for regular swing setups
2. **Post-Earnings Template** — adjusted view for earnings gap plays

---

# 3. SCREENERS — THE FULL WORKFLOW

## Core Philosophy on Screening
> "My pre/post-market routine takes far more screen time than the actual market session. Many overlook the effort, commitment, and discipline it takes to show up daily — even on days when no trades will be executed."

- Post/pre-market work = minimum **2 hours per session**, often done in a coffee shop
- 14 post-market screeners (Finviz + TradingView) + 2 live-market screeners
- **No screener alone captures every opportunity** — screeners only build a GENERIC watchlist
- Actionable ideas come ONLY after watchlist MANAGEMENT, not just screening

## The 14 Post-Market Screeners

### 1. CANSLIM-Inspired Screener (Most viral — 1.9M+ Twitter impressions)
Filters for stocks showing:
- Strong EPS & Sales growth (C + A in CANSLIM)
- New highs or near new highs (N)
- Institutional sponsorship (I)
- Market leading RS (L)
- 2025 addition: "Institutional Transaction" filter in Finviz — catches recent institutional buying/selling activity

### 2. High ADR% Hottest Stock Screener
- Filters for stocks with ADR% > threshold (high momentum names)
- Qullamaggie-style variant: mimics his 2003–2004 TASR-era screening (very tight, high ADR%, strong RS)

### 3. Extended Bases / Cup & Handle (KC Trade-inspired)
- Looks for stocks that have been consolidating for 6+ months ("does the stock WANT to go higher?")
- Prolonged consolidation = coiled spring ready to explode
- This screener found KC before the +180% trade in 2024

### 4. Strongest Mover (1W / 1M / 3M / 6M)
- Pure RS momentum — what has moved the most across timeframes?
- Cross-referencing timeframes reveals sustained leaders vs. one-day wonders

### 5. IPO Screener (Weekly frequency)
- Only Finviz can properly filter by IPO date
- New issues with strong RS = highest-growth potential names

### 6. High Short Float Screener (Weekly frequency)
- Only Finviz filtering parameter can do this
- High short float = potential squeeze fuel on top of technical setup

### 7. Liquid ETF Screener
- Jeff trades beyond individual US equities — ETFs give access to sectors, commodities, crypto, international markets
- Key advantage: correlation diversification — not all correlated to same factor
- Leveraged ETFs preferred for higher ADR% when available

### 8. Screen Within Screen (Watchlist)
- Runs screener filters WITHIN an existing watchlist — narrows already-curated names

### 9. Liquid Mega Cap Fixed Watchlist
- Fixed list of stocks with >$1B average daily dollar volume
- These names always available for trades without RVOL requirement
- Each has a leveraged ETF equivalent listed for higher ADR% option

## Finviz API → TradingView Transfer Hack
By @erikcarell — copies ALL screener results into TradingView watchlist automatically with a code snippet. Consolidates full 14-screener process into organized watchlists in ~3 min.

## 2 Live-Market Screeners (RVOL-based execution)
1. **Focus List Based** — filters for RVOL surges WITHIN your pre-curated Focus List only
2. **Pre-market Gapper Based** — catches stocks gapping up pre-market with above-average volume

---

# 4. THE FOCUS LIST — HOW IT WORKS

## Watchlist vs. Focus List — Critical Distinction
- **Watchlist:** Generic collection from screeners. Potentially 50–200 names. NOT yet actionable.
- **Focus List:** 5–15 names maximum. Each one has been manually reviewed, meets ALL criteria, and is ready to trade if RVOL triggers at open.
- **Stalk List:** Names between watchlist and focus list — worth monitoring but not yet ready

## The 5 Criteria to Upgrade from Watchlist → Focus List

### 1. Relative Strength FIRST (Most Important)
> "Relative Strength First, Setup Second" — Jeff's core rule  
> Qullamaggie: "True focus is always Relative Strength"

A stock MUST be outperforming the market over the past 1 month, 3 months, and ideally 6 months. If the stock is lagging the market, NO setup qualifies it — skip it.
- Use RS line vs SPY/QQQ on daily chart
- Leading industry group = bonus confirmation

### 2. VCP Present in Price (or Price + Volume)
- Price must be contracting — candles getting tighter and tighter
- Volume must be drying up during the contraction phase
- Price must be holding ABOVE the 10-MA and 20-MA (not violating them)
- Pattern must show at least 2–3 contractions of decreasing depth

### 3. High ADR% (Momentum Confirmed)
- ADR% above ~4–5% minimum for swing trading (lower ADR = slower moves)
- High ADR% = momentum is active = price can make substantial daily moves

### 4. Low Float / Small-to-Mid Cap Preferred
- Best % performers almost always have: small-mid market cap + low float + some short interest
- Lower float = each share of volume has more price impact = explosive potential moves

### 5. Not Extended (ATR% from 50-MA < 4x)
- If already at 4x+ ATR extension from 50-MA → NOT on focus list → wait for new base to form

## What the Chart Should Look Like (A-Rated Setup)
From Jeff's "screensaver chart" — key ingredients:
1. Strong prior uptrend (stock already a leader)
2. Smooth pullback or consolidation (not chaotic/volatile)
3. Price coiling above 10-MA and 20-MA
4. Volume contracting during base
5. RS line holding up or making new highs even during base
6. ADR% elevated (momentum not dead)
7. ATR% from 50-MA between 1–3x (room to run)
→ When this breaks out on HIGH RVOL = A-rated execution opportunity

## Real Examples
- **COIN (Jan 2024):** RS leadership + VCP + catalyst → +110% from Feb 2024
- **KC (2024):** Extended base, cup & handle, screened via screener #3 → +180% in 6 weeks
- **WULF (in WGMI group):** Picked as strongest within weakest-link peer group → +120% in 2 months
- **FFIE (2024):** Fundamentally worthless company, but technically perfect high ADR% float setup → traded it anyway (fundamentals irrelevant for short-term trading)
- **RGTI (Sep 9, 2025):** Quallamaggie traded it from Jeff's focus list → +40–80R gain

---

# 5. PRE-MARKET ROUTINE (30 Min Before Open)

## Daily Time Investment
- Post-market: ~2 hours (screening + watchlist management + focus list prep)
- Pre-market (30 min before open): Situational awareness + alerts + news check
- During market: Alert-driven execution, stop management
- Jeff often does this in a coffee shop — it's a business, not a hobby

## The 4 Pre-Market Tools

### 1. CNBC "5 Things to Know Before the Stock Market Opens"
- 3-minute read available 2 hours before open
- Key macro/news events that could affect session

### 2. Top Pre-Market Movers (thestockcatalyst.com)
- If you trade story stocks, earnings gaps, or episodic pivots — essential one-stop view
- Quickly identifies what's moving pre-market and why

### 3. Futures Watchlist (TradingView)
- Check: US100, US500, US2000, US10Y (bond yields)
- Check: BTC, ETH (crypto futures, 24/7)
- Check: Gold, Oil, Natural Gas
- Check: Asian/European indexes (HSI, 0003, NATURA etc.)
- Purpose: understand where global sentiment is before US open

### 4. Setting Price Alerts (TradingView — Critical Step)
- Every stock on Focus List gets a price alert set at the breakout level the night before
- Alert setup = ritual, not optional
- Alerts give you a "feel of the market" — if 6 alerts trigger at once = hot environment; if none trigger = quiet day, reduce risk
- Allows Jeff to NOT stare at screens all day — alerts replace constant monitoring

## Situational Awareness — Reading Market Breadth

### Qullamaggie's Simple Breadth Method
- Look at % of stocks above their 20-MA and 50-MA across the entire market
- If breadth is weakening (fewer stocks above MAs) while index makes new high → DIVERGENCE → reduce long exposure
- This is how Jeff identified market weakness on March 21, 2025 and shorted on March 28, 2025

### TradingView Breadth Symbols
- `MMTW` = % of stocks above 20-MA (short-term)
- `MMFI` = % of stocks above 50-MA (medium-term)  
- `MMOH` = % of stocks above 200-MA (long-term)
- Watch: when MMTW drops sharply while SPY holds → distribution happening under the surface

### Top-Down Process (Market → Sector → Industry → Stock)
1. **Market level:** RSP (equal-weight S&P) vs SPY (cap-weight) — if RSP underperforms, big tech is carrying the market and breadth is weak
2. **Sub-market:** IJS (small value), IJT (small growth), IJJ (mid value), IJK (mid growth), IVE (large value), IVW (large growth) — which is leading?
3. **Sector level:** Compare 11 SPDR sectors (XLK, XLF, XLE, XLV etc.) by % gain from 52-week lows
4. **Industry group:** Which specific industry groups hitting 1-month RS highs? This is where the best stocks live
5. **Stock:** Within the strongest industry group → find the RS leader with VCP setup

### ATR% Index as Market Timing Signal
- When SPY/QQQ reaches **6–7x ATR% from 50-MA** → market is EXTENDED → reduce new longs, prepare for pullback
- When SPY/QQQ drops to **oversold ATR% level** → watch for bounce → best time to go long aggressively
- April 7, 2025: Jeff went long at exact market bottom using this signal

---

# 6. EXECUTION — ENTRY RULES

## The Core Logic
> "An astounding trading idea, when it comes up for execution in the live market, must be reassessed by its risk-to-reward potential based on the price action at THAT MOMENT."

An A-rated setup from your focus list can become a C-rated execution if:
- The stock has already run too far from LoD
- RVOL isn't confirming the move
- Market opened gap-up (compressed intraday cushion)

## The 60% ATR Rule (Hardest Rule)

**Rule:** Do NOT enter if LoD distance already exceeds 60% of ATR at the time of entry.

**How to calculate:**
1. Look at ATR of the stock (shown in Swing Data indicator)
2. Look at current price distance from LoD
3. LoD distance / ATR = your % reading
4. If that reading > 60% → skip the trade

**Why this works:**
- ATR represents the stock's "daily volatility budget" — visualize it as a spring coil
- If 60%+ of that budget is already used up (price moved away from LoD), the spring is already stretched
- Your stop (at LoD) is now too far away → risk/reward collapses
- Historically: entries below 50–60% ATR from LoD have dramatically lower stop-out rates

**Practical example:**
- Stock ATR = $1.00
- LoD = $10.00, current price = $10.65
- LoD distance = $0.65 = 65% of ATR → DO NOT ENTER
- Same stock at current price $10.55 = 55% → BORDERLINE, still consider if RVOL is extreme
- Same stock at $10.40 = 40% → GOOD ENTRY ZONE

**For ORH (Opening Range High) buy-stop entries:**
- Create a "distance column" in your spreadsheet: predetermined entry price – predetermined stop loss / ATR of stock
- Must be <50% to qualify

## The 4x ATR% Rule (Hard Rule #2)
- If stock is already 4x+ ATR% extension from 50-MA → DO NOT ENTER
- The trade has already moved too far from its base — upside limited, downside risk high
- Visualize ATR% from 50-MA as a "launchpad" — you want to enter while still close to the pad

## RVOL Confirmation Rule (Hard Rule #4)
- For stocks NOT in the liquid mega-cap watchlist → MUST have substantial RVOL to enter
- "Price always fades outside of RVOL" — without volume confirmation, breakouts fail
- Exception: Mega-cap liquid names (>$1B daily $ vol) — they trade themselves

## The 30-Minute Rule (Hard Rule #5)
- Wait 30 minutes after market open before entering new positions
- Unless: EXTREME RVOL surfaces (so high it overrides the wait)
- Why: First 30 min is chaotic — spreads are wide, direction unclear, many fakeouts
- The ORH (Opening Range High) is established in the first 30 minutes
- M30 Re-ORH = stock reclaims the 30-min ORH after briefly dipping → high-quality entry signal

## No-Trade Conditions (Hard Rules)
- No trade before pre-market major economic data releases (CPI, Fed, NFP etc.)
- No trade pre/post earnings release (gap risk)
- No biotechs from post-market scan (overnight gap risk is too unpredictable — use LABU/LABD ETFs instead)
- No trade against declining 200-MA (the stock is in a downtrend — fighting the trend)
- No trade into immediate gap resistance zone (price often fails at unfilled gaps)
- No trade when market is gapping up significantly at open (compressed intraday cushion)
- Max 3 NEW positions per session — roll risk as market confirms momentum from prior day

## Never Chase
> "Missing trades won't make you go broke. Chasing them often will."
- If you missed the optimal entry → WAIT for next setup, do not chase
- The stock WILL come back or a new setup will form
- Case study: PSIX — Jeff missed the entry, refused to chase, waited for next setup

---

# 7. THE 3-STOP STRATEGY (Jeff's Original Framework)

## Why It Exists
> "If your win rate is below 40%, your main focus should be on controlling losses."

Most traders experience 1R losses that are actually 1.03–1.3R in practice (slippage, spread, borrowing). The 3-stop strategy caps average loss at **-0.67R** without significantly impacting trade outcomes.

## The Exact Mechanics

### Position Setup (Entry Day = Day 0)
- Divide full position into **3 equal tranches of 33%** each
- Each tranche has its own stop level — staggered from entry toward LoD
- **Stop 1 (first 33%):** Tightest stop — just below recent intraday support
- **Stop 2 (second 33%):** Mid-level stop
- **Stop 3 (final 33%):** Full stop — usually at or near LoD

**Result:** If first stop triggers, you only lose 33% of position at that level. Average loss across all 3 = much less than -1R.

### Day 0–2 Management
- If **profit-to-risk > 2x within Day 0–2:** Shave 33% off total position (take partial profit)
- All 3 stop levels are MAINTAINED but size is adjusted to net balance
- Example: $UNFI +100% EPS surprise, hit 10x ATR% in 25 min → take 33% off immediately, let rest run

### Day 3 Action
- **33% size reduction** on Day 3 regardless of P&L if trade hasn't followed through convincingly
- Consolidate all remaining stops to **breakeven level** on 1 full singular size
- Exception: if trade is clearly accelerating beyond 4x ATR% → shift to "catalyst gap" rules

### Day 4 Onwards
- **Mental stop on 10-MA** — no more staggered stops, pure price action management
- Rule: If daily candle does NOT close below 10-MA → hold the position
- If close below 10-MA on Day 8 → adjust stop to breakeven of that day, let market trade for 5-min ORH opening, then let it take you out naturally
- Repeat this process until position is finally exited
- Jeff held $XLU entry from July 9th for 86+ calendar days using this method

### Day 4+ Nuances (Extended Winners)
- If trade runs beyond **8–10x ATR% extension from 50-MA** while holding → PARTIAL PROFIT SIGNAL
  - Sell 33% of net size, readjust breakeven stop proportionally
  - Stop always remains at breakeven — mental stop at 10-MA
- If swing trade extends for months (becomes a longer hold) → 10-MA sell rule can keep you in for up to 5 months

### Re-Entry Rules (After Stop Trigger)
If 2 stops triggered but price reverses and reclaims the 30-min high:
- Do NOT re-add the 2 lost tranches
- Hold only the remaining 1/3
- Add new position via **inverse pyramid**: e.g., 10,000 shares original → 6,666 stopped out → 3,334 remaining → add 50% of 3,334 (1,667) → back to 50% net size instead of original 33%
- This keeps total R loss within -1R even with re-entry

### Why Average Loss = -0.67R not -1R
- Stop 1 at ~33% of position: loss ≈ 0.2–0.3R
- Stop 2 at ~33%: loss ≈ 0.4–0.5R  
- Stop 3 at final LoD (33%): loss ≈ 1R on that tranche
- Weighted average across all scenarios ≈ 0.67R

### Visual Effect (10 Consecutive Losses)
- Traditional -1R system: -10R total after 10 straight losses
- 3-Stop system: approximately -6.7R after 10 straight losses
- This difference in drawdown depth is the margin between quitting and staying in the game

---

# 8. TRADE MANAGEMENT (Post-Entry)

## Core Principle
> "Don't get fixated on price movements; be patient with the factor of time. A chart has both a y-axis AND an x-axis."

## Sell Into Strength — Always
- Always take partial profit when trade moves significantly in your favor
- **"Sell some into strength, or death by a thousand cuts"**
- BUT: Don't sell too aggressively — let your winners breathe
- If you don't sell into strength, you'll end up selling into weakness (forced out at a loss)
- Rule: **Never lose two weeks of gains in a single day**

## When to Add to a Position
- ONLY add to a position that is ALREADY profitable and above breakeven stop
- Adding to a loser = averaging down = prohibited
- Best time to add: T+3 or later, when trade has proven itself, stock still leading sector/market
- Add to position size using same 3-stop logic but smaller increment (1/4 or 1/3 of original size)
- Durable portfolio (post T+3) → priority shifts to ADDING existing positions, NOT taking new ones

## The 10-MA Sell Rule
- Once in Day 4+, only exit when daily candle CLOSES below 10-MA
- This single rule can keep you in a winner for weeks or months
- Jeff held $XLU for 86 calendar days using this rule
- Caution: When trade hits 4x+ ATR% extension from 50-MA AND closes below 10-MA → exit full position (don't give back)

## Correlation Risk Management
- Never have all big winning trades in the same industry group simultaneously — they move together in streaks AND in crashes
- "All your big winning trades come in a bundle, likewise your losing trades come in a streak" — this is statistically provable in your own journal
- Diversify with lower-beta ideas or ETFs in different sectors when one sector gets crowded

---

# 9. JOURNALING — THE REAL EDGE SOURCE

## Core Principle
> "The greatest improvements in trading performance will come from analyzing YOURSELF, not the market."

Profitable trading = math. Not opinions, not great stock picks. Pure statistics over hundreds of trades.

## What Your Journal Can Reveal (Actionable Insights)

### Insight 1: MA Exit Timing
You may be significantly MORE profitable if you closed trades based on a moving average aligned with your **actual average holding period for winning trades**, rather than the MA you *believe* works. Check your journal.

### Insight 2: Market Cap Sweet Spot
You may have a substantially higher win rate and profit factor with stocks under $10B market cap vs. above. Or vice versa. Your journal will tell you. Stop applying a universal strategy to all market caps.

### Insight 3: Product Type Edge
You may have a CLEAR edge in trading liquid ETFs over individual stocks — or the reverse. If your stock trades are dragging down your ETF profit factor, analyze them separately. Don't average them together.

### Insight 4: RVOL Correlation
The majority of your winning trades likely started from high relative volume execution days. Check this. If true → enforce RVOL filter on ALL entries immediately.

### Insight 5: Loss Elimination via Rules
You could potentially eliminate 70%+ of your losing equity trades by incorporating high RVOL as a strict entry criterion. Reverse-engineer your past trades: remove every trade that didn't have high RVOL at entry. Compare profit factor before/after.

### Insight 6: The 90% Rule
Giovanni's finding: "After reviewing my month, 90% of my losses would have been avoided using 30-min ORB + LoD dist. >60% ATR as strict entry criteria."

## The 7-Part Journal Review (What to Track)
1. **Win rate** across different setups, sectors, market cap ranges
2. **Average winner R** vs. **average loser R** — is your profit factor positive?
3. **Average holding period for winners** vs. losers — are you cutting winners too soon?
4. **Trade entry quality** — what % of trades were entered at <60% ATR from LoD?
5. **P&L Histogram** — distribution of your R-multiples. Are you heavy on small losses and small wins? Or do you have fat tails on the right?
6. **YTD performance by month** — even if YTD looks bad, monthly breakdown may show consistent improvement
7. **Quantifiable edge** — can you state your exact edge in numbers? e.g., "When RVOL >2x at ORH break, my win rate is 52% with avg +1.8R. Without RVOL filter, win rate is 38% with avg +0.9R."

## Period Review Process
- **Monthly:** Review all trades. Mark patterns. Adjust rules.
- **Quarterly:** Bigger picture. Is system improving or degrading?
- Non-negotiable for staying consistently profitable

---

# 10. THE 6 CONVICTION GRAPHICS (Mathematical Foundation)

## Graphic 1: Tighter Entry = Parabolic R Returns
If you cut your entry risk by 50% (tighter stop, same position size), your R-multiple on the SAME move doubles. This has a parabolic effect on profit factor over time. Not linear — parabolic.

## Graphic 2: Monte Carlo Simulation (500 trades)
Comparing same strategy with normal entries vs. 50% tighter entries across 500 simulated trades:
- Tighter entries dramatically reduce drawdown depth
- Tighter entries increase peak equity
- The system's EV doesn't change much — but risk-adjusted returns improve massively

## Graphic 3: Know Your Drawdown Profile
Before live trading any system, simulate what a realistic drawdown looks like:
- With 35% win rate and -0.67R avg loss + +2.5R avg win → what does a 20-trade losing streak look like?
- Knowing this in advance prevents emotional decision-making during drawdowns
- "If you don't know what your drawdown looks like, you'll panic and abandon your system at exactly the wrong moment"

## Graphic 4: Fixed % Risk Compounds Better Than Fixed $ Risk
- Fixed $ risk (e.g., always risk $1,000): As account grows, your risk % shrinks → growth decelerates
- Fixed % risk (e.g., always risk 1% of equity): As account grows, dollar risk grows → compounding accelerates
- Over 1,000 trades, the difference between these two approaches is enormous (exponential vs. linear)

## Graphic 5: Higher Return → Larger Absolute R Increase
As your equity grows, each R unit is worth more in dollar terms. This is why:
- A 35% win rate system is viable long-term if avg win >> avg loss
- The absolute $ improvement per unit of R improvement grows as account grows
- Focus on R-management, not win rate

## Graphic 6: Benefits of High ADR% Securities
- High ADR% stock: You need FEWER shares to achieve your % risk target → less slippage, tighter fills
- Low ADR% stock: You need MORE shares → more slippage, wider spreads, position impact on price
- Capital efficiency: A 5% ADR stock requires ~2.5x less capital allocation than a 2% ADR stock for same risk per trade
- Limitation of 1% risk-to-equity: With small accounts + low ADR% stocks, 1% risk may force position sizes too small to be practical

---

# 11. FULL-TIME TRADING — HARD TRUTHS

## Trading For A Living ≠ Full-Time Trader
- **Trading For A Living (TFAL):** Your primary income comes from trading. The ultimate grail. Extremely rare.
- **Full-Time Trader:** You trade full-time but have other income sources or capital buffer. More achievable.

## Financial Preparation Before Quitting Your Job
- Minimum 12–24 months living expenses separate from trading capital
- Do NOT use trading capital to pay rent — this creates performance anxiety that destroys your edge
- Prove consistent profitability for 2–3 full years (including bear markets)
- Have a tax plan — trading income is taxed differently in most jurisdictions
- Build non-trading assets first (real estate, bonds) — Jeff did this before going fully independent

## The Math Required
- 6% monthly compounded = 100%+ annualized
- Even 27% win rate with correct R management = 114% annualized (proven mathematically)
- But: consistency over hundreds of trades is what matters, not one great year

---

# 12. RECOMMENDED BOOKS

1. **"Japanese Candlestick Charting Techniques"** — Steve Nison
   - Foundation of price action reading
   - Required reading for CFTe and CMT exams
   - Understanding candle patterns within context (support, resistance, volume)

2. **"Phantom of the Pits"** — Anonymous (free online)
   - Most underrated trading book
   - Core lesson: "The best loser is the long-term winner"
   - Key rule: If the market does not prove you right, that doesn't mean it's proved you wrong yet — give it time
   - Another key rule: Add to winning trades, cut losing trades immediately

3. Additional books referenced in tweet thread (link: x.com/jfsrev/status/1803656136526274800)

---

# 13. FREE TOOLS JEFF USES

| Tool | Purpose |
|------|---------|
| TradingView | Charting, screeners, price alerts, breadth analysis |
| Finviz | Post-market screening (especially for Institutional Transaction filter) |
| thestockcatalyst.com | Pre-market gappers, catalysts |
| CNBC "5 Things to Know" | Daily macro news pre-market |
| FinanceCharts.com | Free historical chart research |
| RS Histogram Google Sheet | Free, updates daily, shows sector/stock RS rankings |
| 13F filing tools | Analyze Druckenmiller's quarterly positions |
| IBKR | Execution platform (3-stop strategy tool available) |

---

# 14. RECOMMENDED TRADERS TO FOLLOW

| Trader | Why Follow |
|--------|-----------|
| **@qullamaggie** | Primary influence — pure momentum, RS-first, grit over decades |
| **@BrianLeeTrades** | Best on trade management, small losers, R-multiple optimization |
| **@LoneStockTrader** | ORB precision, 3-stop strategy user |
| **Stanley Druckenmiller** | Top-down macro + sector rotation, patience with conviction |
| **Clement Ang** | Daily top-down commentary, concise and actionable |

---

# 15. CORE MINDSET PRINCIPLES

## On Process
- Post/pre-market routine > the actual market session. Show up every day, even when not trading.
- You trade well because you PREPARED well, not because you're smart
- "Super trades are made not because you are special or intelligent — it is because you turned up and acted in a consistent manner"
- Results come from routine, habits, and behavior — not talent

## On Losses
- "The best loser is the long-term winner" — Phantom of the Pits
- Missing a trade will NOT make you broke. Chasing it can.
- Every loss is data. Keep your journal. Don't hide from past performance.
- Bad loser = permanent losses. Good loser = data for improvement.
- With correct R management, you can be profitable with a 27–35% win rate

## On Patience
- "When fishermen cannot go to sea, they repair nets" — use quiet market days for prep, review, and improvement
- "The crucial thing is to avoid playing when you don't see a fat pitch"
- Always seek REASONS TO AVOID a trade, not reasons to take it
- The urge to give up is often strongest RIGHT before things click

## On Simplicity
- "Simplicity enhances trading performance. Complexity won't."
- You don't need 20 indicators — you need 4 core ones you understand deeply
- "Think in hundreds of trades" — no single trade defines your system

## On Trading Full-Time
- Hard truth: Trading part-time for income is a fallacy
- Good traders don't sell services. Good investors don't sell advice.
- If you have a good career with growth prospects, don't quit it prematurely

---

# 16. FAQ — DIRECT ANSWERS

**Q: How long to become consistently profitable?**
A: Jeff took ~4–5 years of serious effort before consistent profitability. The learning curve is real. (ref: x.com/jfsrev/status/1803419841531093465)

**Q: How many positions at once?**
A: Typically 3–6 active positions. Never more than 3 NEW positions opened in a single session.

**Q: Do you trade biotechs?**
A: Never individual biotechs — overnight gap risk is uncontrollable. Only IBB/XBI via LABU (long) or LABD (short) ETFs for biotech exposure.

**Q: For leveraged ETFs — check LoD and RVOL on the ETF or the underlying?**
A: Both matter, but the ETF chart is what you're trading. For mega-cap/liquid names (SPXL, TQQQ, GLD etc.) — no RVOL requirement. For smaller ETFs — RVOL confirmation required.

**Q: For IBIT/ETHD (crypto ETFs with 24/7 underlying) — how to measure HOD distance?**
A: Use the **trading-session HOD** (9:30am–4pm), not the 24-hour crypto HOD.

**Q: What sectors are excluded from your screeners?**
A: Biotechs excluded from post-market scan. (Other exclusions in dedicated tweet thread.)

**Q: 3-stop strategy — if 2 stops hit but price reverses and breaks 30-min high, re-add?**
A: NO. Keep only the remaining 1/3. If you want to re-enter, use inverse pyramid method — add 50% of your remaining 1/3, bringing you back to ~50% of original. Do not rebuild back to 100%.

**Q: Do you wait 30 minutes to measure ORH?**
A: Yes — the Opening Range High is established in the first 30 minutes. Re-ORH (reclaim of the 30-min high) is a high-quality intraday entry signal.

**Q: How do you decide what's A-rated vs B-rated?**
A: A-rated = RS leader + VCP + RVOL confirming + LoD <60% ATR + ATR% from 50-MA <4x + no gap resistance above + not pre-earnings/econ data. All boxes checked = A-rated. One box missing = B or C. Jeff ONLY trades A-rated setups.

**Q: What's your philosophy in one sentence?**
A: "Find the leading stock in the leading industry group, buy it when it's tight and consolidating above its key MAs with volume drying up, enter only when RVOL confirms the breakout with LoD distance below 60% ATR, manage with 3-stop strategy, hold winners with 10-MA rule, journal everything."

---

# COMPLETE SYSTEM FLOWCHART



Full Substack overview:

## ABOUT JEFF SUN

- Traded for 16+ years, consistently profitable since ~2012
- Manages a small-scale, closed-end asset management fund (single investor, performance-fee basis)
- 2023 tax bill exceeded $100K USD (no capital gains tax in Singapore)
- Owns 13 properties; real estate portfolio crossed $10M USD (July 2025)
- Active on Twitter/X (@jfsrev), LinkedIn, Instagram
- Won USIC 2023 competition (2nd place, small caps category)
- Influenced by: Qullamaggie (Kristjan Kullamägi), Mark Minervini, Stanley Druckenmiller, Phantom of the Pits
- Reference summary of his method: https://qullamaggie.net/jeff-suns-method-and-flow/

---

## CHAPTER 1 — GLOSSARY OF TERMS

| Term | Definition |
|------|-----------|
| **LoD** | Low of Day — intraday price low at the time of reference |
| **RVOL** | Relative Volume — current volume vs. 50-day average session volume |
| **T+3** | T = execution day; +1/+2/+3 = calendar trading days after (excludes weekends & holidays) |
| **VARS** | Volatility Adjusted Relative Strength |
| **VARW** | Volatility Adjusted Relative Weakness |
| **ORH** | Opening Range High — intraday high of the opening range |
| **M30 Re-ORH** | 30-minute post-open reclaim of the opening range high |
| **R / R-Multiple** | Risk unit — profit/loss expressed as multiple of initial risk (entry price minus stop-loss) |
| **X × ATR% from 50-MA** | ATR% multiple extension from the 50-day moving average |
| **ATR** | Average True Range |
| **ADR%** | Average Daily Range (percent) — differs from ATR |
| **VCP** | Volatility Contraction Pattern (popularized by Mark Minervini) — price tightening before expansion |
| **PEAD** | Post-Earnings Announcement Drift — stocks continue drifting in direction of earnings surprise post-announcement |

**Key Principle on VCP:** Every sustainable price expansion rally is ALWAYS preceded by a phase of price contraction/tightening. Jeff will NEVER enter a stock with prior loose price action.

**Tweet References:**
- VARS explanation: https://x.com/jfsrev/status/1909486454260351162
- ATR% from 50-MA: https://x.com/jfsrev/status/1671541248044457986
- VCP: https://x.com/jfsrev/status/1806188623735509403
- PEAD: https://x.com/jfsrev/status/1838201736043057192

---

## CHAPTER 2 — CHARTING: APPROACH USING TRADINGVIEW

### TradingView Template Versions
- **2023 Version:** https://x.com/jfsrev/status/1649333754215948290
  - 4 core indicators shared: ESV Dashboard (EPS/Sales by @JohnMuchow), ADR%/ATR/LoD Table (by ArmerSchlucker), IBD RS Rating (by @DumbleDax / @Fred6724), Pocket Pivot Volume (by @finallynitin)
- **2024 Version:** https://x.com/jfsrev/status/1818297619338395847
  - Two separate templates: default & post-earnings
  - Coded by @DumbleDax; thanks also to @finallynitin, @JohnMuchow
- **2025 Version:** Consistent free indicators (pillars unchanged)

---

### INDICATOR 1: Swing Data — ADR% / RVol / PVol / Float% / Avg $ Vol
**TradingView:** https://www.tradingview.com/v/uloAa2EI/  
**Users:** 75,000+  
**Purpose:** All-in-one panel for swing trading metrics

#### Understanding ADR%
- ADR% = Average Daily Range (percent movement per day)
- **Thread:** https://x.com/jfsrev/status/1852994791795282188 — Trend-Following vs. Range-Expansive behavior
- **Benefits of High ADR%:** https://x.com/jfsrev/status/1856232860107350147
- **Capital allocation by ADR%:** https://x.com/jfsrev/status/1939966489475547529
- Qullamaggie always chooses leveraged ETF of underlying for higher ADR%: https://x.com/jfsrev/status/1970761700472430903
- Full leveraged ETF list (updated monthly): https://x.com/jfsrev/status/1986252984481960281
- Mobile App video demo: https://x.com/jfsrev/status/1744564021565767816

#### Understanding LoD Distance of ATR
- **"60% ATR below LoD" concept:** https://x.com/jfsrev/status/1788583106418541011
  - Price must not have moved more than 60% of ATR below LoD at entry
  - Visualize ATR as a "spring coil" — the tighter the coil, the more explosive the potential
- **Perks of <60% LoD execution:** Avoids chasing, reduces stop-loss frequency dramatically
- USIC 2023 (2nd place): https://x.com/jfsrev/status/1628559711917473793

#### Understanding RVOL (Relative Volume)
- RVOL = current volume run-rate vs. 50-day average
- **Entry confirmation:** Strong RVOL = first proof of institutional buying: https://x.com/jfsrev/status/1946777562648383700
- **ORH entries with RVOL have statistical edge:** https://x.com/jfsrev/status/1809139555041518052
- **RVOL saves from unnecessary stops:** https://x.com/jfsrev/status/1955826518644678725
- Adam H. Grimes explained RVOL in 2015 (best explanation)
- Grimes also wrote a piece on RVOL in 2025 after Jeff's tweet caught his attention

#### Understanding Average $ Volume vs Average Share Volume
- Slippage and wide spreads cost Jeff 6–7% of 2021 total equity: https://x.com/jfsrev/status/1591446897100824577

#### Understanding Market Cap, Low Float%, Short Float
- Best % performers almost always have: Small-mid cap + Low Float + Short Float interest: https://x.com/jfsrev/status/1944595506853970049
- Top 100% performers from 2018–2024 study: https://x.com/jfsrev/status/1852524466510962850

---

### INDICATOR 2: ATR% Multiple from 50-MA
**TradingView:** https://www.tradingview.com/script/oimVgV7e-ATR-multiple-from-50-MA/  
**Users:** 47,000+  
**Purpose:** Quantify how extended a stock is from its 50-day MA in ATR units

#### Key Concepts
- **Core philosophy:** One trading philosophy (ATR% from 50-MA) = first million from swing trading: https://x.com/jfsrev/status/1671541248044457986
- **Quantifying extension objectively:** https://x.com/jfsrev/status/1671541248044457986
- **Favorite tool for partial profit-taking into strength:** https://x.com/jfsrev/status/1671541248044457986
- **Advantage for scaling out profits:** https://x.com/jfsrev/status/1671543338422640641
- **6–7x ATR% for Indexes:** https://x.com/jfsrev/status/1673518673318002688
- **Hard Rule:** Do NOT enter if ATR% from 50-MA exceeds **4x multiples** (extended trade)
- **10x ATR% compression possible at higher prices:** https://x.com/jfsrev/status/1944301326453944377 (LIF example)
- **LIF after 10 weeks:** https://x.com/jfsrev/status/1971841529808670905
- **STX patience example (+20%):** https://x.com/jfsrev/status/1952199616923062404
- **ATR% vs. % Extension from MA** — ATR adjusts for volatility: https://x.com/jfsrev/status/1763496767579103718
- **13-year study (2012–2025) by Denis Hamel** — 5,506 US stocks, ~50M stock-days on ATR extensions (Sept 25, 2025)
- **Never chase extended trades:** https://x.com/jfsrev/status/1971067014346310018 (MSOS Aug vs Sep 2025)
- **Oversold signal use:** https://x.com/jfsrev/status/1909236122871574826
- **Index extension signal (extension top):** https://x.com/jfsrev/status/1802978682669269480
- **Index oversold signal (April 7, 2025 long):** https://x.com/jfsrev/status/1909243817989189774

#### Additional ATR% Indicators
- **Will Hu's historical ATR% indicator** — useful for meme stocks/squeezes (FFIE, OPEN, AMC, BB)
- **Cotton Dog's ATR% Band indicator** — projects ATR% multiple from current price: https://x.com/jfsrev/status/1972225421438779724
- Combining 3-stop strategy + 10x ATR% from 50-MA = significant edge: https://x.com/jfsrev/status/2030681452455883001

---

### INDICATOR 3: VARS — Volatility Adjusted Relative Strength (with Histogram)
**TradingView:** https://www.tradingview.com/script/nbgyYwu1-Volatility-Adjusted-Relative-Strength-VARS-Histogram-Option/  
**Users:** 5,000+

#### Background
- Enhances traditional RS by factoring each stock's unique volatility
- Inspired by 2023 Reddit thread by mattishenner
- Jeff published own VARS with histogram — October 2025: https://x.com/jfsrev/status/1976121442086564329
- VARS thread: https://x.com/jfsrev/status/1909486454260351162
- Settings for swing traders: (per tweet thread)

#### Alternative: IBD RS Indicator by @Fred6724
- Traditional Relative Strength line similar to IBD RS Rating
- Full MarketSmith model replicated on TradingView — FREE
- Link: https://x.com/jfsrev/status/1649338005302415360

---

### INDICATOR 4: Simple Volume with Pocket Pivots by @finallynitin
**TradingView:** https://www.tradingview.com/script/JkB0iCFp-Simple-Volume-with-Pocket-Pivots/  
**Description:** Simple, clean volume script with pocket pivot detection

#### Key Volume Insights
- One day of strong price + high volume can reshape 3 months of price action bias: https://x.com/jfsrev/status/1959451625145434489
- If uncertain about "high RVOL" threshold: use Projected Volume with 50% haircut: https://x.com/jfsrev/status/1950202147787977058

---

### WORTHY MENTION INDICATORS (Secondary Template)
- **EPS & Sales by @Fred6724** — quarterly earnings data dashboard
- **Industry Group Strength by @amphtrading** — how Jeff uses it: https://x.com/jfsrev/status/1845744867047354535
- **Best 8 Free TradingView Scripts (2024):** https://x.com/jfsrev/status/1858822375015661742
- **TradingView Seasonality Table (2025):** https://x.com/jfsrev/status/1971824458341274083

---

## CHAPTER 3 — SCREENERS: FINVIZ (POST-MARKET) + TRADINGVIEW (PRE/LIVE-MARKET)

**Key Principle:** "My pre/post-market work, often done in a coffee shop, easily takes a minimum of 2 hours per session."

**Workflow:** Screening → Watchlist Management → Focus List Preparation → Situational Awareness → Portfolio Stops Management

**Important discussion (read first):** https://x.com/jfsrev/status/1945042238817624213  
**Screening & Watchlist Management — Misunderstood Skill:** https://x.com/jfsrev/status/1945042238817624213

> "My process involves running 16 screeners in total (14 via TradingView, 2 Finviz). No screener alone will capture every opportunity."

### 14 Post-Market Screeners (TradingView + Finviz)
TradingView Screen Sharing introduced Oct 24, 2025 — all 14 screeners shared via single link.

#### 1. CANSLIM-Inspired Calibrated Screener
**Most viral screener — 1.9M+ Twitter impressions**
- TradingView version: https://x.com/jfsrev/status/1796806706028302775
- Finviz version (2025) — includes "Institutional Transaction" filter: https://x.com/jfsrev/status/1964130023751004326
- Finviz mobile web screener: https://x.com/jfsrev/status/1949313660167532903

#### 2. High ADR% Hottest Stock Screener
- TradingView: https://x.com/jfsrev/status/1789602959782977668
- Finviz (2025): https://x.com/jfsrev/status/1964512257918062970
- Finviz (Qullamaggie Style — 2003–2004 TASR): https://x.com/jfsrev/status/1964512257918062970

#### 3. Extended Bases / Prolonged Consolidations (KC Trade-inspired)
Inspired by his 2024 +180% KC trade — Cup & Handle patterns
- Discussion "Does the stock want to go higher?": https://x.com/jfsrev/status/1947145787479331055
- Finviz (2025): https://x.com/jfsrev/status/1965598848761700696

#### 4. Strongest Mover Screener (1W / 1M / 3M / 6M)
- TradingView: https://x.com/jfsrev/status/1659789002814414850
- Finviz: https://x.com/jfsrev/status/1659786288067928064
- Finviz mobile perks: https://x.com/jfsrev/status/1700710382523084964

#### 5. IPO Screener (Weekly)
- Finviz only (only Finviz can filter IPO dates properly): https://x.com/jfsrev/status/1941836386904285491

#### 6. High Short Float Screener (Weekly)
- Finviz only: https://x.com/jfsrev/status/1943548132232663415

#### 7. Liquid ETF Screener
*"Exploring ideas in tradable asset classes beyond correlated equities can provide a valuable edge." — Stanley Druckenmiller*
- TradingView (original): https://x.com/jfsrev/status/1757662271994835388
- Finviz (2025): https://x.com/jfsrev/status/1962458102709837975
- TradingView (2025): https://x.com/jfsrev/status/1962458397380632874
- Liquid ETF discussion: https://x.com/jfsrev/status/1866039252477444166

#### 8. Screen within Screen (Watchlist Screener)
- TradingView: https://x.com/jfsrev/status/1770337966814363698

#### 9. Liquid Mega Cap Fixed Watchlist
- Stocks exceeding **$1B average dollar volume** constant
- Listed with synthetic leveraged ETFs for higher ADR%: https://x.com/jfsrev/status/1962094789068996858
- How to identify opportunities within list: https://x.com/jfsrev/status/1912034116465545492

#### Finviz API Hack — Copy Screen Results to TradingView Watchlist
- By @erikcarell — full code shared publicly
- 3-minute consolidation video: https://x.com/jfsrev/status/1772522489446543679

#### Live Screener Updates
- Consolidated Focus List (Oct 6, 2025): https://x.com/jfsrev/status/1975058662432608568
- Full video walkthrough of daily process (Dec 8, 2025): https://x.com/jfsrev/status/1997975342699696445

#### BONUS Screeners
- Julian Komar's Strongest Stock Scan: https://x.com/jfsrev/status/1704767941835936037
- High ADR% + Inside Day Scan (TradingView): https://x.com/jfsrev/status/1826136493452308698
- Tracking RVOL of Watchlist (TC2000 Volume Buzz equivalent): https://x.com/jfsrev/status/1763217976478609894

### 2 Live-Market Screeners (High RVOL Based)
- TradingView — **Focus List Based:** https://x.com/jfsrev/status/1801498691746021731
- TradingView — **Pre-market Gapper Based:** https://x.com/jfsrev/status/1810643031592497162
- 2025 screener relocation update: https://x.com/jfsrev/status/1798726526961405954
- Live market mainframe setup: https://x.com/jfsrev/status/1946214673482969302
- KOSS example (July 3, 2024 — High RVOL at open): https://x.com/jfsrev/status/1946214673482969302

---

## CHAPTER 4 — UPGRADING WATCHLIST STOCK TO FOCUS LIST

**Daily Process Flow:**
`Screening → Watchlist Management → Focus List Preparation → Situational Awareness (Qualitative) → Portfolio Stops Management`

### Daily Process Workflow
- Screening only builds a generic watchlist: https://x.com/jfsrev/status/1685982477561790464
- Actionable ideas only come after watchlist management: https://x.com/jfsrev/status/1823332977679671753
- Detailed daily workflow: https://x.com/jfsrev/status/1945042238817624213
- Segmenting watchlist into 3 sets (rotating review): https://x.com/jfsrev/status/1757271020007006704
- "Back Watchlist" for calibrating screeners: https://x.com/jfsrev/status/1757277320677904721

### What Qualifies My Focus List

**Criteria for a Watchlist Stock → Focus List:**
1. Strong catalytic move with **high volume** (strong ORH breakout, stage 2+)
2. **High ADR%** = momentum in place, stronger expansive moves ahead
3. **Strong RS** (Relative Strength) — must be a leading stock
4. Volume Dry Up (VDU) — not a definitive criterion but noted
5. Price contraction **above** short-term MAs (10 & 20-MA primarily)
6. Some form of **VCP** in price (or price + volume)
7. Must be an **"A-rated"** idea — never settle for B or C setups

**Jeff's Rule:** Relative Strength First, Setup Second
- RS thread: https://x.com/jfsrev/status/1918527933955883091
- Quallamaggie: "True focus is always Relative Strength": https://x.com/jfsrev/status/1964234400637288671

**Focus List Threads (2023 Summary Series):**
- Part 1: https://x.com/jfsrev/status/1659775853574893569
- Part 2: https://x.com/jfsrev/status/1659780808364916737
- Part 3 (Stalk List → Focus List): https://x.com/jfsrev/status/1659795676925145090
- Further discussion: https://x.com/jfsrev/status/1658343561212067840

**Real Case Examples:**
- COIN (+110% from Feb 2024): https://x.com/jfsrev/status/1751903862225776941
- KC Trade (+180%, 2024 full breakdown): https://x.com/jfsrev/status/1864933928924254327
- Quallamaggie RGTI (Sep 9, 2025): https://x.com/jfsrev/status/1966729241707544714
- 4 Focus List chart types: https://x.com/jfsrev/status/1947147206961795574
- FFIE trade (2024 — fundamentals irrelevant): https://x.com/jfsrev/status/1864933928924254327
- WULF vs. WGMI group (+120%): https://x.com/jfsrev/status/1864933928924254327

**Internalize This Chart (Jeff's screensaver):**
- Simplified version: https://x.com/jfsrev/status/1947147206961795574
- Expanded version (with traditional RS): https://x.com/jfsrev/status/1947147206961795574

### Watchlist Management During Volatility
- Educational thread (Aug 22, 2025): https://x.com/jfsrev/status/1958740868342698388
- Portfolio Update (Aug 23, 2025): https://x.com/jfsrev/status/1959086277841600580
- Portfolio Update (Aug 26, 2025): https://x.com/jfsrev/status/1960244719000392001
- Portfolio Update (Sep 19, 2025): https://x.com/jfsrev/status/1968946399740940605
- Portfolio Update (Oct 2, 2025): https://x.com/jfsrev/status/1973655851937476920
- Focus List limited to X subscribers (mid-Oct 2025): https://x.com/jfsrev/status/1979027014721114490

### Special Trading Nuances
- **Liquid Mega Watchlist opportunities:** https://x.com/jfsrev/status/1912034116465545492
  - Example: AMZN short via AMZD long: https://x.com/jfsrev/status/1970693106849960114
- **ETF nuances (24-hour underlying markets):**
  GLD(XAUUSD), SPXL(ES), IBIT(BTCUSD), SOLT(SOLUSD), BOIL(NG), FXI(China A50), UCO(WTI)
  Thread: https://x.com/jfsrev/status/1960873535687286891
- **Crypto ETF Friday caveat:** https://x.com/jfsrev/status/1966505551040225362
- **High volatility = hunt, not cash:** https://x.com/jfsrev/status/1905817183399375283

---

## CHAPTER 5 — PRE-MARKET ROUTINE & SITUATIONAL AWARENESS

**Key Principle:** Routine must be time-efficient, manageable, sustainable. It cannot be exhausting. Lower timeframes = greater commitment demanded.

### Price Alerts (TradingView)
- Setting alerts = pre-market ritual: https://x.com/jfsrev/status/1772992258020626581
- Alerts give a "feel of the market": https://x.com/jfsrev/status/1772992258020626581

### Pre-Market Routine (30 Min Before Open)
- Brief 2023 routine: https://x.com/jfsrev/status/1659652530123714561
- Elaboration with 4 free tools: https://x.com/jfsrev/status/1810643020599185525
  1. **CNBC "5 Things to Know"** — bookmark, 3-min read, 2 hours before open
  2. **Top Pre-Market Movers (thestockcataylst)** — story stocks, earnings gaps, episodic pivots
  3. **Futures Watchlist (TradingView)** — BTC, ETH, USO, UNG, US index futures, metal ETFs
  4. Additional tools per thread
- **Earnings 6 outcomes (EOD price action post-earnings):** https://x.com/jfsrev/status/1856274307913265637

### Situational Awareness (Objective Methods)

#### Breadth Indicators
- **Simplest breadth indicator (Qullamaggie's method):** https://x.com/jfsrev/status/1819302708194738483
  - Highlighted weakness (March 21, 2025): https://x.com/jfsrev/status/1902954995013783617
  - Shorted market (March 28, 2025): https://x.com/jfsrev/status/1905817183399375283
- **TradingView End of Day Breadth Panel:** https://x.com/jfsrev/status/1909103399959974111
  - Breadth symbols for bird's-eye view: https://x.com/jfsrev/status/1900181447878787094
  - How to use TradingView breadth symbols: https://x.com/jfsrev/status/1899337742733169078
  - MMTW (% stocks above 20-MA) example: https://x.com/jfsrev/status/1659648518867554304
  - March 2025 breadth confirmation: https://x.com/jfsrev/status/1899337742733169078
- **Short-term NH/NL (52-week New Highs/Lows):** https://x.com/jfsrev/status/1659660014406213632

#### Top-Down Approach (Multi-Level Analysis)
1. **Market Level:** RSP vs SPY (Equal-Weight vs Cap-Weight Index): https://x.com/jfsrev/status/1659665526610874372
2. **Sub-Market Level:** https://x.com/jfsrev/status/1659671534213152768
3. **Sector Level:** https://x.com/jfsrev/status/1659673821253865472
   - 5 Key Sectors for Breakout Opportunities: https://x.com/jfsrev/status/1657392854560538624
4. **Industry Group Level:** https://x.com/jfsrev/status/1659679126389936128
   - Druckenmiller's Indicator — Homebuilders: https://x.com/jfsrev/status/1659679126389936128
5. **RS Histogram Spreadsheet (FREE, updates daily after close):**
   - Tutorial: https://x.com/jfsrev/status/1806709652975141131
   - Dr. Yong Yang's tweak (RS_STS%): https://x.com/jfsrev/status/1812759804395528495
   - Bird's-eye live market use: https://x.com/jfsrev/status/1811405619792056725
   - Free Google Sheet version by @RonakSh92987573: https://x.com/jfsrev/status/1807966765223498058
   - Equal Weight ETFs list: https://x.com/jfsrev/status/1767816515334930808
   - Full ETF list (cap-weighted included): https://x.com/jfsrev/status/1726430162609451255

#### ATR% from 50-MA as Market Timing Signal
- **Extension signal (top):** March 2024 before 2-week sell-off: https://x.com/jfsrev/status/1763578529264947251
- **Oversold signal (bottom):** April 7, 2025 long at market bottom: https://x.com/jfsrev/status/1909243817989189774
  - Detailed breakdown: https://x.com/jfsrev/status/1917142121079042435
- **Index ATR% extension using 6–7x multiples:** https://x.com/jfsrev/status/1673518673318002688

#### Breadth + Industry Groups Relationship
- Strengthening breadth + growing count of industry groups at 1-month RS highs: https://x.com/jfsrev/status/1996467543767474436
  - Oct 29 ATH vs Nov 12 vs Dec 3 (2025) comparison

**Self-Evaluation Tool:** Annotate every trade (win or loss) on the index chart: https://x.com/jfsrev/status/1922500217607487503

**Time Spent Daily:** https://x.com/jfsrev/status/1817897455490625636

**Personal Tip:** Maintain a daily fitness routine before market open for mental clarity.

---

## CHAPTER 6 — TRADE EXECUTION: ENTRY, STOP, % RISK

**Core Principle:** "An astounding trading idea, when it comes up for execution in the live market, must be reassessed by its risk-to-reward potential based on the price action at that moment."

Importance of execution quality: https://x.com/jfsrev/status/1851226250553217242

### 15 HARD EXECUTION RULES

| # | Rule | Link |
|---|------|------|
| 1 | **No entry if LoD already exceeds 60% ATR** (ATR = spring coil) | https://x.com/jfsrev/status/1788583106418541011 |
| 2 | **No entry if ATR% from 50-MA > 4x multiple** (ATR% = launchpad) | https://x.com/jfsrev/status/1763489489652212091 |
| 3 | **No biotechs in post-market scan** — gap risk eliminated; use IBB/XBI via LABD/LABU only | https://x.com/jfsrev/status/1919640159844172103 |
| 4 | **No entry without substantial RVOL** (except mega caps & liquid ETFs) — price fades without RVOL | — |
| 5 | **Delay entry 30 min post-open**, unless extreme RVOL surfaces | https://x.com/jfsrev/status/1775885831989067787 |
| 6 | **No entry before pre-market major economic data** or pre/post earnings | https://x.com/jfsrev/status/1889684456778166297 |
| 7 | **Never trade against declining 200-MA** | — |
| 8 | **Never enter into immediate gap resistance zone** | — |
| 9 | **Max 3 new positions per session** — roll risk as market confirms prior day momentum | — |
| 10 | **Never chase** — only enter at most optimal price; missing a trade won't make you broke, chasing will | https://x.com/jfsrev/status/1889342784353833019 |
| 11 | The more consecutive days the market rises, the **more cautious** about new longs | — |
| 12 | With durable portfolio (post T+3), **priority = adding to existing positions** | https://x.com/jfsrev/status/1968946399740940605 |
| 13 | **Extreme caution with gap-up openings** — risk of overextension: https://x.com/jfsrev/status/1968650833211347437 |
| 14 | **Always long ideas** — even short ideas via inverse long synthetic ETFs | https://x.com/jfsrev/status/1976559786788528328 |
| 15 | **Rule 15 — confidential** (X subscribers only, described in daily Focus List) | — |

---

### THE 3-STOP STRATEGY (Jeff Sun's Original Framework)
**Core Principle:** Cap losses at **-0.67R instead of -1R** without significantly impacting the trade outcome.
**Win Rate Threshold:** If win rate is below 40%, focus on controlling losses first.

**Primary thread:** https://x.com/jfsrev/status/1841852289742733701

#### How it Works:
1. **Entry Day = Day 0:** Position divided into 3 equal parts (33% each), each with its own stop level
2. **3 stops at 33% net size** — staggered to final stop (usually LoD)
3. If **profit-to-risk > 2x in Day 0–2:** Shave 33% off. All 3 stop levels maintained, size adjusted to net balance
4. **Day 3 = 33% size down** (immediate partial profit or risk reduction on trades not following through)
5. All stops consolidated to **breakeven level** on 1 full singular size once secured
6. **Day 4+:** Mental stop on **10-MA** — don't interfere if trade doesn't close below 10-MA
7. 1R loss is actually **1.03–1.3R** with slippage, spread, borrowing (not exactly 1R)
8. **Average R loss: ~0.6–0.8R** (not the full -1R most assume)

#### Key Resources:
- 3-Level Stop System (detailed): https://x.com/jfsrev/status/1841852289742733701
- ITA Trade Example (Nov 2024): https://x.com/jfsrev/status/1855927716404761065
- RDDT Example (June 5, 2024): https://x.com/jfsrev/status/1849460684413890758
- Spreadsheet template: https://x.com/jfsrev/status/1855927716404761065
- Re-entry sizing (staying within -1R): https://x.com/jfsrev/status/1841852289742733701
- Graphical display by @RomanBreakouts
- Graphical display by shrederickson's Newsletter
- Further reduction of R loss (US/EU timezone trader): https://x.com/jfsrev/status/1856695351971054067
- IBKR execution tool by @traderwillhu: https://x.com/jfsrev/status/1980884544262926748
- Effect of small losers (underrated): @BrianLeeTrades
- "If you designed exit rules that lift your average R, you've built a printing machine"
- Managing long-term average R losses to boost profit factor: https://x.com/jfsrev/status/1937402718278369337
- 10 consecutive losing trades impact reduction: https://x.com/jfsrev/status/1647931380033257475
- 3-Stop doesn't interfere with trade's intended stop level: https://x.com/jfsrev/status/1960271372707397916
- BigWaveChartist research on 3-Stop: further exploration
- Shoutout from @LoneStockTrader

#### Execution Tools & Evidence:
- Price alerts + simple position sizing spreadsheet + market/buy stop execution
- One trade covering 13 losing streaks: https://x.com/jfsrev/status/1749460835662225835
- Single winning trade covering 50+ losses example
- Pedma's deep dive of Jeff's execution edge
- Never chase PSIX example: https://x.com/jfsrev/status/1967459726096212141
- Live market mainframe: https://x.com/jfsrev/status/1946214673482969302
- Quallamaggie RGTI +40-80R (Sep 9, 2025): https://x.com/jfsrev/status/1976571362488770934
- *"The best loser is the long-term winner" — Phantom of the Pits*

---

## CHAPTER 7 — POST-EXECUTION: TRADE MANAGEMENT

**Core Principle:** "Don't get fixated on price movements; be patient with the factor of time. Remember, a chart has both a y-axis AND an x-axis."

**Full write-up by Kyna Kosling:** "Risk and Position Management with Jeff Sun" (The Trading Resource Hub Substack)

### Key Management Principles
- **Why Certain Quallamaggie Rules Stand the Test of Time:** https://x.com/jfsrev/status/1866483247930306837
- **Sell Into Strength, or Death by Thousand Cuts:** Always sell partial into strength
  - But don't sell too aggressively: https://x.com/jfsrev/status/1866377222925553743
- **Never Lose Two Weeks' Gains in a Day:** https://x.com/jfsrev/status/1866377222925553743
- **When to Add to Position? (BMNR example):** https://x.com/jfsrev/status/1957632693413507158
- **The ONLY way to consistently finish positive YoY with 35% win rate:** https://x.com/jfsrev/status/1966511757910032579
- **Stop Adjustment Rules:** 
  - Day 0–3: Staggered stops (3-stop strategy)
  - Day 4+: Mental stop on 10-MA
  - Sell Rule: 10-MA sell rule can keep you in a trade for up to **5 months**
- **If you don't sell into strength, you'll sell into weakness:** https://x.com/jfsrev/status/1813592325777699255
- **Your performance growth depends on managing existing trades, not seeking new ones:** https://x.com/jfsrev/status/1754127474504700392

---

## CHAPTER 8 — JOURNALING: FINE-TUNING FOR YEAR-OVER-YEAR IMPROVEMENT

**Core Principle:** "Trading is a long-term growth game; too many approach it as a short-term income generator."

**Trading as a Big Data Game:** https://x.com/jfsrev/status/1952995698775081083

### Key Journaling Insights
1. **Profitable trading = math, not opinions or single great picks:** https://x.com/jfsrev/status/1456088827894718470
2. **Greatest improvements come from analyzing yourself:** https://x.com/jfsrev/status/1671541248044457986
3. **Begin with reducing randomness** in your process
4. **Consistency in habits** reduces randomness: https://x.com/jfsrev/status/1658968851009409025
5. **Advice if struggling / missing trades:** https://x.com/jfsrev/status/1842112913936679299
6. **Reduce average holding period for losses:** https://x.com/jfsrev/status/1805502341946523702
7. **6% monthly compounded = 100%+ annualized:** https://x.com/jfsrev/status/1795402114891690414
8. **27% win rate → 114% annualized gain:** https://x.com/jfsrev/status/1940818944228839430
9. **Period review is non-negotiable:** https://x.com/jfsrev/status/1670213508095692800


### Journal Monitoring Series (What to Track)
- Part 1: https://x.com/jfsrev/status/1780477056180187210
- Part 2: https://x.com/jfsrev/status/1794713774903173261
- Part 3: (series continued)
- Part 4: (series continued)
- Part 5 — P&L Histogram: https://x.com/jfsrev/status/1835977828216742003
- Part 6 — "You Might Have Improved Without Realizing It": https://x.com/jfsrev/status/1801928622854533378
- Part 7 — "You Should Know Your Quantifiable Edge Now": https://x.com/jfsrev/status/1823373889264820528

### Additional Journaling Insights
- **If Win Rate <50%, setups are secondary & will never be groundbreaking:** https://x.com/jfsrev/status/1629449806195331072
- **Handling a 3-month drawdown (2022):** https://x.com/jfsrev/status/1560650397043539968
- **Giovanni's insight:** "90% of my losses would have been avoided using 30-min ORB + LoD dist >60% ATR as strict entry criteria": https://x.com/jfsrev/status/1985253780116684880
- **Keep your trade journals no matter how badly you think you traded** — review them and take pride in growth

---

## CHAPTER 9 — 6 CORE GRAPHICS FOR TRADING CONVICTION

*"I want you to truly internalize these 6 graphics, and their relationship to each other. They are intertwined."*

**All discussions include high-quality replies better than any trading course.**

### Graphic 1: Tight Entry = Parabolic R Returns
- Executing at much tighter risk has a parabolic effect on R returns
- By Marios Stamatoudis
- Thread: https://x.com/jfsrev/status/1948260986143801469

### Graphic 2: Monte Carlo Simulation (500 Trades)
- Comparative simulation: normal entries vs. 50% tighter entries
- Thread: https://x.com/jfsrev/status/1948612229240410184

### Graphic 3: Drawdown Profile of Your System
- Know deeply what a drawdown on your system looks like
- Foreword by Michael Nauss CMT
- Thread: https://x.com/jfsrev/status/1866778428709671171

### Graphic 4: Fixed % Risk Relative to Equity (1,000 Trades)
- Benefits of maintaining fixed % risk (not fixed dollar amount) over long term
- Thread: https://x.com/jfsrev/status/1866778428709671171

### Graphic 5: Higher Return = Larger Absolute R Increase
- The higher the return, the larger the absolute increase in R
- By Martin Luk & Kyna Kosling
- Thread: https://x.com/jfsrev/status/1856232860107350147

### Graphic 6: Benefits of High ADR% Securities
- Thread: https://x.com/jfsrev/status/1856232860107350147
- **6.1 Capital Requirement Reference Guide by ADR%:** https://x.com/jfsrev/status/1939966683327996293
- **6.2 Limitation of 1% Risk to Equity:** https://x.com/jfsrev/status/1887356742016848024

### Further Reading
- "To Significantly Boost Annualized Performance, Pair Situational Awareness": https://x.com/jfsrev/status/1948327107509297471
- Treat Trading Like A Long-Term Business: https://x.com/jfsrev/status/1750532256446496997
- A Trading Strategy may offer +EV, but edge doesn't stem from strategy alone: https://x.com/jfsrev/status/1783396490985001118

> *"Many traders who are really close and want to give up really shouldn't. When it all comes together is where you have all those things, and you just need to calibrate it just a little bit to the market, and then it all comes together."* — Qullamaggie, 8/8/2017

---

## CHAPTER 10 — GOING FULL-TIME: HARD TRUTHS

**27-Post Thread: Key Considerations & Financial Preparations Before Going Full-Time:**
https://x.com/jfsrev/status/1591446881426898944

### Key Distinctions
- **"Trading For A Living" (TFAL)** vs. **"Full-Time Trader"** — these are NOT the same
- TFAL is the ultimate grail; extremely difficult even with a profitable 7-figure account for 8+ years
- Trading can become a full-time career — opportunities and data accessibility have lowered barriers to entry
- BUT: Requires grit, right tools, knowledge, mathematical edge built from your own trading stats
- **Hard Truth:** Trading part-time for income is a fallacy: https://x.com/jfsrev/status/1647324202519887873

### Financial Preparation Checklist
- Have at least 12–24 months of living expenses set aside (separate from trading capital)
- Do NOT conflate trading capital with personal income
- Have a backup income plan or existing capital buffer
- Ensure trading returns are consistent over a minimum 2–3 year period, not just bull markets
- Understand tax implications in your jurisdiction
- Diversify into other assets (real estate, etc.) as capital grows

---

## CHAPTER 11 — FIVE RECOMMENDED BOOKS

Thread: https://x.com/jfsrev/status/1803656136526274800

### The Three Core Structural Books
1. **"Japanese Candlestick Charting Techniques"** — Steve Nison
   - Also on CFTe and CMT exam recommended reading list
   - Foundation for price action understanding

2. **"Phantom of the Pits"** — Anonymous (free online)
   - *"The best loser is the long-term winner"* — core quote from this book
   - Jeff considers him worthy of "Market Wizard" honor
   - Key lesson: If the market doesn't prove you right, it doesn't mean it's proved you wrong yet

3. **Books mentioned in thread** (refer to tweet for full list)

### Additional Reading Context
- Quallamaggie's 2013–2024 tax returns: BONUS link in article
- *"You do not know what you don't know"* — reason to read books you haven't heard of

---

## CHAPTER 12 — FREE PRODUCTIVITY TOOLS & WEBSITES

### Twitter/X Tools
- **Best Free Productivity Hack for Twitter:** https://x.com/jfsrev/status/1759128977977778189
- **More Extensive Free Hack for Investors on Twitter:** https://x.com/jfsrev/status/1759129141721579715

### Web Tools Collections
- **Top 8 Free Investing & Trading Web Tools (2023):** https://x.com/jfsrev/status/1663432019756617730
- **Top 9 Additional Free Tools (2024):** https://x.com/jfsrev/status/1746110329946312796
- **25 Free Tools & Websites You May Not Have Heard Of (2024):** https://x.com/jfsrev/status/1839356207750078938
  - Includes tool to analyze Stanley Druckenmiller's quarterly 13F filings: https://x.com/jfsrev/status/1861327986563391785

### TradingView Collections
- **All TradingView threads: hacks, indicators, templates, screening (2024):** https://x.com/jfsrev/status/1792162225723158820
- **Best 8 Free TradingView Public Scripts (2024):** https://x.com/jfsrev/status/1858822375015661742

### Highlighted Tool
- **FinanceCharts.com** — completely free, highly recommended: https://x.com/jfsrev/status/1748982989479174269

---

## CHAPTER 13 — RECOMMENDED TRADERS TO FOLLOW (FINTWIT)

*"I delayed my own progress by 3 years learning the wrong things. Refine your Twitter feed."*

### Top Resources
- **My Top 5 Fintwit Highlights & Discoveries (2024):** https://x.com/jfsrev/status/1839356207750078938
- **Outstanding List of Chart-Focused Accounts by Expertise (2024):** https://x.com/jfsrev/status/1839356207750078938

### Featured Traders

#### BrianLeeTrades
- Jeff's #1 favorite follow
- "The most underrated aspect of trade management and risk/reward is the effect of small losers"
- BrianLeeTrades thread: https://x.com/jfsrev/status/1943188912048083170
- BrianLeeTrades AMA (100+ replies): https://x.com/jfsrev/status/1954372864024731792
- Jeff's summary of 2024 BrianLeeTrades interview: https://x.com/jfsrev/status/1832058045377224796
- "Are You Getting Greedy?" Twitter Space (Jan 2024): https://x.com/jfsrev/status/1748558391537213524

#### LoneStockTrader
- Favorite follow — shoutout for 3-Stop Strategy
- May have solved M1/M5 ORB strategy precision: https://x.com/jfsrev/status/1960890486971097407
- LoneStockTrader thread: https://x.com/jfsrev/status/1741456232081432995

#### Stanley Druckenmiller
- 2023 NBIM Investment Conference conversation with Nicolai Tangen — "pure gold"
- Jeff's 10 key insights extracted: https://x.com/jfsrev/status/1654807288002265093
- Key Druckenmiller quote used by Jeff: *"Exploring ideas in tradable asset classes beyond correlated equities can provide a valuable edge."*

#### Clement Ang
- Favorite for daily top-down commentary
- Easy to read, clear, time-efficient

#### Qullamaggie (Kristjan Kullamägi)
- Primary influence on Jeff's entire process
- Referenced throughout — "hallmark of grit and patience": https://x.com/jfsrev/status/1844654726044090592
- True focus: always Relative Strength

---

## CHAPTER 14 — MINDSET: HIGH-IMPRESSION POSTS & DEEPER THOUGHTS

### Personal Story & Background
- **15 Years of Trading Story (2024):** https://x.com/jfsrev/status/1803003192126677133
- **This Is A Game of Grit:** https://x.com/jfsrev/status/1705416603647422722
- **Being Average Won't Cut It:** https://x.com/jfsrev/status/1655855727041454081
- **I Missed A +$300K Trade After 5 Stop Losses:** https://x.com/jfsrev/status/1667001357637939200
- **Mental Struggle: Money vs Life:** https://x.com/jfsrev/status/1652577558612041728
- **You Don't Need A Privileged Family to Make It:** https://x.com/jfsrev/status/1946563823185621229
- **This Game Has No Room for Ego (Asia Genesis Fund closure):** https://x.com/jfsrev/status/1751174381408317703

### Philosophy & Core Beliefs
- **You Don't Need To Play Every Hand:** https://x.com/jfsrev/status/1654039384180785152
- **Good Trading Is Like Farming:** https://x.com/jfsrev/status/1930253395497263183
- **"Buy & Sell" Button Is Not Your Slot Machine:** https://x.com/jfsrev/status/1955527430099390537
- **Trading Is Not Just A Profession, It's A Passion:** https://x.com/jfsrev/status/1651152624086028289
- **One Trade At A Time:** https://x.com/jfsrev/status/1752628947102384307
- **Cut Out These 2 Types Of People:** https://x.com/jfsrev/status/1803429406599422270
- **Results Come From Routine, Habits, Behavior:** https://x.com/jfsrev/status/1765249321992421511
- **Missing Trades Won't Make You Broke, Chasing Will:** https://x.com/jfsrev/status/1889342784353833019
- **Japanese Principle (Ikigai-style):** https://x.com/jfsrev/status/1857980257065906669
- **When Fishermen Can't Go To Sea, They Repair Nets:** https://x.com/jfsrev/status/1894192503219523789
- **Simplicity Enhances Performance, Complexity Won't:** https://x.com/jfsrev/status/1828437263661039864
- **Think in Hundreds of Trades (Bigger Picture):** https://x.com/jfsrev/status/1658298850870964224
- **The Best Loser Is The Long-Term Winner:** https://x.com/jfsrev/status/1656670028576735233
- **Good Investors Don't Sell Advice, Good Traders Don't Sell Services:** https://x.com/jfsrev/status/1764247097069437106
- **Your Relationship With Uncertainty Determines Performance:** https://x.com/jfsrev/status/1867241088988053935
- **Bitten By A Snake — Focus on Healing, Not Chasing:** https://x.com/jfsrev/status/1883890896716059014
- **Hallmark of Qullamaggie's Grit and Patience:** https://x.com/jfsrev/status/1844654726044090592
- **If You Work Diligently & Intelligently, You'll Excel:** https://x.com/jfsrev/status/1712806229800853798

### Advice Posts
- **If You Have A Good Career With Prospects:** https://x.com/jfsrev/status/1962911428547096947
- **Vulnerable Groups Trading Isn't Suited For:** https://x.com/jfsrev/status/1949819495482085471
- **Everyone Wants To Win Until They See How Many Losses It Takes:** https://x.com/jfsrev/status/1982331679701365183
- **Right Mindset — My Adjustment Over 12 Years (2022):** https://x.com/jfsrev/status/1595826132112535554
- **Train Like A Pro Athlete:** https://x.com/jfsrev/status/1766752486483010011
- **The Rat Race Is Never My Thing:** https://x.com/jfsrev/status/1828437263661039864
- **You Can Be Mediocre In Any Profession — Except Trading:** https://x.com/jfsrev/status/1828437263661039864
- **The Past Is In Your Head, The Future Is In Your Hands:** https://x.com/jfsrev/status/1774292261070950774
- **Make Every Day Count:** https://x.com/jfsrev/status/1841338931046211934
- **Procrastination Will Delay Your Success:** https://x.com/jfsrev/status/1824263299468492994
- **It All Begins With One Good Day:** https://x.com/jfsrev/status/1814852387942900020
- **You Can't Afford To Be Sloppy Even For A Day:** https://x.com/jfsrev/status/1811317580633890899
- **You Can Control Actions, Not Outcomes:** https://x.com/jfsrev/status/1697072459453993118
- **The Urge To Give Up Is Strongest Right Before Breakthrough:** https://x.com/jfsrev/status/1833060753072603374
- **Hard Truth: Trading Part-Time For Income Is A Fallacy:** https://x.com/jfsrev/status/1647324202519887873
- **Longevity Requires A Solid Daily Routine:** https://x.com/jfsrev/status/1499677167193837568
- **Avoid Playing When You Don't See A Fat Pitch:** https://x.com/jfsrev/status/1826058519721947597
- **"Greatness Comes From Character":** https://x.com/jfsrev/status/1803457368237416937
- **Discipline Takes You Where Motivation Can't:** https://x.com/jfsrev/status/1801161982126752075
- **Always Seek Reasons To Avoid A Trade, Not To Take It:** https://x.com/jfsrev/status/1819580459665576429
- **No One Fails In Trading:** https://x.com/jfsrev/status/1756244788238860685
- **Trading Doesn't Involve Prophecies:** https://x.com/jfsrev/status/1735263390606696905
- **Simple Rule to Sidestep Unnecessary Stop Losses:** https://x.com/jfsrev/status/1953836344926405062
- **"The Markets Are Not Predictable":** https://x.com/jfsrev/status/1921440307142668665
- **The 3 Approaches to the Market:** https://x.com/jfsrev/status/1783400365351989416
- **You Need Composure To Succeed:** https://x.com/jfsrev/status/1986782954249691604
- **Trading = Grinding Mathematical Edge + Maintaining Grit:** https://x.com/jfsrev/status/1982702781103485051

---

## CHAPTER 15 — CLOSING REMARKS & CALL TO INSPIRATION

### Jeff's Personal Milestones
- 2023 tax bill: **>$100,000 USD** (no capital gains tax in Singapore)
- **11th property** purchased December 2023 — $1M profit cash out, no mortgage
- **12th property** purchased June 2024 — total real estate portfolio **>$8.5M USD**
- **12th & 13th** (sold 1) July 2025 — portfolio crosses **$10M USD** in real estate
- Previous wrong mindset 12 years ago: https://x.com/jfsrev/status/1749679698475626560

### The Commitment Required
*"If I could inspire you to commit three years to this pursuit... it can be life-changing, but success requires grit, right tools, knowledge, and a mathematical edge built from your own trading."*
- Inspiration post: https://x.com/jfsrev/status/1774991608645329084
- BONUS: Qullamaggie's 2013–2024 tax returns

---

## CHAPTER 16 — ADDITIONAL INFO & FAQ

### Key Annual Market Dates

#### Options Expiration
- Standard monthly options: **3rd Friday of every month**

#### Rebalancing Activities
- **Quarter-end fund/ETF rebalancing:** Last few days of each quarter (Mar, Jun, Sep, Dec)
- **Annual fund/ETF rebalancing:** Around December 31

#### Index Reconstitutions
| Index | Schedule |
|-------|----------|
| S&P 500 (SPX) | 3rd Friday of each quarter ("triple witching") |
| Russell 2000 (IWM) | 4th Friday of June annually |
| MSCI | Semiannually — May & November |
| FTSE | Quarterly — Mar, Jun, Sep, Dec |

---

### FAQ — Thought-Provoking Questions

**"How long did it take to become consistently profitable?"**
→ https://x.com/jfsrev/status/1803419841531093465

**"How would you summarize your trading philosophy?"**
→ https://x.com/jfsrev/status/1810563192701300797

**"How many positions at one time usually?"**
→ https://x.com/jfsrev/status/1969600295635218909

**"In an active session, what's your typical number of trades or R?"**
→ https://x.com/jfsrev/status/1981742077600829462

**"Why such strong emphasis on RVOL?"**
→ Price always fades outside of RVOL — it's the single most reliable confirmation of institutional interest
→ https://x.com/jfsrev/status/1946777562648383700

**"How does a RVOL-driven move look?"**
→ https://x.com/jfsrev/status/1808502472606134494

**"With RVOL, entries often aren't optimal anymore. How do you handle this?"**
→ https://x.com/jfsrev/status/1810643020599185525

**"Where do you source tickers for Focus Stock? Screeners don't highlight them."**
→ Screeners build generic watchlist; Focus List comes from WATCHLIST MANAGEMENT over time. Carry-over from previous days/weeks is normal.

**"For leveraged ETFs — LoD and RVOL on ETF itself, underlying, or both?"**
→ https://x.com/jfsrev/status/1979201615073550404
→ No RVOL requirement for mega-cap/liquid names — RVOL is for smaller/mid-cap

**"Do you trade off the inverse ETF's own chart or underlying for shorts?"**
→ https://x.com/jfsrev/status/1979158430599516580

**"For ETHD and IBIT (24/7 underlying) — how to measure HOD distance?"**
→ Use the trading-session HOD: https://x.com/jfsrev/status/1988990780741149069

**"Do you consider short interest when deciding long/short?"**
→ https://x.com/jfsrev/status/1979199578625970629

**"What sectors are excluded from your TradingView & Finviz filter?"**
→ Biotechs excluded from post-market scan (gap risk); full answer: https://x.com/jfsrev/status/1994253708121788580

**"For 1-month RS by industry group — rolling window or calendar month start?"**
→ https://x.com/jfsrev/status/1991467392558313676

**"How do you scan for institutional inflows?"**
→ Uses Finviz "Institutional Transaction" filter (2025 CANSLIM screener update)

**"Pre-market gap above prior day high — extra caution needed?"**
→ Yes — Rule 13: extremely cautious with layering risk when market gaps up: https://x.com/jfsrev/status/1968650833211347437

**"Do you consider sector ATR extension when putting on risk? (e.g. XLK >5)"**
→ Yes — uses ATR% from 50-MA on sector ETFs same way as individual stocks

**"What does a stalk list name need to qualify for Focus List?"**
→ https://x.com/jfsrev/status/1984100522857787715
→ VCP + RS Leadership + RVOL + LoD <60% ATR + Not extended (ATR% <4x)

**"3-stop strategy: if 2 stops hit, price reverses and breaks 30-min high — re-add?"**
→ Stick with remaining 1/3 only. Do not re-add the lost 2/3 on that break.
→ https://x.com/jfsrev/status/1981345453640995296

**"Do you wait 30 minutes after open to measure ORH?"**
→ https://x.com/jfsrev/status/1981342638541586648

---

## CHAPTER 17 — ATTRACTING INSTITUTIONAL ATTENTION (Paid Subscribers Only)

*Subtle strategies to attract institutional attention for career opportunities or capital allocation — generating management, performance, and ancillary fee streams.*

*(Content exclusive to paid Substack subscribers)*

---

## ADDITIONAL KEY RESOURCES (Referenced Throughout)

### People & Accounts Referenced
| Handle | Description |
|--------|-------------|
| @qullamaggie | Kristjan Kullamägi — primary influence, momentum trader |
| @DumbleDax / @Fred6724 | TradingView indicator coder (MarketSmith clone) |
| @finallynitin | Pocket Pivot Volume indicator |
| @JohnMuchow | EPS/Sales Dashboard |
| @amphtrading | Industry Group Strength indicator |
| @BrianLeeTrades | Favorite Fintwit trader — trade management focus |
| @LoneStockTrader | ORB precision, 3-stop strategy fan |
| @traderwillhu | IBKR 3-stop execution tool |
| @RomanBreakouts | 3-stop graphical display |
| @lowerhighpivots (Jose Garcia) | 3-stop + ATR% combo edge research |
| @erikcarell | Finviz API → TradingView watchlist hack |
| @RonakSh92987573 | Free Google Sheet RS Histogram version |
| Dr. Yong Yang | RS_STS% tweak to RS spreadsheet |
| Martin Luk / Kyna Kosling | R-multiple research |
| Michael Nauss CMT | Drawdown profile research |
| Marios Stamatoudis | Tight entry = parabolic R returns |
| Denis Hamel | 13-year ATR extension study (5,506 stocks) |
| BigWaveChartist | 3-stop strategy further research |
| Mark Minervini | VCP pattern originator |
| Stanley Druckenmiller | Macro/sector rotation influence |
| Adam H. Grimes | RVOL explanation (2015 & 2025) |

### Key Platforms Used
| Platform | Purpose |
|----------|---------|
| **TradingView** | Charting, screeners, watchlists, price alerts, breadth |
| **Finviz** | Post-market screening (14 screeners), Institutional Transaction filter |
| **IBKR (Interactive Brokers)** | Trade execution (3-stop tool available) |
| **Twitter/X** | Daily focus list sharing (subscribers), market commentary |
| **Substack** | Content hub, FAQ reference, archived threads |
| **FinanceCharts.com** | Free chart research tool |

### Leveraged ETF Pairs (Jeff Trades These Instead of Underlying)
| Underlying | Leveraged ETF |
|-----------|--------------|
| S&P 500 | SPXL (long) / SPXS (short) |
| Nasdaq | TQQQ (long) / SQQQ (short) |
| Gold/XAUUSD | GLD / XAUUSD (via GLD, UCO) |
| BTC/Crypto | IBIT, SOLT |
| Natural Gas | BOIL (long) / KOLD (short) |
| China | FXI |
| Oil/WTI | UCO |
| Biotech | LABU (long) / LABD (short) — *only via ETF, never individual biotechs* |
| Amazon short | AMZD |
| META short | METD |
| ETH | ETHD |

---

## CORE TRADING PHILOSOPHY SUMMARY

### The Complete Jeff Sun System at a Glance
```
MARKET CONTEXT (Top-Down)
    ↓
RSP vs SPY → Sector RS → Industry Group RS → Stock RS
    ↓
SCREENING (14 post-market + 2 live)
Finviz (post-market) + TradingView (pre/live)
    ↓
WATCHLIST MANAGEMENT (minimum 2 hrs/session)
Carry over + add new + remove stale
    ↓
FOCUS LIST CRITERIA
✓ RS leadership (Relative Strength FIRST)
✓ VCP (price/volume contraction)
✓ ADR% > threshold (momentum in place)
✓ Low Float + potential catalyst
✓ Not extended (ATR% from 50-MA < 4x)
    ↓
PRE-MARKET ROUTINE (30 min before open)
Alerts set → News scan → Futures check → Top movers
    ↓
LIVE EXECUTION RULES
✓ LoD < 60% ATR at entry
✓ RVOL confirmation (except mega caps)
✓ Wait 30 min post-open (unless extreme RVOL)
✓ Max 3 new positions/session
✓ No earnings, no econ data, no biotech
✓ A-RATED ONLY
    ↓
3-STOP STRATEGY
Entry = 3 tranches × 33%
Stops staggered → consolidate to breakeven → 10-MA mental stop
Target: -0.67R average loss (not -1R)
    ↓
TRADE MANAGEMENT
Sell partial into strength (T+2/T+3)
Add to winners (not losers)
Never lose 2 weeks' gains in 1 day
10-MA = hold signal
    ↓
JOURNALING (Non-Negotiable)
Track: Win rate, avg R, avg hold time losers/winners
Goal: Reduce randomness, increase mathematical edge
```

### The 6 Mathematical Convictions
1. Tighter entry → parabolic improvement in R-multiple
2. Know your system's drawdown profile in advance
3. Fixed % risk (not fixed $) compounds better over 1,000 trades
4. The higher the return, the larger the absolute R increase
5. High ADR% securities = less capital needed for same % return
6. Situational awareness amplifies all of the above

### Key Numbers & Thresholds
| Parameter | Value |
|-----------|-------|
| ATR% from 50-MA entry limit | < 4x |
| ATR% from 50-MA for index extension (top) | 6–7x |
| ATR% from 50-MA for extreme meme stocks | up to 10x+ |
| LoD distance limit at entry | < 60% ATR |
| Max new positions per session | 3 |
| Average R loss target (3-stop) | -0.67R |
| Wait time post-open | 30 min |
| RVOL baseline for confirmation | vs. 50-day avg |
| T+3 framework | Entry day (T) + 3 trading days |
| Win rate for consistent profitability | as low as 27–35% with right R-management |
| Monthly compounded return for 100%+ annual | ~6%/month |

---

## MINDMAP STRUCTURE SUGGESTION (for Claude Code)
```
ROOT: Jeff Sun Trading System
├── 1. GLOSSARY (LoD, RVOL, T+3, VARS, VCP, PEAD, ATR, ADR%, R-Multiple, ORH)
├── 2. CHARTING (TradingView)
│   ├── Indicators (Swing Data, ATR% 50-MA, VARS, Volume/Pocket Pivots)
│   ├── Templates (2023 / 2024 / 2025)
│   └── Key Concepts (ADR%, LoD<60%ATR, RVOL, Float%, Market Cap)
├── 3. SCREENERS
│   ├── 14 Post-Market (Finviz + TradingView)
│   ├── 2 Live-Market (RVOL-based)
│   └── Key Screener Types (CANSLIM, High ADR%, Strongest Mover, IPO, Short Float, ETF)
├── 4. FOCUS LIST PROCESS
│   ├── Daily Workflow (Screen→Watchlist→Focus List→Awareness→Stops)
│   ├── Criteria (RS, VCP, ADR%, LoD, ATR%, Volume)
│   └── Examples (COIN, KC, RGTI, WULF, FFIE)
├── 5. PRE-MARKET ROUTINE
│   ├── Price Alerts
│   ├── 4 Tools (CNBC, Pre-Market Movers, Futures, TradingView Breadth)
│   └── Situational Awareness (Breadth, Top-Down, ATR% Index)
├── 6. EXECUTION RULES
│   ├── 15 Hard Rules (LoD<60%, ATR%<4x, RVOL, 30min wait, Max 3 positions…)
│   └── 3-Stop Strategy (0.67R loss cap, 3×33% tranches, T+3, 10-MA stop)
├── 7. TRADE MANAGEMENT
│   ├── Sell Into Strength (partial)
│   ├── Stop Adjustment (10-MA)
│   └── Adding to Positions (post T+3)
├── 8. JOURNALING
│   ├── Track (Win rate, Avg R, Hold times)
│   ├── Period Review (monthly/quarterly)
│   └── Reduce Randomness
├── 9. CONVICTION GRAPHICS (6 graphics on R, drawdown, ADR%, risk %)
├── 10. FULL-TIME TRADING (financial prep, hard truths)
├── 11. BOOKS (Nison, Phantom of the Pits)
├── 12. FREE TOOLS (TradingView scripts, Finviz, FinanceCharts, Twitter tools)
├── 13. RECOMMENDED TRADERS (@BrianLeeTrades, @LoneStockTrader, @Qullamaggie, Druckenmiller)
├── 14. MINDSET (Grit, Routine, Math, Patience, Long-term thinking)
├── 15. CLOSING (Jeff's results: $10M real estate, $100K+ tax bill)
└── 16. FAQ (RVOL entries, Leveraged ETFs, 3-stop re-entry, ORH timing…)
```

---

*Last updated: March 2026 | Source: jfsrev.substack.com/p/my-trading-tools-process-routine*
*All X/Twitter links point to @jfsrev threads for detailed context*