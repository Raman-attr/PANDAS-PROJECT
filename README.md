# 🎬 Anime Data Feature Extraction & Cleaning

## 📌 Overview

This project focuses on transforming raw and unstructured anime data into a clean, structured format suitable for analysis. The dataset contained inconsistent date formats, unclear episode counts, and messy time-related fields.

---

## 🔍 Problem Statement

Real-world datasets are often incomplete and inconsistent.
In this project, the anime dataset had:

* Mixed date formats (e.g., "Jan 2020 - Mar 2021")
* Non-numeric episode values (e.g., "Unknown", "12+ eps")
* Unstructured time-related data

---

## ✅ Solution

* Cleaned and standardized raw data
* Extracted meaningful features such as:

  * Month
  * Duration (in months)
* Converted episode data into numeric format
* Prepared dataset for analysis

---

## 🛠 Tools & Technologies

* Python
* Pandas
* Datetime
* Dateutil

---

## ⚙️ Feature Engineering

* Extracted month from date fields
* Calculated total duration using `relativedelta`
* Cleaned and converted episode counts
* Handled missing and inconsistent values

---

## 📊 Key Insights

* Identified top 5 anime with highest episode count
* Found longest-running anime in the dataset
* Observed trends in anime duration and release periods

---

## 📁 Project Structure

```
Anime-Feature-Extraction/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│
├── src/
│
├── outputs/
│
├── requirements.txt
└── README.md
```

---

## 🚀 How to Run

1. Clone the repository
2. Install dependencies:

```
pip install -r requirements.txt
```

3. Run the Jupyter Notebook:

```
jupyter notebook
```


## 🎯 Learning Outcomes

* Handling real-world messy datasets
* Feature engineering techniques
* Data cleaning and preprocessing
* Writing reusable Python functions

---

## 🔗 Connect with Me

www.linkedin.com/in/raman-attri-58140724a
