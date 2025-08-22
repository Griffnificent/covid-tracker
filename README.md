# COVID-19 Global Data Tracker

A beginner-friendly data analysis project that downloads the latest global COVID-19 dataset, explores trends, and visualizes key metrics (cases, deaths, tests, vaccinations) using Python in a Jupyter Notebook.

## 🎯 Objectives

* Load and clean COVID-19 data from a trusted public source (Our World in Data).
* Explore global and country-level trends.
* Build clear visualizations (time series, bar charts, and a world map).
* Add light interactivity (country & metric selectors).
* Run the notebook end-to-end without errors and share on GitHub.

## 🧰 Tools & Libraries

* Python 3.9+
* Jupyter Notebook
* pandas, numpy
* matplotlib, plotly
* ipywidgets (for interactivity)
* requests (robust data download)

## 📦 Project Structure

```
covid19-global-data-tracker/
├─ notebooks/
│  └─ covid19_global_tracker.ipynb
├─ src/
│  └─ __init__.py
├─ outputs/               # charts/exports saved here by the notebook
├─ requirements.txt
├─ .gitignore
├─ LICENSE
└─ README.md
```

## ▶️ How to Run (Windows / macOS / Linux)

1. **Create & activate a virtual environment (recommended)**

   ```bash
   # Windows (PowerShell)
   python -m venv .venv
   .venv\Scripts\Activate.ps1

   # macOS/Linux
   python3 -m venv .venv
   source .venv/bin/activate
   ```

2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Launch Jupyter and open the notebook**

   ```bash
   jupyter notebook
   ```

   Open: `notebooks/covid19_global_tracker.ipynb` and run all cells (Kernel → Restart & Run All).

## 🌍 Data Source

* Our World in Data (OWID) COVID-19 dataset. The notebook pulls from:

  * `https://covid.ourworldindata.org/data/owid-covid-data.csv` (primary)
  * `https://raw.githubusercontent.com/owid/covid-19-data/master/public/data/owid-covid-data.csv` (fallback)

## 📝 Notes & Tips

* If an internet connection is blocked, download the CSV manually and place it in `notebooks/data/owid-covid-data.csv`, then set `USE_LOCAL_FILE = True` in the notebook.
* All figures are saved in `outputs/` when you run the export cells.

## 🔍 Insights & Reflections (example prompts)

* Which countries have the highest total cases and deaths? What about per million people?
* How do vaccination rates relate to case/death trends over time?
* Are there data gaps or anomalies you noticed?
* What did you learn building this? What was challenging? What would you add next?

## ✅ Submission Checklist

* [ ] Notebook runs from start to finish without errors.
* [ ] Plots render correctly.
* [ ] README updated with your reflections.
* [ ] Pushed to a **public GitHub repo** and link shared.

---

*This project is for educational use. Data is provided “as is”; always verify conclusions with multiple sources.*
