# Guest vs Member Usage Analysis

## Main Business Question
How can we understand the difference in usage between guest users and member users? Are there opportunities to convert guests into members?

## Project Goals
- **Usage Patterns:**  
  - Who uses the app more: guests or members?
  - What are the peak days and hours?
  - Which regions have the highest usage?

- **Preferences Analysis:**  
  - What types of vehicles are preferred by each user type?
  - What is the preferred payment method (cash vs card)?
  - What are the average distance, duration, and trip cost?

- **Financial Analysis:**  
  - Do guests spend more per trip?
  - Who travels longer distances?
  - Spend and revenue per kilometer.

- **Geo Segmentation:**  
  - Which areas have high guest usage?
  - Are there regions that deserve focused membership campaigns?

- **Performance & Satisfaction (if ratings are available):**  
  - Is there a difference in driver ratings between guests and members?

## Data Columns Description

| Column Name         | Description                                                       |
|---------------------|-------------------------------------------------------------------|
| ride_id             | Unique identifier for each trip                                   |
| start_area          | Area where the trip starts                                        |
| end_area            | Area where the trip ends                                          |
| vehicle_type        | Type of vehicle used for the trip                                 |
| start_date          | Date when the trip starts (YYYY-MM-DD)                            |
| start_time          | Time when the trip starts (HH:MM)                                 |
| end_date            | Date when the trip ends (YYYY-MM-DD)                              |
| end_time            | Time when the trip ends (HH:MM)                                   |
| ride_duration_min   | Duration of the trip in minutes                                   |
| distance_km         | Distance of the trip in kilometers                                |
| price_egp           | Trip price in Egyptian Pounds (EGP)                               |
| user_type           | Type of user: Guest or Member                                     |
| driver_rating       | Driver's rating for the trip (1–5, if available)                  |
| payment_method      | Payment method: Cash or Card                                      |      

## How to Use
1. The main data file is `usage_analysis.xlsx`.
2. Open and analyze the data using Excel.
3. You can add new data or use the columns to explore patterns and insights.

## Notes
- The dataset is sample data for analysis purposes and not real user data.
- For any suggestions or questions, feel free to contact the repository owner.
