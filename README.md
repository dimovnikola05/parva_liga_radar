# parva_liga_radar
Per-90 player comparison radar chart analyzing Winger / Attacking Midfielder profiles in the Bulgarian First League (efbet Liga) using Python and mplsoccer.(Not official stats)
# 🇧🇬 efbet Liga (Bulgarian First League): Player Comparison Radar Template

A professional football analytics visualization template designed for scouting and performance analysis in the Bulgarian First Professional Football League (efbet Liga). Built using Python, `mplsoccer`, and `pandas`, this project visualizes attacking profiles normalized **Per 90 Minutes**.

---

## 📈 Visual Output

![Parva Liga Radar](parva_liga_winger_radar.png)

---

## ⚠️ Data Source & Methodology Notice

> **Note on Data:** The figures presented in this demonstration project are **sample / mock metrics Per 90** created for illustrative purposes to demonstrate the visualization pipeline for the Bulgarian First League. The Python script is fully modular and built to ingest real match event / tracking data exported from sources like FBref, Sofascore, Wyscout, or Hudl.

---

## ⚙️ Metrics Breakdown

The script benchmarks metrics against typical Bulgarian First League positional standards for Wingers / Attacking Midfielders:

* **Non-Penalty Goals Per 90:** Open-play scoring efficiency.
* **xG Per 90:** Expected Goals generated from shot quality.
* **xA Per 90:** Expected Assists accumulating chance creation quality.
* **Key Passes Per 90:** Shot-assisted passes leading directly to team scoring opportunities.
* **Successful Dribbles Per 90:** Completed 1v1 take-ons in 1-on-1 situations.
* **Progressive Carries Per 90:** Ball carries moving the team significantly closer to the opponent's goal.

---

## 💡 Practical Application for Clubs
This visualization pipeline allows performance analysts and recruitment teams in Bulgaria to:
1. Quickly load real CSV data exports from providers (Wyscout/Instat/FBref) to generate clean comparative scouting reports.
2. Compare domestic talent against prospective foreign recruits before signing decisions.
3. Present intuitive visual feedback to technical staff and sporting directors.

---

## 🛠️ Tech Stack
* **Language:** Python 3.13
* **Visualization:** `mplsoccer` (Radar Module) & `matplotlib`
* **Data Handling:** `pandas`, `numpy`
