# 🔥 Algerian Forest Fires EDA & Regression Project

This project focuses on analyzing the **Algerian Forest Fires Dataset** from the UCI Machine Learning Repository and building regression models to predict the **Fire Weather Index (FWI)** — a key indicator of wildfire risk.

---

## 📦 Dataset

- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Algerian+Forest+Fires+Dataset++)
- **Regions covered:** Bejaia and Sidi Bel-Abbes (Algeria)
- **Period:** June 2012 – September 2012
- **Features:** Temperature, Relative Humidity, Wind Speed, Rain, FFMC, DMC, DC, ISI, BUI, FWI, and Classes (Fire/No Fire)

---

## 🛠 Project Goals

- Perform **Exploratory Data Analysis (EDA)** on the dataset
- Extract meaningful **insights and patterns**
- Handle **preprocessing and outlier treatment**
- Frame a **regression problem** to predict FWI
- Build baseline regression models

---

## 🔍 Key Insights

### 🌦 Weather System Report
- **Temperature:** Most fires occurred between 30–37°C
- **Rain:** Fires mainly under no to very light rain (0.0–0.3 mm)
- **Wind Speed:** Highest fire counts at 13–19 km/h
- **Relative Humidity:** Most fires when RH is 50–80%

### 🔥 FWI System Components Report
- **FFMC (28.6–92.5):** >75 → High fire risk
- **DMC (1.1–65.9):** >10–30 → High fire risk
- **DC (7–220.4):** >25 → High fire risk
- **ISI (0–18):** >3 → High fire risk
- **BUI (1.1–68):** >10 → High fire risk
- **FWI (1–31.1):** 3–25 → High fire risk

### 📈 Other EDA Highlights
- Strong correlation: FFMC, DMC, DC, ISI, BUI with FWI
- Rain variable had limited impact (mostly zero values)
- Clear separation between fire and no-fire groups in boxplots

---

## ⚙️ Preprocessing Steps

- Handled missing values and fixed data types
- Detected and addressed outliers
- Converted ‘Classes’ into binary labels
- Prepared features for regression modeling

---

## 🤖 Models Planned

- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor

---

## 📁 Repository Structure

