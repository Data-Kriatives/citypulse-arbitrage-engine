# CityPulse – Local Arbitrage Engine

A real-time scraping + analytics engine that identifies **underpriced, high-demand products** on local marketplaces (starting with Kijiji Toronto). Built to solve a real-world problem: **how to flip items for profit using data**.

---

## Why This Project?

**Make money**: Finds arbitrage opportunities across phones, cars, bikes — things people buy and sell often.  
**Learn end-to-end**: From web scraping to visualization to ML-based price alerts.  
**Get hired**: Tells recruiters you can build production-grade projects, not just toy notebooks.

---

## Tools & Stack

| Layer | Stack |
|-------|-------|
| Scraping | `requests`, `BeautifulSoup`, (later: `Selenium`, `Playwright`) |
| Data | `pandas`, CSV, SQLite |
| Scheduling | `cron`, `apscheduler`, `Airflow` (later) |
| Visuals | `matplotlib`, `seaborn`, `Power BI`, `Streamlit` |
| ML (later) | `scikit-learn`, `LightGBM`, `prophet` |
| Deployment | Streamlit + Hugging Face Spaces |

---

## Project Phases

| Phase | Description |
|-------|-------------|
| ✅ Phase 0 | **Project Setup** (You are here) |
| ⏳ Phase 1A | Select marketplace category (e.g., used iPhones) & inspect structure |
| 🔜 Phase 1B | Build MVP scraper for selected category |
| 🔜 Phase 1C | Clean, store, and analyze the data |
| 🔜 Phase 2 | Add scheduling & historical price tracker |
| 🔜 Phase 3 | Visualize trends with Streamlit dashboard |
| 🔜 Phase 4 | ML-powered alerts for best resale flips |
| 🔜 Phase 5 | Add 2nd and 3rd marketplaces (e.g., Craigslist, Facebook) |

---

## Dataset Example (Goal)

| Title | Price | Location | Date Posted | Link |
|-------|-------|----------|-------------|------|
| iPhone 12 Pro | $720 | North York | 2025-06-02 | kijiji.ca/... |
| ... | ... | ... | ... | ... |

---

## Final Deliverables (v1.0)
- Real-time product price dashboard
- Trend analysis (by suburb, day of week, model, etc.)
- Predictive pricing engine (Phase 4+)
- Live alerts for underpriced listings

---

> Built by [Srivatsav Shrikanth](https://github.com/your-username), a Machine Learning Engineer in progress
> Built by [Kathy Anusha Felix](https://github.com/your-username), a Data Analyst in progress
