# 🐼 Pandas Revision — Complete Guide with Superstone Dataset

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Latest-green?style=for-the-badge&logo=pandas)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)
![Dataset](https://img.shields.io/badge/Dataset-superstone.csv-orange?style=for-the-badge)

---

## 📌 About This Project

This repository contains a **comprehensive Pandas revision notebook** covering all major concepts of data manipulation and analysis using the **Superstone dataset** (`superstone.csv`).

Yeh project un sabhi important Pandas functions aur techniques ko cover karta hai jo real-world data analysis mein use hoti hain — data loading se lekar advanced transformations tak.

---

## 📂 Repository Structure

```
pandas-revision/
│
├── pandas_revision.ipynb      # Main Jupyter Notebook
├── superstone.csv             # Dataset used for analysis
└── README.md                  # Project documentation
```

---

## 📊 Dataset Used

| Detail | Info |
|--------|------|
| **File Name** | `superstone.csv` |
| **Type** | CSV (Comma Separated Values) |
| **Domain** | Retail / Sales Data |

---

## 🧠 Topics Covered

### 1️⃣ Data Loading & Inspection
- `pd.read_csv()` se data load karna
- `.head()`, `.tail()`, `.info()`, `.describe()`
- `.shape`, `.columns`, `.dtypes`

### 2️⃣ Filtering & Selection
- Boolean filtering with conditions
- `.loc[]` and `.iloc[]`
- Multi-condition filtering (`&`, `|`)
- Column selection and slicing

### 3️⃣ Missing Values & Data Cleaning
- `.isnull()`, `.notnull()`, `.isnull().sum()`
- `.fillna()` — mean, median, custom values
- `.dropna()` — rows/columns
- Duplicate detection and removal with `.duplicated()` & `.drop_duplicates()`

### 4️⃣ GroupBy Operations
- `.groupby()` with aggregation functions
- `.agg()` — multiple functions at once
- GroupBy with multiple columns
- `.size()`, `.count()`, `.sum()`, `.mean()`

### 5️⃣ Merge & Join
- `pd.merge()` — inner, left, right, outer joins
- Merging on single and multiple keys
- Handling duplicate column names after merge

### 6️⃣ Pivot Table
- `pd.pivot_table()` — summarizing data
- `aggfunc` — sum, mean, count
- Multi-index pivot tables

### 7️⃣ DateTime Analysis
- `pd.to_datetime()` — date parsing
- Extracting `.dt.year`, `.dt.month`, `.dt.day`, `.dt.dayofweek`
- Time-based filtering and resampling

### 8️⃣ apply() & Lambda Functions
- `.apply()` with custom functions
- Lambda functions for inline transformations
- `apply()` on rows (`axis=1`) and columns

---

## ⚙️ How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/codebyavneesh/pandas-revision.git
   cd pandas-revision
   ```

2. **Install dependencies:**
   ```bash
   pip install pandas numpy jupyter
   ```

3. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook pandas_revision.ipynb
   ```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Python 3.x** | Programming Language |
| **Pandas** | Data Manipulation & Analysis |
| **NumPy** | Numerical Operations |
| **Jupyter Notebook** | Interactive Development |

---

## 👨‍💻 Author

<table>
  <tr>
    <td align="center">
      <b>codebyavneesh</b><br/>
      <a href="https://linkedin.com/in/codebyavneesh">
        <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat-square&logo=linkedin" alt="LinkedIn"/>
      </a>
      &nbsp;
      <a href="https://github.com/codebyavneesh/pandas-revision">
        <img src="https://img.shields.io/badge/GitHub-Repo-black?style=flat-square&logo=github" alt="GitHub Repo"/>
      </a>
    </td>
  </tr>
</table>

---

## 🌟 If you found this helpful...

Agar yeh notebook aapko helpful lagi toh **⭐ Star** zaroor karo — isse aur logon tak pahunchne mein madad milti hai!

---

> _"Data is the new oil — and Pandas is your refinery."_ 🐼
