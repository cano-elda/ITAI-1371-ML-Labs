# ITAI-1371-ML-Labs

Course lab repo for machine learning tools and practice.

## What’s in this repo

| File | Purpose |
|------|---------|
| `Module_02_Lab_Exercise.ipynb` | Module 2 lab notebook |
| `requirements.txt` | pandas, numpy, matplotlib, scikit-learn, jupyter |

## Module 2: Tools Used in Machine Learning

**Goal:** Set up your tools, load a dataset, make a plot, document your work, and keep it on GitHub.

### You will be able to

- Use Jupyter, Google Colab, and VS Code / Cursor
- Import pandas, NumPy, Matplotlib, and scikit-learn
- Write Markdown documentation
- Keep work in a GitHub repository

### Tools (what each one is for)

- **Jupyter / Colab** — run code and notes in one place
- **pandas** — tables of data
- **NumPy** — numbers and arrays
- **Matplotlib** — charts
- **scikit-learn** — ML algorithms and datasets
- **GitHub** — save and share projects
- **VS Code / Cursor** — edit and run notebooks

### Lab path

How the notebook flows:

1. **Part 1** — Environment setup and import libraries
2. **Part 2** — Load Iris; look at shape, features, and species
3. **Part 3** — Scatter plot: sepal length vs sepal width
4. **Part 4** — Means and counts by species
5. **Part 5** — GitHub and documentation habits
6. **Assessment**
   - **Task 1** — NumPy mean and standard deviation of sepal length
   - **Task 2** — Bar chart of species counts
   - **Reflection** — fill in observations in Markdown

## How to run this lab

**Option A — Cursor / VS Code**

1. Open `Module_02_Lab_Exercise.ipynb`
2. Select kernel **Python 3.12 (ITAI-1371)** (or the Python 3.12 interpreter)
3. Run all cells from the top (leave the `pip install` cell commented out)

**Option B — Local Jupyter**

```bash
pip install -r requirements.txt
jupyter notebook
```

Then open `Module_02_Lab_Exercise.ipynb`.

**Option C — Google Colab**

Upload the notebook. Libraries are already installed.

## Dataset (Iris)

- 150 flowers
- 4 measurements: sepal length, sepal width, petal length, petal width
- 3 species: setosa, versicolor, virginica

## Next

Module 3: types of machine learning, a first classifier, and the fuller ML workflow.
