# 🐼 Pandas_Practice_Resume
This repository represents my continuous journey of my Data Scientist. This repo includes my practice on various Pandas concepts and operations with different types of Datasets files like .csv, .xlsx and .JSON etc.

=>  Core Tools :

1. Python
2. Pandas
3. Jupyter
4. Status

> A structured, hands-on journey through **Pandas** — from the fundamentals of data exploration to advanced data wrangling operations like merging, grouping, and aggregation. This repository is part of my continuous learning path toward becoming a **Data Scientist / ML Engineer**.

---

## 📌 About This Repository

This repo documents my practical practice with **Pandas** across multiple real-world-style datasets (`.csv`, `.xlsx`, `.json`). Every notebook here reflects a specific concept I've studied and implemented hands-on — not just theory, but working code, outputs, and edge cases I ran into along the way (and fixed).

The repository is organized into progressive parts, each building on the last.

---

## 🗂️ Repository Structure

```
Pandas_Practice_Resume/
│
├── Pandas_Part_1/                     # Fundamentals of Pandas
│   ├── Data_sources&Data_sets/        # Raw datasets used for practice
│   ├── Intro.ipynb                    # Introduction to Pandas & Series/DataFrame basics
│   ├── Understanding_data.ipynb       # Exploring structure, dtypes, shape of data
│   ├── Describe.ipynb                 # Statistical summaries (.describe(), .info())
│   ├── Rows.ipynb                     # Row selection, indexing, slicing (loc/iloc)
│   ├── Topic.ipynb                    # Core Pandas concept practice
│   └── Practice_Example.ipynb         # Applied practice problems
│
├── Pandas_Part_2/                     # Intermediate / Data Wrangling
│   ├── DataSets&DataFiles/            # Datasets used across Part 2 notebooks
│   ├── Add_Upd_Rem.ipynb              # Adding, updating, removing columns/rows
│   ├── Handling_Missing_Data.ipynb    # NaN handling — fillna, dropna, interpolation
│   ├── GroupBy.ipynb                  # Grouping, aggregation, split-apply-combine
│   ├── Sorting&Aggregation.ipynb      # sort_values, sort_index, agg functions
│   └── Merging&Sorting.ipynb          # merge(), join(), concat() — all join types
│
└── README.md
```

---

## 🧠 Topics Covered

### 📘 Part 1 — Foundations

- Pandas `Series` vs `DataFrame` fundamentals
- Reading data from multiple sources (`.csv`, `.xlsx`, `.json`)
- Exploring datasets — `.head()`, `.tail()`, `.shape`, `.info()`, `.describe()`
- Row & column selection — `.loc[]`, `.iloc[]`, boolean indexing
- Data types and structure inspection

### 📗 Part 2 — Data Wrangling & Aggregation

- Adding, updating, and removing rows/columns dynamically
- Handling missing data — `isna()`, `fillna()`, `dropna()`, imputation strategies
- `groupby()` operations — split-apply-combine workflow
- Aggregation functions — `sum()`, `mean()`, `count()`, custom `agg()`
- Sorting — `sort_values()`, `sort_index()`, multi-column sorting
- **Merging & Joining datasets**:
  - `Inner Join` — matching records only
  - `Left Join` — all records from left + matched from right
  - `Right Join` — all records from right + matched from left
  - `Outer Join` — union of both datasets
  - `Cross Join` — Cartesian product of two datasets

---

## 🛠️ Tech Stack

| Tool               | Purpose                          |
| -------------------------------------------------------
| ![Python]          | Core programming language        |
| ![Pandas]          | Data manipulation & analysis     |
| ![Jupyter]         | Interactive notebook environment |
| ![VSCode]          | Development environment          |

---

## 🚀 How to Use This Repo

1. Clone the repository
   ```bash
   git clone https://github.com/Ahmtech611/Pandas_Practice_Resume.git
   ```
2. Navigate into the project folder
   ```bash
   cd Pandas_Practice_Resume
   ```
3. Install dependencies
   ```bash
   pip install pandas numpy openpyxl jupyter
   ```
4. Launch Jupyter and explore any notebook
   ```bash
   jupyter notebook
   ```

---

## 🎯 Why This Repo Exists

I'm building this repository as part of my transition into **Data Science → Machine Learning Engineering**, following a structured self-learning path. Every notebook here is practiced independently — the goal isn't just to run code, but to genuinely understand *why* each operation works the way it does (including debugging real errors like `MergeError`, `KeyError`, and `ValueError` along the way).

---

## 📈 What's Next

- [ ] Advanced GroupBy — multi-level grouping & pivot tables
- [ ] Data visualization integration (Matplotlib & Seaborn with Pandas)
- [ ] Feature engineering practice notebooks
- [ ] Real-world end-to-end EDA projects

---

## 👤 Author

**Ahmad Tech**

- GitHub: [@AhmdTech](https://github.com/Ahmtech611)
- Focus: Data Science → ML Engineering → AI Product Management

---

⭐ If you find this helpful for your own Pandas learning journey, feel free to star the repo!
