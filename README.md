
# Pandas Learning Journey

A structured repository containing interactive Jupyter Notebooks dedicated to mastering **Pandas** for data analysis, manipulation, cleaning, and visualization in Python.

## 📂 Repository Contents

Each notebook in this repository covers a fundamental pillar of data science with Pandas:

### 1. 📖 Reading Files (`reading files.ipynb`)
Learn how to ingest data into Pandas from various file formats and handle initial data inspection.
- Importing datasets (Excel workbooks, CSVs, etc.) using `pd.read_csv()` and `pd.read_excel()`.
- Handling multi-sheet Excel workbooks (`sheet_name`).
- Essential inspection methods like `.head()`, `.tail()`, and viewing high-level structural info.

### 2. 🔍 Filtering and Indexing (`filtering and indexing.ipynb`)
Master how to locate, slice, and filter data with precision.
- Navigating and resetting DataFrame indices using `.set_index()` and `.reset_index()`.
- Slicing data based on positions (`.iloc[]`) and labels (`.loc[]`).
- Filtering rows using conditional logical operations (Boolean masking).
- Sorting indexes and handling display options (e.g., `pd.set_option`).

### 3. 🧼 Data Cleaning (`Data Cleaning.ipynb`)
Hands-on techniques to clean real-world, messy datasets.
- Dropping irrelevant or duplicate records.
- Handling missing data (`NaN` values) using fill or drop strategies.
- Standardizing and cleaning string values (e.g., stripping whitespace, formatting addresses, and splitting columns).
- Resetting indices post-cleanup to maintain clean, referenceable DataFrames.

### 4. 🔗 Merge and Join (`merge and join.ipynb`)
Combine multiple datasets together using relational algebra principles.
- Merging DataFrames using inner, outer, left, and right joins via `pd.merge()`.
- Joining DataFrames on shared index values.
- Concatenating datasets vertically or horizontally using `pd.concat()`.

### 5. 📊 Group By & Aggregation (`group_by and aggregration.ipynb`)
Aggregate, summarize, and extract insights from grouped records.
- Splitting datasets into groups using `.groupby()`.
- Applying aggregation functions (`.mean()`, `.sum()`, `.count()`, `.std()`).
- Generating descriptive statistical summaries using `.describe()` on grouped data.

### 6. 📉 Visualization (`visualization.ipynb`)
Bring data to life using integrated plotting libraries.
- Quick plotting directly from Pandas DataFrames.
- Creating standard charts: line, bar, scatter, and histograms.
- Utilizing and customizing Matplotlib style sheets (e.g., `ggplot`, `seaborn`, `classic`).
- Adjusting visual parameters (labels, legends, and axis limits).

---

## 🛠️ Requirements & Setup

To run these notebooks locally, you'll need Python installed along with the following packages:

```bash
pip install pandas openpyxl matplotlib
