
---

## 🔧 Tools & Technologies
- Python (Pandas, NumPy, datetime)
- Power BI Desktop
- DAX (for basic calculations)
- GitHub

---

## 📈 Data Preparation (Python)

The data was cleaned and pre-processed in Python with the following steps:

- Loaded original Uber dataset from Kaggle
- Removed missing values and duplicates
- Parsed `pickup_datetime` as datetime object
- Extracted:
  - `hour`, `day`, `month`, `day_of_week`, and `year`
- Engineered `distance_km` using the Haversine formula (pickup ↔ dropoff)
- Exported enhanced dataset as `uber_cleaned_with_distance.csv` for Power BI

📌 Full code in [`assignment1_itbd.ipynb`](./assignment1_itbd.ipynb)

---

## 📊 Dashboard Features (Power BI)

Interactive dashboard built in Power BI includes:

### 📌 Visuals:
- **Fare Distribution by Bins**
- **Average Fare by Passenger Count**
- **Fare vs Distance (Scatter Plot)**
- **Total Rides by Hour of Day**
- **Fare by Weekday and Distance**
- **Rides by Day Over the Years**
- **Pickup Location Map (Geo Map)**
- **KPI Cards**:
  - Max Fare
  - Total Rides
  - Average Distance

### 🎛️ Interactivity:
- Slicers for:
  - Day of Week


📌 Power BI file: [`uber_analysis.pbix`](./uber_analysis.pbix)

---

## 📷 Screenshots
See the `screenshots/` folder for:
- Data Cleaning Steps
- Power BI Visual Development
- Final Dashboard Layout

---

## 📌 Key Insights

- Most Uber rides are short-distance and occur between 5 PM–9 PM
- Average ride fare is relatively consistent regardless of passenger count
- Peak ride activity is concentrated in the NYC metro area
- Fridays show slightly higher ride volumes than other days

---

## 📬 Submission

- 🔗 GitHub Repo Link: *[https://github.com/4ri3ll4/intro_to_bigdata_assignment1]*
- 📧 Submitted to: **eric.maniraguha@auca.ac.rw**
- 🗓️ Deadline: July 25, 2025

---

## 🧠 Author

👩🏽 **Ariella Ampoze Rurebwayire**    
AUCA — Introduction to Big Data Analytics  


---

# intro_to_bigdata_assignment1
