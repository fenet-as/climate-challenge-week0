# 🌍 African Climate Trend Analysis — Week 0 Challenge

## 📌 Overview

This project is part of the 10 Academy Data Engineering, Financial Analytics, and Machine Learning Engineering program.

It sets up a reproducible environment for analyzing historical climate data (2015–2026) from five African countries:

* Ethiopia
* Kenya
* Sudan
* Tanzania
* Nigeria

The goal of Week 0 is to build a clean project structure, practice Git workflow, and set up CI/CD before starting data analysis.

---

## 🎯 Objectives

* Set up a reproducible Python environment
* Practice Git branching and commits
* Implement CI/CD using GitHub Actions
* Prepare a clean structure for data analysis work

---

## 🗂️ Project Structure

```
climate-challenge-week0/
│
├── .github/workflows/ci.yml     # GitHub Actions CI pipeline
├── notebooks/                   # EDA notebooks (future work)
├── scripts/                     # Helper scripts
├── src/                         # Source code
├── tests/                       # Unit tests
├── requirements.txt             # Dependencies
├── .gitignore                   # Ignored files
└── README.md                    # Documentation
```

---

## ⚙️ Setup Instructions

### 1. Clone repository

```bash
git clone https://github.com/<your-username>/climate-challenge-week0.git
cd climate-challenge-week0
```

---

### 2. Create virtual environment

```bash
python -m venv venv
```

---

### 3. Activate environment

**Mac / Linux:**

```bash
source venv/bin/activate
```

**Windows:**

```bash
venv\Scripts\activate
```

---

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

---

## 📦 Dependencies

```txt
pandas
numpy
matplotlib
seaborn
scipy
jupyter
streamlit
```

---

## ⚙️ CI/CD Pipeline

A GitHub Actions workflow is included in `.github/workflows/ci.yml`.

It:

* Sets up Python 3.10
* Installs dependencies
* Verifies environment setup
* Runs automatically on every push to `main`

---

## 🚫 Git Ignore

The following are excluded from Git:

* `venv/`
* `data/`
* `.csv files`
* `.ipynb_checkpoints/`
* system files like `.DS_Store`

---

## 🧠 Notes

* This repository follows clean Git practices using feature branches
* No datasets are stored in GitHub
* Designed for reproducibility and scalability

---


