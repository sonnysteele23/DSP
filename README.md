# DSP — Operator

> The single pane of glass for every dollar, hour, and mile your DSP burns.

A software platform built for Amazon DSP (Delivery Service Partner) owners — connecting operational truth (Cortex, Mentor, Netradyne, fuel cards) to financial truth (settlements, payroll, accounting) in one live cockpit.

## 🚀 Live demo

**[sonnysteele23.github.io/DSP](https://sonnysteele23.github.io/DSP/)**

Click through all six modules with realistic dummy data calibrated to a 25-route, $3.2M DSP.

## 📊 The pitch deck

[`deck/Operator_DSP_Pitch.pptx`](deck/Operator_DSP_Pitch.pptx) — 21 slides covering:

- The visibility problem ($80K → $200K take-home, same 25 routes)
- Five places profit walks out the door every week
- What we're building (six modules, one cockpit)
- Data connections (DSP Console, Mentor, Netradyne, Cortex, payroll, fuel cards, accounting, insurance)
- The math: $197K average annual recovery on a $3.2M DSP
- 12-month build timeline (3 phases, usable from week 12)
- Market sizing: 4,400+ DSPs, $13B+ combined revenue
- Competitive pricing landscape
- Recommended pricing: Lite $399 / Pro $899 / Multi $1,499 per month
- Four monetization models (SaaS, per-route, recovery share, marketplace)
- Go-to-market roadmap
- 5-year potential: ~$5.4M ARR at 11% TAM penetration

## 🧩 What's in the prototype

The prototype is a single, self-contained HTML file with seven working views:

| Module | What it shows |
| --- | --- |
| **Dashboard** | Hero KPIs, live revenue ticker, alerts, cost mix, scorecard outlook, fleet/driver watch |
| **Financial Truth** | Settlement breakdown by component, monthly P&L bars, per-route margin |
| **Labor Engine** | Driver punches vs. route plan, OT alerts, auto-generated rescue recommendations |
| **Driver Hub** | Churn-risk-sorted roster, exit-interview patterns, cost-of-churn ledger |
| **Fleet Health** | Per-van CPM / MPG / fuel, VAN-23 fuel anomaly deep-dive, PM calendar |
| **Disputes** | Open chargebacks with countdown timers, recovery trend, win rate by code |
| **Scorecard Optimizer** | All 8 metrics with bottlenecks, "what gets you to Fantastic", 13-week tier history |

## 🛠️ Run locally

No build step. No dependencies. Just open the file:

```bash
git clone https://github.com/sonnysteele23/DSP.git
cd DSP
open index.html      # macOS
xdg-open index.html  # Linux
start index.html     # Windows
```

Or serve it with any static server:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## 📁 Repo structure

```
DSP/
├── index.html          # The prototype (single self-contained file)
├── deck/
│   └── Operator_DSP_Pitch.pptx
├── README.md
├── LICENSE
└── .gitignore
```

## 🎯 Status

Pre-MVP. Pitch + prototype stage. Looking for one design-partner DSP to validate before building Phase 1.

## 📜 License

MIT — see [LICENSE](LICENSE).

---

*Built for an Amazon DSP owner in Phoenix, AZ. Designed to scale to all 4,400+ DSPs in the network.*
