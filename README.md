# Lab 2 — DSAR (Codespaces-Ready)

This folder is preconfigured for **GitHub Codespaces** with Python, Jupyter, GitHub Copilot, and **Data Wrangler**.
It also installs the Lab 2 Python dependencies on first launch.

## Quick Start (Students)
1. Open this repo on GitHub → **Code** → **Create codespace on main**.
2. Wait for the container to finish building (first run only).
3. Upload or open **Lab2.ipynb** and **L2L3dataset.csv** at the repo root (this folder).
4. Start working in the notebook. Saved figures can go in `./figures/`.
5. **Commit** and **push** when done.

## Installed in the Dev Container
- Python 3.11 base image
- VS Code extensions: Python, Jupyter, GitHub Copilot (+ Chat), **Data Wrangler**
- Packages via `requirements.txt`: numpy, pandas, matplotlib, seaborn, scipy, ipykernel, jupyterlab
- `nbstripout` is set up so notebook outputs are stripped from commits (clean diffs).

## Notes
- If you need classic Notebook instead of JupyterLab: `pip install notebook`.
- Figures: save with `plt.savefig('figures/hist_var.png', dpi=150, bbox_inches='tight')`.
