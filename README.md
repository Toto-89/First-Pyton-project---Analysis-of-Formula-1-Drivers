# Formula 1 Drivers Analysis — 2008 Season

Analysis of drivers’ and constructors’ performance in the **2008 Formula One World Championship**, using only the Python Standard Library.

---

## Objectives
- Calculate **individual performance** (points, wins, podiums)
- Generate **Drivers’ Standings** and save to `Drivers_Standings_2008.txt`
- Compute **Constructors’ Standings**
- Show **top 10 summaries** in console

---

## Dataset
- **File:** `formula1_data.csv`  
- **Fallback URL:** auto-download if missing  
- **Columns:**  
  - Driver | Team | Race | Country | Position  
- **Scoring system (2008):** 10–8–6–5–4–3–2–1 for positions 1–8

---

## Main Features
- `driver_performance(name)` → `[points, wins, podiums]`
- `create_drivers_standings()` → dict of drivers and points
- `save_drivers_standings_txt()` → exports standings to TXT
- `constructors_standings()` → dict of teams and points
- Preview tables printed in console

---

## Example Output

**Driver Performance**
Lewis Hamilton → [98 points, 5 wins, 10 podiums]


**Top 3 Drivers**


Hamilton – 98

Massa – 97

Kubica – 75


**Top 3 Constructors**


Ferrari – 172

McLaren – 151

BMW – 135


---

## Quickstart
1. Clone the repo and run the notebook/script.  
2. If `formula1_data.csv` is missing, it will be downloaded automatically.  
3. Run the cells in order: CSV setup → Utilities → Analysis → Standings → Demo.  

---

## License
MIT License © 2025 *Salvatore Spagnolo*
