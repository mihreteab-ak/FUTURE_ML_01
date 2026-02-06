# FUTURE_ML_01

A simple time-series forecasting pipeline implemented in a Colab notebook (`FUTURE_ML_01_V2.ipynb`).  
It loads the *Sample - Superstore.csv* dataset from Google Drive, aggregates monthly sales, creates lag and calendar features, trains a Random Forest model, and produces a 12-month rolling forecast.

---

## Files

- `FUTURE_ML_01.ipynb` — main Colab notebook (source of this README)  
- `README.md` — this file  
- `data/Sample - Superstore.csv` — expected dataset (the notebook uses `/content/drive/MyDrive/Sample - Superstore.csv`)

---

## Requirements

- Python 3.8+ (works in Colab)  
- Libraries: `numpy`, `pandas`, `matplotlib`, `scikit-learn`

Install locally with:

```bash
pip install numpy pandas matplotlib scikit-learn
