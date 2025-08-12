Hotel Booking Analysis 🏨

📌 Project Overview
This case study explores hotel booking data to uncover patterns in customer behavior, cancellations, pricing trends, and seasonality.
The dataset contains detailed booking information for city and resort hotels, including guest demographics, booking channels, lead times, and reservation outcomes.
Through data cleaning, feature engineering, and visual analysis, the goal is to provide actionable insights for hotel management to improve operational efficiency and customer satisfaction.

📂 Dataset
Source: hotel_bookings.csv

Key Columns:

hotel – Hotel type (Resort, City)

is_canceled – Booking cancellation flag

lead_time – Days between booking and arrival

arrival_date_year, arrival_date_month, arrival_date_day_of_month

stays_in_weekend_nights, stays_in_week_nights

adults, children, babies

reserved_room_type, assigned_room_type

booking_changes, deposit_type, customer_type

adr – Average Daily Rate

And more...

🛠 Steps Performed
1. Data Cleaning & Preprocessing
Filled missing values (children, agent, company, country)

Removed duplicates

Converted categorical variables for analysis

Parsed and standardized date columns

Created derived features:

total_stay_nights

total_guests

arrival_date from year, month, and day

2. Exploratory Data Analysis (EDA)
Booking distribution by hotel type

Seasonality trends in bookings

Cancellation rates by customer type & deposit type

Lead time distribution analysis

ADR trends across months and room types

Booking channel preferences

Comparison of reserved vs assigned room types

3. Visualization
Bar plots, histograms, and line charts using Matplotlib/Seaborn

Monthly ADR & booking trends

Heatmaps for cancellation patterns

Stacked bar charts for customer type and market segment

📊 Key Insights
High cancellation rates linked to certain deposit types and market segments.

Seasonality effects with peak bookings in specific months for both hotels.

Lead time significantly impacts cancellation probability.

Room upgrades common for repeat customers.

City hotels tend to have higher ADR compared to resort hotels.

🚀 Tools & Libraries
Python – Data processing & analysis

Pandas – Data cleaning & transformation

Matplotlib & Seaborn – Visualization

Jupyter Notebook – Interactive analysis
