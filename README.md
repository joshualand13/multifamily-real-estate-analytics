Multifamily Real Estate Investment & Predictive Analytics

Project Overview

This project explores how data science and predictive analytics can improve investment decisions and operational performance in multifamily real estate.

The objective is to analyze property-level data, identify financial and operational patterns, and develop predictive models that support better business decisions.

Business Questions

What factors influence rental revenue?

Which properties demonstrate the strongest financial performance?

Can historical data predict future occupancy?

Which properties have unusually high operating expenses?

How can predictive analytics improve investment decisions?

The dataset has 2 CSV files, one with 10 columns -

realtor-data.csv (2,226,382 entries)
brokered by (categorically encoded agency/broker)
status (Housing status - a. ready for sale or b. ready to build)
price (Housing price, it is either the current listing price or recently sold price if the house is sold recently)
bed (# of beds)
bath (# of bathrooms)
acre_lot (Property / Land size in acres)
street (categorically encoded street address)
city (city name)
state (state name)
zip_code (postal code of the area)
house_size (house area/size/living space in square feet)
prev_sold_date (Previously sold date)
NB:

brokered by and street addresses were categorically encoded due to data privacy policy
acre_lot means the total land area, and house_size denotes the living space/building area

Another with 2 columns that are used to indicate the cost of living in each state. Provided by WorldPopulationReview.com.
state 
CostOfLivingIndexByState_2025



Technical Stack

Python

SQL

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

Power BI

Project Roadmap

Obtain and prepare real estate datasets

Perform exploratory data analysis

Calculate financial performance metrics

Analyze rental revenue and occupancy

Develop predictive models

Implement anomaly detection

Build a Power BI dashboard

Document business recommendations

Financial Metrics

Net Operating Income (NOI)

Capitalization Rate

Occupancy Rate

Operating Expense Ratio

Revenue Growth

Expected Business Applications

Rental revenue forecasting

Property performance evaluation

Occupancy prediction

Operating expense optimization

Investment risk analysis

Disclaimer

Independent portfolio project using public or synthetic data. Not affiliated with Cortland or based on proprietary company information.
