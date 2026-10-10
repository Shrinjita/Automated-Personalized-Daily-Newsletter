# 🎀 The Daily Planner & Executive Journal

> **A chic, aesthetic daily planner & executive intelligence journal crafted for AI & automation engineers. Powered by a live Google Sheet refreshed at midnight IST, it curates unbiased briefings across Indian politics, global geopolitics, equities, deep tech, and frontier AI research into a responsive 3-column layout with executive breakdowns and source links.**

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new)
![License: MIT](https://img.shields.io/badge/License-MIT-pink.svg)
![Layout: 3--in--a--row](https://img.shields.io/badge/Layout-3--in--a--Row-d9778f.svg)
![Live Sync](https://img.shields.io/badge/Database-Google%20Sheets%20Live%20Sync-blue.svg)

---

## 🌸 Overview & Philosophy

**The Daily Planner & Executive Journal** marries two worlds:
1. **The Visual Aesthetic:** A whimsical, pastel daily planner and mood board inspired by chic digital scrapbooks, delicate ribbon bows (🎀), sakura corners (🌸), soft rose quartz and lavender palettes, and interactive habit widgets.
2. **The Linguistic Register:** Rigorous, boardroom-grade corporate English. Technical architectures, legal precedents, and financial mechanics are explained with complete clarity and executive precision—simplifying concepts without diluting professional vocabulary.

---

## ✨ Key Features

* **3-in-a-Row Responsive Grid:** Clean, multi-column broadsheet architecture displaying exactly 3 cards per row on desktop screens, eliminating dead margins while maintaining comfortable vertical rhythm.
* **Interactive Daily Planner Dashboard:**
  * **Mood Tracker:** Interactive emoji selector (`😄`, `😊`, `😐`, `🙁`, `😫`) that updates on click.
  * **Day & Date Selector:** Visual weekly pill bar (`[M] [T] [W] [T] [F] [S] [S]`) highlighting the current day.
  * **Weather & Hydration Tracker:** Live weather status alongside 8 clickable water/matcha drops (`💧`) to track daily intake.
  * **Strategic Intent Banner:** A sunset cloud gradient card framing your daily operating mantra with a direct link to your live spreadsheet.
* **Dynamic Volume Support:** No arbitrary quotas. If a heavy news cycle produces 50 critical events, all 50 are structured and rendered. If a section experiences zero verified updates, it remains clean without filler.
* **Live Category Ribbons:** Filter pills feature real-time counters (e.g., `🎀 All (12)`, `🏛️ Indian Politics (3)`, `🔬 Deep Tech (1)`).
* **Multi-Source Neutral Verification:** Factual cross-referencing across government gazettes, court registries, PRS Legislative Research, and scientific repositories to guarantee balanced, unbiased intelligence.

---

## 📖 The 3 Mandatory Sections per Card

Every article card adheres strictly to a 3-part executive structure:

```text
┌─────────────────────────────────────────────────────────────┐
│ 🎀 [Category Badge]                             [Read Time] │
│ Headline in Editorial Serif Typography                      │
│                                                             │
│ ⚡ IN SHORT                                                  │
│ 1–2 sentence high-level executive takeaway.                 │
│                                                             │
│ 📖 IN DETAIL BREAKDOWN                                      │
│ [▼ Expand Drawer]                                           │
│ In-depth operational mechanics, legal/structural context,    │
│ and actionable career or market implications.               │
│                                                             │
│ 🔗 TECHNICAL SOURCES:                                       │
│ [↗ Verified Link 1]  [↗ Verified Link 2]                    │
└─────────────────────────────────────────────────────────────┘
```

---

## 🏛️ The 10 Tracked Intelligence Domains

1. **Indian Politics & Governance:** Supreme Court & CJI bench orders (institutional safety directives, POSH compliance), Parliamentary legislative committee reviews (BNS, criminal justice timelines), and DPDP Act operationalization.
2. **Global Geopolitics:** Critical minerals security under the US-India iCET pact, OSAT semiconductor manufacturing corridors, and multi-region supply chain de-risking.
3. **Corporate Wealth & Taxes:** New vs. Old Tax Regime mathematical arbitrage for tech salaries (>₹15 LPA), Section 80C/80D/NPS optimizations, Equity Tax Slabs (LTCG at 12.5%, STCG at 20%), and annual tax-harvesting strategies.
4. **Financial Jargon Demystified:** Analogy-driven breakdowns of enterprise valuation metrics—distinguishing P/E multiples from the PEG ratio (<1.0) and analyzing Free Cash Flow (FCF) yields.
5. **Career Strategy & Macro Impact:** Analysis of why routine syntax generation is commoditizing, and how to command top-percentile compensation via agentic workflow orchestration (LangGraph, Power Platform, RunDeck) and automated evaluation telemetry.
6. **Biochem & Frontier AI Research:** Generative diffusion architectures applied to de novo protein design, SE(3)-equivariant continuous coordinate denoising, and inverse structural folding.
7. **Deep Tech Infrastructure:** Co-packaged silicon photonics, optical interconnects, and laser waveguides resolving the AI datacenter interconnect bottleneck.
8. **Enterprise Systems:** Self-healing AIOps pipelines bridging enterprise ITSM platforms (BMC Remedy, ServiceNow) with parameterized RunDeck automation playbooks.
9. **Microsoft Ecosystem:** Autonomous event-driven triggers in Copilot Studio, supervisory multi-agent architectures, and automated evaluation benchmarking in Azure AI Foundry.
10. **Experimental Wonder ("Surprise Me"):** Serendipitous interdisciplinary breakthroughs (e.g., radical pair quantum entanglement in avian cryptochrome proteins inspiring GPS-jam-resilient quantum sensors).

---

## 📊 Live Google Sheet Architecture

Your central database is managed via a dedicated 2-tab Google Sheet:

* **Direct Sheet Link:** [The Daily Dispatch — Live Database (Google Sheet)](https://docs.google.com/spreadsheets/d/1X8pT8HQ6knoCl-_baF6qEtl51d2y2YlYoYZ1EVl2fcw/edit)

### Tab 1: `Daily Intelligence Feed`
Houses the active day's articles. The web app reads this tab live to render the 3-column broadsheet:
* `ID`: Unique record identifier (e.g., `pol-1`, `geo-1`).
* `Category`: Primary domain taxonomy.
* `Category Badge`: Icon-embellished pill label (e.g., `🏛️ Supreme Court & CJI`).
* `Headline`: Editorial headline.
* `In Short`: Mandatory executive summary.
* `In Detail Breakdown`: Mandatory comprehensive technical/strategic breakdown.
* `Links JSON`: Array of verified source titles and URLs.
* `Read Time`: Estimated reading duration.

### Tab 2: `Editorial Preferences`
Serves as the persistent control center tracking all 15 core directives:
* Corporate English register standards.
* Dynamic volume directives.
* Multi-source neutral verification protocols.
* Hard-news Indian politics scope.
* Domain priorities and weekly feedback logs.

---

## ⏰ Automation & Schedules

* **Midnight Database Overwrite (12:00 AM IST):** A scheduled pipeline (`0 0 * * *`) retrieves multi-source updates, formats them into the 3 mandatory sections, and executes a clean overwrite of Tab 1 in the live Google Sheet.
* **Weekly Feedback Sync (Sunday 8:00 PM IST):** An automated check-in (`0 20 * * 0`) prompts for weekly feedback to recalibrate topic depths, tone, and category weights for the upcoming week. Preferences are also synchronized in your [Google Keep Editorial Note](https://keep.google.com/?note=1UMGKn_NxjFN7U27XcpnTLPuUxw6VnnPfkQ04RNnIyQumnz0BytFTABtmqjjaNw).

---

## 🚀 Deployment Guide

### Deploying to Vercel (Recommended)
1. Push `index.html` and `README.md` to your GitHub repository.
2. Navigate to [Vercel](https://vercel.com/), select **Add New > Project**, and import your repository.
3. Keep the default static deployment settings and click **Deploy**.

### Connecting Your Live Google Sheet
1. Open [The Daily Dispatch — Live Database](https://docs.google.com/spreadsheets/d/1X8pT8HQ6knoCl-_baF6qEtl51d2y2YlYoYZ1EVl2fcw/edit).
2. Click **File > Share > Publish to web**.
3. Under the dropdown, select the **Daily Intelligence Feed** tab and set the format to **Comma-separated values (.csv)**.
4. Click **Publish** and copy the generated link.
5. In your live website, click **🎀 Connect Google Sheet**, paste the CSV URL, and click **Save & Sync Feed**. The browser saves the link in `localStorage` and automatically updates on every visit!
