# Executive-Hotel-Booking-EDA-Report
Exploratory Data Analysis on 25K+ hotel bookings — data cleaning, univariate/bivariate/correlation analysis, and executive insights on cancellations, pricing, and guest satisfaction (Python, Pandas, Seaborn).
# Executive Hotel Booking — Exploratory Data Analysis

An end-to-end EDA on 25,180 hotel bookings across 10 locations and two hotel types (City & Resort), covering data quality assessment, cleaning, univariate/bivariate/group-wise analysis, correlation analysis, and management-ready recommendations.

## 📁 Contents

| File | Description |
|---|---|
| [Hotel_Booking_EDA.ipynb](./Hotel_Booking_EDA.ipynb) | Full, executed analysis notebook — code, charts, and outputs |
| [Executive_Hotel_Booking_EDA_Report.docx](./Executive_Hotel_Booking_EDA_Report.docx) | Executive-ready summary report with key visuals, insights, and recommendations |
| [Day15_Executive_Hotel_Booking_EDA_Dataset.csv](./Day15_Executive_Hotel_Booking_EDA_Dataset.csv) | Source dataset |

## 🎯 Objective

Assess data quality, understand booking and cancellation behaviour, identify revenue and satisfaction drivers, and translate findings into actionable recommendations for hotel management.

## 🧪 Workflow

1. **Data Understanding** — shape, structure, data types, summary stats
2. **Data Quality Assessment** — missing values, duplicates, inconsistent categories, illogical entries, outliers
3. **Data Cleaning & Preprocessing** — deduplication, text standardization, type correction, missing-value treatment, feature engineering
4. **Descriptive Statistics**
5. **Univariate Analysis** — distributions of hotel type, location, market segment, ADR, lead time, satisfaction
6. **Bivariate & Group-wise Analysis** — cancellation rate by hotel type/segment/lead-time/deposit type, revenue and ADR by location, satisfaction by customer type
7. **Correlation Analysis** — numeric feature relationships with cancellation likelihood

## 🔑 Key Insights

- **72% of bookings** end in cancellation or no-show, driven heavily by long lead times and non-refundable-deposit bookings.
- **Market segment/channel** is a leading indicator of cancellation risk — Online TA and Group bookings cancel more than Direct or Corporate.
- **Resort Hotels** command a higher average ADR than City Hotels; revenue is concentrated in a handful of top locations.
- **Guest satisfaction** correlates more with service responsiveness (special requests fulfilled) than with room price.
- **Booking volume and cancellation rate move together seasonally**, pointing to peak-season overbooking risk.

## 🛠️ Tools

Python · Pandas · NumPy · Matplotlib · Seaborn · Jupyter Notebook

## 🚀 How to Run

```bash
pip install pandas numpy matplotlib seaborn jupyter
jupyter notebook Hotel_Booking_EDA.ipynb
```

## 📌 Recommendations Snapshot

1. Tighten cancellation policy for long-lead-time bookings
2. Audit the non-refundable deposit product
3. Add confirmation controls on high-risk channels (Online TA, Groups)
4. Adopt location- and hotel-type-aware dynamic pricing
5. Invest in front-line service personalization
6. Build a seasonal staffing/overbooking-buffer plan
7. Standardize data capture and validation at source
