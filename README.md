# missing-data

# Missingness Unmasked

**A hands-on, simulation-driven walkthrough of missing data** — from MCAR/MAR/MNAR mechanisms to practical detection and imputation using NumPy, masked arrays, and scikit-learn (KNNImputer & Iterative/MICE).

> Notebook: **`Missing-Data.ipynb`**

---

## Why this exists
Real-world datasets are messy. This notebook shows *why* values go missing, *how* to diagnose the mechanism, and *what* to do about it without biasing your analysis.

---

## What you'll learn
- **Mechanisms**: Missing Completely at Random (MCAR), Missing at Random (MAR), and Missing Not at Random (MNAR).
- **Detection**: Finding `np.nan`, counting per row/column, computing proportions, and leveraging **NumPy masked arrays** (`np.ma`) for stats like mean/covariance.
- **Imputation**:
    - **KNNImputer** for structure-aware fill-in.
- **IterativeImputer (MICE)** for multiple imputation via chained models (`sample_posterior = True`).
- **Model impact**: How missingness skews parameters; using **GaussianMixture** to illustrate structure-dependent (MAR) missingness.
- **Reproducibility**: Seeding simulations; generating multiple imputed datasets.

---

## Structure

├─ Missing-Data.ipynb # Primary laboratory notebook.

├─ README.md.

└─ (optional) requirements.txt # You can specify the pin versions if you wish.
