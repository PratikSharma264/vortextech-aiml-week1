# Vortex Tech AI & ML Internship – Week 1

## Data Cleaning and Exploratory Data Analysis (EDA)

This repository contains my Week 1 assignment for the **Vortex Tech AI & ML Internship Program 2026**. The objective of this task is to begin working with a real-world dataset using Python and Pandas by setting up the development environment, loading the dataset, and performing an initial inspection.

---

## 📌 Objective

The primary objective of this stage is to:

* Set up the Python environment.
* Install the required libraries.
* Download a public dataset.
* Load the dataset into a Jupyter Notebook.
* Perform an initial inspection of the dataset.

---

## 🛠 Prerequisites

Before starting, install **Python 3.x** from the official Python website.

Required Python libraries:

```bash
pip install pandas matplotlib seaborn jupyter
```

---

## 📂 Dataset

For this project, the **Titanic Dataset** from Kaggle is used.

**Source:** https://www.kaggle.com/datasets/yasserh/titanic-dataset

Download the dataset in **CSV** format and place it inside the project's `data` folder.

---

## ▶️ Running the Project

### 1. Launch Jupyter Notebook

Open a terminal in the project directory and run:

```bash
jupyter notebook
```

Create a new Jupyter Notebook (`.ipynb`) file.

---

### 2. Load the Dataset

Import the Pandas library and read the CSV dataset.

```python
import pandas as pd

df = pd.read_csv("../data/Titanic-Dataset.csv")
```

If the notebook is in the same directory as the dataset, use:

```python
df = pd.read_csv("Titanic-Dataset.csv")
```

---

### 3. Initial Data Inspection

Display the first few rows of the dataset:

```python
df.head()
```

Display dataset information:

```python
df.info()
```

These commands provide an overview of the dataset, including the column names, data types, number of records, and any missing values.

---

## 📁 Project Structure

```text
vortextech-aiml-week1/
│
├── data/
│   └── Titanic-Dataset.csv
│── images/
├── notebook/
│   └── Week1_DataCleaning_EDA.ipynb
│
├── README.md
└── requirements.txt
```

---

## 🚀 Current Progress

* ✅ Python environment configured
* ✅ Required libraries installed
* ✅ Dataset downloaded
* ✅ Jupyter Notebook created
* ✅ Dataset successfully loaded
* ✅ Initial dataset inspection completed

This README covers the initial setup and data loading phase of the Week 1 assignment. Subsequent sections, including data cleaning, exploratory data analysis, summary statistics, and visualizations, will be added as the project progresses.
