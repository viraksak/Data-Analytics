#Data Analytics Projects

A curated collection of completed Data Analytics and Exploratory Data Analysis (EDA) projects developed as part of professional data analytics coursework, fully equipped with verified datasets and documentation.

---

## Projects Overview

### 1. [01_Automatidata_NYC_Taxi_Trip_Analysis](./01_Automatidata_NYC_Taxi_Trip_Analysis)
- **Description:** Exploratory data analysis, statistical inspection, and fare/distance modeling for New York City Taxi and Limousine Commission (TLC) trip records to optimize operational insights and revenue understanding for Automatidata.
- **Technologies Used:** Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook.
- **Notebooks:**
  - `Activity_Course 2 Automatidata project lab.ipynb`: Stage 1 — Data exploration, summary statistics, and data cleaning.
  - `Activity_Course 3 Automatidata project lab.ipynb`: Stage 2 — Comprehensive Exploratory Data Analysis (EDA), distribution visualization (boxplots, histograms, scatter plots), trip duration analysis, and payment type breakdowns with preserved outputs.
- **Datasets:**
  - `datasets/2017_Yellow_Taxi_Trip_Data.csv` (22,699 records, 18 columns). Public domain open dataset from NYC TLC.

### 2. [02_TikTok_Claims_Classification](./02_TikTok_Claims_Classification)
- **Description:** Data inspection, exploratory evaluation, and visualization of TikTok video claims and user engagement metrics to prepare and structure data for a machine learning claims classification pipeline.
- **Technologies Used:** Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook.
- **Notebooks:**
  - `Activity_Course 2 TikTok project lab.ipynb`: Stage 1 — Video claims data inspection, claim status distribution (`claim` vs. `opinion`), and author ban status analysis with preserved execution outputs.
  - `Activity_Course 3 TikTok project lab.ipynb`: Stage 2 — Comprehensive Exploratory Data Analysis (EDA), engagement visualizations (view, like, share, and download count distributions), and claims analysis with preserved outputs.
- **Datasets:**
  - `datasets/tiktok_dataset.csv` (19,382 records, 12 columns).
  - `images/`: PACE workflow diagrams and process assets.

### 3. [03_Waze_User_Churn_Analysis](./03_Waze_User_Churn_Analysis)
- **Description:** User churn analysis and behavioral segmentation for Waze, analyzing driver retention, trip frequency, driving days, and device platforms (iPhone vs. Android).
- **Technologies Used:** Python, Pandas, NumPy, Jupyter Notebook.
- **Notebooks:**
  - `Activity_Course 2 Waze project lab.ipynb`: Exploratory analysis comparing churned vs. retained users, handling missing values in labels, analyzing driving patterns per day, and evaluating mobile platform retention rates (16/16 cells fully executed).
- **Datasets:**
  - `datasets/waze_dataset.csv` (14,999 records, 13 columns). Recovered and verified from official course repository.

---

## Repository Structure

```text
DA/
├── README.md
├── .gitignore
├── 01_Automatidata_NYC_Taxi_Trip_Analysis/
│   ├── Activity_Course 2 Automatidata project lab.ipynb
│   ├── Activity_Course 3 Automatidata project lab.ipynb
│   ├── 2017_Yellow_Taxi_Trip_Data.csv
│   └── datasets/
│       └── 2017_Yellow_Taxi_Trip_Data.csv
├── 02_TikTok_Claims_Classification/
│   ├── Activity_Course 2 TikTok project lab.ipynb
│   ├── Activity_Course 3 TikTok project lab.ipynb
│   ├── tiktok_dataset.csv
│   ├── images/
│   │   ├── Plan.png
│   │   ├── Analyze.png
│   │   ├── Construct.png
│   │   ├── Execute.png
│   │   └── Pace.png
│   └── datasets/
│       └── tiktok_dataset.csv
└── 03_Waze_User_Churn_Analysis/
    ├── Activity_Course 2 Waze project lab.ipynb
    ├── waze_dataset.csv
    └── datasets/
        └── waze_dataset.csv
```

---

## Environment & Requirements

To explore or execute these notebooks locally, install the standard data analytics stack:

```bash
pip install jupyter pandas numpy matplotlib seaborn
```
