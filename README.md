# Lab 2 — DSAR (Codespaces-Ready)

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/jl2578/Lab2?quickstart=1)

This folder is preconfigured for **GitHub Codespaces** with Python, Jupyter, **GitHub Copilot**, and **Data Wrangler**.  
On first launch, dependencies install automatically via `requirements.txt`.

## Quick Start
1. Click the **“Open in GitHub Codespaces”** button above (or on the repo page: *Code → Create codespace on main*).
2. After the container builds, open **Lab2.ipynb** and make sure **L2L3dataset.csv** is in the repo root.
3. Run the notebook; save any figures to `./figures/` (e.g., `plt.savefig('figures/hist_var.png', dpi=150, bbox_inches='tight')`).
4. Use **Data Wrangler** (command palette → “Launch Data Wrangler”) if helpful for inspection/cleaning.

## Saving Your Work (IMPORTANT)
- Jupyter **auto-saves** to the workspace, but those changes **aren’t in Git history** until you **Commit** (local) and **Push** (to GitHub).  
- A Codespace can become **inactive** and be **deleted after 30 days** of no use. If you haven’t pushed, you may lose work.
- Best practice:
  - Use **Source Control** → *Commit* your changes with a message.
  - Click **Sync/Push** to upload to GitHub so your work is safely stored in the repo.
  - (Optional) Export key figures or PDFs for your reflection as an extra backup.

## Dev Container Contents
- **Python 3.11** base image
- VS Code extensions: Python, Jupyter, **Data Wrangler**, GitHub Copilot (+ Chat)
- Python packages: `numpy`, `pandas`, `matplotlib`, `seaborn`, `scipy`, `ipykernel`, `jupyterlab`
- `nbstripout` configured via `.gitattributes` to keep notebook diffs clean

## Figures
Save plots to `./figures/` (kept in Git via `.gitkeep`). Example:
```python
plt.savefig('figures/box_var.png', dpi=150, bbox_inches='tight')
