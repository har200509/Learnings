# 📊 Pandas Tutorial Notebook

This Jupyter Notebook provides a comprehensive hands-on introduction to core **pandas** functionalities. It demonstrates how to create and manipulate `DataFrames`, perform indexing, load and save data, and use powerful functions like `groupby`, `apply`, `map`, and sorting.

## 📘 Contents

### 1. **Creating and Displaying DataFrames**
- Creating a DataFrame from a dictionary.
- Setting custom row indices.
- Displaying shape and head of the DataFrame.

### 2. **Series Object**
- Creating and displaying a `pandas.Series` object.

### 3. **Reading and Writing CSV Files**
- Reading a CSV file (`NYC_Jobs.csv`) with a specific index column.
- Writing a DataFrame to a CSV file (`people.csv`) and reading it back.

### 4. **Indexing and Selection**
- Index-based selection using `.iloc`.
- Label-based selection using `.loc`.
- Conditional filtering using `.loc` with boolean conditions.

### 5. **Descriptive Statistics and Unique Values**
- Using `.describe()` to generate statistical summaries.
- Getting unique values with `.unique()`.
- Counting frequency with `.value_counts()`.

### 6. **Applying Functions**
- Using `.apply()` to transform column values (e.g., lowercase transformation of strings).
- Using `.map()` for fast element-wise transformation via dictionary mapping.

### 7. **Grouping and Aggregation**
- Grouping data using `.groupby()`.
- Aggregating with `.agg()` to calculate min, max, count, and mean.
- Grouping by multiple columns and using `.describe()`.

### 8. **Sorting**
- Sorting values by multiple columns using `.sort_values()`.
- Selecting top `n` entries with `.nlargest()`.

## ✅ Requirements
- Python 3.x
- pandas
- Jupyter Notebook

Install dependencies:
pip install pandas notebook

## 📂 Files
* `NYC_Jobs.csv`: Sample dataset used for analysis.
* `people.csv`: Demonstration CSV created and read during the session.
* This notebook (`pandas_tutorial.ipynb`): Contains all examples and explanations.

## 📌 Notes
* All operations are performed in-memory; original data remains unchanged unless explicitly saved.
* Sorting and CSV export operations use `inplace=True` and `index=False` for control.
* GroupBy and aggregation methods are useful for summarizing large datasets.

## 📤 Future Enhancements
* Handling missing data.
* Data type conversions.
* Merging and joining datasets.
* Visualizations using matplotlib/seaborn.

## 🧑‍💻 Author

This notebook was created as part of a practical introduction to pandas for data manipulation and exploration.
