# nyc-yellow-taxi-data-analysis
This project involved analyzing a sample dataset from the New York City Taxi &amp; Limousine Commission (TLC), sourced from the NYC Open Data program. The original dataset contains 113 million trips; a sample of 22,699 trips with 18 variables was used for efficiency.
## 📂 Dataset Summary
- **Source:** NYC Open Data
- **Total Records:** 22,699 taxi trips
- **Features:** 18 columns including trip distance, fare amount, passenger count, tip amount, payment type, etc.

| Column Name          | Description                                                  |
|----------------------|--------------------------------------------------------------|
| VendorID             | Taxi company ID (1 or 2)                                     |
| tpep_pickup_datetime | Pickup date and time                                         |
| tpep_dropoff_datetime| Dropoff date and time                                        |
| passenger_count      | Number of passengers                                         |
| trip_distance        | Distance of the trip in miles                                |
| RatecodeID           | Rate code used for the trip                                  |
| payment_type         | 1=Credit card, 2=Cash, 3=No charge, 4=Dispute, etc.          |
| fare_amount          | Meter-calculated fare                                        |
| tip_amount           | Tip amount (recorded for credit card payments)               |
| total_amount         | Total amount charged                                         |

## 🛠 Technologies Used
- Python
- Pandas
- Jupyter Notebook
- Numpy

## 📊 Project Highlights
✅ Checked for missing values and cleaned the dataset  
✅ Explored and summarized data types  
✅ Calculated average tips for credit card payments using Boolean Masking and `groupby()`  
✅ Analyzed the total amount per vendor  
✅ Identified important features for predictive modeling  

## 🔎 Key Insights
- **Trip Distance** and **Fare Amount** are critical variables for prediction.
- Higher average tip amounts are observed with credit card payments.
- Vendor data is fairly balanced between the two providers.
- Missing data is minimal but important for `tip_amount` due to unrecorded cash tips.

## 🧠 Next Steps
- Build a predictive model using key variables like `trip_distance`, `fare_amount`, and `payment_type`.
- Perform deeper Exploratory Data Analysis (EDA) and visualization.
- Consider seasonal or time-based trends in trips and payments.

## ✅ Skills Demonstrated
- Data Cleaning & Wrangling
- Exploratory Data Analysis (EDA)
- GroupBy, Boolean Masking, and Data Aggregation
- Statistical Summary & Data Interpretation
- Python & Pandas Proficiency
