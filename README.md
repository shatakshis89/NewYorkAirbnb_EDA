# NewYorkAirbnb_EDA

This repository presents a **comprehensive exploratory data analysis (EDA)** of
the [NYC Airbnb Open Data](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data).
The goal is to clean, explore, and visualize patterns in Airbnb listings using Python data-science libraries.

## 📊 Project Objectives
* Examine pricing trends across boroughs and room types.
* Identify relationships between location, availability, and price.
* Detect and handle missing values.
* Visualize host activity, reviews, and geographical distribution.

## 🗂️ Dataset
Key columns:
- **id**, **name**, **host_id**, **host_name**
- **neighbourhood_group** (Manhattan, Brooklyn, etc.)
- **neighbourhood**, **latitude**, **longitude**
- **room_type** (Entire home/apt, Private room, etc.)
- **price**, **minimum_nights**
- **number_of_reviews**, **last_review**, **reviews_per_month**
- **calculated_host_listings_count**, **availability_365**


## 🔎 Exploratory Analysis Highlights
* Manhattan and Brooklyn dominate listings and have the highest median prices.
* Entire homes/apartments command higher prices than private rooms.
* Host activity follows a power-law: a few hosts manage hundreds of listings.
* Seasonal trends and borough-specific availability patterns were uncovered.
