# 🏏 IPL Data Analysis & Visualization

A Python project performing exploratory data analysis (EDA) and visualization on Indian Premier League (IPL) match data using **Pandas**, **Seaborn**, and **Matplotlib**.

---

## 📁 Repository Structure

```
ipl_data_analysis/
├── Rahul_Biswas_ipl_224.py   # Main analysis script
├── ipl.csv                   # Dataset
└── README.md
```

---

## 📊 Dataset

**`ipl.csv`** — Match-level IPL data including teams, toss results, win margins (by runs and wickets), umpires, and match outcomes.

---

## 🔧 Requirements

- Python 3.x
- pandas
- seaborn
- matplotlib

Install dependencies:

```bash
pip install pandas seaborn matplotlib
```

---

## 🚀 Usage

```bash
python Rahul_Biswas_ipl_224.py
```

---

## 📝 Features

### 1. Data Analysis

| Step | Description |
|------|-------------|
| Full Data Print | Displays entire DataFrame |
| Shape | Rows and columns count using `df.shape` |
| Columns | Lists column names and their values |
| Describe | Summary statistics via `df.describe()` |
| Head / Tail | First and last 10 rows |
| Min / Max | Min and max of `win_by_runs` column |
| Filtering | Matches where `win_by_runs > 30` |
| Slicing | Rows 2 to 5 using index slicing |

### 2. Data Cleaning

- **Null Value Detection** — `df.isnull()` to identify missing entries across all columns
- **Column-Level Null Check** — Specifically checks `win_by_runs` and `umpire3` columns for missing values

### 3. Data Visualization

**Matplotlib:**

| Plot | Description |
|------|-------------|
| Line Plot | `win_by_runs` vs `win_by_wickets` |
| Scatter Plot | `win_by_runs` vs `win_by_wickets` |
| Box Plot | Distribution of `win_by_runs` |

**Seaborn:**

| Plot | Description |
|------|-------------|
| Bar Plot | Result vs Toss Winner, colored by `win_by_runs` |
| Joint Plot | Relationship between result and toss winner |
| Pair Plot | Pairwise relationships, colored by match result |
| Box Plot | Result vs Toss Winner distribution |
| Scatter Plot | Result vs Toss Winner, hued by `win_by_runs` |
| Histogram | Frequency distribution of match results |

---

## 👤 Author

**Rahul Biswas**
GitHub: [@RahulBiswas224](https://github.com/RahulBiswas224)

---

## 📄 License

This project is open source and available for educational purposes.
