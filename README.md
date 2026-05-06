# SAAM Portfolio — Sustainable & Carbon-Constrained Portfolio Analysis

Jupyter notebook implementing a full portfolio construction and carbon metrics analysis on the PAC investment universe (Scope 1 emissions, WACI, Carbon Footprint).

## Project structure

```
📁 project/
├── saam_portfolio.ipynb          ← main notebook
├── Sustainability.xlsx           ← data file (required)
├── risk_free_tb3ms_2014_2024.csv ← risk-free rate data (required)
└── requirements.txt              ← Python dependencies
```

> The three data files must be in the **same folder** as the notebook.

---

## Quickstart (step by step)

### 1. Install Python

Download and install **Python 3.10** from the official website:
👉 https://www.python.org/downloads/release/python-31011/

During installation on Windows, check **"Add Python to PATH"**.

---

### 2. Download the project

Click the green **Code** button on GitHub → **Download ZIP**, then unzip the folder somewhere on your computer.

---

### 3. Open a terminal in the project folder

**Mac:**
- Open `Terminal`
- Type `cd ` (with a space), then drag and drop the project folder into the terminal → press Enter

**Windows:**
- Open the project folder in Explorer
- Click the address bar, type `cmd`, press Enter

---

### 4. Install the dependencies

```bash
pip3 install -r requirements.txt
```

*(On Windows use `pip` instead of `pip3`)*

---

### 5. Launch Jupyter

```bash
python3 -m jupyter notebook
```

*(On Windows: `python -m jupyter notebook`)*

Your browser will open automatically. Click on `saam_portfolio.ipynb` to open the notebook.

---

### 6. Run the notebook

In the Jupyter menu: **Kernel → Restart & Run All**

---

## Dependencies

| Package | Version |
|---|---|
| Python | 3.10.x |
| numpy | 1.26.4 |
| scipy | 1.13.1 |
| pandas | 2.2.3 |
| matplotlib | 3.8.4 |
| cvxpy | 1.4.3 |
| scikit-learn | 1.4.2 |
| openpyxl | 3.1.2 |
| jupyter | 1.0.0 |
| notebook | 7.2.2 |
