# missing-data

# Missingness Unmasked

**A hands-on, simulation-driven walkthrough of missing data** — From MCAR, MAR, and MNAR mechanisms to practical detection and imputation using NumPy, masked arrays, and scikit-learn, including KNNImputer, Iterative, and MICE methods.

> Notebook: **`Missing-Data.ipynb`**

---

## Why this exists
Real-world datasets often contain inconsistencies. This notebook demonstrates *why* data may become missing, *how* to identify the mechanism behind it, and *what* steps to take in order to avoid biasing your analysis.

---

## What you'll learn
- **Mechanisms**: Missing Completely at Random (MCAR), Missing at Random (MAR), and Missing Not at Random (MNAR).
- **Detection**: Identifying `np.nan`, counting values per row and column, computing proportions, and utilising **NumPy masked arrays** (`np.ma`) for statistical measures like mean and covariance.
- **Imputation**:
    - **KNNImputer** For a more organised method of completing fill-in tasks..
- **IterativeImputer (MICE)** For performing multiple imputation using chained equations (`sample_posterior = True`).
- **Model impact**: The impact of missing data on statistical parameters: Using **GaussianMixture** to illustrate the effects of structure-dependent (Missing At Random - MAR) missingness.
- **Reproducibility**: Creating several imputed datasets by conducting seeding simulations.

---

## Structure

├─ Missing-Data.ipynb # Primary laboratory notebook.

├─ README.md

└─ (optional) requirements.txt # You can choose the pin versions.
