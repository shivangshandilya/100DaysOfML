# 🏃 Ultra-Marathon Runners Data Analysis

This project explores a massive dataset of ultra-marathon running records sourced from [Kaggle](https://www.kaggle.com/datasets/pablohdezma/the-big-dataset-of-ultra-marathon-running). The dataset contains over **7 million race records** collected between **1798 and 2022**, offering a rich foundation for data cleaning, visualization, and beginner-level machine learning insights.

---

## 📁 Dataset

* **Title**: *The Big Dataset of Ultra-Marathon Running*
* **Source**: [Kaggle](https://www.kaggle.com/datasets/pablohdezma/the-big-dataset-of-ultra-marathon-running)
* **Size**: 7M+ records
* **Scope**: Covers event-level data for ultra-marathon races across multiple countries over two centuries.

---

## 🔧 Libraries Required

Make sure you have the following Python libraries installed:

```bash
pip install pandas seaborn
```

---

## 📊 What This Project Does

1. **🧹 Data Cleaning**

   * Removed missing and inconsistent entries
   * Processed text fields for country, race length, and time
   * Created new features such as athlete age and average speed

2. **📈 Data Visualization**
   Used **Seaborn** to understand and communicate insights from the data:

   * `displot()` for distribution of speeds and ages
   * `histplot()` for race frequency analysis
   * `violinplot()` to compare performance across categories like gender, country, or race type

---

## 🌱 Why This Is Beginner-Friendly

This project is ideal for beginners because:

* It uses **only Pandas and Seaborn**, so you don't need to know any advanced tools.
* It emphasizes **data cleaning**, which is a crucial skill for real-world data science.
* All plots are built from scratch using **simple, readable syntax**.
* The notebook is structured step-by-step — easy to follow and replicate.

---

## 🤖 ML Concepts Touched Upon

Although this project doesn’t involve building a full machine learning model, it covers foundational concepts essential for ML:

* **Feature Engineering**: Creating new columns like `athlete_age` or `average_speed`
* **Exploratory Data Analysis (EDA)**: Identifying trends and distributions
* **Data Preprocessing**: Handling missing values, standardizing text data
* **Data Visualization**: A critical first step before model-building

These steps lay the groundwork for future tasks like clustering runners, predicting race outcomes, or classifying athletes based on performance.

---


## 📸 Some Screenshots

<img width="1672" height="936" alt="Screenshot 2025-07-20 080021" src="https://github.com/user-attachments/assets/1ac70ada-0a62-47c6-b0f7-891820ff7029" />

<img width="1486" height="760" alt="Screenshot 2025-07-20 080057" src="https://github.com/user-attachments/assets/2bbfbd88-e390-4b09-a847-1540c35294df" />

<img width="1484" height="704" alt="Screenshot 2025-07-20 080207" src="https://github.com/user-attachments/assets/3d66e79f-d4d7-497a-8ece-1578db1e0bc5" />




