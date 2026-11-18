# 04. Cyclistic Bike-Share Analysis

A comprehensive Case Study on Cyclistic Bike-Share data (Google Data Analytics Capstone Project) analyzing user behavior patterns between casual riders and annual members to drive subscription conversion strategies.

---

## Business Task
Analyze Cyclistic bike trip data to identify differences in how annual members and casual riders use bikes differently, and provide actionable marketing insights to convert casual riders into annual members.

### Stakeholders
- **Lily Moreno:** Director of Marketing
- **Marketing Analytics Team**
- **Cyclistic Executive Team**

### Core Business Question
> *How do annual members and casual riders use Cyclistic bikes differently?*

---

## Key Business Insights

1. **Ride Frequency:** Annual members completed significantly more trips overall than casual riders, indicating routine use for daily commutes.
2. **Trip Duration:** Casual riders take significantly longer rides on average compared to annual members, suggesting leisure and recreation.
3. **Weekly Patterns:** Member trips peak during weekdays (Monday–Friday) matching commuter schedules, while casual rides spike on weekends.
4. **Seasonal Trends:** Both groups exhibit peak usage during summer months, but member ridership remains more resilient through autumn and winter.
5. **Bike Type Preference:** Both classic and electric bikes are popular, with casual riders showing strong preference for electric bikes during recreational trips.
6. **Hourly Usage:** Member activity peaks during typical rush hours (8:00 AM and 5:00 PM), whereas casual activity rises steadily throughout the afternoon.
7. **Top Stations:** Popular starting and ending stations for casual riders cluster heavily along waterfront parks, leisure attractions, and tourist hubs.

---

## Project Visualizations

The following charts generated in the notebook are preserved in [`images/`](./images):

| Visualization | Filename |
|---|---|
| **Ride Count Comparison** | `Ride Count.png` |
| **Average Ride Duration** | `Average Ride Length.png` |
| **Weekly Usage Trends** | `Weekly Usage.png` |
| **Monthly Seasonality** | `monthly usage.png` |
| **Hourly Commute Patterns** | `Hourly Usage.png` |
| **Bike Type Preference** | `Bike Type.png` |
| **Top 10 Start Stations** | `Top 10 Start Station.png` |
| **Top 10 End Stations** | `Top 10 End Station.png` |

---

## Technologies Used
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Plotly Express, Glob, OS
- **Environment:** Jupyter Notebook / Google Colab

---

## Data Notice & Architecture
- **Full Dataset (Local):** The complete local dataset is stored in `data/` (~2.58 GB across `cyclistic_combined.csv`, `cyclistic_cleaned.csv`, and `data/raw/` monthly files). It is fully accessible for local runs and excluded from Git commits via `.gitignore` to comply with GitHub's 100 MB single-file limit.
- **Repository Sample:** A verified 5,000-row sample (`datasets/cyclistic_sample.csv`) is included in the Git repository for immediate preview and testing.
- **Full Data Download:** Instructions and links to download the complete raw historical data archives are documented in [`datasets/README.md`](./datasets/README.md).
