# Matplotlib from Scratch

A hands-on Matplotlib practice repo with small notebooks for core plotting, subplots, histograms, pandas-backed charts, and a couple of dataset walkthroughs.

## What is inside

| File | Focus |
| --- | --- |
| `main.ipynb` | Basic line, marker, grid, label, and bar chart practice |
| `Subplot.ipynb` | Subplot layout examples |
| `scatter_graph  histogram.ipynb` | Scatter plots and histograms |
| `food-pyramid.ipynb` | Food pyramid style plotting practice |
| `Matplotlib_with_pandas.ipynb` | Pokemon CSV exploration with pandas and Matplotlib |
| `ALL_plots.ipynb` | Mixed plot practice using the social media addiction dataset |
| `practise-on-iris-flower-dataset.ipynb` | Iris dataset analysis and visualization practice |

## Setup

Use Python 3.12 or newer. The notebooks were refreshed with the current Matplotlib 3.10 line in mind, so keeping packages recent is the easiest path.

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
jupyter lab
```

## Notes

- The local CSV notebooks use repo-relative paths, so they should run from the project root without editing machine-specific paths.
- Keep datasets in the root folder unless you update the matching notebook path.
- The notebooks are intentionally simple and practice-focused; the goal is to make each plot idea easy to revisit.
