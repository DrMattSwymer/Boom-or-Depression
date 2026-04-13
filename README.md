# Retirement Simulation Game: Boom or Depression

An interactive, classroom-ready economics simulation that allows students to experience how long-term investing is affected by market risk, global events, and economic uncertainty across four decades.

Designed for **financial literacy, economics, and social studies instruction**, this game emphasizes **risk vs. reward**, **diversification**, and the unpredictability of global markets.

---

## 📌 Overview

**Boom or Depression** is a browser-based simulation game where players invest a fixed monthly amount across different investment types and then experience randomized economic outcomes every decade from **2030 to 2060**.

Each decade:
- A global economic scenario is revealed
- The market enters a **Boom** or **Depression** (hidden until reveal)
- Mutual fund returns fluctuate accordingly
- Bonds may fail during severe depressions
- Safe options preserve value but yield minimal growth

The game intentionally mirrors real-world uncertainty—there is **no optimal strategy**.

---

## 🎮 Gameplay Flow

1. **Introduction**
   - Sets the theme and stakes of long-term investing

2. **Instructions**
   - Players receive **$600/month**
   - They choose how to allocate funds across investment types (externally, on paper or spreadsheet)

3. **Scenario Phase**
   - A future global event is presented
   - Teachers pause gameplay here to lock in allocations

4. **Market Reveal**
   - The economy enters a **Boom** or **Depression**
   - Mutual fund return rates are revealed
   - Bonds may collapse in extreme downturns

5. **Progression**
   - Advances through decades: **2030, 2040, 2050, 2060**
   - Final totals are calculated externally

---

## 💰 Investment Options

| Investment Type | Description | Risk Level |
|-----------------|------------|-----------|
| Under the Mattress | 0% return, complete safety | None |
| Savings Account | ~0.05% return, near-total safety | Very Low |
| Bonds | 3% return, may fail in severe depressions | Moderate |
| Mutual Funds | Highly variable (±1% to ±15%) | High |

---

## ⚠️ Key Mechanics

- **Weighted Scenarios**  
  Every scenario has a built-in probability for a Boom or Depression.

- **Locked Outcomes**  
  Once a scenario loads, its outcome is pre-generated and stored to prevent “back button cheating.”

- **Magnitude System**  
  Events are categorized as:
  - Low (1–4%)
  - Medium (3–8%)
  - High (7–15%)

- **Bond Failure Risk**
  - During **high-magnitude depressions**, bonds have a **40% chance** of total loss.

---

## 🧑‍🏫 Teacher Features

- Built-in **teacher pause warning** before market reveal
- Designed for **whole-class pacing**
- No student devices required beyond viewing the screen
- Final calculations intentionally left manual to:
  - Encourage spreadsheet skills
  - Promote discussion and error-checking
  - Prevent “solve-for-me” behavior

---

## 🧠 Learning Objectives

Students will:
- Understand long-term investment risk
- Experience volatility and compounding over time
- Compare conservative vs aggressive strategies
- Recognize that outcomes depend on timing and uncertainty
- Learn why diversification matters

---

## 🛠️ Technical Details

- **Single HTML file**
- Vanilla **HTML / CSS / JavaScript**
- No external libraries
- No backend or data storage
- Fully offline-compatible
- Works in all modern browsers

---

## 🚀 How to Run

1. Download or clone the repository
2. Open `index.html` in any modern web browser
3. Click **Start Game**
4. Play through each decade as a class

No installation required.

---

## 🔄 Resetting the Game

Use the **“Play Again”** button at the end to reshuffle scenarios and outcomes for a fresh run.

---

## 📄 License

This project is intended for **educational use**.  
Feel free to modify, remix, or extend it for classroom purposes.

---

## ✨ Possible Extensions

- Add student portfolio tracking inside the app
- Export decade results to CSV
- Introduce inflation adjustments
- Add additional decades or alternate timelines
- Create difficulty modes with different volatility levels

---

**Who survives the market?**
