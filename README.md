# basic_BCI_analysis

A collection of Jupyter notebooks exploring the fundamentals of **Brain-Computer Interface (BCI)** analysis — from loading raw EEG data and applying signal processing techniques, to building a basic machine learning pipeline for classification.

---

## 📌 Overview

This repository serves as a learning/reference project for anyone getting started with BCI and EEG signal analysis. It walks through the core steps of a BCI pipeline using real EEG recordings (PhysioNet EEG Motor Movement/Imagery dataset) and progressively introduces more advanced concepts, ending with a Level 1 ML foundation.

---

## 📂 Repository Contents

| File | Description |
|------|-------------|
| `BCI_Basic_Project.ipynb` | Introductory BCI project — initial commit |
| `BCI_S001R04.ipynb` | Analysis of run R04 with a confusion matrix |
| `BCI_S001R08.ipynb` | Analysis of run R08 with a confusion matrix |
| `BCI_S001R12.ipynb` | Basic BCI pipeline replica using run R12 |
| `Fourier_transform.ipynb` | Fourier transform / frequency-domain analysis of EEG |
| `level1_ML_foundation_BCI.ipynb` | Histograms (Seaborn), overlay comparisons, and inference — Level 1 ML foundation |
| `S001R08.edf` | EEG dataset file (run R08) |
| `S001R12.edf` | EEG dataset file (run R12) |

---

## 🧠 Topics Covered

- Loading and inspecting `.edf` EEG recordings
- Basic preprocessing and visualization of EEG signals
- Frequency-domain analysis using the **Fourier Transform**
- Building a baseline BCI classification pipeline
- Evaluating models with **confusion matrices**
- Exploratory data analysis using **Seaborn** (histograms, overlay comparisons)
- Drawing inferences from model outputs

---

## 🛠️ Requirements

To run the notebooks, install the following Python packages:

```bash
pip install numpy pandas matplotlib seaborn scipy scikit-learn mne jupyter
```

- **mne** — for reading `.edf` EEG files
- **scipy / numpy** — for signal processing and FFT
- **scikit-learn** — for ML models and metrics
- **matplotlib / seaborn** — for visualization

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/aparna-2001/basic_BCI_analysis.git
   cd basic_BCI_analysis
   ```

2. Launch Jupyter:
   ```bash
   jupyter notebook
   ```

3. Open any notebook (start with `BCI_Basic_Project.ipynb`) and run the cells.

---

## 📊 Dataset

The `.edf` files included (`S001R08.edf`, `S001R12.edf`) are EEG recordings from the **PhysioNet EEG Motor Movement/Imagery Dataset**. In this dataset:
- `S001` refers to subject 1
- `R08` / `R12` refer to specific experimental runs (e.g., real vs. imagined motor movement tasks)

---

## 🎯 Purpose

This repo is intended as a hands-on introduction to BCI signal processing for beginners. It documents the journey from raw EEG signals to a working classification pipeline, and can serve as a foundation for more advanced BCI projects.

---

## 👤 Author

**APARNA M P**

---
