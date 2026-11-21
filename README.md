# Data Analytics Projects

A curated collection of completed Data Analytics and Exploratory Data Analysis (EDA) projects developed as part of professional data analytics coursework, fully equipped with verified datasets, visualizations, and documentation.

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
- **Datasets & Assets:**
  - `datasets/tiktok_dataset.csv` (19,382 records, 12 columns).
  - `images/`: PACE workflow diagrams and process assets.

### 3. [03_Waze_User_Churn_Analysis](./03_Waze_User_Churn_Analysis)
- **Description:** User churn analysis and behavioral segmentation for Waze, analyzing driver retention, trip frequency, driving days, and device platforms (iPhone vs. Android) through exploratory data analysis and visual storytelling.
- **Technologies Used:** Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook.
- **Notebooks:**
  - `Activity_Course 2 Waze project lab.ipynb`: Stage 1 — Exploratory analysis comparing churned vs. retained users, handling missing values in labels, analyzing driving patterns per day, and evaluating mobile platform retention rates (16/16 cells fully executed).
  - `Activity_Course 3 Waze project lab.ipynb`: Stage 2 — Comprehensive Exploratory Data Analysis (EDA), distribution visualization (boxplots and histograms for sessions, drives, km, duration, driving days, and activity days), user churn proportions, and outlier handling (42/42 cells fully executed).
- **Datasets & Assets:**
  - `datasets/waze_dataset.csv` (14,999 records, 13 columns).
  - `images/`: PACE workflow diagrams and process assets.

### 4. [04_Cyclistic_Bike_Share_Analysis](./04_Cyclistic_Bike_Share_Analysis)
- **Description:** Case study analyzing over 5.7 million bike trips for Cyclistic, identifying behavioral differences between casual riders and annual members to formulate data-driven conversion and marketing strategies.
- **Technologies Used:** Python, Pandas, NumPy, Matplotlib, Plotly Express, Jupyter Notebook.
- **Notebooks & Reports:**
  - `Cyclistic.ipynb`: Comprehensive end-to-end data processing, feature engineering, exploratory data analysis, and visualizations.
  - `report/Business Insight.txt`: Key business findings, usage comparisons, and strategic recommendations for stakeholders.
- **Datasets & Assets:**
  - `datasets/cyclistic_sample.csv` (5,000 records, 18 features sample dataset).
  - `datasets/README.md`: Data dictionary and instructions for downloading full Divvy tripdata archives.
  - `images/`: High-resolution charts (ride counts, average ride length, hourly/weekly/monthly usage, bike types, and top stations).

### 5. [glossaries](./glossaries)
- **Description:** Official reference glossaries from Google's professional certificates (Google Data Analytics, Google Advanced Data Analytics, and Google AI Essentials), categorized by program and course milestone with specific, descriptive filenames.
- **Programs Covered:**
  - `Google_Advanced_Data_Analytics/`: Complete certificate master glossary and individual glossaries for Courses 1, 2, and 7.
  - `Google_Data_Analytics/`: Complete 8-course master glossary and course-level glossaries for Courses 1, 2, 4, 5, and 6.
  - `Google_AI_Essentials/`: Official AI Essentials course glossary.

---

## Repository Structure

```text
.
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
├── 03_Waze_User_Churn_Analysis/
│   ├── Activity_Course 2 Waze project lab.ipynb
│   ├── Activity_Course 3 Waze project lab.ipynb
│   ├── waze_dataset.csv
│   ├── images/
│   │   ├── Plan.png
│   │   ├── Analyze.png
│   │   ├── Construct.png
│   │   ├── Execute.png
│   │   └── Pace.png
│   └── datasets/
│       └── waze_dataset.csv
├── 04_Cyclistic_Bike_Share_Analysis/
│   ├── Cyclistic.ipynb
│   ├── README.md
│   ├── report/
│   │   └── Business Insight.txt
│   ├── images/
│   │   ├── Average Ride Length.png
│   │   ├── Bike Type.png
│   │   ├── Hourly Usage.png
│   │   ├── monthly usage.png
│   │   ├── Ride Count.png
│   │   ├── Top 10 End Station.png
│   │   ├── Top 10 Start Station.png
│   │   └── Weekly Usage.png
│   └── datasets/
│       ├── README.md
│       └── cyclistic_sample.csv
└── glossaries/
    ├── README.md
    ├── Google_Advanced_Data_Analytics/
    │   ├── Google_Advanced_Data_Analytics_Certificate_Complete_Glossary.docx
    │   ├── Course_1_Foundations_of_Data_Science_Glossary.docx
    │   ├── Course_2_Get_Started_with_Python_Glossary.docx
    │   └── Course_7_Google_Advanced_Data_Analytics_Capstone_Glossary.docx
    ├── Google_Data_Analytics/
    │   ├── Google_Data_Analytics_Certificate_Complete_Glossary.docx
    │   ├── Course_1_Foundations_Data_Data_Everywhere_Glossary.docx
    │   ├── Course_2_Ask_Questions_to_Make_Data_Driven_Decisions_Glossary.docx
    │   ├── Course_4_Process_Data_from_Dirty_to_Clean_Glossary.docx
    │   ├── Course_5_Analyze_Data_to_Answer_Questions_Glossary.docx
    │   └── Course_6_Share_Data_Through_the_Art_of_Visualization_Glossary.docx
    └── Google_AI_Essentials/
        └── Google_AI_Essentials_Course_Glossary.docx
```

---

## Environment & Requirements

To explore or execute these notebooks locally, install the standard data analytics stack:

```bash
pip install jupyter pandas numpy matplotlib seaborn plotly
```
