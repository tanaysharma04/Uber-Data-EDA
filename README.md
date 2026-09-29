# 🚖 Uber Ride Booking Data Analysis (EDA)

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on an Uber ride booking dataset to uncover trends, identify data quality issues, and generate business insights. The analysis includes data cleaning, visualization, handling missing values, and examining factors affecting ride bookings and cancellations.

---

## 📂 Dataset

The dataset contains information about Uber ride bookings, including:

- Booking Status
- Vehicle Type
- Pickup & Drop Locations
- Ride Distance
- Booking Value
- Customer Ratings
- Driver Ratings
- Payment Method
- Cancellation Reasons
- Average VTAT (Vehicle Time of Arrival)
- Average CTAT (Customer Time of Arrival)
- Ride Date & Time

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Plotly

---

## 📊 Exploratory Data Analysis

The following analyses were performed:

### Data Cleaning
- Removed duplicate records
- Handled missing values
- Standardized location names
- Corrected invalid values
- Converted columns to appropriate data types

### Univariate Analysis
- Booking Status distribution
- Vehicle Type distribution
- Payment Method analysis
- Ride Distance distribution
- Booking Value distribution
- Customer Ratings
- Driver Ratings

### Bivariate Analysis
- Booking Status vs Vehicle Type
- Ride Distance vs Booking Value
- Customer Ratings vs Driver Ratings
- Cancellation Reasons analysis
- Payment Method vs Booking Status

### Outlier Detection
- Box plots
- IQR-based analysis
- Detection of abnormal ride distances and booking values

---

## 📈 Key Insights

Some insights obtained from the analysis include:

- Most rides were successfully completed.
- Certain vehicle types were booked more frequently.
- Ride distance has a positive relationship with booking value.
- Missing values required preprocessing before analysis.
- Customer and driver ratings generally remained high.
- Cancellation patterns highlighted common operational issues.

---

## 📁 Project Structure

```
Uber-Data-EDA/
│
├── EDA.ipynb
├── delhi_uber_dataset.csv
├── .gitignore
└── README.md
```

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/tanaysharma04/uber-data-eda.git
```

2. Move into the project directory

```bash
cd uber-data-eda
```

3. Install dependencies

```bash
pip install pandas numpy matplotlib plotly
```

4. Launch Jupyter Notebook

```bash
jupyter notebook
```

5. Open **EDA.ipynb** and run all cells.

---

## 📚 Libraries Used

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import plotly.express as px
```

---

## 🎯 Learning Outcomes

Through this project, I learned:

- Data preprocessing techniques
- Handling missing values
- Detecting and treating outliers
- Data visualization
- Exploratory Data Analysis (EDA)
- Drawing business insights from real-world datasets

---

## 👨‍💻 Author

**Tanay Sharma**

---

