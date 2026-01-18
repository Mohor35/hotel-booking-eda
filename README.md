## Hotel Booking Demand – Exploratory Data Analysis (EDA)

### Project Overview
This project performs an exploratory data analysis on hotel booking data
to understand booking patterns, guest behavior, pricing trends,
seasonality, and cancellation behavior across City and Resort hotels.

### Dataset
Hotel Booking Demand dataset (`hotel_bookings.csv`)

### Steps Performed
- Loaded and inspected the dataset to understand structure and missing values
- Cleaned data by handling missing values, removing duplicates, and filtering invalid prices
- Created new features such as total nights stayed and total guests
- Performed analysis on non-cancelled bookings where required
- Conducted exploratory data analysis using visualizations to answer business questions

### Key Insights
- City Hotels receive higher booking volume but also experience higher cancellation rates.
- Resort Hotels show strong seasonality with higher ADR during summer months.
- Most guests originate from a limited number of countries.
- Guests with more special requests are less likely to cancel their bookings.
- Online Travel Agencies dominate hotel bookings.
- Resort Hotel guests tend to have longer stays compared to City Hotel guests.

### Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

### How to Run
1. Clone the repository
2. Install dependencies using `pip install -r requirements.txt`
3. Run the notebook `hotel_booking_eda.ipynb` in Jupyter Notebook
