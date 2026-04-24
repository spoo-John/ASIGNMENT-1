# Football Analysis Exercise (AI - Exercise 1)

Dataset: International Football Results (1872–2024)

This folder contains a notebook solution that answers Q1–Q11 and produces the required plots.

## Setup

1. Create a Python environment (venv/conda).
2. Install deps:
   ```bash
   pip install -r requirements.txt
   ```
3. Download the Kaggle dataset CSV and save it as:
   - `data/results.csv`

> Note: The notebook will try `../data/results.csv` first (recommended when running from `notebooks/`), then fall back to `data/results.csv` and `results.csv`.

## Run

Open the notebook:
- `notebooks/Football_Analysis.ipynb`

Run all cells to compute the answers and generate the required plots.

## Results (snapshot)

Computed from `data/results.csv` (your provided file) by running the notebook cells.

### Basic Exploration

1. Matches in dataset: **49,287**
2. Earliest year: **1872**; Latest year: **2026** (latest date: 2026-06-27)
3. Unique teams/countries (home ∪ away): **333**
4. Most frequent home team: **Brazil** (614 matches as home)

### Goals Analysis

5. Average goals per match: **2.938**
6. Highest scoring match: **Australia 31–0 American Samoa** (2001-04-11), total goals **31**
7. More goals scored at home or away?
   - Home goals total: **86,426** (avg 1.756)
   - Away goals total: **58,192** (avg 1.182)
   - Conclusion: **More goals are scored by home teams**
8. Most common total goals value: **2** (10,927 matches)

### Match Results

9. % home wins: **48.91%**
10. Home advantage: **Yes** (Home Win 48.91% vs Away Win 28.23%; Draw 22.86%)
11. Most wins historically: **Brazil** (670 wins)
