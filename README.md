# Data Engineering -- Railway Data Analysis

## 📌 Project Overview

This project was completed as part of a **Data Engineering internship
project**.\
The objective was to load, clean, transform, analyze, and visualize
railway/train data using Python and Pandas.

The dataset contains **11,113 train records** and **5 columns** related
to train numbers, train names, source stations, destination stations,
and operating days.

## 🛠️ Technologies Used

-   Python
-   Pandas
-   NumPy
-   Matplotlib
-   Seaborn
-   Jupyter Notebook

## 📂 Dataset

The dataset contains the following columns:

  Column                       Description
  ---------------------------- ---------------------------------
  `Train_No`                   Train number
  `Train_Name`                 Train name
  `Source_Station_Name`        Source station
  `Destination_Station_Name`   Destination station
  `days`                       Day on which the train operates

Dataset size: **11,113 rows × 5 columns**

## 🔍 Project Tasks

### Level 1 -- Data Loading & Inspection

-   Imported the railway dataset using Pandas.
-   Inspected the first records, shape, columns, and data types.
-   Performed basic data cleaning and standardization.

### Level 2 -- Data Analysis

-   Filtered train records based on conditions.
-   Performed grouping and aggregation.
-   Classified records into:
    -   `weekday`
    -   `weekend`

### Level 3 -- Exploratory Analysis

-   Analyzed the distribution of trains across days of the week.
-   Identified frequently occurring source stations.
-   Identified frequently occurring destination stations.
-   Analyzed frequently occurring source-to-destination routes.
-   Compared weekday and weekend operations.
-   Performed exploratory analysis involving the operating day.

### Level 4 -- Visualization & Reporting

-   Created charts for train distribution and station analysis.
-   Created route and operating-day visualizations.
-   Prepared a detailed PDF report containing analysis, tables, charts,
    and findings.

## 📊 Key Findings

### Train Distribution by Day

  Day           Train Records
  ----------- ---------------
  Monday                1,503
  Tuesday               1,628
  Wednesday             1,612
  Thursday              1,526
  Friday                1,649
  Saturday              1,593
  Sunday                1,602

**Friday** has the highest number of train records in the dataset, with
**1,649**.

### Weekday vs Weekend

  Operating Type     Records
  ---------------- ---------
  Weekday              7,918
  Weekend              3,195

The dataset contains substantially more weekday train records than
weekend records.

### Top Source Stations

1.  CST-MUMBAI --- 513
2.  SEALDAH --- 372
3.  CHENNAI BEACH --- 339
4.  HOWRAH JN. --- 338
5.  KALYAN JN --- 285

### Top Destination Stations

1.  CST-MUMBAI --- 514
2.  SEALDAH --- 373
3.  CHENNAI BEACH --- 342
4.  HOWRAH JN. --- 337
5.  KALYAN JN --- 284

### Top Routes

  Source → Destination         Records
  -------------------------- ---------
  TAMBARAM → CHENNAI BEACH         137
  CHENNAI BEACH → TAMBARAM         137
  CST-MUMBAI → PANVEL               94
  PANVEL → CST-MUMBAI               93
  RAVLI JN → CST-MUMBAI             90

## 📁 Repository Structure

``` text
data-engineering-railway-analysis/
│
├── Train_data_engineering.ipynb
├── Railway_info.csv
├── Railway_Data_Engineering_Report.pdf
└── README.md
```

> **Note:** Before making the repository public, verify that the dataset
> can be publicly redistributed. If the dataset is not permitted for
> public sharing, upload the notebook and report without the CSV, or use
> a suitable public dataset.

## ▶️ How to Run

1.  Clone or download this repository.
2.  Open `Train_data_engineering.ipynb` in Jupyter Notebook or
    JupyterLab.
3.  Make sure the required Python libraries are installed.
4.  Keep `Railway_info.csv` in the same directory as the notebook if you
    are using the included dataset.
5.  Run the notebook cells from top to bottom.

Install the main dependencies with:

``` bash
pip install pandas numpy matplotlib seaborn jupyter
```

## 📄 Project Files

-   **Jupyter Notebook:** Contains the complete data analysis workflow
    and Python code.
-   **Dataset:** Railway/train information used for the analysis.
-   **PDF Report:** Summarizes the analysis, visualizations, and key
    findings.

## 🎯 Skills Demonstrated

-   Data loading and inspection
-   Data cleaning
-   Data transformation
-   Filtering
-   GroupBy and aggregation
-   Categorical analysis
-   Route analysis
-   Exploratory Data Analysis (EDA)
-   Data visualization
-   Report preparation
-   Python/Pandas-based data analysis

## 👨‍💻 Author

**Dhruv Chauhan**

Data Engineering Internship Project
