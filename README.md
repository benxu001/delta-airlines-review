# Delta Airlines Customer Review Analysis (Tableau)

This project explores customer review data for **Delta Airlines** using an interactive Tableau dashboard. The goal is to understand how passenger satisfaction varies across **time, geography, traveler segments, and seat classes**, and to identify which aspects of the travel experience most influence overall ratings and recommendations.

## Dashboard Overview

The dashboard presents a high-level view of Delta Airlines customer sentiment along with deeper analytical breakdowns. It is designed to support both executive-level summary insights and exploratory analysis.

### Key Features

- **Top-level KPIs** summarizing overall performance, including:
  - Total number of reviews
  - Percentage of customers who would recommend Delta
  - Overall average rating (out of 10)
  - Component ratings:
    - Cabin staff service
    - Food & beverages
    - Ground service
    - Seat comfort
    - Value for money

- **Time-series analysis** of average ratings by quarter (2015–2026), highlighting long-term trends and periods of volatility.

- **Geographic analysis** showing average ratings by country, allowing for regional comparison of customer experience.

- **Customer segmentation analysis**, including:
  - Average ratings by traveler type (Business, Solo Leisure, Family Leisure, Couple Leisure)
  - Average ratings by seat type (Economy, Premium Economy, Business Class, First Class)

- **Interactive controls**:
  - Metric picker to switch between overall rating and individual service dimensions
  - Date range slider
  - Filters for continent, traveler type, and seat type

<img width="1403" height="786" alt="image" src="https://github.com/user-attachments/assets/08169ab6-3991-4c45-ab84-fe59a2fbcc41" />

## Key Insights

- Overall customer satisfaction is **moderate**, with only about **one-third of reviewers recommending Delta**, suggesting gaps between expectations and perceived value.
- **Premium cabin experiences** (Business and First Class) receive consistently higher ratings than Economy, indicating a meaningful quality divide by fare class.
- **Solo leisure travelers** tend to rate Delta more favorably than business travelers, who appear more critical across multiple service dimensions.
- Ratings show significant volatility over time, with notable disruptions around the 2020–2021 period, reflecting broader industry challenges.

## Tools & Skills Demonstrated

- Tableau dashboard design and layout best practices  
- Parameter-driven metric switching  
- Time-series and segmentation analysis  
- KPI development and executive-style summary views  
- Data cleaning, normalization, and storytelling for stakeholders  

## Data Collection & Source

The data used in this project was collected by **web scraping customer reviews** from *Airline Quality (Skytrax)*:

- **Source:** https://www.airlinequality.com/airline-reviews/delta-air-lines

## Live Dashboard

View the interactive dashboard on Tableau Public:  
https://public.tableau.com/app/profile/ben.xu01/viz/DeltaAirlinesReview_17696346213040/Dashboard2
