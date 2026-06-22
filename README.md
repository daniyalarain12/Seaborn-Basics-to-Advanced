# 📈 Seaborn — Basics to Advanced

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-0.13.x-4C72B0?style=for-the-badge&logo=python&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.x-orange?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.x-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

> A complete Seaborn learning repository — covering relational, categorical, distribution and matrix plots — with built-in datasets and a dedicated notebook on combining Seaborn with Matplotlib.

---

## 📁 Repository Structure

```
Seaborn-Basics-to-Advanced/
│
├── 01_Seaborn_Intro_and_Relplot.ipynb
├── 02_Relational_Plots.ipynb
├── 03_Categorical_Plots.ipynb
├── 04_Distribution_Plots.ipynb
├── 05_Matrix_Plots.ipynb
└── 06_Seaborn_and_Matplotlib_Together.ipynb
```

---

## 📚 Topics Covered

| # | Notebook | Topics | Datasets Used |
|---|----------|--------|--------------|
| 01 | Seaborn Intro & Relplot | `set_theme()`, `load_dataset()`, `get_dataset_names()`, `relplot()` — scatter & line, hue, size, style | tips |
| 02 | Relational Plots | `scatterplot()`, `lineplot()`, errorbar, ax parameter | tips, flights |
| 03 | Categorical Plots | `barplot()`, `boxplot()`, hue grouping, distribution comparison | tips |
| 04 | Distribution Plots | `histplot()`, bins, single variable distribution | penguins |
| 05 | Matrix Plots | `heatmap()`, pivot table, cmap, annot, fmt | flights |
| 06 | Seaborn + Matplotlib Together | Subplots with `ax=`, `fig.suptitle()`, `tight_layout()`, combining both libraries | tips |

---

## 🔑 Key Concepts

### Seaborn vs Matplotlib
| Feature | Matplotlib | Seaborn |
|---------|-----------|---------|
| Level | Low-level, full control | High-level, statistical focus |
| Code | More verbose | Less code, cleaner syntax |
| DataFrames | Manual column extraction | Direct DataFrame + column name support |
| Themes | Manual styling | Beautiful built-in themes |
| Use case | Any plot type | Statistical visualizations |

### Figure-level vs Axes-level Functions
| Type | Examples | Use When |
|------|---------|----------|
| **Figure-level** | `relplot()` | Controlling entire figure, faceting |
| **Axes-level** | `scatterplot()`, `lineplot()`, `barplot()`, `boxplot()`, `histplot()`, `heatmap()` | Working with subplots, combining with Matplotlib |

### Built-in Datasets Used
| Dataset | Content |
|---------|---------|
| **tips** | Restaurant bill and tip data |
| **flights** | Monthly airline passenger counts 1949–1960 |
| **penguins** | Physical measurements of 3 penguin species |

---

## 🛠️ Tech Stack

| Library | Purpose |
|---------|---------|
| **Seaborn** | Statistical data visualization |
| **Matplotlib** | Figure layout, subplots, titles, saving |
| **Pandas** | Data loading and manipulation |

---

## ▶️ How to Run

1. Clone the repository
```bash
git clone https://github.com/daniyalarain12/Seaborn-Basics-to-Advanced.git
```

2. Install required libraries
```bash
pip install seaborn matplotlib pandas jupyter
```

3. Launch Jupyter Notebook
```bash
jupyter notebook
```

4. Open any notebook and run all cells

---

## 🗺️ My Data Science Learning Journey

This is part of my ongoing Data Science & AI Engineering roadmap:

| Repository | Status |
|-----------|--------|
| [Python — Basics to Advanced](https://github.com/daniyalarain12/Python-Basics-to-Advanced) | ✅ Completed |
| [NumPy — Basics to Advanced](https://github.com/daniyalarain12/NumPy-Basics-To-Advanced) | ✅ Completed |
| [Pandas — Basics to Advanced](https://github.com/daniyalarain12/Pandas-Basics-to-Advanced) | ✅ Completed |
| [Matplotlib — Basics to Advanced](https://github.com/daniyalarain12/Matplotlib-Basics-to-Advanced) | ✅ Completed |
| [Netflix EDA — Project](https://github.com/daniyalarain12/Netflix-EDA-Visualization) | ✅ Completed |
| **Seaborn — Basics to Advanced** | ✅ Completed |
| Combined Data Science Projects | 🔜 Coming Soon |
| Machine Learning | 🔜 Coming Soon |

---

## 📬 Connect With Me

[![GitHub](https://img.shields.io/badge/GitHub-daniyalarain12-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/daniyalarain12)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/daniyal-arain)

---

⭐ **If you find this repository helpful, please give it a star!** ⭐
