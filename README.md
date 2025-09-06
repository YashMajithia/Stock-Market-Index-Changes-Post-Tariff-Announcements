# Stock-Market-Index-Changes-Post-Tariff-Announcements
Tracking changes across world market indexes post announcement of tariffs by the United States of America Government.

## 📌 Project Overview
This project analyzes the impact of Trump-era tariff announcements on major global stock indexes. Using Yahoo Finance data, the study compares how markets across the US, Europe, and Asia reacted to different tariff events.

The analysis focuses on market performance within a 30-day window before and after each announcement, highlighting volatility and investor sentiment during tariff shocks.

---

## 📊 Datasets & Sources
- **Yahoo Finance API** (via `yfinance`)

Stock Indexes tracked:
- 🇺🇸 S&P 500 (`^GSPC`)
- 🇬🇧 FTSE 100 (`^FTSE`)
- 🇯🇵 Nikkei 225 (`^N225`)
- 🇩🇪 DAX (`^GDAXI`)
- 🇨🇳 Shanghai Composite (`000001.SS`)

---

## ⚙️ Methodology
1. Define tariff announcement dates and descriptions:
   - Feb 1, 2025 → Tariffs on Mexican, Canadian, and Chinese goods
   - Feb 10, 2025 → Tariffs on steel and aluminium
   - Apr 2, 2025 → Global tariffs with a 10% baseline
2. Pull stock index data using yfinance.
3. Compute percentage change in closing prices within the 30-day window.
4. Compare results across different countries.

---

## 📈 Results
| Date       | Event Description                           | S\&P 500 | FTSE 100 | Nikkei 225 | DAX   | Shanghai Composite |
| ---------- | ------------------------------------------- | -------- | -------- | ---------- | ----- | ------------------ |
| 2025-02-01 | Tariffs on Mexican, Canadian, Chinese goods | -0.67%   | 2.63%    | -3.54%     | 5.24% | 2.83%              |
| 2025-02-10 | Tariffs on steel and aluminium              | -8.15%   | -3.10%   | -5.18%     | 1.90% | 1.74%              |
| 2025-04-02 | Global tariffs with 10% baseline            | -1.18%   | -1.30%   | 2.03%      | 0.47% | -2.12%             |

---

## 📚 Tools & Libraries
- Python 3.x
- Pandas
- yfinance
- Jupyter Notebook

---

## 🔑 Key Insights
- US markets (S&P 500) showed the sharpest decline on Feb 10, 2025 (-8.15%), highlighting investor sensitivity to steel and aluminium tariffs.
- European markets (FTSE, DAX) were mixed — DAX gained +5.24% during the first announcement but fell slightly during the global tariff phase.
- Asian markets (Nikkei, Shanghai Composite) displayed resilience, with smaller percentage swings compared to the US, though still showing volatility.
- Overall, tariffs triggered short-term volatility, but market reactions varied regionally depending on trade dependencies.

---

## 🚀 Future Improvements
- Extend analysis to commodities (steel, aluminium).
- Include trade volume data for deeper insights.

---

## 📜 License
This project is open-source. Feel free to contribute!

---

⭐ If you found this useful, don’t forget to star this repo! ⭐
