# Bitcoin Investment Calculator (Kost Edition) 
A beginner-friendly, web-based cryptocurrency investment simulator designed to help users calculate potential profits and losses without risking real money.

### try it now 
https://bitcoin-calculator-nine.vercel.app/

## 🌟 Overview
This tool is specifically tailored for the "Anak Kost" (student/budget-conscious) demographic, providing relatable financial perspectives by converting profits/losses into everyday equivalents like "Nasi Padang" meals or "Coffee" cups.

**Built 100% with AI**
This entire project—from the HTML structure and Tailwind styling to the complex JavaScript logic for Futures/Spot calculations—was generated using **Gemini Pro** via natural language prompting.

**Developer:** Gemini Pro (AI) & You (Prompter)
**Development Time:** A few hours
**Codebase:** Zero manual coding, 100% AI-generated.

##  Features
### What can this calculator do?

### 1. Real-Time Data 
- Fetches live Bitcoin prices automatically using the CoinGecko Public API
- Supports currency toggling between IDR (Rupiah) and USD
- No API Key required for local use

### 2. Dual Trading Modes 
- **Spot Mode (Safe):** Simulates buying the actual asset. Calculates fees and net holdings
- **Futures Mode (Risky):** Simulates contract trading with Leverage (1x - 125x) and Long/Short positions. Includes a liquidation calculator to show when your money hits zero

### 3. Exchange Fee Simulation 
- Includes built-in fee presets for popular Indonesian exchanges:
  - Tokocrypto, Indodax, Pintu, Ajaib Kripto, Reku
  - International exchanges (Binance/Bybit)
- Calculates trading fees (maker/taker) and deposit fees automatically

### 4. Interactive Simulation 
- **Budget Input:** Enter your starting capital (e.g., Rp 200,000)
- **Price Scenarios:** Use a slider or manual input to simulate "What if Bitcoin drops 50%?" or "What if it moons?"
- **Fun Facts:** Displays relatable "Kost Perspective" commentary based on your PnL (Profit and Loss)

### 5. Educational Hub 
- **School of Crypto:** An integrated accordion section explaining key concepts like Halving, Dollar Cost Averaging (DCA), Risk Management, and the difference between Spot and Futures in simple terms

## Tech Stack
- HTML5
- Tailwind CSS (via CDN)
- Vanilla JavaScript
- CoinGecko API

## Disclaimer
> This tool is for educational and entertainment purposes only.
> The calculations are estimates and may not reflect the exact execution prices or fees on real exchanges due to spread and market volatility.
> Cryptocurrency trading involves high risk. Always do your own research (DYOR).
