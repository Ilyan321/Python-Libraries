# Python Libraries - Pandas Learning Guide

A hands-on learning repository for mastering the **Pandas** library in Python, structured as a progressive day-by-day course with notebooks, scripts, and real-world datasets.

## Topics Covered

- **DataFrames & Series** — Creating, inspecting, and understanding core Pandas data structures
- **Data Exploration** — `.head()`, `.tail()`, `.info()`, `.describe()`, `.shape`, `.dtypes`, `.nunique()`
- **Reading CSV Files** — Loading external data with `pd.read_csv()` and its parameters
- **Indexing & Selection** — Label-based (`.loc[]`) and position-based (`.iloc[]`) data access
- **Sampling** — Randomly selecting rows with `.sample()`

## Repository Structure

```
├── Day_1_Intro_to_Pandas.py        # Day 1 — Introduction to Pandas
├── Day_2_Pandas.ipynb               # Day 2 — DataFrame creation & inspection
├── Day_3_Reading_CSV_Pandas.ipynb   # Day 3 — Reading CSVs, .loc & .iloc indexing
├── Pandas.ipynb                     # General Pandas fundamentals notebook
├── Pandas_Notes.txt                 # Quick reference notes
├── dataset.csv                      # Simple practice dataset (ID, Value_A, Value_B)
├── data/
│   ├── bios.csv                     # Olympic athlete biographical data
│   ├── results.csv                  # Olympic competition results
│   └── noc_regions.csv              # Country/region code lookup
└── warm-up data/
    └── coffee.csv                   # Beginner-friendly coffee sales data
```

## Getting Started

### Prerequisites

- Python 3.x
- Pandas (`pip install pandas`)
- Jupyter Notebook (`pip install notebook`)

### Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/Ilyan321/Python-Libraries.git
   ```
2. Install dependencies:
   ```bash
   pip install pandas notebook
   ```
3. Launch Jupyter and work through the notebooks in order:
   ```bash
   jupyter notebook
   ```

## Datasets

| File | Description |
|------|-------------|
| `dataset.csv` | Simple 6-row numeric dataset for basic practice |
| `warm-up data/coffee.csv` | Weekly coffee sales by type (Espresso, Latte) |
| `data/bios.csv` | Olympic athlete bios (name, DOB, country, height, weight) |
| `data/results.csv` | Olympic competition results (year, discipline, event, medal) |
| `data/noc_regions.csv` | NOC country code to region name mapping |

## Learning Path

| Day | Topic | File |
|-----|-------|------|
| 1 | Introduction to Pandas | `Day_1_Intro_to_Pandas.py` |
| 2 | DataFrame creation & data exploration | `Day_2_Pandas.ipynb` |
| 3 | Reading CSVs, `.loc` & `.iloc` indexing | `Day_3_Reading_CSV_Pandas.ipynb` |