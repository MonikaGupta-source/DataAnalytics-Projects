# 📊 Student Mental Health Analysis – Complete EDA & Visualization

> A data-driven project to understand stress, anxiety, depression, and burnout among students. Perfect for juniors learning data analysis.

---

## 📁 Project Files

| File | What it contains |
|------|------------------|
| `EDA_student_mental_health` | **Exploratory Data Analysis** – Data cleaning, correlation matrix, groupby aggregations, pivot tables, new feature engineering, and **hypothesis testing (two-sample z-test)**. |
| `visualization_student_mental_health` | **Data Visualization** – Histograms, boxplots, KDE plots, violin plots (and more – currently a work in progress 🚧). |

---

## 🔍 What I Did in the EDA File

- ✅ Cleaned missing values & outliers  
- ✅ Created **new columns** (e.g., stress_per_hour, burnout_index)  
- ✅ Used **groupby** & **pivot tables** to summarize data by gender, academic year, etc.  
- ✅ Performed **correlation analysis** (heatmap)  
- ✅ Conducted **two-sample z-test** (hypothesis testing) – compared stress levels between male/female or different year groups  

---

## 📈 What I Did in the Visualization File

- 📊 **Histograms** – distribution of study hours, sleep hours  
- 📦 **Boxplots** – compare anxiety scores across academic years  
- 🎻 **KDE plots** – smooth density of depression scores  
- 🎻 **Violin plots** – detailed spread of stress levels by category  

> ⚠️ *This notebook is still being improved – more plots and interactive charts coming soon.*

---
## ⚙️ How to Run

**Install dependencies:**
```bash
pip install pandas numpy matplotlib seaborn scipy jupyter
```

**Launch Jupyter Notebook:**
```bash
jupyter notebook
```
Open `.ipynb` files and run cell by cell.

---

## 📌 Key Insights

- 📚 Students with **>6 study hours** show higher stress (p < 0.05 in z-test)
- 😴 **Sleep deprivation** correlates with higher burnout
- 🎻 Violin plots reveal that **final-year students** have wider depression score ranges

---

## 👩‍💻 Author

**Monika Gupta**
*Aspiring Data Scientist | Python & Pandas Enthusiast*
📌 *Learning in public – one analysis at a time.*

---

## ⭐ For You (Fellow Students)

This project is a **beginner-friendly template**. You can learn:
- How to **clean real-world data**
- How to **test hypotheses** (z-test)
- How to create **publication-ready plots**

Feel free to share this repo link with your batchmates!
If it helps you, don't forget to **star ⭐** this repo!

