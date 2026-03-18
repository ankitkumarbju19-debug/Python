# 🧠 Left vs Right-Handedness Death Age Analysis

## 📌 Project Overview

This project analyzes whether left-handed individuals tend to die younger than right-handed individuals using historical datasets on:

* Left-handedness rates by age
* U.S. death distributions (1990, 1999, 2018)

The analysis combines demographic data with probability-based modeling to estimate the **average age at death** for left- and right-handed individuals.

---

## 🎯 Objective

To investigate the long-standing claim:

> "Do left-handed people die earlier than right-handed people?"

---

## 📊 Key Findings

### 📅 1990 Data

* **Average age (Left-Handed):** 67.25 years
* **Average age (Right-Handed):** 72.79 years
* **Difference:** 5.55 years

### 📅 2018 Data

* **Average age (Left-Handed):** 70.29 years
* **Average age (Right-Handed):** 72.63 years
* **Difference:** 2.34 years

---

## 🔍 Interpretation

* Earlier data suggests left-handed individuals had a **lower average lifespan**.
* However, by 2018, the gap significantly **decreases**.
* This trend is likely due to:

  * Reduced societal pressure to switch handedness
  * Better recording and reporting of left-handed individuals

---

## 🧪 Methodology

1. **Data Sources**

   * Left-handedness rate by age
   * U.S. death distribution datasets

2. **Approach**

   * Estimated probability of being left-handed at different ages
   * Combined with death distribution data
   * Calculated conditional probabilities for age at death

3. **Analysis Techniques**

   * Probability modeling
   * Weighted averages
   * Data visualization (graphs)

---

## 📈 Visualizations Included

* Left-handedness rate vs Age
* Mean left-handedness vs Birth Year
* Death distribution (1999)
* Conditional age-at-death (1990 & 2018)

---

## 🛠️ Technologies Used

* Python 🐍
* Pandas (data manipulation)
* NumPy (numerical computation)
* Matplotlib (visualization)

---

## 📂 Project Structure

```
├── data/                 # Dataset files
├── notebooks/           # Jupyter notebooks / analysis
├── src/                 # Python scripts
├── outputs/             # Graphs and results
├── LeftRightHandedness_Report.pdf
└── README.md
```

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone <your-repo-link>
cd <repo-folder>
```

2. Install dependencies:

```bash
pip install pandas numpy matplotlib
```

3. Run the analysis script or notebook:

```bash
python main.py
```

or open the notebook:

```bash
jupyter notebook
```

---

## ⚠️ Limitations

* Results depend on historical data accuracy
* Cultural biases in older datasets may affect conclusions
* Not a causal study—only statistical inference

---

## 📌 Conclusion

The belief that left-handed people die younger appears to be **historly biased**. Modern data shows that the difference in lifespan is **minimal and decreasing over time**.

---

## 🙌 Author

**Ankit Kumar**

---

## ⭐ Acknowledgment

Inspired by statistical studies on handedness and demographic data analysis.

---
