# Capstone-Project
Dynamic Pricing for Urban Parking Lots
Background and Motivation
Urban parking spaces are a limited and highly demanded resource. Prices that remain static
throughout the day can lead to inefficiencies — either overcrowding or underutilization.
To improve utilization, dynamic pricing based on demand, competition, and real-time
conditions is crucial.
This project simulates such a system: participants will create an intelligent, data-driven
pricing engine for 14 parking spaces using real-time data streams, basic economic theory,
and ML models built from scratch, using only numpy, pandas libraries.
Data Description
You are given data collected from 14 urban parking spaces over 73 days, sampled at
18 time points per day with 30 minutes of time difference (from 8:00 AM to 4:30
PM the same day).
Each record includes the following:
Location Information:
• Latitude and Longitude of each parking space (to calculate proximity to competitors).
