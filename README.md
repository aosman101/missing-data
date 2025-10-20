# missing-data

# Missingness Unmasked

**A hands-on, simulation-driven walkthrough of missing data** — fFrom MCAR, MAR, and MNAR mechanisms to practical detection and imputation using NumPy, masked arrays, and scikit-learn (KNNImputer, Iterative, and MICE).

> Notebook: **`Missing-Data.ipynb`**

---

## Why this exists
Real-world datasets often contain inconsistencies. This notebook demonstrates *why* data may become missing, *how* to identify the mechanism behind it, and *what* steps to take in order to avoid biasing your analysis.

---

## What you'll learn
- **Mechanisms**: Missing Completely at Random (MCAR), Missing at Random (MAR), and Missing Not at Random (MNAR).
- **Detection**: Identifying `np.nan`, counting values per row and column, computing proportions, and utilizing **NumPy masked arrays** (`np.ma`) for statistical measures like mean and covariance.
- **Imputation**:
    - **KNNImputer** For a more structured approach to fill-in tasks.
- **IterativeImputer (MICE)** For performing multiple imputation using chained equations (`sample_posterior = True`).
- **Model impact**: The impact of missing data on statistical parameters: Using **GaussianMixture** to illustrate the effects of structure-dependent (Missing At Random - MAR) missingness.
- **Reproducibility**: Generating multiple imputed datasets through seeding simulations.

---

## Structure

├─ Missing-Data.ipynb # Primary laboratory notebook.

├─ README.md.

└─ (optional) requirements.txt # You can choose the pin versions.
