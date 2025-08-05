# Bike Sharing Analysis Project

### Overview
This project is an Exploratory Data Analysis (EDA) of a Bike Sharing Dataset. The main goal is to understand how different factors like season, weather, user type, and time of day affect bike rental demand. The analysis helps identify business patterns and give ideas for better operations and marketing.

### Project Workflow
- Data Cleaning & Preprocessing
  - No outliers in day.csv.
  - Some outliers in hour.csv during rush hours or extreme weather.
- Exploratory Data Analysis (EDA)
   -  Descriptive Statistics
   - **Hourly Data**
       - Avg hourly rentals: 173
       - Max hourly rentals: 642
       - Registered users dominate rentals.
  -  **Daily Data**
      - Avg daily rentals: 4,504
      - Avg registered: 3,656 | Avg casual: 848
      - Avg temperature: 0.49 (normalized)
      - Weather is mostly Clear/Partly Cloudy
- Data Visualization
- Strategy Suggestion

### Key Business Insights
**1. Seasonal Trends**
- Fall has the highest total and daily rentals (peak season).
- Spring has the lowest, possibly due to poor weather.
- Rentals follow a clear cycle: increasing from Spring → Fall → dropping in Winter.

**2. Weather Impact**
- Clear weather = more rentals (~2.26 million)
- Rentals drop with mist/clouds, and almost disappear with rain (~37k).

**3. Hourly Usage Patterns**
- **Weekdays:** Two clear peaks at 08:00 and 18:00 (commute times).
- **Weekends:** Rentals are evenly spread from 10:00 to 18:00.

**4. Weekdays vs. Weekends**
- Weekday rentals: ~2.29M | Weekend rentals: ~1M

5. 👥 User Behavior
Registered Users: 81.2% of rentals (2.67M), rent during commute hours.

Casual Users: Only 18.8% (620k), rent mostly during daytime.

Strategy: Keep registered users loyal with perks. Convert casual users with weekend offers or loyalty points.

6. 🎉 Holidays vs. Non-Holidays
Rentals drop significantly during holidays.

On non-holidays, rentals follow commute trends (peaks in morning/evening).

Strategy: Run holiday campaigns to encourage biking for fun or leisure.

7. 🌡️ Environmental Effects
Rentals increase with temperature (up to a point).

Wind and humidity have small negative impacts.

Strategy: Monitor weather forecasts to predict demand and prepare accordingly.
