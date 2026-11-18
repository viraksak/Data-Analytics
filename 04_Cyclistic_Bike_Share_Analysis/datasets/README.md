# Cyclistic Bike-Share Datasets

## Overview
The complete dataset for this project comprises over **5.7 million rides** across 2023 Divvy trip data (~2.58 GB raw and cleaned CSV files). Due to GitHub's 100 MB file size limit, full raw datasets are hosted externally, while a representative 5,000-row sample is provided in this directory for quick local inspection.

- **Sample File:** `cyclistic_sample.csv` (5,000 records, 18 features)
- **Data Source:** [Index of Divvy Tripdata](https://divvy-tripdata.s3.amazonaws.com/index.html)
- **Data License:** The data is provided by Motivate International Inc. under the [Divvy Data License Agreement](https://divvybikes.com/data-license-agreement).

---

## Data Schema
| Column | Type | Description |
|---|---|---|
| `ride_id` | string | Unique identifier for each bike trip |
| `rideable_type` | string | Type of bike (`classic_bike`, `electric_bike`, `docked_bike`) |
| `started_at` | datetime | Trip start timestamp |
| `ended_at` | datetime | Trip end timestamp |
| `start_station_name` | string | Name of departure docking station |
| `start_station_id` | string | Identifier for departure docking station |
| `end_station_name` | string | Name of destination docking station |
| `end_station_id` | string | Identifier for destination docking station |
| `start_lat` | float | Starting latitude coordinates |
| `start_lng` | float | Starting longitude coordinates |
| `end_lat` | float | Ending latitude coordinates |
| `end_lng` | float | Ending longitude coordinates |
| `member_casual` | string | Rider classification (`member` or `casual`) |
| `ride_length` | string / float | Duration of the trip |
| `day_of_week` | string / int | Day of the week of trip start |
| `month` | int | Month of trip start |
| `hour` | int | Hour of trip start (0–23) |
| `date` | string | Date in `YYYY-MM-DD` format |

---

## Instructions to Download Full Raw Datasets
1. Download the monthly trip archives from the [Divvy Tripdata Portal](https://divvy-tripdata.s3.amazonaws.com/index.html).
2. Extract the CSV files into a local `data/raw/` folder.
3. Run the preprocessing pipeline in `Cyclistic.ipynb` to concatenate and clean the datasets into `cyclistic_cleaned.csv`.
